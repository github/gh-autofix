# `gh-autofix`

_Code scanning autofix is currently in [public beta](https://github.blog/2024-03-20-found-means-fixed-introducing-code-scanning-autofix-powered-by-github-copilot-and-codeql/)_

A `gh` CLI extension allowing users to easily edit autofix suggestions in their local repository checkout.

## Installation

Requires the [GitHub CLI extension](https://cli.github.com/).

```bash
gh extension install github/gh-autofix
```

For usage see help outout.

```bash
gh autofix --help
```

## Background

The `gh-autofix` extension for the `gh` CLI allows users to view and apply autofix suggestions made on their pull requests. See the [code scanning autofix documentation](https://docs.github.com/en/code-security/code-scanning/managing-code-scanning-alerts/about-autofix-for-codeql-code-scanning) for more information.

Code scanning autofix is currently in public beta, see the [announcement post for more details](https://github.blog/2024-03-20-found-means-fixed-introducing-code-scanning-autofix-powered-by-github-copilot-and-codeql/).

## Requirements

Requires the [GitHub CLI extension](https://cli.github.com/), see [Installation](#installation) above.

## License

This project is licensed under the terms of the MIT open source license. Please refer to [MIT](./LICENSE) for the full terms.

## Maintainers

See [CODEOWNERS](./CODEOWNERS)

## Support

See [SUPPORT](./SUPPORT.md)
