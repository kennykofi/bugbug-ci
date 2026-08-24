
# bugbug-ci

Runs the involve.me BugBug E2E suites in CI via GitHub Actions.

## How it runs

Manually via the Actions tab, and nightly at 04:00 UTC.
A full run takes around 11 minutes.

## Adding a suite

Add a name/id pair to the matrix in .github/workflows/bugbug.yml.
Suite IDs come from the BugBug suite URL.


End-to-end test suite run in CI via BugBug Cloud Runner and GitHub Actions
