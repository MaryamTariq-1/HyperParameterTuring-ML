# HyperParameterTuring-ML

This repository contains the project on hyperparameter tuning of machine learning models. The aim of this project is to optimize the performance of machine learning models by fine-tuning hyperparameters using techniques such as grid search and random search.

## Project Overview

The project involves:
- Understanding hyperparameters
- Implementing grid search
- Implementing random search
- Evaluating the tuned models

## Dataset

The dataset used in this project is `Eemails.csv`, which contains information relevant to classifying emails.

## File Structure

- `Emails.csv`: The dataset file.
- `HyperParameterTuningModels.ipynb`: The Python script for performing hyperparameter tuning and model evaluation.
- `README.md`: This file.

## Requirements

- Python 3.6 or higher
- pandas
- scikit-learn
- scipy

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/MaryamTariq-1/HyperParameterTuring-ML.git
    ```

2. Install the required packages:
    ```bash
    pip install pandas scikit-learn scipy
    ```

## Usage

1. Run the analysis script:
    ```bash
    jupyter notebook HyperParameterTuningModels.ipynb
    ```

## Hyperparameter Tuning

The hyperparameter tuning includes the following steps:

1. **Understanding Hyperparameters:**
   - Familiarize yourself with the concept of hyperparameters and their significance in machine learning models.

2. **Grid Search:**
   - Implement grid search to systematically explore the hyperparameter space and find the best combination of hyperparameters.
   - Define the hyperparameter grid for the `RandomForestClassifier` model.
   - Use `GridSearchCV` from scikit-learn to find the best combination of hyperparameters.

3. **Random Search:**
   - Use random search as an alternative to grid search for hyperparameter tuning, especially when the hyperparameter space is large.
   - Define the hyperparameter distribution for the `RandomForestClassifier` model.
   - Use `RandomizedSearchCV` from scikit-learn to randomly sample hyperparameters and find the best combination.

4. **Model Evaluation:**
   - Evaluate the performance of the tuned models using metrics such as accuracy, classification report, and confusion matrix.
   - Compare the best models obtained from grid search and random search.

## Results

The project demonstrates how to optimize machine learning model performance through hyperparameter tuning, using both grid search and random search techniques. The evaluation metrics help in assessing the improvements and effectiveness of the tuned models.

## Pro Tips

- Start with a coarse grid or random search and refine the search space based on initial results.
- Use libraries like scikit-learn's `GridSearchCV` or `RandomizedSearchCV` for efficient hyperparameter tuning.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- Performed Internship at CodexCue!

## Contact

For any questions or inquiries, please contact:
- Your Name: [marymughal216@gmail.com]
- GitHub: [MaryamTariq-1]
