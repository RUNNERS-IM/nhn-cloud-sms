# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0] - 2024-06-07

### Added
- Initial release of the NHN Cloud SMS library
  - Added `NHNCloudSMS` class with methods:
    - `send_sms(recipient_number, message)`
    - `send_bulk_sms(recipient_numbers, message)`
    - `schedule_sms(recipient_number, message, schedule_time)`
    - `get_sms_status(request_id)`
    - `get_sent_sms_list(start_date, end_date)`
- Added `.env` file support for SMS library
  - Environment variables: `NHN_CLOUD_APP_KEY`, `NHN_CLOUD_SECRET_KEY`, `NHN_CLOUD_SENDER_PHONE_NUMBER`
- Comprehensive test coverage with `unittest` and support for mocking API calls using `unittest.mock`

### Changed
- None

### Fixed
- None
