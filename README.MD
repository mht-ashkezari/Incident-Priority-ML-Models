# Incident Prioritization Using Machine Learning Models in Jupyter Notebook (VSCode)

## Introduction
This project aims to develop a machine learning model for prioritizing IT support incidents. The models used are Random Forest and Gradient Boosting Machines (GBM), trained and evaluated on the 'Incident management process enriched event log' dataset. The goal is to predict the priority of incidents, even when critical features like 'impact' and 'urgency' are unavailable. This document provides instructions for running the project code in a Jupyter Notebook within Visual Studio Code (VSCode), using Conda as the Python interpreter.

## Dataset

The dataset used for this project is too large to be included in the repository. You can download it from [Google Drive](https://drive.google.com/file/d/1GbSwxXyRnevFH2WmIk3C0sT6a8x1fFd1/view?usp=sharing).

Once downloaded, place the `incident_event_log.csv` file in the `ML_FinalPrj` folder.


## Prerequisites
- Visual Studio Code must be installed along with the Jupyter extension.
- A Conda environment should be set up and selected as the Python interpreter.
- The following libraries are required in your Conda environment: `imblearn`, `matplotlib`, `numpy`, `pandas`, and `sklearn`. Install them using Conda or pip.

## Instructions for Running the Code

### Running All Code at Once
To run all the code in the Jupyter Notebook:
1. Open the Jupyter Notebook file (`finalProject.ipynb`) in VSCode.
2. Ensure the correct Conda environment is activated.
3. Click on the 'Run All' button in the top right corner of the notebook or navigate to the 'Run' menu and select 'Run All Cells'.
4. The notebook will execute all code blocks sequentially, managing dependencies.

### Running Individual Code Blocks
To run individual code blocks:
1. Open the Jupyter Notebook file (`finalProject.ipynb`) in VSCode.
2. Ensure the correct Conda environment is activated.
3. Run the blocks in their intended order:
    - **Step 1**: Dataset inspection.
    - **Step 2-3**: Handle missing values (using different scenarios for Random Forest and GBM).
    - **Step 4-5**: Feature selection.
    - **Step 6**: Exploratory data analysis.
    - **Step 7**: Implement model functions.
    - **Steps 8-13**: Feature engineering, model building, and hyperparameter tuning.
4. Use the 'Run' button for each block or press `Shift + Enter` to execute.

## Additional Notes
- It is important to follow the order of execution for the code blocks to ensure accurate results.
- Steps 1 and 7 are prerequisites for their respective successors.
- Running all cells at once will maintain the dependencies and correct order of execution.

## Results Overview
- The models (Random Forest and GBM) achieved high accuracy in prioritizing incidents, with Random Forest being the better performer for deployment in real-world scenarios.

## Support
For any queries or assistance with this project, please feel free to reach out.
