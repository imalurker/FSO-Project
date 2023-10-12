# Free-Space Optical Communication (FSO) Power Predictor


## Overview

This project focuses on predicting Free-Space Optical (FSO) communication power levels based on visibility range and Signal-to-Noise Ratio (SNR). By estimating power levels accurately, network operators can optimize performance and reliability.

## Getting Started

### Prerequisites

Make sure you have the following prerequisites installed:

- Python (3.x recommended)
- Jupyter Notebook
- Required Python libraries: pandas, scikit-learn, and matplotlib (install using pip or conda)

### Usage

1. Launch Jupyter Notebook in the project directory:

    ```
    jupyter notebook
    ```

2. Open and run the `free-space-optical-communication.ipynb` notebook to train and evaluate the linear regression model.

## Data

The dataset is stored in the `Dataset/` directory. Replace the placeholder dataset file with your own data in CSV format. The dataset creation process is ongoing.

## Model Training

The Jupyter Notebook contains Python code for:

- Data loading and preprocessing.
- Model selection and training (linear regression).
- Model evaluation using Mean Squared Error (MSE).

## Results

The model's performance is evaluated using the Mean Squared Error (MSE) metric. A low MSE indicates a strong fit between the predicted "Power" values and the actual data.

## Contributors

- **KumaR Shivam** - [GitHub]([insert_github_url_here](https://github.com/imalurker))

Acknowledgment:

- Faculty: **Dr. Sasithra Anbalagan** and **Sowmyaa Vathsan**

## License

This project is licensed under the [MIT License](LICENSE).
