# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2022-04-30
### Changed
- logic that ignores favicon.ico was removed.

### Added
- when a request is recieved from a path that does not exists it logs and return 404
- calibre program argument was added to hide some files like metadata.opf and cover.jpg

### Fixed
- A panic when a path does not exists, not it logs an error instead.

## [0.1.2] - 2022-04-30

### Changed
- fix favicon.ico typo
- remove app arguments about author is not necesary and is not intuitive

## [0.1.1] - 2022-04-26
### Changed
- Returns 404 when the path contains favicon.ico

## [0.1.0] - 2021-06-10
### Changed
- time is calculated only once
- updated the mimetype returned for the navigation and acquisition xmls

## [0.0.11] - 2021-06-05
### Changed
- return to filepath as the best way to handle paths for different platforms.

## [0.0.10] - 2021-05-06
### Added
- Unittests

### Changed
- structure of the project changed but public endpoint remains backward compatible.

## [0.0.9] - 2021-05-06
### Changed
- using actions in github for building binaries only when tagging.

## [0.0.8] - 2021-05-06
### Changed
- using actions in github for building binaries only when tagging.

## [0.0.7] - 2021-05-06
### Changed
- using actions in github for testing

## [0.0.6] - 2021-05-06
### Changed
- using actions in github for testing

## [0.0.5] - 2020-05-06
### removed
- usage of filepath package

## [0.0.4] - 2020-05-15
### Added
- debug flag (idea from @clash04)
- comic support thanks to @clash04
- fix hrel that didnt allow the download. (found the issue @clash04)

## [0.0.3] - 2019-03-10
### Added
- A change log was added.
- Added a message when the server started in the stadin

### Changed
- fix rel and type for acquisition
- In the code change where the parameters are defined.
- Changed serveFeedauthor parameter for author.
- Adding host parameter.
- Start using go modules.
- Fixing typo in file extension gif
- The MIME-type for FB2 changed to text/fb2+xml

### Removed
- vendor folder.


## [0.0.2] - 2017-05-11
### Changed
- Using builders to generate the xml.
- Adding binaries in the release section.

## [0.0.1] - 2017-03-24
### Added
- first version of dir2opds was relased.