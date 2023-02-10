# Changelog for LightStands API

## 2.1-pre (Pending changes)
- Replaced error `scopenotcovered` with `forbidden`.
- `{GET, PATCH} /users/{userid}/tags/_read` will return `forbidden` if no access to the resource.

## 1.6

- `scopenotcovered` is going to be replaced by `forbidden` in version 2.1-pre. Now `scopenotcovered` error will be shipped with `forbidden` aside.
- added endpoints to manage applications
- fixed multiple errors are not wrapped in basic error model.
