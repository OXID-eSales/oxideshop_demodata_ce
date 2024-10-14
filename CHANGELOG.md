# Change Log for OXID eShop Community Edition Demo Data Component

## v8.0.2 - 2024-10-14

### Fixed
- Remove unnecessary `<small>` tags from CHF currency

## v8.0.1 - 2024-03-18

### Fixed
- Shift oxcontents into its proper position to allow better comparisons
- Use the same oxcontents part for all editions (the additional fields all have proper defaults for now)
- Accessibility issues reported by eye able
  - Links must have accessible text (primary the enlarge links on images)
  - Identical links with different targets (same as above)
  - Jump in the heading order (content started with h3, while only h1 exists before)
  - Abbreviation markup
  - Removed example text in `how to order page` page
  - Invalid URL in `test customers` page

## v8.0.0 - 2023-05-09

### Changed
- Switched to Twig template engine/APEX Theme
- License updated

## v7.1.0 - 2023-05-03

### Changed
- License updated

## v7.0.1 - 2022-08-16

### Changed
- Update credits page content

## v7.0.0 - 2021-06-09

### Changed
- Decoded all encoded value to compatible with mysql 8

## v6.0.5 - 2022-08-16

### Changed
- Update credits page content

## v6.0.4 - 2020-04-21

### Removed
- Removed date values from titles and descriptions

## v6.0.3 - 2019-04-26

### Changed
- Removed the `out/pictures/generated` directory from package
    - this directory is filled dynamically by shop.

### Fixed
- Fixed wording in changelog file.

## v6.0.2 - 2019-04-18

### Removed
- `blFooterShowGuestbook` config option [#0006696](https://bugs.oxid-esales.com/view.php?id=6696)

### Fixed
- `oxrightofwithdrawal` content page content fixed
    - getBaseDir now called on oViewConf object
    - `ddmedia` directory added in pictures, in place of earlier removed `wysiwyg` directory
        - new OXID Visual CMS module uses this directory for file upload by default

## v6.0.1 - 2018-01-24
