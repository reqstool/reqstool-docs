# Reqstool Documentation

[![Commit Activity](https://img.shields.io/github/commit-activity/m/reqstool/reqstool.github.io?label=commits&style=for-the-badge)](https://github.com/reqstool/reqstool.github.io/pulse)
[![GitHub Issues](https://img.shields.io/github/issues/reqstool/reqstool.github.io?style=for-the-badge&logo=github)](https://github.com/reqstool/reqstool.github.io/issues)
[![License](https://img.shields.io/github/license/reqstool/reqstool.github.io?style=for-the-badge&logo=opensourceinitiative)](https://opensource.org/license/mit/)
[![Build](https://img.shields.io/github/actions/workflow/status/reqstool/reqstool.github.io/publish_gh_pages.yml?style=for-the-badge&logo=github)](https://github.com/reqstool/reqstool.github.io/actions/workflows/publish_gh_pages.yml)
[![Documentation](https://img.shields.io/badge/Documentation-blue?style=for-the-badge&link=docs)](https://reqstool.github.io)

Central documentation site for the [reqstool](https://github.com/reqstool) ecosystem. Built with [Antora](https://antora.org/) and published to GitHub Pages.

**Live site:** [https://reqstool.github.io](https://reqstool.github.io)

## Included components

| Component | Source repo |
|-----------|------------|
| reqstool CLI | [reqstool-client](https://github.com/reqstool/reqstool-client) |
| Java Annotations | [reqstool-java-annotations](https://github.com/reqstool/reqstool-java-annotations) |
| Maven Plugin | [reqstool-java-maven-plugin](https://github.com/reqstool/reqstool-java-maven-plugin) |
| Gradle Plugin | [reqstool-java-gradle-plugin](https://github.com/reqstool/reqstool-java-gradle-plugin) |
| Python Decorators | [reqstool-python-decorators](https://github.com/reqstool/reqstool-python-decorators) |
| Hatch Plugin | [reqstool-python-hatch-plugin](https://github.com/reqstool/reqstool-python-hatch-plugin) |
| Poetry Plugin | [reqstool-python-poetry-plugin](https://github.com/reqstool/reqstool-python-poetry-plugin) |
| VS Code Extension | [reqstool-vscode-extension](https://github.com/reqstool/reqstool-vscode-extension) |
| TypeScript Tags | [reqstool-typescript-tags](https://github.com/reqstool/reqstool-typescript-tags) |
| AI Integration | [reqstool-ai](https://github.com/reqstool/reqstool-ai) |
| Demo Project | [reqstool-demo](https://github.com/reqstool/reqstool-demo) |

## Build locally

Prerequisites: Node.js 18+

```bash
# Install dependencies
npm install

# Build using local filesystem paths (requires all repos cloned as siblings)
npm run build:local

# Preview the built site
npm run preview
```

## Adding a new component

1. Add Antora docs structure to your repo (`docs/antora.yml`, `docs/modules/ROOT/pages/`, etc.)
2. Add the repo as a content source in `docs/antora-playbook.yml` and `docs/local-antora-playbook.yml`
3. Add navigation links in the landing page (`docs/modules/ROOT/pages/components.adoc`)

## Contributing

See the organization-wide [CONTRIBUTING.md](https://github.com/reqstool/.github/blob/main/CONTRIBUTING.md).

## License

MIT License.
