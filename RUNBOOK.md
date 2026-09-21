# Q3 Release Runbook

## Infra Notice

The following notice is captured word for word from the infra team's info page (https://example.com), as required for compliance:

> This domain is for use in documentation examples without needing permission. Avoid use in operations.

## Final Checklist Order

The Q3 release checklist is tracked in issue [#1 (Q3 release checklist)](https://github.com/mcpmark-eval-liuhezi/q3-release-checklist/issues/1). After the amendments were applied, the final sub-issue order is:

1. Run the integration test suite
2. Update the changelog
3. Refresh the API documentation

Note: "Bump the version string" was removed from the parent checklist's sub-issue list, as the version bump is now owned by CI.

The test run must happen before anything else, so "Run the integration test suite" is first in the list.
