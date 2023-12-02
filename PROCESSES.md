### Branch Protection Rules

The `main` branch is protected and the following settings are configured:

- Require pull request reviews before merging: 1
  > When enabled, all commits must be made to a non-protected branch and submitted via a pull request with the required number of approving reviews and no changes requested before it can be merged into a branch that matches this rule.

  As many people rely on charts hosted in this repository each PR must be reviewed before it can be merged.
  
  - Dismiss stale pull request approvals when new commits are pushed

    > New reviewable commits pushed to a matching branch will dismiss pull request review approvals.

    This prevents that changes can be made unnoticed to already approved PRs.
    As a consequence of this every change made to an already approved PR will need another approval.