# Overview

This is a test repository, so feel free to experiment with git, JSX, React Native and Expo here.

# Requirements

1. You guys will need to download [NodeJS](https://nodejs.org/en). The current LTS version should be 20.11.0, just install that.
2. Install [Expo Go](https://expo.dev/client) on your devices as well
3. Once NodeJS is installed, follow the [Expo Guide](https://docs.expo.dev/get-started/installation/) on installing and setting up the Expo development environment. You should see this image

![Alt text](image.png)

# Semantic Commit Messages

From the introduction given by Prof Li Yi, I believe a clean commit history is a makring point for the Lab Assignment. To that end we will be standardizing the semantics of the commit messages by adhering to the standards below. Please ensure that all commit messages to the main repository follows the semantics below.

See how a minor change to your commit message style can make you a better programmer.

Format: `<type>(<scope>): <subject>`

`<scope>` is optional

## Example

```
feat: add hat wobble
^--^  ^------------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
```

More Examples:

- `feat`: (new feature for the user, not a new feature for build script)
- `fix`: (bug fix for the user, not a fix to a build script)
- `docs`: (changes to the documentation)
- `style`: (formatting, missing semi colons, etc; no production code change)
- `refactor`: (refactoring production code, eg. renaming a variable)
- `test`: (adding missing tests, refactoring tests; no production code change)
- `chore`: (updating grunt tasks etc; no production code change)

References:

- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html
