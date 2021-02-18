# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this
project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

_There are no unreleased changes at the moment._

## [0.3.0] - 2021-02-18

### Added

* New parameters for the `AsyncBufferedConsumer` constructor: `import_url`,
  `request_timeout`, `groups_url`, `api_host`, `retry_limit`, `retry_backoff_factor`,
  `verify_cert`.

### Changed

* Extra arguments (`*args`, `**kwargs`) are no longer accepted in the
  `AsyncBufferedConsumer` constructor.

## [0.2.0] - 2019-07-11

### Added

* Argument `api_key` for `AsyncBufferedConsumer.send`, for compatibility with the version
  4.3.2 of the Mixpanel package.

### Changed

* Breaking change: Argument of `flush` renamed from `async` to `async_` for
  compatibility with Python 3.7.

## [0.1.0] - 2015-12-28

### Added

* Compatibility with Python 3.

## [0.0.6] - 2015-09-16

## [0.0.5] - 2014-11-25

## [0.0.4] - 2014-09-29

## [0.0.3] - 2014-04-29

[Unreleased]: https://github.com/jessepollak/mixpanel-python-async/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/jessepollak/mixpanel-python-async/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/jessepollak/mixpanel-python-async/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/jessepollak/mixpanel-python-async/compare/v0.0.6...v0.1.0
[0.0.6]: https://github.com/jessepollak/mixpanel-python-async/compare/v0.0.5...v0.0.6
[0.0.5]: https://github.com/jessepollak/mixpanel-python-async/compare/v0.0.4...v0.0.5
[0.0.4]: https://github.com/jessepollak/mixpanel-python-async/compare/v0.0.3...v0.0.4
[0.0.3]: https://github.com/jessepollak/mixpanel-python-async/releases/tag/v0.0.3
