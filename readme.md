GitHub provides some default environment variables for many useful parameters of your repository. We can use them anywhere inside the workflow.

Here is a list of default env variables in GitHub Actions
GITHUB_WORKFLOW The name of the workflow.
GITHUB_RUN_ID A unique number for each run within a repository. This number does not change if you re-run the workflow run.

GITHUB_RUN_NUMBER A unique number for each run of a particular workflow in a repository. This number begins at 1 for the workflow's first run, and increments with each new run. This number does not change if you re-run the workflow run.

GITHUB_ACTION The unique identifier (id) of the action.

GITHUB_ACTIONS Always set to true when GitHub Actions is running the workflow. You can use this variable to differentiate when tests are being run locally or by GitHub Actions.

GITHUB_ACTOR The name of the person or app that initiated the workflow.

GITHUB_REPOSITORY The owner and repository name.

GITHUB_EVENT_NAME The name of the webhook event that triggered the workflow.

GITHUB_EVENT_PATH The path of the file with the complete webhook event payload.

GITHUB_WORKSPACE The GitHub workspace directory path.

GITHUB_SHA The commit SHA that triggered the workflow.

GITHUB_REF The branch or tag ref that triggered the workflow.

GITHUB_HEAD_REF Only set for forked repositories. The branch of the head repository.

GITHUB_BASE_REF Only set for forked repositories. The branch of the base repository.

GITHUB_SERVER_URL Returns the URL of the GitHub server.

GITHUB_API_URL Returns the API URL.

GITHUB_GRAPHQL_URL Returns the GraphQL API URL