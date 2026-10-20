# Troubleshooting Job Monitoring

This topic describes common problems that can occur while
monitoring automated jobs.

## Job Displays Failed Status

### Possible causes

A job can fail when:

- A required dependency is unavailable.
- The configured service is not running.
- The job reaches its configured retry limit.

### Recommended checks

1. Verify that the required services are available.
2. Review the job details.
3. Check the configured retry settings.
4. Review the related application logs.

If the problem persists, contact the appropriate system
administrator.

---

## Job Does Not Appear

Verify that:

- Job Monitoring is enabled.
- Automated processing is enabled.
- Your account has the required permissions.
