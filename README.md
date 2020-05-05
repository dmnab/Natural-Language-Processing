# Natural-Language-Processing

  This is a Natural Language Processing project example created by dmnab

# Objective

  The objective of this project is to determine if a review is positive or negative analyzing text extraction from reviews of restaurants
  Many machine learning classification algorithms were analyzed, KNN, Random Forest, SVM (Gaussian Kernel) but finally, Naive Bayes was chosen due to its accuracy and F1 score
  The dataset provided was made for educational purposes and they are not real customers reviews
  The model comparison table is also provided

# Tools used:

  * Spyder (Python 3.7)
  * Pandas
  * Re
  * NLTK

# Follow the steps to run it
  
  * Download the files
  * Install Anaconda Spyder or other IDE
  * Open Natural Language Processing project.py
  * Make sure you set the proper directory where the dataset is located (i.e: Restaurant_Reviews.tsv)
  * Run file
  
# Interpreting the results
  * 1000 reviews were taken from the dataset which 800 were used to train the model and 200 were used to test it. 
  * x_test is the set to test the model and y_test variable contains the predictions of the model where 0 means a positive review and 1 a negative review
  * It was got 146 correct predictions which mean accuracy of 73% and F1 score equal to 77%
