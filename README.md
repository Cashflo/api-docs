# API Docs
API Docs for External/Internal APIs

## Usage
1. Make changes in the API specification in the YML Specification and save it
Note: If you are planning to use WYSIWYG (What You See Is What You Get) editior for enhancing the documentation you can do that here -  [Link](https://editor.swagger.io/)

2. Use the below command to generate the docs html
`npx @redocly/cli build-docs internal/openapi-spec.yaml -o internal-docs/index.html`

3. TBD Move the files from `internal-docs` towards private s3 for interna consumption currently testing with github itself. 
