An end-to-end machine learning project is one that will involve the process of data collection and processing,you storing it in a database for future retrieval. This stage is called the data engineering stage

then you will want to retrieve that data and understand it, if it is not yet cleaned. we want to clean the data that has been collected  and analyse it, visualise it for deep insights so that you can have a proper undetstanding of which features you should keep and which you should throw away. A lot of this information is got from the data analysis stage. Very important

Next up is now to select the best model that will be used to train the data, also selecting the right features and (of course you should know the target what you want to predict in the first place)


1. A dedicated folder that will hold all about your data collection and data loading process... This will contain, in this, case all about your web scraping, how to structure the data and the functions that you use to store this into a database

2. Retrieval and analysis layer of things, this is where you will retreive the data that you have in the database and use it for analysis and feature extraction, you usually will have more columns after you have done the feature extraction step. This is because you will have brought out the best in your data.. you get?

3. Select the best model or suites of models that you want to train your data on, when you are done training this model, you will pick the best model that you have there and imporove on that model using methods like hyperparameter finetuning experiments and so on

4. You will want to store this your best model for future improvements.

5. In a company case scenario, you will want to create a pipeline that will be run automatically and will version your models for you.



You will want to create a topic and find a way to get the data. We want to be able to predict the values of house prices right? you can create your own dataset by scraping estate websites of their house data.

This will show that you truly know what you want... You will collect all these datasets and store them somewhere, say in a sqlite db for local development...  Next up, you will retrieve that data for analysis and  machine learning

You can build a Streamlit application at this point to be able to visualise the dataset that you have collected from the internet and aanlaysed... To learn something on cron jobs... 

gathering data