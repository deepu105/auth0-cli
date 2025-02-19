---
layout: default
parent: auth0 apis
has_toc: false
---
# auth0 apis list

List your existing APIs. To create one, run: `auth0 apis create`.

## Usage
```
auth0 apis list [flags]
```

## Examples

```
  auth0 apis list
  auth0 apis ls
  auth0 apis ls --number 100
  auth0 apis ls -n 100 --json
```


## Flags

```
      --json         Output in json format.
  -n, --number int   Number of APIs to retrieve. Minimum 1, maximum 1000. (default 100)
```


## Inherited Flags

```
      --debug           Enable debug mode.
      --no-color        Disable colors.
      --no-input        Disable interactivity.
      --tenant string   Specific tenant to use.
```


## Related Commands

- [auth0 apis create](auth0_apis_create.md) - Create a new API
- [auth0 apis delete](auth0_apis_delete.md) - Delete an API
- [auth0 apis list](auth0_apis_list.md) - List your APIs
- [auth0 apis open](auth0_apis_open.md) - Open the settings page of an API
- [auth0 apis scopes](auth0_apis_scopes.md) - Manage resources for API scopes
- [auth0 apis show](auth0_apis_show.md) - Show an API
- [auth0 apis update](auth0_apis_update.md) - Update an API


