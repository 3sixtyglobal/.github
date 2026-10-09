# 3Sixty Global .github

Organisation-wide default community health files for the [3sixtyglobal](https://github.com/3sixtyglobal) GitHub organisation.

GitHub uses the files in this repository as defaults for any repository in the organisation that does not define its own versions. A repository can override any of these by adding a file with the same name to its own `.github` folder.

## Contents

### Issue Templates

Located in [ISSUE_TEMPLATE](ISSUE_TEMPLATE). Blank issues are disabled via [config.yml](ISSUE_TEMPLATE/config.yml), so every issue must use one of the templates below.

| Template                                              | Title prefix | Labels                          | Purpose                                                          |
| ----------------------------------------------------- | ------------ | ------------------------------- | ---------------------------------------------------------------- |
| [Bug report](ISSUE_TEMPLATE/bug-report.md)            | `bug: `      | `bug`, `needs-triage`           | Report a defect with reproduction steps and environment details  |
| [Feature request](ISSUE_TEMPLATE/feature-request.md)  | `feat: `     | `enhancement`, `needs-triage`   | Propose a new feature or enhancement                             |
| [Chore](ISSUE_TEMPLATE/chore.md)                      | `chore: `    | `chore`, `needs-triage`         | Maintenance work such as dependency, tooling or config updates   |
| [Documentation](ISSUE_TEMPLATE/documentation.md)      | `docs: `     | `documentation`, `needs-triage` | Add or improve documentation for a feature, API or process       |
| [Spike](ISSUE_TEMPLATE/spike.md)                      | `spike: `    | `spike`, `needs-triage`         | Time-boxed research or investigation of a technical topic        |

All templates apply the `needs-triage` label so new issues can be reviewed and prioritised.

### Pull Request Template

[PULL_REQUEST_TEMPLATE.md](PULL_REQUEST_TEMPLATE.md) is used for every new pull request. It asks for a description, the type of change, a summary of the changes made and the testing performed.

## Contributing

Changes to this repository affect every repository in the organisation that relies on the defaults, so keep edits focused and raise a pull request for review.

When adding a new issue template, make sure the labels it references exist in the target repositories, otherwise GitHub will not apply them.
