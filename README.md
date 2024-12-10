![Logo](https://github.com/mmahesh09/Credit-Card-Fraud-Detection/blob/3a0260e1b2123ca4b70b704110e74eb0744ad259/Credit-Card%20fraud%20detection.png)

# Credit Card Fraud Detection: CardRaksha 💳



Credit card fraud causes huge financial losses worldwide. This project uses machine learning to identify fraudulent transactions by finding unusual patterns in the data. The model will classify transactions as either legitimate or fraudulent using methods like supervised learning and anomaly detection. Key challenges include dealing with unbalanced data, keeping up with new fraud methods, and making quick, real-time predictions. By using efficient algorithms, the goal is to reduce financial losses, improve accuracy, and detect fraud quickly to protect financial systems.

## Index
![Features](##Features)
![Dataset](##Dataset)
![Tech Stack](##Tech)
![Methodlogy](##Methodlogy)
## Features ♻️

1. ### Real-time Fraud Detection
   CardRaksha uses advanced machine learning algorithms and data analytics to detect fraudulent transactions in real-time. By analyzing transaction patterns, the system can flag suspicious activities instantly, allowing quick intervention to prevent financial loss.

2. ### AI-Powered Anomaly Detection
   The project leverages artificial intelligence (AI) and machine learning (ML) models (such as decision trees, neural networks, or ensemble methods) to recognize patterns of normal transactions and detect anomalies. These models continuously learn from new data to improve fraud detection accuracy over time.

3. ### Enhanced Security and Privacy
   CardRaksha emphasizes secure data handling and privacy by implementing robust encryption techniques and anonymizing sensitive transaction details. The project ensures that user data remains confidential while offering high accuracy in detecting fraudulent activities.

## Dataset 📂

The dataset contains 10,000 entries with six columns: **Profession**, **Income**, **Credit_card_number**, **Expiry**, **Security_code**, and **Fraud**.

- **Profession** (categorical) indicates the individual's occupation.
- **Income** (numerical) shows the annual income.
- **Credit_card_number**, **Expiry**, and **Security_code** are sensitive details associated with credit card information.

- **Fraud** (binary) is the target variable indicating whether fraud occurred (1 for fraud, 0 for no fraud).

The dataset appears to focus on detecting fraudulent transactions or behavior based on personal and financial details. It contains no missing values, and the data types are correctly assigned. However, the 
presence of sensitive information like credit card numbers suggests the need for privacy-preserving analysis. Further exploration is required to understand the distribution of fraud cases and relationships 
between features.


## Tech Stack 💻

**Language:** Python🐍

**Libraries used:** Numpy, Pandas, Matplotlib, Scikit-learn


## Methodlogy
![Methodlogy](https://github.com/mmahesh09/Credit-Card-Fraud-Detection/blob/1175e223b7575c4e05876b83336da37f9c7f1a9c/methodlogy.jpg)

From this figure the Methodology 
1. Collecting Credit Card Data Sets
The first step involves gathering a comprehensive dataset of credit card transactions. This dataset includes various features such as the profession of the cardholder, annual income, credit card number, expiry date, security code, and whether the transaction was fraudulent or not.

2. Preprocessing Missing Values
Next, we address any missing values in the dataset. Ensuring complete and accurate data is crucial for building an effective fraud detection model. Techniques such as imputation or removing missing values are used to prepare a clean dataset.

3. Apply Oversampling Techniques
Credit card fraud datasets often have a significant class imbalance, with far fewer fraudulent transactions compared to legitimate ones. To handle this imbalance, oversampling techniques like SMOTE (Synthetic Minority Over-sampling Technique) are applied. This helps create a balanced dataset by generating synthetic samples for the minority class (fraudulent transactions).

4. Normalization
Normalization is the process of scaling the features to a standard range. This step ensures that all features contribute equally to the model's learning process and helps improve the model's performance. Common normalization techniques include Min-Max Scaling and Z-Score Normalization.

5. Feature Selection
Feature selection involves identifying the most relevant features that contribute to detecting fraudulent transactions. This step reduces the dimensionality of the data, removes irrelevant or redundant features, and improves the model's efficiency and accuracy.

6. Machine Learning Based Classifiers
With the preprocessed and balanced dataset, we apply machine learning algorithms to build the fraud detection model. Various classifiers such as decision trees, neural networks, or ensemble methods are trained and evaluated. These models learn patterns from the data to differentiate between legitimate and fraudulent transactions.

7. Validation with Performance Measure
Finally, the model's performance is validated using appropriate metrics such as accuracy, precision, recall, and F1-score. This step ensures that the model reliably detects fraudulent transactions while minimizing false positives and false negatives. Validation helps fine-tune the model for better accuracy and robustness.



