# Changelog

## [1.0.1](https://github.com/opal/opal-sprockets/compare/v1.0.0...v1.0.1)

*28 July 2021*

- Open the opal dependency to all v1 versions


## [1.0.0](https://github.com/opal/opal-sprockets/compare/v0.4.9.1.0.3.7...v1.0.0)

*19 February 2021*

- Bump the supported sprockets version to v4
- Add support for Opal v1.1
- Only support Ruby comments in directive preprocessor (no one should have ever used "//", ["/*", or "*/")
- Fix the namespaces and move everything under Opal::Sprockets (the legacy namespaces will be dropped in version 1.1)
- The version schema has been simplified, not expecting sprockets to have major earthquakes like it was for v4


## [v0.4.9](https://github.com/opal/opal-sprockets/compare/v0.4.8.1.0.3.7...v0.4.9.1.0.3.7)

*11 September 2020*

- Avoid OpalLoaded undefined when applications have no dependencies.


## [v0.4.8](https://github.com/opal/opal-sprockets/compare/v0.4.7.1.0.3.7...v0.4.8.1.0.3.7)

*14 September 2019*

- Revert the changes in 0.4.7


## [v0.4.7](https://github.com/opal/opal-sprockets/compare/v0.4.6.1.0.3.7...v0.4.7.1.0.3.7)

*14 September 2019*

- Require `opal/sprockets` before calling `Opal::Sprockets.loaded_asset`


## [v0.4.6](https://github.com/opal/opal-sprockets/compare/v0.4.5.1.0.3.7...v0.4.6.1.0.3.7)

*24 July 2019*

- Allow multiple calls to the code produced by `Opal::Sprockets.load_asset`


## [v0.4.5](https://github.com/opal/opal-sprockets/compare/v0.4.4.1.0.3.7...v0.4.5.1.0.3.7)

*25 May 2019*

- Opal is now loaded as part of the bootstrap process instead of being marked as preloaded by the processor
- Simplified code for loading-related scripts


## [v0.4.4](https://github.com/opal/opal-sprockets/compare/v0.4.3.0.11.0.3.7...v0.4.4.1.0.3.7)

*12 May 2019*

- Target Opal v1.0


## [v0.4.3](https://github.com/opal/opal-sprockets/compare/v0.4.2.0.11.0.3.1...v0.4.3.0.11.0.3.7)

*13 February 2019*

- Drop support for older Sprockets versions


## [v0.4.2](https://github.com/opal/opal-sprockets/compare/v0.4.1.0.11.0.3.1...v0.4.2.0.11.0.3.1)

*7 September 2018*

- Inline source-maps with their source-contents for better performance and simpler architecture


## [v0.4.1](https://github.com/opal/opal-sprockets/compare/v0.4.0.0.10.0.3.0.0...v0.4.1.0.11.0.3.1)

*30 December 2017*

- Added support for Opal 0.11
- `Opal::Sprockets.load_asset` now works without the need to access the sprockets environment (needed by `sprockets-rails` v3+)
- Documentation updates
