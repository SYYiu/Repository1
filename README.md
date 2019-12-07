Title: A proposed design model for sentiment analysis of online customer reviews 

A high-level NLP-based data science pipeline design approach is proposed and implemented for sentiment analysis of online customer reviews in this repository. The proposed process for sentiment analysis consists of three stages: 

Stage 1 (Data Collection) - A web scarping technique is proposed and implemented here to collect and prepare customer reviews data from a review platform (namely Trustpilot). 

Stage 2 (Data Exploration) - A set of procedures for performing initial data exploration on the collected customer reviews dataset is defined. 

Stage 3 (Sentiment Analysis) - A sentiment analysis model technique is proposed and implemented for classifying online customer reviews into positive, negative or neutral sentiment. 

Please note - The implementations for Stage 2 and 3 of the proposed process are performed using Apache Spark (3.0.0 preview release) to take into consideration of the fact that faster processing would be required in the future as more and more consumers post their reviews online. 

This pipeline of design approach has been successfully demonstrated on the customer reviews of Myer (an upmarket department store chain in Australia) available on Trustpilot.

https://au.trustpilot.com/review/www.myer.com.au

Hence, the repository contains the following iPython notebooks and an example customer reviews dataset collected from Stage 1 of the process. 