# Seatplus

This repository acts as central repository for all Seatplus packages.

[![Seatplus](https://seatplus.net/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fhero.0a60fcf7.png&w=1200&q=75)](https://seatplus.net)

Please head to [https://seatplus.net](https://seatplus.net) for the documentation and explanation of features.

## Support

Support for Seatplus is provided through the [discussions forum](https://github.com/seatplus/seatplus/discussions).

## Bugs and Feature Requests

Before you submit a bug or feature request, please read the [discussions](https://github.com/seatplus/seatplus/discussions) and [issues](https://github.com/seatplus/seatplus/issues) first.

To create please a new issue use the following links:
* [Bug](https://github.com/seatplus/seatplus/issues/new?assignees=&labels=&template=bug_report.md&title=).
* [Feature Request](https://github.com/seatplus/seatplus/issues/new?assignees=&labels=&template=feature_request.md&title=)

## Repositories

| Repository                                           | Description                                                                                                | Dependencies                        |
|------------------------------------------------------|------------------------------------------------------------------------------------------------------------|-------------------------------------|
| [base-app](https://github.com/seatplus/base-app)     | Base repository to use for deploying to production or development using docker-compose                     | core, web, auth, eveapi, esi-client |
| [Core](https://github.com/seatplus/core)             | Core php project. For manual installations this is the most important repo.                                | by default: web, auth, eveapi, esi-client |
| [Web](https://github.com/seatplus/web)               | Seatplus frontend package                                                                                  | auth, eveapi, esi-client            |
| [Auth](https://github.com/seatplus/auth)             | Seatplus authentication package providing access for http middlewares and authentication and authorization | eveapi, esi-client              |
| [Eveapi](https://github.com/seatplus/eveapi)         | Seatplus eveapi package orchestrating queue workers to update esi resources                                | esi-client                |
| [ESI client](https://github.com/seatplus/esi-client) | Seatplus esi client to consume and cache ESI resources                                                     | auth, eveapi, esi-client            |

