Change Log
================================================================================

All notable changes to the structure and content of the blog
[FinanceMNL.com](https://financemnl.com/) will be documented in this file.

This changelog tries to adhere to the
[Keep a Changelog](http://keepachangelog.com) format as much as possible. The
notable exceptions are:

- no [Semantic versioning](http://semver.org): the version numbers are simply
  dates in ISO format since each version of the blog means a new post/page or a
  change of the content, not a new feature, bugfix or compatibility break, since
  the website is completely static.
- no `Deprecated` and `Security` sections for the same reason as in the previous
  point.

********************************************************************************

2018-04-15
---------------------------------------


### Added

- Website Logo/Favicon by [Renan Barco](https://dribbble.com/renanbarco)


### Changed

- Config.toml to add links to License and Github Repo.


### Removed

- Favicon and Avatar from Themes.

### Fixed

Nothing.

#### Security fixes

Nothing.


2018-04-13
---------------------------------------


### Added

- Netlify-CMS


### Changed

Nothing.


### Removed

Nothing.


### Fixed

Nothing.

#### Security fixes

- Modified `Referrer-Policy` HTTP header to make it compliant with most browsers.
  Chrome, Edge, IE etc. are not supporting the `strict-origin-when-cross-origin`
  directive, so `no-referrer-when-downgrade` is chosen instead.
