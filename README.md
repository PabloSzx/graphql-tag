# graphql-tag-esm

Fork of graphql-tag, but full esm.

To be used to replace the non-esm version, you can use dependency linking:

With `pnpm`, you can do:

```json
{
  "pnpm": {
    "overrides": {
      "graphql-tag": "npm:graphql-tag-esm@2.12.8"
    }
  }
}
```
