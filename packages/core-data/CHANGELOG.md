## v2.0.0 (Unreleased)

### Breaking Change

- `dispatch("core").receiveTerms` has been deprecated. Please use `dispatch("core").receiveEntityRecords` instead.
- `getCategories` resolvers has been deprecated. Please use `getEntityRecords` resolver instead.
- `select("core").getTerms` has been deprecated. Please use `select("core").getEntityRecords` instead.
- `select("core").getCategories` has been deprecated. Please use `select("core").getEntityRecords` instead.
- `wp.data.select("core").isRequestingCategories` has been deprecated. Please use `wp.data.select("core/data").isResolving` instead.
- `select("core").isRequestingTerms` has been deprecated. Please use `select("core").isResolving` instead.