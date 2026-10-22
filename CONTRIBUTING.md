# Contributing

Everyone taking part follows the [code of conduct](CODE_OF_CONDUCT.md). The repository's README says how to set it
up and run its checks.

## Pull requests

- One change per pull request, with tests for the behaviour it changes.
- Every pull request runs the repository's CI; its last job, `ci`, must pass before a merge.
- Pull requests are squash-merged: the title becomes the commit subject and the description its body, so the title
  follows [Conventional Commits](https://www.conventionalcommits.org/) (`fix: retry failed uploads`).
- Report security problems privately, as [SECURITY.md](SECURITY.md) describes, not in an issue or pull request.
