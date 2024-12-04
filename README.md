# Spam Email Detection Using Random Forest Classifier

## Project Description
This project aims to build a machine learning-based spam email detection system. By leveraging text-processing techniques and multiple classification algorithms, the project identifies spam emails with high accuracy. The implementation also includes an ensemble learning approach to combine the strengths of individual classifiers.

---

## Features
- **Text Data Transformation**: Converts email text to numerical vectors using TF-IDF.
- **Multiple Classifiers**:
  - Naive Bayes
  - Random Forest
  - Gradient Boosting
- **Ensemble Learning**: Majority voting combines predictions from individual classifiers.
- **Evaluation Metrics**: Accuracy score, confusion matrix, and classification report.

---

## Tools and Libraries
The following libraries and tools were used:
- **Python Libraries**:
  - `pandas` and `numpy` for data manipulation.
  - `scikit-learn` for vectorization, classifiers, and evaluation metrics.
- **Machine Learning Models**:
  - `MultinomialNB` (Naive Bayes)
  - `RandomForestClassifier`
  - `GradientBoostingClassifier`

---

## Workflow
1. **Data Loading**:
   - The dataset is loaded from a CSV file containing email text and a spam indicator.

2. **Data Preprocessing**:
   - Splits the dataset into training and testing sets.
   - Converts email text into numerical representations using `TfidfVectorizer`.

3. **Model Training**:
   - Trains three models: Naive Bayes, Random Forest, and Gradient Boosting.

4. **Ensemble Learning**:
   - Combines predictions using majority voting to enhance accuracy.

5. **Model Evaluation**:
   - Evaluates the ensemble model's performance with accuracy, confusion matrix, and classification report.

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone (https://github.com/kendrickchibueze/Spam_Email_Detection_Using_Random_Forest_Classifier.git)
   cd Spam_Email_Detection_Using_Random_Forest_Classifier
