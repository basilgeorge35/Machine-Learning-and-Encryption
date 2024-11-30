I did this code as part of my MSc final semester thesis.


This project explores the performance of machine learning models, specifically Support Vector Machines (SVM), Logistic Regression and Perceptron, in spam detection tasks for both encrypted and unencrypted data. To address privacy concerns during the process, this research applies the Paillier homomorphic encryption scheme, allowing computations on encrypted data without decryption. 

Three machine learning models were trained on email datasets, and their performance was assessed in both encrypted and unencrypted environments. These models were trained on a dataset of emails classified as spam and ham(non-spam), with preprocessing done using the TfidfVectorizer for feature extraction, followed by Principal Component Analysis (PCA) for dimensionality reduction. Results indicate that while encrypted models exhibit slightly lower accuracy and significantly longer test times(due to the encryption step), they still offer a good solution for privacy-preserving spam detection.
