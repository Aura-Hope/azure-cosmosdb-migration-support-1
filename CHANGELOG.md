# Change Log

All notable changes to the "ads-extension-mongo-migration" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [1.0.0] 13-04-2023 - Public Preview

- Initial release.
- Has ability to connect to mongo servers, assess all databases and collections for migration readiness. Report is generated highlighting all actions user can take for migration readiness.

## [1.0.1] 08-05-2023 - Bug fixes

- Missing assessments HTML report on certain cases has been fixed.
- Fix on number overflow in data size fields of HTML report.
- Other cosmetic fixes.

## [1.1.0] 26-06-2023 - Minor updates and bug fixes

- Added a new dialog for more details on errors.
- Added telemetry to track metrics.
- Bug fixes including few accessibility issues.

## [2.0.0] 10-11-2023 - Support for migration

- Added support to create and monitor migrations.

## [2.0.2] 10-11-2023 - Support for deleting migration

- Added support to delete migrations.

## [2.0.3] 20-02-2024 - Accessibility bug fixes and performance improvement

- Improved execution time for assessment runs.
- Accessibility bug fixes.

## [2.1.0] 22-03-2024 - Data assessment and accessibility bug fixes

- Added data assessment feature.
- Accessibility bug fixes.

## [2.1.1] 15-04-2024 - Minor updates and bug fixes

- Added confirm settings dialog.
- Telemetry bug fixes.

## [2.2.0] 19-06-2024 - Data assessment telemetry, performance improvement and bug fixes

- Data assessment telemetry 
- Updated performance for schema migration
- Bug fixes in assessment
- XSS attack prevention in HTML report

## [3.0.0] 02-07-2024 - Online migration

- Added support to create online migrations.
- Added support to cancel migrations.

## [3.1.0] 12-07-2024 - Migrate capped collections and check connectivity

- Added support to migrate capped collections.
- Added connectivity check of source and target cluster before starting migration.

## [3.1.1] 31-07-2024 - Updates to vCore assessments

- Updated the assessments for vCore to the latest updates from Mongo team.

## [3.1.2] 13-08-2024 - Data migration telemetry

- Telemetry updates and minor fixes.

## [3.1.3] 30-08-2024 - Minor bug fixes

- Bug fixes in telemetry, schema migration and accessibility.

## [3.1.4] 03-10-2024 - Minor exception fixes

- Fixing error messages appearing when test connectivity check fails.

## [3.1.5] 12-12-2024 - Minor bug fixes

- Fixed minor bugs.

## [3.1.6] 17-12-2024 - Minor bug fixes

- Fixed minor bugs for schema migration.

## [3.1.7] 20-02-2025 - Updates to vCore assessments

- Updates for vCore assessments, security updates and minor fixes