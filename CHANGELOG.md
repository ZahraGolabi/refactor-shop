# Changelog

All notable changes to this project will be documented in this file.
## [1.0.2] - 2026-11-28

### Fixed
- Reverted 1.0.1: discounted products show the discounted price again.

## [1.0.1] - 2026-11-28

### Changed
- Show the original price on product cards (introduced a bug, reverted in 1.0.2).

## [1.0.0] - 2026-11-23

### Added
- Initial release of the Persian RTL grocery shop.
- TanStack Router for route management and URL search parameter handling.
- Zustand store for cart management with persistent local storage.
- Light/Dark theme switching with persisted theme state.
- Product catalog with categories, filtering, and sorting.
- Product details page and responsive checkout form.
- Automated CI pipeline, Dockerfile, and Vercel configuration.

### Changed
- Refactored component tree and architecture adhering to strict layer separation.
- Enforced strict TypeScript checks and oxlint rules without warning exemptions.
- Persian RTL formatting with `fa-IR` locale for numbers and prices.

### Fixed
- RTL layout and responsive styling across mobile and desktop views.
- Offer application and category product rendering flow.
