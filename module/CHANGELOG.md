# Change log

## [2.6.1] - 2025-04-07
### Fixed
- Store settings page header.
### Internal
- Rename function.

## [2.6.0] - 2025-04-04
### Added
- Forgotten Password page protection.
### Internal
- Code improvements.

## [2.5.0] - 2025-03-12
### Fixed
- JS-script and CSS-stylesheet links.
### Added
- Compatibility with OpenCart 2.x (PHP 5.6).
### Internal
- File structure was changed.

## [2.4.2] - 2025-02-24
### Fixed
- Type declarations.

## [2.4.1] - 2025-01-20
### Fixed
- Event handlers.

## [2.4.0] - 2025-01-14
### Changed
- The bot detection method is now more compatible with third-party themes, such as Journal.
- Advanced bot detection is now always enabled.

## [2.3.0]
- Unreleased

## [2.2.0] - 2024-09-25
### Added
- Deferred JS-script loading.
### Fixed
- Internals for better compatibility.

## [2.1.0] - 2024-06-13
### Added
- Behavior-based detection as an option.

## [2.0.2] - 2024-05-27
### Fixed
- Autofilling issue.

## [2.0.1] - 2024-05-23
### Fixed
- Removed redundant variable in template.
### Changed
- Added a unique ID, because some templates place multiple captchas on the same page at the same time (for example, the second one can be placed in modal windows).

## [2.0.0] - 2024-05-21
### Removed
- Admin and customer login protection (cause: redundant, better use store config option `Max Login Attempts` and `.htaccess` as the first line of defense for the admin login page).
### Changed
- Launch method. Now it looks alike other captchas, so the honeypot is now available wherever captcha download is provided. Additionnaly the honeypot is available on the gift certificate page, where is captcha is not provided by default.
- Spambot behavior dection (a bit improved).

## [1.6.1] - 2024-05-04
### Fixed
- target form detection (4x).
- renamed admin folder support (4x).
### Internal
- Minor code refactoring.

## [1.6.0] - 2024-04-23
### Fixed
- In the admin, the honeypot script was still running even after logging.
### Improved
- Honeypot placing method.
- Minor improvements.
### Removed
- Product review writing protection (just allow to write reviews for logged customers only!).
### Internal
- Minor code refactoring.

## [1.5.2] - 2024-03-25
### Changed
- Protection of guest/register checkout page is more human-friendly.
### Improved
- Honeypot placing method.
### Internal
- Removed redundant part from the admin twig file.
- Minor code refactoring.
### New
- OC4-compatible version.

## [1.5.1] - 2024-02-26
### Fixed
- PHP warning on admin login page.

## [1.5.0] - 2024-02-24
### Added
- Product returns protection.

## [1.4.1] - 2024-02-15
### Internal
- Minor code improvements.

## [1.4.0] - 2023-11-16
### Changed
- Moved to Extension/Captcha.

## [1.3.3] - 2023-11-16
### Fixed
- Checkout guest and register issue.

## [1.3.2] - 2023-11-05
### Changed
- Now the honeypot js file is generated by the php script.
- The honeypot is inactive on the admin login page in maintenance mode.
- Activation delay is configurable.

## [1.3.1] - 2023-11-04
### Added
- Honeypot activation delay;
### Changed
- Honeypot place finder.
### Fixed
- Checkout guest and register issue.

## [1.3.0] - 2023-11-03:
### Fixed
- Issue with the first login attempt of the admin.
### Internal
- Code improvements.

## [1.2.0] - 2023-11-01:
### Fixed
- Affiliate login page
- Checking the honeypot input fields for availability in the submitted form.

## [1.1.0] - 2023-11-01:
### Changed
- Search for elements on the checkout page
- Checking the honeypot input fields for availability in the submitted form.

## [1.0.0] - 2023-10-27:
- First release
