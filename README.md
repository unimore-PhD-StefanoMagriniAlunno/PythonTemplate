# Python Template
Repository template for python projects

## Get start
### Requirements
  - **Operative System Ubuntu 22.04 LTS**
    ```bash
    cat /etc/os-release
    ```
  - **Other installations:**
    ```bash
    git --version
    pdm --version
    ```
### Download and installation
  Use this template to make a new repository, and clone it in your device.

  Initialize your project with `pdm`:
  ```bash
  pdm init
  ```
  follow the procedures, then:
  ``` bash
  pdm add pre-commit black mypy pytest
  pdm run pre-commit install
  ```
