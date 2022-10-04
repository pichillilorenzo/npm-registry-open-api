<div align="center">

# NPM Registry Open API

</div>

[![license](https://img.shields.io/github/license/pichillilorenzo/npm-registry-open-api)](/LICENSE)
[![Donate to this project using Paypal](https://img.shields.io/badge/paypal-donate-yellow.svg)](https://www.paypal.me/LorenzoPichilli)

Servers:
- https://registry.npmjs.org
- https://registry.npmjs.cf
- https://registry.yarnpkg.com
- https://api.npmjs.org

Paths implemented:
- GET `/`
- GET `/-/all`
- GET `/{packageName}`
- GET `/{packageName}/{version}`
- GET `/-/v1/search`
- GET `/downloads/point/{period}`
- GET `/downloads/point/{period}/{packageName}`
- GET `/downloads/range/{period}`
- GET `/downloads/range/{period}/{packageName}`
- GET `/versions/{packageName}/last-week`
- PUT `/-/user/org.couchdb.user:{user}`
- GET, POST `/-/npm/v1/user`
- GET, POST `/-/npm/v1/tokens`
- DELETE `/-/npm/v1/tokens/token/{uuid}`
- DELETE `/-/user/token/{token}`
- GET `/-/npm/v1/hooks`
- POST `/-/npm/v1/hooks/hook`
- GET, PUT, DELETE `/-/npm/v1/hooks/hook/{id}`

## Open API Spec Download

You can download the YAML file using [jsDelivr](https://www.jsdelivr.com/):
[https://cdn.jsdelivr.net/gh/pichillilorenzo/npm-registry-open-api@main/npm-registry-open-api.yaml](https://cdn.jsdelivr.net/gh/pichillilorenzo/npm-registry-open-api@main/npm-registry-open-api.yaml)

It is recommended to replace `main` with [a release tag](https://github.com/pichillilorenzo/npm-registry-open-api/tags).

## Usage

Using the official [@openapitools/openapi-generator-cli](https://www.npmjs.com/package/@openapitools/openapi-generator-cli) generator:
```bash
openapi-generator-cli generate -i https://cdn.jsdelivr.net/gh/pichillilorenzo/npm-registry-open-api@main/npm-registry-open-api.yaml -g typescript-fetch
```

## License

Released under the [ISC](/LICENSE) license.
