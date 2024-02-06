# AutoStreamML

AutoStreamML is an automated machine learning pipeline developed using Streamlit. This application simplifies the process of data uploading, exploratory data analysis (EDA), machine learning model training, and model downloading.

## Features

- **Upload Data**: Users can upload their dataset in CSV format.
- **Automated EDA**: Generate profile reports from the dataset to understand its characteristics.
- **Machine Learning**: Train and compare multiple machine learning models on the dataset.
- **Download Model**: Download the best-performing model.

## Getting Started

### Prerequisites

Before running AutoStreamML, ensure you have the following installed:
- Python
- Streamlit
- Pandas
- Pandas Profiling
- PyCaret

### Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/manikantpandey/AutoML-WebApp.git
```

Navigate to the cloned directory and install the required packages:
```bash
pip install -r requirements.txt
```

# Running the Application
## Start the Streamlit server:
```bash
streamlit run app.py
```
# Usage
**Upload:** Navigate to the 'Upload' section to upload your CSV dataset.
**Profiling:** After uploading, switch to the 'Profiling' section to view an automatic EDA report.
**Machine Learning:** Go to the 'ML' section to train and compare models. Select your target variable and click 'Train Model'.
*Download:** Access the 'Download' section to download the trained model.

# Contributing
Contributions to improve AutoStreamML are welcome. Please fork the repository and create a pull request with your features or fixes.

# License
This project is licensed under the MIT License - see the LICENSE.md file for details.

