<!-- BADGES:START -->
[![CI](https://github.com/POps-Rox/tf-overlays-baseline/actions/workflows/ci.yml/badge.svg)](https://github.com/POps-Rox/tf-overlays-baseline/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/POps-Rox/tf-overlays-baseline/pulls)
[![Maintained](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/POps-Rox/tf-overlays-baseline/graphs/commit-activity)
[![Terraform](https://img.shields.io/badge/Terraform-%3E%3D1.5-623CE4.svg?logo=terraform)](https://www.terraform.io)
<!-- BADGES:END -->

# Azure NoOps Terraform Baseline

Azure NoOps Terraform Baseline Guide (ETB) is a collection of tutorials amd guides on how to get started with Terraform in Azure NoOps.

Documentation and guides are hosted in this [GitHub repository](https://github.com/POps-Rox/terraform-overlays-baseline).

## Development

### Windows

1. Install Python:

    ```console
    winget install --id "Python.Python.3.12" -e
    ```

1. Restart your machine to complete the installation.

1. Create and activate virtual environment:

    ```console
    python -m venv "venv" . "venv\Scripts\activate"
    ```

1. Install requirements:

    ```console
    python -m pip install --upgrade pip pip install -r "requirements.txt"
    ```

1. Run development server:

    ```console
    mkdocs serve
    ```

### Container

1. Read [this document](https://code.visualstudio.com/docs/devcontainers/containers).

1. Open this repository in the development container.

1. Run the development server:

    ```console
    mkdocs serve
    ```

## Contributing

See [Contributing guidelines](CONTRIBUTING.md).
