# **Multi-Class Text Classification with Naive Bayes**

This project applies the **Naive Bayes algorithm** to build a multi-class text classification model using a dataset of over 2 million customer complaints about consumer financial products. **Natural Language Processing (NLP)** is used to extract meaningful insights from textual data and classify the complaints into different product categories.

## **Objective**

- Learn the applications of the Naive Bayes algorithm for text classification.
- Build a multi-class classification model for categorizing customer complaints.
- Perform preprocessing tasks such as tokenization, stopword removal, punctuation removal, and vectorization.
- Evaluate the model's performance and predict product categories for new complaints.

---

## **Approach**

1. Introduction to the Naive Bayes algorithm.
2. Data description and visualization.
3. Data preprocessing:
   - Conversion to lowercase.
   - Tokenization.
   - Stopwords removal.
   - Punctuation removal.
   - **Vectorization** using `CountVectorizer`.
4. Building the Naive Bayes classification model.
5. Model evaluation and accuracy metrics.
6. Predictions on new complaints.

---

## **Technologies Used**

- **Python**: Programming language.
- **Scikit-learn**: For machine learning and model building.
- **NLTK**: For Natural Language Processing tasks such as tokenization and stopword removal.
- **Pandas**: For data manipulation.
- **Matplotlib & Seaborn**: For data visualization.
- **Google Colab**: For running and testing the project in an online notebook environment.

---

## **How to Run**

1. Clone the repository:
   ```bash
   git clone https://github.com/carlosrod723.git
   cd NaiveBayes-MultiClass-Classification
   ```
2. Install the required libraries:
   ```pip install -r requirments.txt```

3. Run the Jupyter or Google Colab notebook to train the model and make predictions

## **Dataset and Data Dictionary**

The dataset contains over 2 million customer complaints related to various financial products, including credit cards, loans, and mortgages. Each record includes detailed information such as the complaint narrative, product type, issue, and company response, making it ideal for text classification and sentiment analysis tasks.

| Column Name                   | Description                                                  |
|-------------------------------|--------------------------------------------------------------|
| Date received                  | The date the complaint was received                          |
| Product                        | The product for which the complaint is raised                |
| Sub-product                    | More specific category under the product                     |
| Issue                          | The primary issue of the complaint                           |
| Sub-issue                      | More detailed description of the issue                       |
| Consumer complaint narrative   | The actual text of the complaint                             |
| Company public response        | Response from the company if publicly available              |
| Company                        | Name of the company the complaint is directed towards        |
| State                          | U.S. state where the complaint was filed                     |
| ZIP code                       | ZIP code of the customer                                     |
| Tags                           | Tags related to the complaint (e.g., older adults, veterans) |
| Consumer consent provided?     | Whether the consumer provided consent for the narrative      |
| Submitted via                  | The method used to submit the complaint (e.g., Web, Phone)   |
| Date sent to company           | The date the complaint was sent to the company               |
| Company response to consumer   | The company's response to the complaint                      |
| Timely response?               | Whether the company responded to the complaint in a timely manner |
| Consumer disputed?             | Whether the consumer disputed the company's response         |
| Complaint ID                   | Unique ID of the complaint                                   |

