# AppscopePack
Pack for the AppScope

Example of data Pipelines which are designated to work on data from the AppScope source:

- Extract the HTTP headers from HTTP request and HTTP responses
- Verify if the HTTP requests use only methods mentioned in `http_method_schema.json`
- Verify if the HTTP request and response don't contains the HTTP headers mentioned in  `http_forbidden_headers_schema.json`
