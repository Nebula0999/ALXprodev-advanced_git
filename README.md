# ALXprodev-advanced_git
## Hook Directory

The `hook` directory contains scripts that automate tasks at various points in the Git workflow. Each file corresponds to a specific Git hook:

- **pre-commit**: Checks code formatting and runs tests before allowing a commit. Prevents commits if checks fail.
- **commit-msg**: Validates the commit message format to ensure consistency and adherence to project guidelines.
- **pre-push**: Runs additional tests or checks before code is pushed to a remote repository, blocking the push if any check fails.
- **post-merge**: Executes scripts after a successful merge, such as installing dependencies or notifying team members.

These hooks help maintain code quality and enforce project standards automatically.