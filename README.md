# PR Review Agent Acceptance Fixture

This intentionally small public repository exercises live GitHub App acceptance.

Base-refresh fixture: open pull requests must be reviewed against this revision.

Live-base resolver fixture: the App must use the branch tip, not PR payload history.

The failing branch intentionally keeps the calculator regression reproducible.
