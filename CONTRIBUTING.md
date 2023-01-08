# Contributing

We welcome contributions to our project!

Before you start, please take a moment to review this document in order to make the contribution process easy and effective for everyone involved.

## Getting Started

- Make sure you have a [GitHub account](https://github.com/signup/free).
- Submit an issue, assuming one does not already exist.
  - Clearly describe the issue including steps to reproduce when it is a bug.
  - Make sure you use the latest version of the project.
- Fork the repository on GitHub.

## Making Changes

- Create a branch from where you want to base your work.
  - This is usually the `main` branch.
  - To quickly create a topic branch based on `main`, use `git branch my-contribution main` followed by `git checkout my-contribution`.
- Make commits of logical units.
- Check for unnecessary whitespace with `git diff --check` before committing.
- Make sure your commit messages are in the proper format.
  - Your commit message should contain a brief summary of your changes, written in the imperative mood and less than 50 characters long, followed by a blank line and then a more detailed explanation of your changes.
  - The summary should be in the imperative mood (e.g. "Add feature" instead of "Adding feature" or "Added feature") and should not end with a period.
  - If your commit pertains to an open issue, you should include a reference to it in the commit message (e.g. "Fixes #123").
- Make sure you have added the necessary tests for your changes.
- Run all tests and ensure that all pass.
- Run all lints to ensure that your code follows our style guidelines.

## Submitting Changes

- Push your changes to a topic branch in your fork of the repository.
- Submit a pull request to the original repository.
- The PR should include a description of your changes and why you are making them.
- The PR should also include relevant issue numbers if applicable.
- The PR should be reviewed by at least one other developer before being merged.

## Additional Resources

- [General GitHub documentation](https://help.github.com/)
- [GitHub pull request documentation](https://help.github.com/articles/creating-a-pull-request/)
