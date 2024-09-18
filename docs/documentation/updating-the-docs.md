# Updating The Docs

This guide explains how to update the [broncobots-docs](https://github.com/FRCTeam1987/broncobots-docs) project.

## Prerequisites
- [Create a GitHub account.](../programming/github/create-an-account.md)
- Optional: [Be a member of the Broncobots organization.](../programming/github/join-the-organization.md)
- Optional: [Python](https://www.python.org/) and / or [Docker](https://docker.com), along with an IDE like [VSCode](https://vscode.dev/).

## Prepare for committing changes.
- If you are a member of the Broncobots organization, then [create a branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository#creating-a-branch) in this repository for the relevant change.
- If you are not a member of the Broncobots organization, then [create a fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo).
- Clone the repository or be comfortable making changes directly on GitHub.

## Adding Docs
1. Copy the template.md from the root directory and paste it to the appropriate directory in this project.
    - Create a new directory if needed.
2. Replace generic content from the template with the new specific information.
3. Update the mkdocs.yml file in the root directory with structure for the new content.

## Updating Docs
1. Edit the relevant files directly.

## Removing Docs
1. Delete the relevant files.
2. Remove references to the deleted files in the mkdocs.yml file in the root directory.

## Submitting Changes For Review
1. Commit your changes early and often.
2. Open a Pull Request to merge your changes into the `master` branch.
    - [From a branch.](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
    - [From a fork.](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)

## References
- MKDocs: [writing and structuring docs](https://www.mkdocs.org/user-guide/writing-your-docs/)
- Markdown cheat sheet: [formatting docs](https://github.com/im-luka/markdown-cheatsheet)

