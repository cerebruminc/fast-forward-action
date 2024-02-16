# fast-forward-action

This GitHub Action is designed to facilitate a fast-forward merge process for projects. It is triggered via a workflow call, allowing it to be reused across different repositories and workflows.
This action is designed to be used in conjunction with the [MergeFreeze](https://www.mergefreeze.com/) platform, which provides a token for the `MERGEFREEZE_TOKEN` secret. When this workflow runs, it will unfreeze the branch and then merge the pull request, and finally freeze the branch again.

### How it Works

1. **Trigger**: The action is triggered when a specific comment (`/fast-forward`) is made on a pull request. This is checked against the `comment_body` input in the workflow.
2. **Validation**: Upon being triggered, the action first validates if the pull request is mergeable and if the base branch of the pull request is either `demo`, `staging`, or `production`. This ensures that the action only proceeds with fast-forward merges that are safe and meet the predefined criteria.
3. **Merge Process**: If the validation checks pass, the action attempts a fast-forward merge from the compare branch to the base branch. This is done while ensuring that the merge adheres to the fast-forward policy, maintaining a linear history.

### Usage

```yml
on:
  issue_comment:

jobs:
  fast-forward:
    uses: cerebruminc/fast-forward-action/.github/workflows/index.yml@master
    secrets:
      GITHUB_AUTH_TOKEN: ${{ secrets.GHA_NODEJS_TOKEN }}
      MERGEFREEZE_TOKEN: ${{ secrets.MERGEFREEZE_TOKEN }}
```

### Secrets

- **`GITHUB_AUTH_TOKEN`**: A GitHub token is required to interact with GitHub's API for fetching pull request details and performing the merge operation.
- **`MERGEFREEZE_TOKEN`**: A token from the MergeFreeze platform is required to freeze and unfreeze branches as part of the merge process.
