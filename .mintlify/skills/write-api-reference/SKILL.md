---
name: write-api-reference
description: Write or update API reference pages. Use when adding a new endpoint, documenting request parameters, or adding response examples.
public: true
---

# Write API reference pages

- Create one MDX page per endpoint.
- Set `openapi` in the frontmatter when an OpenAPI spec is available, for example `openapi: "GET /users"`.
- Use `<ParamField>` for request parameters and `<ResponseField>` for response fields.
- Include at least one request example and one response example.
- Add the new page to `docs.json` navigation.
