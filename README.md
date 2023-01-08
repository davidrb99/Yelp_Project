# Practice 3 - YELP DATASET

### Title: __Pennsylvania State restaurants rating predictions using Natural Language Processing (NLP)__

__Author__: David Rivero Berrocoso.

__Github__: This project will be uploaded to my personal account:
	- https://github.com/davidrb99

In order to develop this project, we will focus on `yelp_academic-dataset_business.json` and `>yelp_academic-dataset_reviews.json`. The project will be divided in three notebooks.

1. Business Dataset Understanding.

	In this first notebook we have focused on the fundamentals of the project, trying to unsderstand the data contained, the distribution of the business mentioned and to find out which businesses were the best to model. In this case, we have decided to use geospatial representations. Pennsylvania state restaurants turned to be the better group for our project.
2. Natural Language Processing + Analysing Business Model.

	In this second notebook we checked out the reviews dataset. This dataset was easier to understand since we have filtered mos of the information about the businesses in the first notebook. Furthermore, there were only three important variables in this dataset, 'business_id', 'stars' and 'text'. Once we analysed the dataset, we brought Natural Language Processing(NLP) toolkit to process the text into stopwords. Finally, we have used the processed texts and the information we got in the first notebook to create an overview about the restaurants in Pennsylvania, using visualization to analyse common characteristics and interactive geospatial visualizations.
3. Model & Interpretability.
	In this last notebook we focused on vectorise the text variable and to defie the target variable for the model. Then, we used a Support Vector Classificator model to classify a restaurant in top or non-top experience depending on the text of a review. Finally, in the interpretability chapter we have used an random forest classifier to ease the plotting of the SHAP visualizations and pick some samples to be plotted and explained, besides another two examples for Graphs from Networkx library.

The project will be located in YELP_PROJECT directory, which contains the following folders:

1. data: which contains the project data in several formats(.csv, .json)
	1. RAW: Unprocessed data that has been used only for visualitation or filtering.
	2. Processed: Processed data that is meant to be used only in this project.

2. docs: which contains .HTML documents from the notebooks to ease its visualization.
3. images: which contains images that are used in the notebooks to support the markdowns.
4. models: which contains Machine Learning model that is used in our project.
5. notebooks: which contains the three notebooks where the project has been developed.
6. README: current document.

IMPORTANT: this project has been developed in colaboration with Gabriela Gutiérrez-Colomer.

