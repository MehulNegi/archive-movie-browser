# Changelog

## [Unreleased]

## [1.2.0] - 2026-09-21

### Added

- Added shareable views with filters and searches stored in the URL ([#100](https://github.com/amponce/archive-movie-browser/pull/100)).
- Added a keyhole generated poster for films without artwork ([#98](https://github.com/amponce/archive-movie-browser/pull/98)).
- Added a mobile layout that shows films first ([#99](https://github.com/amponce/archive-movie-browser/pull/99)).

### Changed

- Refreshed the poster index with 75 additional uploads ([#90](https://github.com/amponce/archive-movie-browser/pull/90)).
- Updated the header and footer to reflect the collection being browsed ([#91](https://github.com/amponce/archive-movie-browser/pull/91)).

### Fixed

- Fixed movie card callbacks being recreated across parent renders ([#93](https://github.com/amponce/archive-movie-browser/pull/93)).
- Fixed focus handling in the movie detail dialog ([#94](https://github.com/amponce/archive-movie-browser/pull/94)).
- Improved poster matching for catalogue-prefixed titles ([#95](https://github.com/amponce/archive-movie-browser/pull/95)).
- Bounded and improved expiration of the TMDB cache ([#96](https://github.com/amponce/archive-movie-browser/pull/96)).

## [1.1.0] - 2026-09-20

### Added

- Added search suggestions with word-based matching ([#73](https://github.com/amponce/archive-movie-browser/pull/73)).
- Added generated posters for films without posters ([#59](https://github.com/amponce/archive-movie-browser/pull/59)).
- Added accessibility improvements for filters, movie cards, and the detail page ([#52](https://github.com/amponce/archive-movie-browser/pull/52), [#53](https://github.com/amponce/archive-movie-browser/pull/53)).
- Added security headers, social preview tags, and Dependabot configuration ([#74](https://github.com/amponce/archive-movie-browser/pull/74)).

### Changed

- Added a poster index to improve poster matching without requiring a TMDB API key ([#89](https://github.com/amponce/archive-movie-browser/pull/89)).
- Upgraded the project to React 19 and Vite 8 ([#87](https://github.com/amponce/archive-movie-browser/pull/87)).

### Fixed

- Improved matching of messy Archive.org upload titles to films ([#59](https://github.com/amponce/archive-movie-browser/pull/59)).
- Improved TMDB request handling and caching ([#56](https://github.com/amponce/archive-movie-browser/pull/56), [#96](https://github.com/amponce/archive-movie-browser/pull/96)).
- Fixed detail-page posters and movie accessibility issues ([#71](https://github.com/amponce/archive-movie-browser/pull/71)).

## [1.0.0] - 2026-09-20

### Added

- Added browsing across Archive.org film collections with genre filtering ([#2](https://github.com/amponce/archive-movie-browser/pull/2), [#5](https://github.com/amponce/archive-movie-browser/pull/5)).
- Added search across collections and support for films without recorded runtime ([#5](https://github.com/amponce/archive-movie-browser/pull/5)).
- Added generated title covers for films without posters ([#7](https://github.com/amponce/archive-movie-browser/pull/7)).
- Added shareable film links and improved detail-page navigation ([#20](https://github.com/amponce/archive-movie-browser/pull/20)).
- Added automated retries for transient Archive.org errors ([#27](https://github.com/amponce/archive-movie-browser/pull/27)).
- Added CI, tests, and an MIT license ([#24](https://github.com/amponce/archive-movie-browser/pull/24)).

### Changed

- Improved filtering, pagination, and search behavior ([#4](https://github.com/amponce/archive-movie-browser/pull/4)).
- Improved handling of duplicate uploads by collapsing re-uploads of the same film ([#7](https://github.com/amponce/archive-movie-browser/pull/7)).

### Fixed

- Fixed broken filters and updated the logo ([#1](https://github.com/amponce/archive-movie-browser/pull/1)).
- Fixed runtime and collection filtering issues ([#23](https://github.com/amponce/archive-movie-browser/pull/23), [#28](https://github.com/amponce/archive-movie-browser/pull/28)).