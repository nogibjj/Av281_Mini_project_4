# Mini Project 4 for IDS706 fall 2023
[![Matrix Test python 3.8, 3.9, 3.10, 3.11](https://github.com/nogibjj/Av281_Mini_project_4/actions/workflows/python.yml/badge.svg)](https://github.com/nogibjj/Av281_Mini_project_4/actions/workflows/python.yml)
Python template with matrix testing on python versions 3.8, 3.9, 3.10, and 3.11 to be used for GitHub codespaces

## Project Structure

- **`Jupyter Notebook(src/desc_stats.ipynb)`**:
  - Contains cells that perform descriptive statistics using Pandas.
  - Validated using the nbval plugin for pytest.

- **`Python Script(src/main.py)`**:
  - Executes the same descriptive statistics using Pandas.

- **`lib.py(src/lib.py)`**:
  - Holds shared code used by both the script and the notebook.

- **`Makefile`**:
  - Contains four commands (Run by GitHub Workflows on each Push and Pull):
    - `Test`: Run all tests (notebook, script, and lib)
    - `Format`: Format code with Python black
    - `Lint`: Lint code with Ruff
    - `OnInstall`: Install dependencies via `pip install -r requirements.txt`

- **`test_script.py(tests/test_main.py)`**:
  - Contains tests for the Python script.

- **`Pinned requirements.txt`**:
  - Specifies exact versions of dependencies.

- **`Github Actions Workflow`**:
  - Install Requirements, Format, Lint, Test, and Run Main.py


## Workflow

## Matrix Testing Strategy:
<p align = "center"><img width="1000" alt="Screenshot 2023-09-11 at 11 55 09 AM" src="https://github.com/nogibjj/Av281_Mini_project_4/blob/main/Images_for_mini_project_4/Matrix.png"></p>

### Install Dependencies
  - pip install everything in the requirements.txt file

### Linting
<p align = "center"><img width="417" alt="Screenshot 2023-09-11 at 11 55 09 AM" src="https://github.com/nogibjj/Av281_Mini_project_4/blob/main/Images_for_mini_project_4/lint.png"></p>    

### Testing
<p align = "center"><img width="1000" alt="Screenshot 2023-09-11 at 11 53 56 AM" src="https://github.com/nogibjj/Av281_Mini_project_4/blob/main/Images_for_mini_project_4/test.png"></p>

### Formatting
<p align = "center"><img width="407" alt="Screenshot 2023-09-11 at 11 53 56 AM" src="https://github.com/nogibjj/Av281_Mini_project_4/blob/main/Images_for_mini_project_4/format.png"></p>

### Run Main Script
<p align = "center"><img width="417" alt="Screenshot 2023-09-11 at 11 55 09 AM" src="https://github.com/nogibjj/Av281_Mini_project_4/blob/main/Images_for_mini_project_4/Run.png"></p>

### Data Visualization
<p align = "center"><img width="1000" alt="Screenshot 2023-09-11 at 11 55 09 AM" src="https://github.com/nogibjj/Av281_Mini_project_4/blob/main/Images_for_mini_project_4/datavis.png"></p>

