# data_scince_life_cycle
#As data science I can fine tune a data science life cycle from data collection to deployment to production. You can go through the brief description of how I manage my projects which is of five set of  steps.

1. Data Collection 
Data can be collected through web scraping ,  3th party API or can be provided by the client or the company depending on the situation.

2. Feature Engineering  
(Data cleaning and data wrangling)

At this point I covert the raw data to useful data for the algorithm to work on it aproperly. So I explore the data by checking if there is ;
        1 Numerical data by visualizing the data
        2 categorical feature by plotting a graph
        3 Outliers by plotting box plot
By the use of python package matplotlib, seanborn and PDF function. Then handle the missing values be evaluating the mean, mode and medium. I proceed on making the the data sate balanced by scaling down the data sate by standardization or normalization and treating the outliers. My final move is to change the categorical data to Numerical data. Further more I can use automated EDA that does all the process by it self in same specific case.       

3. Feature Selection
Feature Selection is the simplest part, there is some several way to do it like;
      1 Correlation
      2 K-neighbor
      3 Chisquere
      4 Genetic algorithm
      5 Feature importance by extractrec classifiers.

4. Model Selection (Machine learning)
At this point I choose the best algorithm for the project by selecting the algorithm that I think works best, I prepare the data and build the model then make predictions . To check if the algorithm is the best for the project I evaluate the model accuracy , confusion matrix , precision and recall. If it's bad I repeat the process with another algorithm and if it's okay I move on by improving the model by hyperameter optimization and then save the model as .pkl , .pt , .sav extension. In some cases I use AutoMl  like TPOT and Sk-learn to speed up thing.

5. Model deployment
In model deployment I can either use the cloud services like tensorflow saving, Google and AWS or I can just locally deploy in my machine. Then I host the model in the server side using frame works like flask and Django and expose the model as lite weight API to any front end application like mobile app and desktop. By the use of Dockers and Kubernetes which is mostly used in production. Then I connect it with a database (SQL,noSQL)or S3 bucket to save the output or for data archival.
