# NovaFlow 4.6 Release Notes

## About This Release

NovaFlow 4.6 introduces improvements to automated job processing,
administrator controls, and system notifications.

## What's New

### Enhanced Job Monitoring

Administrators can now monitor automated jobs from a centralized
dashboard.

The dashboard provides information about:

- Job status
- Start time
- Completion time
- Retry attempts

## Enhancements

### Improved Failure Notifications

Failure notifications now provide additional processing information
to help administrators investigate unsuccessful jobs.

### User Management Improvements

The User Management page has been updated to simplify user searches
and role assignment.

## Resolved Issues

### Job status did not refresh automatically

**Issue:** The job status displayed an outdated value under certain
processing conditions.

**Resolution:** The status refresh behavior has been updated so that
the latest available processing state is displayed.

### Role update required a new login

**Issue:** Permission changes were not reflected until the user
started a new session.

**Resolution:** Role updates now take effect after the user's
permissions are refreshed.

## Known Issues

### Delayed notification during high processing volume

Failure notifications may be delayed when a large number of jobs
are processed simultaneously.

## Configuration Impact

Review automated job-processing configurations after upgrading if
your environment uses custom retry settings.

## Before You Upgrade

Review:

- Current configuration
- Integration dependencies
- Custom roles
- Automated processing settings

Test the upgrade in a non-production environment before deployment.
