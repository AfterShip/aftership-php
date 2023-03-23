# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [5.3.0] - 2023-03-22
### Added
- Add CURL OPT for API request

## [5.2.0] - 2023-03-17
### Added
- Add API: POST `trackings/{slug}/{tracking_number}/mark-as-completed`
- Add API: POST `trackings/{id}/mark-as-completed`
- Add Request Header: `as-api-key`
- Add AES signature
- Add RSA signature

## [5.1.3] - 2022-07-20
### Added
- Add API: POST `estimated-delivery-date/predict-batch`

## [5.1.2] - 2021-03-17
### Added
- Add additional_fields params for each API request

## [5.1.1] - 2017-08-21
### Added
- Better handle UTF-8 encodings

## [5.1.0] - 2017-07-14
### Added
- comply to psr-2 (get_by_id -> getById)
- use psr-4 to autoload files rather than psr-0
- rewrite example/testing.php file
- added travis for CI
- added unit tests
- configured code climate for code quality monitoring.

## [5.0.10] - 2017-01-17
### Added
- add back empty constructor in request

[5.1.3]: https://github.com/AfterShip/aftership-sdk-php/compare/5.1.2...5.1.3
[5.1.2]: https://github.com/AfterShip/aftership-sdk-php/compare/5.1.1...5.1.2
[5.1.1]: https://github.com/AfterShip/aftership-sdk-php/compare/5.1.0...5.1.1
[5.1.0]: https://github.com/AfterShip/aftership-sdk-php/compare/5.0.10...5.1.0
[5.0.10]: https://github.com/AfterShip/aftership-sdk-php/releases/tag/5.0.10