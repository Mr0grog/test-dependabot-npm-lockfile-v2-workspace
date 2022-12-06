# Example of Dependabot (non) Issue with NPM Lockfile v2 and Workspaces

Dependabot is not updating the `package-lock.json` file for NPM *workspaces* that use version 3 lockfiles. (It works fine for non-workspaces repos.)

The repo demonstrates working functionality with version 2 lockfiles. Compare the Dependabot PRs here to those in https://github.com/Mr0grog/test-dependabot-npm-lockfile-v3-workspace.
