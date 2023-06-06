# DiabatesPredictionAIModel
# Diabetes Prediction with Support Vector Machine (SVM)

This project aims to predict whether a person has diabetes or not using a Support Vector Machine (SVM) model. The prediction is based on certain features such as glucose level, blood pressure, body mass index (BMI), etc.

## Requirements

- Python 3.x
- scikit-learn
- pandas
- numpy

## Installation

To run this project, you need to have Python installed on your system. You can download Python from the official website: [https://www.python.org/downloads/](https://www.python.org/downloads/)

After installing Python, you can install the required packages by running the following command in your terminal:

```bash
pip install scikit-learn pandas numpy
```

## Dataset

The dataset used for this project is the Pima Indians Diabetes Database, which is publicly available at the UCI Machine Learning Repository: [https://archive.ics.uci.edu/ml/datasets/pima+indians+diabetes](https://archive.ics.uci.edu/ml/datasets/pima+indians+diabetes)

The dataset consists of several features such as number of pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, and age. The target variable indicates whether a person has diabetes (1) or not (0).

## Usage

1. Clone this repository:

```bash
git clone https://github.com/manushadananjaya/DiabetesPredictionAIModel.git
```

2. Navigate to the project directory:

```bash
cd diabetes-prediction
```

3. Run the `DiabatesPredictionProject.py` script:

```bash
python DiabatesPredictionProject.py
```

The script will load the dataset, preprocess the data, train the SVM model, and provide the prediction results.

## File Structure

The project directory contains the following files:

- `DiabatesPredictionProject.py`: The main Python script that performs data preprocessing, model training, and prediction.
- `diabetes.csv`: The dataset file (Pima Indians Diabetes Database).
- `README.md`: This readme file.

## Results

After running the `DiabatesPredictionProject.py` script, you will see the prediction results displayed in the console. The results will include the accuracy of the SVM model on the test data and additional evaluation metrics such as precision, recall, and F1-score.

## Contributing

If you want to contribute to this project, you can follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/bugfix.
3. Make your changes and commit them.
4. Push the changes to your fork.
5. Submit a pull request explaining your changes.

## License

This project is licensed under the MIT License. You can find more details in the [LICENSE](LICENSE) file.

## Acknowledgments

- Pima Indians Diabetes Database: [https://archive.ics.uci.edu/ml/datasets/pima+indians+diabetes](https://archive.ics.uci.edu/ml/datasets/pima+indians+diabetes)
- scikit-learn: [https://scikit-learn.org](https://scikit-learn.org)

Feel free to modify this README file according to your specific project structure and requirements.
