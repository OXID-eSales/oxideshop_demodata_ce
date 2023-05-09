# Change Log for OXID eShop Community Edition Demo Data Component

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [v8.0.0] - 2023-05-09

### Changed
- Switched to Twig template engine/APEX Theme
- License updated

## [v7.1.0] - 2023-05-03

### Changed
- License updated

## [v7.0.1] - 2022-08-16

### Changed
- Update credits page content

## [v7.0.0] - 2021-06-09

### Changed
- Decoded all encoded value to compatible with mysql 8

## [v6.0.5] - 2022-08-16

### Changed
- Update credits page content

## [v6.0.4] - 2020-04-21

### Removed
- Removed date values from titles and descriptions

## [v6.0.3] - 2019-04-26

### Changed
- Removed the `out/pictures/generated` directory from package
    - this directory is filled dynamically by shop.

### Fixed
- Fixed wording in changelog file.

## [v6.0.2] - 2019-04-18

### Removed
- `blFooterShowGuestbook` config option [#0006696](https://bugs.oxid-esales.com/view.php?id=6696)

### Fixed
- `oxrightofwithdrawal` content page content fixed
    - getBaseDir now called on oViewConf object
    - `ddmedia` directory added in pictures, in place of earlier removed `wysiwyg` directory
        - new OXID Visual CMS module uses this directory for file upload by default

## [v6.0.1] - 2018-01-24

[v8.0.0]: https://github.com/OXID-eSales/oxideshop_demodata_pe/compare/v7.1.0...v8.0.0
[v7.1.0]: https://github.com/OXID-eSales/oxideshop_demodata_ce/compare/v7.0.0...v7.1.0
[v7.0.0]: https://github.com/OXID-eSales/oxideshop_demodata_ce/compare/v6.0.4...v7.0.0
[v6.0.4]: https://github.com/OXID-eSales/oxideshop_demodata_ce/compare/v6.0.3...v6.0.4
[v6.0.3]: https://github.com/OXID-eSales/oxideshop_demodata_ce/compare/v6.0.2...v6.0.3
[v6.0.2]: https://github.com/OXID-eSales/oxideshop_demodata_ce/compare/v6.0.1...v6.0.2
[v6.0.1]: https://github.com/OXID-eSales/oxideshop_demodata_ce/compare/v6.0.0...v6.0.1
