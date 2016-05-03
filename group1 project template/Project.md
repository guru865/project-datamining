# Using twitter to see the trends on usage of programming languages.

=============

# OVERVIEW 

In our day to day life we see machine learning and analaysis of open data set useful to the developers across the world to build a tool to explore some useful information . We would like to use data from our twitter which contain rich data source which can pull information about any topic which we would like to invesigate.Data from twitter can be used in different ways to research different trends like brands revalution of a products,fetching reviews about newly launched products and thier services.
Using twitter would like to see the trends In programming community where there is always a decision to make on which launguage to use. Each have thier own pros and cons. Some programming languages see an increase in usage and some reduce in usage. 
By using twitter we would like to take two programming languages which are a bit similar  java and scala (Java8 with its streams and lambda is closer to scala) and see what people think about them.We would like to compare the based on tweet sentiments how many are positive/negative for each programming language.
  How popular is the programming language.



# DATA

We would like to fetch data from twitter streaming API by downloading tweets related to keywords like ruby,java , python etc.
As a next step we need to access the 4 modules of information from twiiter as API key , API secret , Access token and Access token secret .
We will be using the Python library "tweepy" to connect to Twitter Streaming API and download the data .
We selected tweets which are retweeted more than 10 times and we the tweet is not a retweet. 

Cleaning Data :The twitter tweet would contain a lot of information that is not needed for this project.
  Like links user name b RT tags and hashtags.
  Used python re module to remove tags and clean data
  The regular expression for each of them is mentioned in the code.



# RESEARCH QUESTIONS
Initial methodology
would like to explore the trending programming languages and compares the trends in two programming languages Java & Scala.
And mentions how many positive tweets and negative tweets are mentioned.We would like to compare the based on tweet sentiments how many are positive/negative for each programming language.How popular is the programming language.?



# MODELS AND ANALYSIS

The models are described and the preliminary analyses performed in a Jupyter Notebook libraries like pandas and We used http://text-processing.com/api/sentiment/ rest based call to get the sentiment for each tweet. When a tweet is given as input the restApi returns positive/negative/nuetral tag.


# CODE AND APPLICATION
 




We are team of three , Kishore kumar Sunkoju ,Rahul Monthe and Deepthi Chenagoni we will be sharing our work amoung ourselves .
Kishore will be taking care of development ,data analaysis to pull tweets from tweepy API that was created to provide data to analyze tweets  on programming languages.  deepthi and rahul would work on  data analaysis and help in provinding small code snippets when we come across errors and  together we are collaborating to check the progress of the project testing.




# PROJECT TEAM, DELIVERABLES AND CHECKPOINTS
These tables show  examples of the data that should go into each column and row.


## TEAM

| Team member | Roles and skills | Contributions |
|-------------|-------------------------|---------------------------------------------|
| Kishore Kumar Sunkoju | API development ,data analaysis, Python| Scripting ,Data Analysis,QA |
| Deepthi Chenagoni | Data analysis ,Testing ,documentation | build scripts , data analysis,testing |
| Rahul Monthe | Testing ,Data analysis ,documentation |  Data analysis,test harness; |

## DELIVERABLES AND CHECKPOINTS





| Checkpoint date and due date| Expected Deliverable                                                          | Responsible team member(s) | Checkpoint results                                                                                                                  |
|---------------|-------------------------------------------------------------------------------|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
|2/14/16| Using twitter to see the trends on usage of programming languages.  | Kishore Kumar Sunkoju ,Deepthi Chenagoni , Rahul Monthe   | Submitted a project proposal for our future project |
|3/15/16 |Updated the research questions ,data section and  In a process of creating a streaming script which collects data from twitter because as you know twitter has a limitation on number of request you make per day. 2. Twitter data contains information that is not useful for sentiment analysis.3. Using the API http://textprocessing.com/api/sentiment to see if initial results match our criteria.| Kishore  Kumar sunkoju, Rahul Monthe  |           Able to pull the tweets data related to programming languages java vs scala and sort and plot the number of tweets in java and scala           |
| 3/20/16 | Will upload intital project code .Will also modify answer/update the research question depending upon the results seen in initial analysis | Rahul Monthe ,Deepthi Chenagoni ,Kishore Kumar S |     As a next step we need to take Relevant Tweets|
| 4/3/16 |Cleaning Data ,twiiter had ot of information that is not needed for this project.Like links user name b RT tags and hashtags.| Kishore  Kumar sunkoju ,Rahul Monthe ,Deepthi Chenagoni  | Used python re module to remove tags and clean data   |
| 4/25/16 | Check the results and extracting sentiment | Kishore  Kumar sunkoju ,Rahul Monthe |used http://text-processing.com/api/sentiment/ rest based call to get the sentiment for each tweet. When a tweet is given as input the restApi returns positive/negative/nuetral tag. Used matplotlib to create graphs        |
| 05/01/16 | Present a final report of the project  | Kishore Kumar Sunkoju , Rahul Monthe,Deepthi Chenagoni  |Prepared a detailed documentation and PPT , Concluded the project with results shows that Java still has a lot of positive impression in the minds of programmers and eventhough scala is covering the gap, it hasn't done it so far.|



