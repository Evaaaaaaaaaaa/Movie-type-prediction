==============================================================================================
==============================================================================================
This file briefly outlines related works that has been done in project
==============================================================================================
=========

		
		
		Table of Contents
		1  Feature Selection From audio and visual data 
		2  Preprocessing audio and visual data for later use 
		3  Feature engineering for "Tag"
		3.1  Visualisation on tag 
		4  Convert "tag" into vector form
		4.1  perform TF-IDF on "tag" 
		4.2  perform count vectors on "tag" 
		5  Classify based on tf-idf tag only
		5.1  Zero R base line 
		5.2  CNB (tf-idf) "tag" only 
		5.3  LR (tf-idf) "tag" only 
		5.4  Random Forest (tf-idf) "tag" only 
		6  Classify based on tf-idf tag, visual and audio combined dataset
		6.1  Zero R base line 
		6.2  LR (tf-idf tag, visual and audio combined) 
		6.3  MNB and CNB on (tf-idf tag, visual and audio combined) 
		6.4  Perceptron 
		6.5  MLP (tf-idf tag, visual and audio combined) 
		6.6  Sequential neural network on tag, audio and visual combined dataset 
		7  Classify on "tag" (count vectors)
		7.1  CNB on (count vector) tag 
		7.2  LR on (count vectors) tag 
		7.3  LR: "tag" (count vector) with audio and visual data 
		8  Reload the dataset, and train on combined "Title" and "tag" features
		8.1  LR on title and tag 
		8.2  CNB on "title" and "tag" 
		8.3  MLP on "title" and "tag" 
		
==============================================================================================
		
The aim of the project is to test on the hypothesis that Multilayer Perceptron would 
outperform both Logistic regression and Naive Bayes model.

Comparison was building using data with feature combination (tf-idf “tag”, “visual"
and “audio” combined)


The analysis of models behaviour are shown in the report.

==============================================================================================
