# IMDB_Movies_Data_inestigation (Udacity First Project)  

## Introduction.  
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. Here i will be looking critically into the dataset follwing the steps as they appear in my table of content,  to get some usefull information about the data. This is my first project as a Data Analyst 

## Data Wrangling  
>After a careful look at the given data, there are lots of things we noticed in the data, they includes the following;  
            1. There are lots of NaN Values that needs to be removed.  
            2. There are Zero values under the budget and revenue columns; i will also have to rmove them to have a clean data  
            3. i will check of there are duplicate data and also clean them  
            4. Also looking at the data types; there are some data without the correct data types too, hence i will correct them.
         We will look into each of these issues and solve them so as to have a clean data for exploration.  
         
### Project Insights  
These are some of the details we explored in the course of this analysis;  
  1. Which Genre are the most popular from year to year.  
     From the graph in the notebook, we can see that comedy( represented by orage) is the most popular over the selected years with the highest count in 2015, follwoed by Drama( ther green legend); with the highest count in the year 2009 and then Action|Thriller.  
  2. Which of the production companies produce the most movies?  
     The 'Universal pictures' produce the most films over the year with 14.4% followed by 'Warner Bros' with the total of 14.1% and the third is 'Columbia Pictures' with 8.9% production. while the Lengendary Pictures and DreamWorks SKG has the least production
  3. Which movie year generates the highest revenue?  
     The year with the highest gnerated revenue is in 1977 followed by 1997 and 1985 from the sample of 1000.  
     
### Conclusions.
From the above analysis and more in the notebook, we were able to arrive at the following conclusions.
1. Many people are interested in watching comedy movies followed by drama and thriller  
2. The company with highest movie production is the Universal pictures it also shows in the revenue they generates.  
    this will inturn bring more popularity to them as actore in the industries wants to be associated with profits  
3. 1977 is the year with the highest revenue in the movie industry followed by 1997, there were not much increase in  
    the generation of revenue from 2012 to 2015  
4. in the scatter plot visualisation we found out that increase in budget also brings increase in revenue. and we tend to have more directors with low budget than those with high budget  
5. it looks like the movie industries have created an average movie time policy so as to make the movies not to be too long, hence becoming boring.  
     
### Limitations:  
> From the Analysis performed above, there are some limitations to it  
    1. they do not represent the entire data frame, i only took out samples to make my job clearer.  
    2. i really found it so difficult to create my own function sand also use builtin functions,  
       but am glad am getting use to them.  
    3. i am not yet so perfect with using seaborn package. i beleive i will get use to it in the future
    
