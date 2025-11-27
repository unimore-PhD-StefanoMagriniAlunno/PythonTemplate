# SciML
little repo with Scientific Machine Learning experiments

## Get start
### Requirements
  - **Operative System Ubuntu 22.04 LTS**
    ```bash
    cat /etc/os-release
    ```
  - **Nvidia CUDA Toolkit 12.4**
    ```bash
    nvidia-smi
    ```
  - **Python version 3.10**
    ```bash
    python3 --version
    ```
  - **Other installations:**
    ```bash
    git --version
    pdm --version
    ```
### Download and installation
  ```bash
  git clone https://github.com/unimore-PhD-StefanoMagriniAlunno/PythonTemplate
  cd PythonTemplate
  pdm init
  ```
  follow the procedures, then:
  ``` bash
  pdm add pre-commit black mypy pytest
  pdm run pre-commit install
  ```
