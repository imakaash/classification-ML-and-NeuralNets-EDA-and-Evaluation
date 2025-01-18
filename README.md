## Classification, Machine Learning, Neural Networks, EDA, and Evaluation

This project focuses on classification tasks using machine learning and neural networks, including exploratory data analysis (EDA) and model evaluation. It contains two main notebooks:

## 1. Data_Cleaning,_EDA_and_Feature_Engineering.ipynb

This notebook deals with a dataset of 1,000 hotels and their reviews from Datafiniti's Business Database. It includes the following activities:

-   Data cleaning
-   Exploratory Data Analysis (EDA)
-   Feature engineering
-   Fixing date-related features

The dataset includes information such as hotel location, name, rating, review data, title, and username. The full schema of the data is available at [Datafiniti Business Data Schema](https://developer.datafiniti.co/docs/business-data-schema).

## Results:

-   Accuracy of the model: 0.83370100118785
-   F1 score of the model: 0.8895152198421645

The model's performance in classifying hotels as "Good" or "Bad" based on user reviews has significantly improved. Both the recall and F1 score for determining bad reviews show good results. The notebook suggests checking the model's performance on manually given reviews for further evaluation.

## 2. MNIST_Fashion_Data_Classification.ipynb

This notebook focuses on classifying the Fashion MNIST dataset using neural networks. Key points include:

-   Dataset: 70,000 grayscale images (28x28 pixels)
    
    -   60,000 training samples
    -   10,000 testing samples
    
-   10 classes of clothing items
-   Implementation of a neural network classifier
-   Model evaluation and performance analysis

## Results:

-   Achieved 91.20% accuracy on the test set
-   Most classes show good precision, recall, and F1 scores
-   Class 6 (Shirt) shows lower performance, possibly due to similarity with Class 0 (T-shirt/top)

The notebook includes visualizations of training and validation accuracy, as well as a detailed confusion matrix to analyze model performance across different classes. It also notes that after a certain number of epochs, the validation accuracy and training loss become constant, despite continued learning on the training set.Both notebooks demonstrate various aspects of the machine learning pipeline, from data preparation to model implementation and evaluation, showcasing the application of classification techniques in different domains.
