# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

Aug 12, 2024 - Upgrade now to checkout extensibility for a better way to customize your checkout that increases speed, conversion, and integrates with Shop Pay. Checkout.liquid will no longer be supported for the information, shipping, and payment pages as of August 13, 2024.

## [4.6.0] - Upgraded to checkout extensibility for a better way to customize your checkout that increases speed, conversion, and integrates with Shop Pay. Checkout.liquid will no longer be supported for the information, shipping, Thankyou and payment pages - Nov 17, 2023

## [4.6.0] - Removed Power Review - Apr 17, 2023

### Added

- N/A

### Fixed

- Thankyou Page {Post Checkout}

### Changed

- N/A

### Removed

- Removed Power Review Thankyou page script.
- Removed Power Review tracking code scipt.

## [4.6.0] - Mouseflow - Apr 15, 2023

### Added

- [checkout.liquid](https://github.com/patchology/shopify/blob/with-checkout-liquid/layout/checkout.liquid).
- Added mouse-flow script Theme Settings >>> Checkout >> Order status page > Additional scripts.
- Added mouse-flow script in checkout.liquid [@54](https://github.com/patchology/shopify/blob/4ade42d75e74bc562b37fb191f2c84a4d5e2ffeb/layout/checkout.liquid#L54).
- Added mouse-flow script in theme.liquid [@454](https://github.com/patchology/shopify/blob/f13e16cf7e9fc5b0392cadf867e25772973276de/layout/theme.liquid#L454).

### Fixed

- Mouse-flow tracking on the whole checkout process.
- Mouse-flow tracking on all pages of the website

### Changed

- N/A

### Removed

- N/A

## [4.6.0] - Recycling Program - Apr 10, 2023

### Added

- Added wrapper recycling in [cart.liquid @367](https://github.com/patchology/shopify/blob/4e5932bd95c92b4a120832ba02ffdc4167ecb853/sections/cart.liquid#L367).
- Added CSS for recycling program in [cart.liquid @376](https://github.com/patchology/shopify/blob/4e5932bd95c92b4a120832ba02ffdc4167ecb853/sections/cart.liquid#L376).
- Added wrapper recycling in cart-drawer.liquid [@274](https://github.com/patchology/shopify/blob/4e5932bd95c92b4a120832ba02ffdc4167ecb853/snippets/cart-drawer.liquid#L274).
- Added CSS for recycling program in cart-drawer.liquid [@283](https://github.com/patchology/shopify/blob/4e5932bd95c92b4a120832ba02ffdc4167ecb853/snippets/cart-drawer.liquid#L283).
- Added ID ="{{- 'cart.label.updatequantity' | t }} - {{ line_item.variant_id | strip_html -}}" in cart-line-items.liquid [@160](https://github.com/patchology/shopify/blob/4e5932bd95c92b4a120832ba02ffdc4167ecb853/snippets/cart-line-items.liquid#L160).
- Added ID ="{{- 'cart.label.quantitybox' | t }} - {{ line_item.variant_id | strip_html -}}" in cart-line-items.liquid [@161](https://github.com/patchology/shopify/blob/4e5932bd95c92b4a120832ba02ffdc4167ecb853/snippets/cart-line-items.liquid#L161).
- Added "updatequantity" and "quantitybox" label in en.default.json [@160](https://github.com/patchology/shopify/blob/4e5932bd95c92b4a120832ba02ffdc4167ecb853/locales/en.default.json#L160).

### Fixed

- N/A

### Changed

- N/A

### Removed

- N/A
