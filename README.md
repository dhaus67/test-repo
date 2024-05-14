# Test repo

Generic test repo to test out all sort of things related to GitHub Actions and any other random jazz.

## Roxctl

Contains a roxctl dispatch workflow which currently does the following:
- Based on a RHACS endpoint
- Retrieve credentials via GitHub OIDC
- Install roxctl
- Run a sample command (roxctl central whoami)
- On a Linux, MacOS(AMD), MacOS(M1), and Windows runner
