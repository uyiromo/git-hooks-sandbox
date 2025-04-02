# git-hooks-sandbox

## Hooks

The `hooks/` directory contains custom git hooks for various Git operations. Below is the list of files in this directory:

- `applypatch-msg`
- `commit-msg`
- `fsmonitor-watchman`
- `post-update`
- `pre-applypatch`
- `pre-commit`
- `pre-merge-commit`
- `pre-push`
- `pre-rebase`
- `pre-receive`
- `prepare-commit-msg`
- `push-to-checkout`
- `sendemail-validate`
- `update`

## Using the Hooks

Set the `core.hooksPath` configuration locally in your Git repository:

```bash
git config --local core.hooksPath $(realpath hooks)
```
