# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [6.1.0] - 2020-10-23
### Added
- A `javadoc.source.version` property (set to `8` by default).

### Removed
- `cobertura` plugin.

## [5.0.0] - 2020-02-10
### Changed
- Renamed `travis` profile to `coveralls`.

## [4.3.1] - 2020-02-06
### Changed
- Effectively the same as 4.3.0, just re-released due to Sonatype issues.

## [4.3.0] - 2020-02-05 [YANKED]
### Yanked
- Timeouts during upload to Sonatype caused a partial release.
### Added
- Added [Spotless Maven Plugin](https://github.com/diffplug/spotless/tree/master/plugin-maven), version 1.27.0 with 
  default import order matching most existing Java projects.

## [4.2.0] - 2019-09-02
### Added
- Added `spotbugs-maven-plugin`, version 3.1.12.2.
### Changed
- Updated `hotels-oss-plugin-config` version to 1.3.0 (was 1.2.2).
- Changed `overWrite` to `true` in `maven-dependency-plugin` configuration.

## [4.1.0] - 2019-06-27
### Added
- Added a check-for-updates profile which verifies if there are dependencies that can be upgraded.
### Changed
- Updated `maven-checkstyle-plugin` version to 3.1.0 (was 3.0.0).
- Updated `maven-compiler-plugin` version to 3.8.1 (was 3.8.0).
- Updated `maven-jar-plugin` version to 3.1.2 (was 3.1.0).
- Updated `maven-javadoc-plugin` version to 3.1.0 (was 3.0.1).
- Updated `maven-jxr-plugin` version to 3.0.0 (was 2.5).
- Updated `maven-pmd-plugin` version to 3.12.0 (was 3.10.0).
- Updated `maven-source-plugin` version to 3.1.0 (was 3.0.1).
- Updated `maven-surefire-plugin` version to 2.22.2 (was 2.22.0).
- Updated `jacoco-maven-plugin` version to 0.8.4 (was 0.8.2).

## [4.0.1] - 2019-03-01
### Changed
- Default Copyright line changed to "Expedia, Inc.".

## [4.0.0] - 2019-01-28
### Removed
- Removed `findbugs-maven-plugin` from reporting as it's not compatible with JDK versions greater than 1.8.

## [3.0.1] - 2019-01-24
### Changed
- Added `maven-site-plugin` to `pluginManagement` section.

## [3.0.0] - 2019-01-24
### Changed
- Updated `jdk` version to 1.8 (was 1.7).
- Updated `maven-compiler-plugin` version to 3.8.0 (was 3.7.0).
- Updated `jacoco-maven-plugin` version to 0.8.2 (was 0.8.1).
- Added `maven-compiler-plugin` option in order to add constructor parameters' names to compiled classes.

### Removed
- Removed `cobertura-maven-plugin` from reporting as it's not compatible with JDK versions greater than 1.8.

## [2.3.5] - 2019-01-07
### Changed
- Updated `hotels.oss.plugin.config` version to 1.2.2 (was 1.1.0).

## [2.3.4] - 2018-12-21
### Changed
- Disabled javadoc doclint correctly for this plugin version.

## [2.3.3] - 2018-07-27
### Changed
- Allow late replacement of `$argLine` property for [Surefire Plugin](https://maven.apache.org/surefire/maven-surefire-plugin/test-mojo.html#argLine). 

## [2.3.2] - 2018-07-26
### Fixed
- Surefire plugin `<argLine>` keeps any pre-existing value in addition to our custom `${test.arguments}`. See [#20](https://github.com/HotelsDotCom/hotels-oss-parent/issues/20). 

## [2.3.1] - 2018-07-25
### Changed
- Execute maven-javadoc-plugin jar goal on snapshots. See [#18](https://github.com/HotelsDotCom/hotels-oss-parent/issues/18).

## [2.3.0] - 2018-07-18
### Changed
- Moved to Sonatype's updated recommendations for publishing artifacts to Maven Central. See [#16](https://github.com/HotelsDotCom/hotels-oss-parent/issues/16).

## [2.2.0] - 2018-07-17
### Changed
- Upgraded versions of plugins to the latest ones.
- Introduced properties to control the versions of some plugins and updated those.

## [2.1.1] - 2018-06-15
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
