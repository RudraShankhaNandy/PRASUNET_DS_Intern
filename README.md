# PRASUNET_DS_Intern
 Data Science Internship at PRASUNET Company

4 of the 5 tasks were completed

TASK1 : 
Given - datasets cotaining populations(different datasets for different genders, age groups etc.) of different countries over several years 
Task - to analyze the variation of gender population(male and female population) and age-based population over the years
Procedure - 1. The csv files were loaded and converted to dataframes
            2. In female population and age-based population dataframes there were percentages of total population in the cells. So the actual population count needed to be calculated using those percentages and the dataframe containing total population count.
            3. 4 functions were created using Pandas, Seaborn and Matplotlib that takes in country name creates bar charts showing the change in population of country over the years.

TASK2 :
Given - Titanic Dataset
Task - EDA to be performed on the dataset
Procedure - 1. The dataset was loaded and converted to dataframe
            2. Using seaborn heatmap null values were analysed
            3. Seaborn Boxplots & Barcharts were used to analyse the data

TASK3 :
Given - Bank Marketing dataset fromthe UCI Machine Learning Repository
Task -  Build  a  decision  tree  classifier  to  predict  whether  a  customer  willpurchase  a  product  or  service  based  on  their  demographic  andbehavioral data. Use a
        dataset such as the Bank Marketing dataset fromthe UCI Machine Learning Repository
Procedure - 1. The dataset was directly download and loaded using pip
            2. Null handling was done by using ml algorithm(XGBClassifier) to predict the missing values
            3. A XGBClassifier model was created based on the given data which reported a 90+ % accuracy on training data and it was saved in a pkl file

TASK4 :
Given - Twitter sentiment dataset
Task - Analyze  and  visualize  sentiment  patterns  in  social  media  data  to understand  public  opinion  and  attitudes  towards  specific  topics  or brands.
Procedure - NLTK was used to lemmatize and vectorize the texts with different words. TF - IDF Vectorizer was used to give special emphasis on words