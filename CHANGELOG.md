# Change Log for OXID eShop Enterprise Edition Core Component

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [6.0.3] - Unreleased

### Added

### Changed

### Deprecated

### Removed

### Fixed

## [6.0.2] - 2019-04-18

### Removed
- `blFooterShowGuestbook` config option

### Fixed
- `oxrightofwithdrawal` content page content fixed
    - getBaseDir now called on oViewConf object
    - `ddmedia` directory added in pictures, in place of earlier removed `wysiwyg` directory
        - new OXID Visual CMS module uses this directory for file upload by default

## [6.0.1] - 2018-01-24


[6.0.3]: https://github.com/OXID-eSales/oxideshop_demodata_ce/compare/v6.0.2...HEAD
[6.0.2]: https://github.com/OXID-eSales/oxideshop_demodata_ce/compare/v6.0.1...v6.0.2
[6.0.1]: https://github.com/OXID-eSales/oxideshop_demodata_ce/compare/v6.0.0...v6.0.1
