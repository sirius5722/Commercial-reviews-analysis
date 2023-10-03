# Commercial-reviews-analysis With GUI
The project is a Program that aims to Analyze customer reviews for online-bought products . And extract insights , word trends … etc. In order to help online sellers improve and understand their customer needs.
### With a Modern GUI using Tkinter .



>> Important Note : In order to Run the code quickly while editing , Don't call processData Function and use the already processed data file that's called  (ClothesReviews_processed.csv) instead of main dataset file .





# Source code body

## A) Functions Purposes
### 1- processData Function :

* Text Processing tasks (i.e. Tokeniation , Stemming , Removing stop words) On Reviews Text to create a clean review that's ready for analyzing

### 2- doEDA Function :

* It's responsible for data Analysis and creating Visualizations that would be helpfull for the business owner
* It Creates a Word Cloud in order to know the Trends in data

### 3- viewEDA Function :

* It Creates a tabview In order to show the visualizations created by doEDA Function

### 4- sentimentAnalyzer Function :

* It Takes a user input and do Sentiment Analysis using vaderSentiment module 
* The result Shows If the Input is (positive , negative , neutral)


#### Angry Catto 


