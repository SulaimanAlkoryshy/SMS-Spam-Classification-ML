# SMS-Spam-Classification-ML
This project is designed to classify SMS messages into **Ham**  or **Spam**. Using Natural Language Processing (NLP) and probabilistic modeling, the system identifies fraudulent or unwanted messages with high reliability.


## Key Features
* **Text Preprocessing:** Cleaning and tokenization of raw SMS data.
* **Feature Extraction:** Implementation of **TF-IDF Vectorization** to convert text into meaningful numerical features.
* **Efficient Modeling:** Utilizing the **Multinomial Naive Bayes** algorithm, known for its effectiveness in text classification tasks.
* **High Precision:** Optimized to ensure zero "False Positives" for ham messages.

## Performance Results
The model was evaluated on a test set and achieved the following metrics:
* **Accuracy Score:** 97.29%
* **Precision Score:** 100.00% (Spam detection is highly reliable)
* **F1-Score:** Strong balance between precision and recall for both classes.

## Dataset
The Dataset uses is the **SMS Spam Collection Dataset**, containing over 5,000 labeled messages.

* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter Notebook
