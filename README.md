# Jupyter-Boilerplate Project

This project provides configurations for using Jupyter and R together in VSCode. The `devcontainer.json` file specifies the Docker container configuration, leveraging the Remote-Containers feature in VSCode to provide a convenient, unified development environment.

## Getting Started

1. First, install VSCode, Docker, and the VSCode extension that enables the Remote-Containers feature.

2. Clone this repository:

    ```bash
    git clone https://github.com/Kishikawa1286/Jupyter-Boilerplate.git
    ```

3. Open VSCode and use the Remote-Containers feature to open the project. This will automatically create and start the Docker container as defined.

Or you can use GitHun Codespaces.

## How to Use R in Jupyter

1. Open a new notebook using the Jupyter feature in VSCode.

2. Click on the kernel selection dropdown in the upper right corner of the notebook.

3. From the dropdown menu, select 'R'.

Now, you are ready to run R code in your Jupyter notebook. You can add a new cell, input your R code, and execute it.

## Notes

This configuration uses the R kernel in Jupyter. Therefore, make sure to always select the R kernel when opening a Jupyter notebook. Otherwise, R code will not execute correctly.
