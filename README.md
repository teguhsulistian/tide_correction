# TIDE CORRECTION

## Important note

This repository is initial work in developing tide correction for various tide correction purposes (image tagging, echosounder correction, and tide prediction)

## Installation

### Environment Setup using uv

1. **Clone the repository**

    Clone the `tide-correction` repository:

    ```bash
    git clone https://github.com/teguhsulistian/tide_correction.git
    cd indonesia-coastlines
    ```

2. **Create a new environment using uv**

    Move to the repository directory and create a new environment using `uv`, then activate the environment:

    ```bash
    uv venv
    .venv\Scripts\activate   
    ```

3. **Install required packages**

   Install the required packages for `indonesia-coastlines`:

    ```bash
    uv pip install -e .
    ```

4. **Register the ipykernel package**

   Register the `ipykernel` package to use the Jupyter notebooks:

    ```bash
    python -m ipykernel install --user --name=tide_correction --display-name "Python (tide_correction)"
    ```

5. **Deactivate the environment**

   When you are done working in the environment, you can deactivate it:

    ```bash
    deactivate
    ```

