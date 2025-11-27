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
  follow the procedure
  ``` bash
  pdm install
  pdm run pre-commit install
  ```
### Issues
  If you have more version of python in your system, it's possible read the following **WARNING**:
  ```bash
  WARNING: Project requires a python version of ==3.10.*, The virtualenv is being created for you as it cannot be matched to the right version.
  ```
  Check the version of used python with:
  ```bash
  pdm info
  ```
