# XML Reader

Tool to QA Job Sync JSON files.

Files are expected to line delimited JSON files. Example:

```
{"referenceId" : 111,"company" : {"id" : "ABC Company"},"employer" : null,"title" : "Product Manager"}
{"referenceId" : 222,"company" : {"id" : "ABC Company"},"employer" : null,"title" : "Data Scientist"}
{"referenceId" : 333,"company" : {"id" : "ABC Company"},"employer" : null,"title" : "Financial Analyst"}
```

## Local Development

- Start server:
  - `npx http-server`
- Browse:
  - http://localhost:8080/
