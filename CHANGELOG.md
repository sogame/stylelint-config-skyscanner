# Change Log

## UNRELEASED

_Nothing yet..._

## 2.0.0-beta.4
- Upgraded `stylelint` peerDependency to `^11.0.0`
- Upgraded dependencies:
  - `babel-eslint` to `^10.0.3`
  - `eslint` to `^5.16.0`
  - `eslint` to `^6.5.1`
  - `eslint-config-airbnb` to `^17.1.0`
  - `eslint-config-airbnb` to `^18.0.1`
  - `eslint-plugin-import` to `^2.18.2`
  - `eslint-plugin-jsx-a11y` to `^6.2.3`
  - `eslint-plugin-react` to `^7.16.0`
  - `jest` to `^24.9.0`
  - `stylelint` to `^11.0.0`
  - `stylelint-config-standard` to `^19.0.0`
  - `stylelint-declaration-strict-value` to `^1.1.6`
  - `stylelint-order` to `^3.1.1`
  - `stylelint-scss` to `^3.11.1`

## 2.0.0-beta.3
- Upgraded `stylelint` peerDependency to `^10.1.0`

## 2.0.0-beta.2
### Fixed
- Disabled `no-descending-specificity` rule

## 2.0.0-beta.1
### Changed
- Upgraded `stylelint` peerDependency to `^9.1.1`
- Upgraded dependencies:
  - `stylelint-config-standard` to `18.1.0`
  - `stylelint-order` to `^0.8.1`
  - `stylelint-scss` to `^2.4.0`

## 1.0.1
### Fixed
- Relaxed semver range for `stylelint` peer dependency from `~8.0.0` to `^8.0.0`
- Upgraded `stylelint-scss` from `1.5.1` to `^2.1.0`
- Upgraded `stylelint-order` from `0.6.0` to `"^0.7.0`

## 1.0.0
### Added
- Flex and grid rules to `order/order` rule
- Added `selector-max-type` as warning (for now) to prevent interference between stylesheets
- Allow `@else` and `@else if` SCSS rules to be on same line as `@if` closing bracket
- Styleguide!

### Changed
- `selector-no-id` rules replaced by functionally identical `selector-max-id`
- Updated dependencies and peerDependencies:
  - `stylelint` to `8.0.0`
  - `stylelint-scss` to `1.5.1`
  - `stylelint-order` to `0.6.0`
  - `stylelint-declaration-strict-value` to `1.0.4`

## 0.1.5
### Fixed
- Fixed links in messages for `selector-class-pattern` and `scss/at-mixin-pattern`

## 0.1.4
### Added
- Added tests
- Added message to `selector-class-pattern` and `scss/at-mixin-pattern`

### Changed
- Upgraded `stylelint-order` and `stylelint-scss` to fix downstream bugs

## 0.1.3
### Added
- `at-rule-no-vendor-prefix`, `media-feature-name-no-vendor-prefix`, `property-no-vendor-prefix`, `selector-no-vendor-prefix`, `value-no-vendor-prefix` to encourage Autoprefixer usage
- `string-quotes`, `selector-attribute-quotes`, `font-family-name-quotes` to standardise string usage
- `unspecified: 'bottomAlphabetical'` to `order/properties-order` rule
+
## 0.1.2
### Changed
- `scss/at-mixin-pattern` changed to include some valid edge cases

### Fixed
- Regex for `scss/at-function-pattern`, `scss/at-mixin-pattern`, `scss/dollar-variable-pattern`, and `scss/percent-placeholder-pattern` now works as intended

## 0.1.1
### Changed
- `scss/at-function-pattern`, `scss/at-mixin-pattern`, `scss/dollar-variable-pattern`, and `scss/percent-placeholder-pattern` updated to use the same kebab case regex as class names
### Removed
- `scss/operator-no-newline-before` as it clashed with `scss/operator-no-newline-after`

## 0.1.0 - Initial config
### Added
- Initial config based on [`stylelint-config-standard`](https://www.npmjs.com/package/stylelint-config-standard)
