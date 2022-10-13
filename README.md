<!--
  ** DO NOT EDIT THIS FILE
  **
  ** 1) Make all changes to `doc/README.yaml`
  ** 2) Run `make doc/build` to rebuild this file
  **
-->


![logo](doc/logo.png)


<!-- SHIELDS -->


<!-- TITLE & DESCRIPTION -->
# AWS Terraform Dev Container

A VSCode Dev Container with [tools][tools] to help you build and manage AWS infrastructure with Terraform

<!-- SCREENSHOTS -->

## Screenshots
---
<details open>
  <summary>Expand</summary>


| ![screenshot-1](doc/images/screenshot-1.gif) |
|:--:|
| *Develop your project in a Docker container* |

| ![screenshot-2](doc/images/screenshot-2.gif) |
|:--:|
| *Increase productivity with well-defined `Make` commands* |

| ![screenshot-3](doc/images/screenshot-3.gif) |
|:--:|
| *Ensure every team member has all the tools on their correct versions* |

| ![screenshot-4](doc/images/screenshot-4.png) |
|:--:|
| *Extensions already installed for you* |

</details>


## Table of Contents
---


 - [Usage](#usage) 
 - [Prerequisites](#prerequisites) 




 - [References](#references) 
 - [License](#license) 
 - [Copyright](#copyright) 

<!-- USAGE -->

## Getting started
---
1. On a terminal, inside your Terraform project, execute the following on Mac, Linux or [WSL][wsl]:
```bash
curl -sL https://raw.githubusercontent.com/awslabs/aws-terraform-dev-container/main/scripts/init.sh | bash
````
2. Open the folder with VSCode
3. Reopen in Container

To reopen in container manually, open the [command pallete](https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette) on VS Code and select `Rebuild and Reopen in Container`



<!-- PREREQUISITES -->

## Prerequisites
---
- [Docker](https://www.docker.com/products/docker-desktop/) - The fastest way to containerize applications
- [Visual Studio Code](https://code.visualstudio.com/) - Visual Studio Code is a code editor redefined and optimized for building and debugging modern web and cloud applications.
- [VSCode Remote Development Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack) - An extension pack that lets you open any folder in a container, on a remote machine, or in WSL and take advantage of VS Code's full feature set.



<!-- INSTALLATION -->


<!-- TESTING -->


<!-- DEPLOYMENT -->


<!-- INCLUDE OTHER DOCS -->

## Make

```
Available targets:

  aws/cli-version                     Display AWS CLI version
  checkov/run                         Run Checkov
  checkov/version                     Display checkov version
  doc/build                           Build README.md based on doc/README.yaml (and/or doc/.terraform-docs.yml)
  doc/init                            Initialize project's documentation
  gitignore/init                      Create a .gitignore file with most common rules
  go/install                          Install Golang
  gomplate/version                    Display Gomplate version
  go/version                          Display Go version
  help/clean                          Help screen
  init                                Initialize project with default configuration
  pre-commit/install-hooks            Install pre-commit hooks
  pre-commit/install                  Install pre-commit using Pip3
  pre-commit/run                      Execute pre-commit hooks on all files
  pre-commit/update                    Update pre-commit-config.yml with the latest version
  pre-commit/version                  Display pre-commit version
  python/install                      Install Python 3
  python/pip-install                  Install Python 3 Pip
  python/version                      Display Python & Pip version
  python/virtualenv-create            Create a Python 3 virtualenv in the current directory
  python/virtualenv                   Install Python 3 virtualenv
  terraform/apply                     Builds or changes infrastructure according to Terraform configuration files in DIR
  terraform/clean                     Remove temporary files and directories
  terraform/destroy                   Destroy Terraform-managed infrastructure.
  terraform-docs/build                Build doc/terraform-docs.md with Terraform Docs
  terraform-docs/init                 Create initl configuration
  terraform-docs/version              Display Terraform Docs version
  terraform/fmt                       Check if the input is formatted. Exit status will be 0 if all input is properly formatted and non-zero otherwise.
  terraform/init/backend              Initialize a new or existing Terraform working directory by creating initial files, loading any remote state, downloading modules, etc.
  terraform/init                      Initialize a new or existing Terraform working directory by creating initial files, loading any remote state, downloading modules, etc.
  terraform/plan                      Generates an execution plan for Terraform
  terraform/validate                  Validate the configuration files in a directory, referring only to the configuration and not accessing any remote services such as remote state, provider APIs, etc.
  terraform/version                   Display Terraform version
  terrascan/run                       Run Terrascan
  terrascan/version                   Display Terrascan version
  tflint/init                         Init AWS TFLINT
  tflint/version                      Display TFLINT version
  tfsec/run                           Run TFSEC
  tfsec/version                       Display TFSEC version
  tfswitch/run                        Execute tfswitch
  tfswitch/version                    Display tfswitch version

```

<!-- TASKS -->


<!-- REFERENCES -->

## References
---
<details open>
  <summary>Expand</summary>

* [Terraform by HashiCorp][terraform] - Terraform is an open-source infrastructure as code software tool that enables you to safely and predictably create, change, and improve infrastructure.
* [VSCode Dev Container][vscode-dev-container] - The Visual Studio Code Remote - Containers extension lets you use a Docker container as a full-featured development environment.
* [Changelog](CHANGELOG.md) - Where all notable changes to this project are documented.
* [Code Of Conduct](CODE_OF_CONDUCT.md) - Amazon Open Source Code of Conduct
* [License](LICENSE) - Apache License Version 2.0


</details>


<!-- LICENSE -->

## License
---
This library is licensed under the MIT-0 License. See the [LICENSE][license] file.


<!-- COPYRIGHT -->

## Copyright
---
Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.


<!-- LINKS -->

[docker]: https://www.docker.com/products/docker-desktop/
[vscode-dev-container]: https://code.visualstudio.com/docs/remote/containers
[terraform]: https://www.terraform.io/
[license]: LICENSE
[tools]: TOOLS
[wsl]: https://learn.microsoft.com/en-us/windows/wsl/install


