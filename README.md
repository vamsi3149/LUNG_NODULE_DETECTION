### 1. Preprocess.ipynb
- **Purpose**: This notebook is focused on preprocessing medical imaging data.
- **Libraries Used**: 
  - `os`, `cv2`, `copy`, `numpy`, `pandas`, `glob`, `tqdm`, `SimpleITK`, `matplotlib.pyplot`, `sklearn.cluster`, and `skimage.measure`.
- **Dataset Handling**: The root directory and target directory for the dataset are defined. The dataset appears to be the LUNA16 dataset, and the code reads annotations from a CSV file.
- **File Counts**: The notebook counts the number of files and displays the first few rows of the annotation DataFrame.

Now, let's proceed with summarizing the second notebook, `2. Dataset_preparation.ipynb`.

### 2. Dataset_preparation.ipynb
- **Purpose**: This notebook handles the preparation of the dataset for training and testing.
- **Libraries Used**: 
  - `numpy`, `os`, `random`, `tqdm`, `IPython.display`.
- **Dataset Handling**: 
  - The names of the lung ROI files are listed and shuffled.
  - The dataset is split into training and testing sets, with 80% for training and 20% for testing.



# Project Title

## Project Description
A brief overview of what the project does and its purpose. This project involves preprocessing medical imaging data, preparing datasets, and training and testing a UNet model for segmentation.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation
Step-by-step instructions on how to set up and run the project. This may include:
1. Clone the repository
    ```sh
    git clone https://github.com/your_username/your_project_name.git
    ```
2. Navigate to the project directory
    ```sh
    cd your_project_name
    ```
3. Install the required packages
    ```sh
    pip install -r requirements.txt
    ```

## Usage
Instructions on how to use the notebooks:

### 1. Preprocess.ipynb
- **Purpose**: Preprocess medical imaging data.
- **How to Run**: Open the notebook and run all cells. Ensure the dataset is in the specified root directory.

### 2. Dataset_preparation.ipynb
- **Purpose**: Prepare the dataset for training and testing.
- **How to Run**: Open the notebook and run all cells. It splits the dataset into training and testing sets.

### 3. UNet_Training.ipynb
- **Purpose**: Train the UNet model.
- **How to Run**: Open the notebook and run all cells. Ensure the dataset is prepared and paths are correctly set.

### 4. UNet_testing.ipynb
- **Purpose**: Test the trained UNet model.
- **How to Run**: Open the notebook and run all cells. Ensure the model is trained and paths are correctly set.

## Features
- Preprocess medical imaging data.
- Split data into training and testing sets.
- Train a UNet model.
- Test the trained UNet model.

## Contributing
Guidelines for contributing to the project:
1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.


