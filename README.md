# actions-test-repo

## publish to npm on release
- git tag v0.1
- add create release
- add publish to npm on release
- if: github.event_name == 'push' || (github.event_name == 'pull_request' && github.event.action != 'closed')