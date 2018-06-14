# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).
## [2.1.1] - 2018-06-14
### Changed
- Upgraded nexus-staging-maven-plugin to version 1.6.8 (was 1.6.3).

## [2.1.0] - 2018-05-18
### Added
- Added support for JaCoCo coverage reports.

## [2.0.6] - 2017-12-14
### Added
- Added a travis profile which triggers coveralls.

## [2.0.5] - 2017-11-20
### Added
- Added profile for sonatype oss release with gpg plugin.

## [2.0.4] - 2017-11-17 [YANKED]
### Changed
- Added profile for sonatype oss release with gpg plugin.

## [2.0.3] - 2017-09-26
### Changed 
- Name ${test.arguments} -> test.arguments in surefire plugin profile.
- maven-surefire-plugin version set to 2.20.1.

## [2.0.2] - 2017-09-26 [YANKED]
### Changed 
- No changes, was caused by a mistaken release build.

## [2.0.1] - 2017-09-22 [YANKED]
### Changed
- Add test.arguments parameter for surefire plugin.

## [2.0.0] - 2017-07-12
### Changed
- Updated to the newest version for all plugins which have had releases since the latest update.

## [1.2.0] - 2017-06-14
### Added
- Change log.
### Changed
- Updated Findbugs plug-in to 3.0.4 from 2.5.3 as the earlier version was not compatible with Java 8.
- Added profile to enable `-Xdoclint` to work around blocking Javadoc warnings in JDK versions since 1.8.

## [1.1.1] - 2017-03-07
### Added
- Previous version, no changes recorded.
