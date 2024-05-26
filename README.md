# GDZ-Datathon

This repository contains the code and resources for the GDZ-Datathon project. The project includes two Jupyter notebooks: `main.ipynb` and `utils.ipynb`, and a `requirements.txt` file for setting up the required Python environment.

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Usage](#usage)
- [Files](#files)
- [Contributing](#contributing)
- [License](#license)

## Overview

The GDZ-Datathon project is designed to process and analyze data, specifically focusing on predicting `bildirimsiz_sum` values for various districts using machine learning models. The project uses a combination of data preprocessing, feature extraction, model training, and prediction to achieve this goal.

## Setup

To set up the environment and run the notebooks, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/gdz-datathon.git
    cd gdz-datathon
    ```

2. **Create a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Download the Weather Data**:
    - The weather data is too large to be included in the GitHub repository directly. Please download the weather data from the following link and place it in the `gdz-datathon-data` directory:
        - [Download Weather Data](https://drive.google.com/file/d/1quUNUw8PzK2ajUzno6dZEGhJRGMN_1OA/view?usp=sharing)

## Usage

The project consists of two main notebooks: `main.ipynb` and `utils.ipynb`.

- `main.ipynb`: This notebook contains the main workflow for loading data, preprocessing, training models, and making predictions.
- `utils.ipynb`: This notebook contains utility functions used throughout the project.

### Running the Notebooks

1. **Open Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

2. **Open and run `main.ipynb`**:
    - Load the notebook in your browser.
    - Follow the instructions and execute the cells sequentially.

3. **Open and run `utils.ipynb`**:
    - Load the notebook in your browser.
    - This notebook should be run to ensure all utility functions are available for `main.ipynb`.

## Files

- **main.ipynb**: The main Jupyter notebook containing the core analysis and model training pipeline.
- **utils.ipynb**: A notebook containing utility functions used in `main.ipynb`.
- **requirements.txt**: A file listing the required Python packages to run the notebooks.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please create an issue or submit a pull request.

### How to Contribute

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature-branch`)
6. Create a new Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

