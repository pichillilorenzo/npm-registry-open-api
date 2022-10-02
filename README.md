<div align="center">

# NPM Registry Open API

</div>

[![license](https://img.shields.io/github/license/pichillilorenzo/known-http-header-db)](/LICENSE)
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

## License

Released under the [ISC](/LICENSE) license.

This project is strongly inspired by the [node-query-registry](https://github.com/velut/node-query-registry).
