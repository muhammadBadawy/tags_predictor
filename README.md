Questions tags prdictor

This project is about predicting the tags for Stackoverflow questions<br>

This is going through many steps of loading and pre-processing the data<br>
Then doing EDA (Exploratory Data Analysis) to visualize the data and have better understanding of the data and class distribution<br>
Then doing topic modeling<br>
Training mutiple models and selecting the most fitting one<br>
And building a data pipeline to use it for prediction applications<br>


* Reading the datasets

    * Importing the Questions.csv and Tags.csv
    * Left joining the 2 dataframes
    * Fixing incorrect columns Datatypes
    * Selecting the required columns
------------
* Data pre-processing

    * Removing unwanted special chars
    * Removing stop words
    * Tokenization
    * Lemmatization
    * Stemming
    
------------
* EDA (Exploratory Data Analysis)

    * Sorting tags by the appearance frequency
    * Visializing the most common tags (100 tag)
------------
* Topic modeling

    * Clustering the questions to 15 cluster to get the most discussed 15 topic
------------
* Modeling pipeline

    * Encoding the input
    * Vectorize the input (TfIdf)
    * Splitting the df to training and testing
    * Implementing the evaluation functions
    * Training multiple models to get the best model
    * Evaluating and selecting the best model duo to the defined evaluation function
------------
* Building an inverse pipeline to predict tags on real applications
