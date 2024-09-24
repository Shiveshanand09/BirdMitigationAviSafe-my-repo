# Machine Learning Mini Project

This project demonstrates the use of machine learning techniques to analyze and classify data. A **Decision Tree Classifier** is applied to the dataset to predict specific outcomes based on the input features.

## Table of Contents
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Description

The purpose of this project is to apply machine learning algorithms to classify data. Specifically, we are using a **Decision Tree Classifier** to build a predictive model. The dataset used in this project is processed to extract relevant features and is split into training and testing sets.

## Dataset

The dataset is loaded from a CSV file containing information about various parameters:
- Date and Time
- Month
- Day Fraction
- Individual ID
- Altitude

## Technologies Used

The following Python libraries and technologies were utilized in the project:
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **scikit-learn**: For machine learning algorithms and model evaluation.
- **Jupyter Notebook**: For interactive coding and experimentation.

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/ml-mini-project.git
    ```

2. Navigate to the project directory:

    ```bash
    cd ml-mini-project
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter Notebook:

    ```bash
    jupyter notebook ML_Mini_project.ipynb
    ```

2. Run the notebook to:
   - Load and preprocess the dataset
   - Split the data into training and testing sets
   - Train the Decision Tree Classifier
   - Evaluate the model performance

3. The code for training the model and calculating accuracy can be found in the notebook.

## Results

The model's performance is evaluated using the **accuracy score** from the scikit-learn library. The accuracy indicates how well the model predicts the target variable based on the features.

## Contributing

Feel free to contribute to this project by submitting a pull request or opening an issue for discussion.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
