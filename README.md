# playground-release-tag-with-github-actions

This is a playground to find how tag and release work with github-actions.

This is setup as follow:

- [`pre-release`](/.github/workflows/pre-release%20copy.yml) One CI to push pre-release when a push is appended on master
- [`release`](/.github/workflows/release.yml)Another one to publish a release when a new tag is pushed
