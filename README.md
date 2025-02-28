
# Useful Workflows

This repository contains a collection of GitHub Actions workflows designed to automate various tasks for your projects.

## Workflows

### 1. Single Pip Dependabot
- **File:** `single_pip_dependabot.yml`
- **Description:** Automates dependency updates for Python projects using pip.
- **Schedule:** Daily

### 2. Restyled
- **File:** `restyled.yml`
- **Description:** Automatically restyles pull requests using Restyled.io.
- **Trigger:** On pull request

### 3. NPM Dependabot
- **File:** `npm_dependabot.yml`
- **Description:** Automates dependency updates for Node.js projects using npm.
- **Schedule:** Daily

### 4. Next.js Deploy
- **File:** `nextjsdeploy.yml`
- **Description:** Builds and deploys a Next.js site to GitHub Pages.
- **Trigger:** On push to the main branch and manual dispatch

### 5. Markdown Formatting
- **File:** `markdown_formatting.yml`
- **Description:** Formats Markdown files using Prettier.
- **Trigger:** On push or pull request for Markdown files

### 6. Jupyter Notebook Formatting
- **File:** `jupyter_notebook_formatting.yml`
- **Description:** Formats Jupyter notebooks using Black.
- **Trigger:** On push or pull request

### 7. Batch Pip Dependabot
- **File:** `batch_pip_dependabot.yml`
- **Description:** Automates dependency updates for Python projects using pip, batching updates weekly.
- **Schedule:** Weekly

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Code of Conduct

This project adheres to a [Code of Conduct](./CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

