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

## Open API Spec Download

You can download the YAML file using [jsDelivr](https://www.jsdelivr.com/):
[https://cdn.jsdelivr.net/gh/pichillilorenzo/npm-registry-open-api@main/npm-registry-open-api.yaml](https://cdn.jsdelivr.net/gh/pichillilorenzo/npm-registry-open-api@main/npm-registry-open-api.yaml)

It is recommended to replace `main` with [a release tag](https://github.com/pichillilorenzo/npm-registry-open-api/tags).

## License

Released under the [ISC](/LICENSE) license.

This project is strongly inspired by the [node-query-registry](https://github.com/velut/node-query-registry).
