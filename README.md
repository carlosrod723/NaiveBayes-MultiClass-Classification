# Multi-Class Text Classification with Naive Bayes**

This analysis focuses on the Naive Bayes algorithm to build a multi-class text classification model using a dataset of customer complaints about consumer financial products. Natural Language Processing (NLP) is used to analyze and extract meaningful insights from textual data. The focus is on classifying customer complaints into various product categories using the Naive Bayes algorithm.

## **Objective**

- Understand the Naive Bayes algorithm and its applications in text classification.
- Build a multi-class text classification model.
- Perform preprocessing steps such as tokenization, stopword removal, and punctuation removal.
- Evaluate the performance of the model and make predictions on new reviews.

---

## **Approach**

1. Introduction to Naive Bayes algorithm.
2. Data description and visualization.
3. Data preprocessing:
   - Conversion to lowercase.
   - Tokenization.
   - Stopwords removal.
   - Punctuation removal.
4. Building the Naive Bayes classification model.
5. Model evaluation and accuracy metrics.
6. Predictions on new reviews.

---

## **Data Dictionary**

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

---
