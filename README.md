# OADA Server GitHub Action

A GitHub action to start a local instance of
the [OADA reference API server](https://github.com/OADA/server).
Useful for creating testing workflows for OADA compliant projects.

## Usage

```yaml
- uses: Qlever-LLC/OADA-Server-action@v1.0.0
  with:
    # Version of OADA server to use, e.g., v3.1.0
    # The default is 'latest' which uses the latest stable release
    version: latest
```
