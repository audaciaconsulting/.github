# Contributing to Audacia Projects

Thank you for your interest in contributing to one of Audacia's open source projects! We welcome contributions from the community to help improve our projects. This guide will provide you with the necessary information and guidelines to make the contribution process smooth and effective.

## Feature Request

If there is a feature in a project that you would like to suggest, please open an issue with the following information:

- A clear and descriptive title summarizing the feature request.
- A description of your use case, i.e. why the feature is required.
- An indication as to whether or not you would like to implement the feature yourself.

## Issue Reporting

If you encounter any issues or bugs while using our projects, we appreciate your feedback. When reporting an issue, please provide the following information:

- A clear and descriptive title summarizing the issue.
- Detailed steps to reproduce the issue.
- Expected behavior and actual behavior observed.
- Any relevant error messages or logs.

## Getting Started

To get started with contributing to Audacia projects, please follow these steps:

1. Fork the repository to your GitHub account.
2. Clone the forked repository to your local machine.
3. Create a new branch for your changes: `git checkout -b my-branch-name`.
4. Make your desired changes and improvements to the codebase.
5. Commit your changes with descriptive commit messages: `git commit -am 'feat: Add new feature'`.
   - Note we prefer [conventional commits](https://www.conventionalcommits.org/).
6. Push the changes to your forked repository: `git push origin my-branch-name`.
7. Open a pull request on the main repository.

### Code Guidelines

To maintain consistency and readability, please adhere to the following guidelines when contributing to Audacia projects:

- Follow the existing code style and formatting conventions.
- Write clear and concise code with meaningful variable and function names.
- Document any public APIs, classes, or functions using appropriate comments.
- Add unit tests for new features and ensure existing tests pass.
- Run the code through linting and formatting checks before submitting a pull request.

### Pull Request Guidelines

When submitting a pull request, please consider the following guidelines:

- Provide a clear and descriptive title for your pull request.
- Include a summary of the changes made and their purpose.
- Reference any related issues by mentioning them in the pull request description.
- Ensure that your branch is up to date with the main/master branch before submitting the pull request.
- Be responsive to any feedback or questions during the review process.

Our code review guidelines are documented [here](https://audacia.co.uk/technical-blog/our-guidelines-for-code-review).

### Recording Change History

Before submitting a pull request, please ensure that the changes have been documented in the relevant `CHANGELOG.md`

### Versioning

Audacia libraries previously utilised a versioning system that would automatically iterate the patch numbers in instances where neither the major or minor number had been altered and determined if a package was to be marked as prerelease based on the branch name (a name other than `main` or `master`).
This functionality has been removed in favour of a manual system where the branch is tagged and released under whatever version number has been entered in either the CSPROJ or package.json.
Update version numbers according to the significance of the change being added.
To mark a version as `prerelease`, add the to the end of the number `-prerelease`.

## License

By contributing to the Audacia project, you agree that your contributions will be licensed under the [MIT License](https://mit-license.org/).

---

We appreciate your contributions to Audacia, and we value your time and effort in making our projects better. Thank you for your support!
