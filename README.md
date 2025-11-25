# Applied ML Course Final Project: Regression Analysis

This project is a comprehensive regression analysis performed as the final project for the Applied Machine Learning course. It explores various regression techniques to model and predict outcomes based on a given dataset.

## Table of Contents
- Project Overview
- File Directory
- Getting Started
  - Prerequisites
  - Setup and Installation
- Running the Notebook
- Peer Review
 
---
 
## Project Overview
 
This project performs a regression analysis on a medical insurance dataset with the goal of predicting individual medical costs (`charges`). The analysis involves data exploration, preprocessing, and the training of multiple linear regression models, including those using `scikit-learn` pipelines with polynomial features. Model performance is compared using R-squared, MAE, and RMSE to determine the most effective approach.
 
---
 
## File Directory
 
- `regression_block.ipynb`: The main [Jupyter Notebook](https://github.com/matthewpblock/ml_regression_block/blob/main/regression_block.ipynb) containing all data preprocessing, analysis, model training, and evaluation.
- `peer_review.md`: Contains the [peer review](https://github.com/matthewpblock/ml_regression_block/blob/main/peer_review.md) feedback and analysis for this project.
- `data/`: Directory for storing the dataset(s). 
- `requirements.txt`: A list of all Python dependencies required to run the project.
 
---
 
## Getting Started
 
Follow these instructions to set up the project environment and run the analysis on your local machine.
 
### Prerequisites
 
- Python 3.8+
- `pip` and `venv`
 
### Setup and Installation
 
This project uses a dedicated virtual environment (`.venv`) called **ml_regression_block** to manage dependencies.
 
1.  **Clone the repository (or download the source code):**
    ```sh
    git clone <your-repository-url>
    cd ml_regression_block
    ```
 
2.  **Create and activate a virtual environment:**
 
    -   **Windows (PowerShell/CMD):**
        ```powershell
        python -m venv .venv
        .\.venv\Scripts\activate
        ```
 
    -   **macOS / Linux (Bash/Zsh):**
        ```sh
        python3 -m venv .venv
        source .venv/bin/activate
        ```
 
3.  **Install the required packages:**
 
    ```sh
    pip install -r requirements.txt
    ```
 
---
 
## Running the Notebook
 
VS Code’s kernel detection can sometimes fail, so the recommended workflow is to activate the environment and run Jupyter manually from your terminal.
 
1.  **Activate the virtual environment (if not already active):**
 
    - **Windows (PowerShell):**
      ```powershell
      .\.venv\Scripts\activate
      ```
    - **macOS / Linux (Bash/Zsh):**
      ```sh
      source .venv/bin/activate
      ```
 
2.  **Start the Jupyter Notebook server from your terminal:**
    ```sh
    jupyter notebook
    ```
 
3.  **Open the notebook:**
    Your web browser should open with the Jupyter interface. Click on `regression_block.ipynb` to open the notebook and run the cells.
 
---
 
## Peer Review
 
The peer review for this project can be found in the `peer_review.md` file.