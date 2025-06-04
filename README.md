# Fake News Detection

This project implements a machine learning model to detect fake news. It uses text preprocessing, feature extraction with TF-IDF, and two classification algorithms: Logistic Regression and Decision Trees.

## Project Structure

- `Fake.csv`: Dataset containing fake news articles.
- `True.csv`: Dataset containing true news articles.
- `FakeNews.ipynb`: The Jupyter Notebook containing the code for data processing, model training, and evaluation.
 
## Getting Started

### Prerequisites

- Python 3
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, re, string

You can install the required libraries using pip:

### Running the Code

1.  Clone the repository or download the files.
2.  Ensure `Fake.csv` and `True.csv` are in the same directory as the notebook.
3.  Open the notebook (`FakeNews.ipynb`) in a Jupyter environment (like Google Colab or Jupyter Notebook).
4.  Run the cells sequentially.
5.  The final cell will prompt you to enter news text for manual testing.

## Code Overview

The code performs the following main steps:

1.  **Data Loading and Preprocessing:** Loads the datasets, adds a 'class' label, and cleans the text data.
2.  **Data Splitting:** Splits the data into training and testing sets.
3.  **Feature Extraction:** Converts the text data into numerical features using TF-IDF.
4.  **Model Training:** Trains Logistic Regression and Decision Tree models.
5.  **Model Evaluation:** Evaluates the trained models using classification reports.
6.  **Manual Testing:** Provides a function to test the models with new text input.

## Models Used

- **Logistic Regression:** A linear model for binary classification.
- **Decision Tree Classifier:** A tree-based model for classification.

## Results

The classification reports printed in the notebook show the precision, recall, and F1-score for each class (fake and true) for both models.

## Contributing

Feel free to contribute to this project by suggesting improvements, adding more models, or enhancing the text preprocessing.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
