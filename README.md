# Automated-Spam-Detection-in-Social-Media-Comments-Using-Machine-Learning

## Project Overview
This project aims to develop an automated system to detect spam in social media comments using machine learning techniques. By leveraging a Naive Bayes classifier, the model is trained to identify patterns and distinguish between spam and legitimate comments. The project uses a dataset containing YouTube comments, labeled as spam or not, to build and evaluate the model's performance.

## Features
- **Data Preprocessing:** Cleaning and preparing the dataset for model training, including handling missing values and transforming text data into a suitable format for machine learning algorithms.
  
- **Feature Extraction:** Utilizing `CountVectorizer` to convert text data into a matrix of token counts, which serves as input features for the classification model.
  
- **Naive Bayes Classifier:** Implementation of the Bernoulli Naive Bayes model, which is particularly effective for binary classification tasks like spam detection.
  
- **Model Evaluation:** Assessment of model performance using accuracy, precision, recall, and F1-score to ensure the reliability of spam detection.
  
- **Visualization:** Displaying sample predictions and performance metrics to provide insights into the model's effectiveness.

## Tools Used
- **Python:** Core language for developing the model and conducting data analysis.
- **Pandas & NumPy:** For data manipulation and numerical computations.
- **Scikit-learn:** Machine learning library used for model training, feature extraction, and evaluation.
  
## How to Use
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Soniya-krishikka/Automated-Spam-Detection-in-Social-Media-Comments-Using-Machine-Learning.git
   ```
   
2. **Navigate to the Project Directory:**
   ```bash
   cd spam-detection-in-social-media
   ```
   
3. **Install the Required Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   
4. **Run the Jupyter Notebook:**
   Open the `.ipynb` file and execute the cells to preprocess the data, train the model, and evaluate its performance.

## Insights
- **Spam Detection:** The Naive Bayes model is well-suited for detecting spam in social media comments, showing high accuracy and reliable performance.
- **Model Evaluation:** The model's performance metrics, including precision and recall, indicate a strong ability to differentiate between spam and non-spam comments.

## Conclusion
This project demonstrates the effectiveness of machine learning in automating the detection of spam in social media comments. The Naive Bayes classifier, combined with feature extraction techniques, provides a powerful solution for maintaining the quality of online interactions by filtering out unwanted content.


