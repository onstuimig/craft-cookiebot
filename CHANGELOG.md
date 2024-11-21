# Changelog

## 3.0.0 - 2024-11-21
### Added
- Craft 5 support
- Option to disable consent mode defaults
- Option to use .eu TLD

## 2.1.2 - 2022-10-05
### Changed
- Turned off autoBlockingMode

## 2.1.1 - 2022-10-05
### Fixed
- Fixed typed property error

## 2.1.0 - 2022-10-05
### Added
- Added autoBlockMode setting
### Fixed
- Hardened json_decode

## 2.0.0 - 2022-07-08
### Added
- Craft v4 compatibility

## 1.0.9 - 2020-01-17
### Fixed
- Fixed wrongful functioning of requiresConsent  

## 1.0.8 - 2019-12-13
### Fixed
- Fixed declaration template bug 

## 1.0.7 - 2019-04-20
### Fixed
- Upgraded cookiebot support for version 2 of the cookie, that handles cookies that don't require consent

## 1.0.6 - 2018-07-06
### Fixed
- Downgraded to PHP 7.0 support

## 1.0.5 - 2018-07-06
### Added
- Added minimum PHP version 7.1

## 1.0.4 - 2018-06-08
### Fixed
- Changed hasCpSettings to true in composer.json and removed public property from Plugin class

## 1.0.3 - 2018-06-08
### Fixed
- Removed version from composer.json (see composer/packagist#587)

## 1.0.2 - 2018-06-08
### Added
- Added settings override possibility from `cookiebot.php` config file
### Fixed
- Fixed service template rendering issues

## 1.0.1 - 2018-06-07
### Fixed
- Fixed issue of cookiebot service naming; renamed `service` component to `cookiebot`
- Set `$hasCpSettings` to `true`

## 1.0.0 - 2018-06-07
### Added
- Initial release