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
### Project Initialization
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
### Test
  Test your repository with your first commit:
  ```bash
  git add .
  git commit -m "Project initialization"
  git pull
  git push
  ```

### Data Science suite
  This is a list of packages for data science studies.
  
  Notebook suite:
  ```bash
  pdm install jupyter ipykernel notebook jupyterlab nbconvert
  ```
  
  Data management suite:
  ```bash
  pdm install pandas numpy
  ```

  Data visualisation suite:
  ```bash
  pdm install matplotlib seaborn plotly
  ```
  
  Scientific calculus suite:
  ```bash
  pdm install scipy sympy scikit-learn statsmodels
  ```

  GPU NVIDIA boost suite:
  ```bash
  pdm install pytorch cudf cupy rapids
  ```

  Big Data suite:
  ```bash
  pdm install dask pyarrow fastparquet tensorflow
  ```
