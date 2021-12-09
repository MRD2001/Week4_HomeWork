# Week4_HomeWork
Homework Repo for Week3-4 

> In this homework we will try to create a custom porfolio of stocks and compare its performance to other stocks. Using python and pandas packages to show how the agorithmic trading starategies work.
 The input are some of the provided CSV files including a data from wale investors porfolios. We need to do:
 - Read and wrnagle data
 - Determine the sucess of each portfolio
 - Choose and evaluate a customer portfolio

## The Path statement is not working well for me. So, I used the command os.chdir() , to reach to the resources directory and the files inside it


 
 ## Import Dependencies
 
 - The most popular anaconda scientific modules pandas and numpy.
 - datetime
 - path
 - pylot : A Flask extenstion that adds structure and map our views and presnet the results visually. 
 - os : provide portable way of using the operating system functionality. This one is used, due to that path is not functioning properly. So, I used it to get the CSV files.
 
 ## Read and Cleanse Data
 
 > read all the provided files and create dataframes for each. Then sort them and run some cleaning, by removing nulls, and convert values to its correct type
 
 ## Portfolio Analysis
 
 ### Performance Analysis
 > Analyse the performance of the combined portfolio, by calculating the returns and cumuluttive returns
 
 ### Risk Analysis
 
 > Analyse Risk, through ploting the box graph. this will allow us to visually see which portfolio that have the largest spread , and the smallest spread. In addition to whihc portfolio have the greatest outliners.
 > Continue Analyse risk, this time by calculating Standaderd deviation. To get which portfolio have a higher annulaised standard deviation from S&P 60 TSX
 > Calculate the rolling statistics, which represents risk over time. We will see that all portfolios tend to see an increase in risk at the same time risk increases in the S&P 60 TSX. 
 > Calcuating Correlation and Beta. Correlation will give us which portfoio mostly resembles the returns of S&P 60 TSX.Voltality of the portfoio is provided by Beta. 
 > More about Beta: A beta of 1 indicates that the security's price tends to move with the market; a beta greater than 1 indicates that the security's price tends to be more volatile than the market; a beta of less than 1 means it tends to be less volatile than the market. 
 > Extra Factor : The caculation of the exponentially weighted moving average (ewm).This is one of the wonderful features of the pandas library imported to our code.This Python feature, enable us to focus more on the results of the analysis, not the coding. When visually display the ewm , we will see which portfolio will react significally to recent price changes than any other protfolio.
 > Sharpe Ratios calculations, taking return-to-risk into account. This ration will show us which portfolio performed both the market as a whole as well as the whale management fund. Provides also, comparison between the protfolios.
 
 
 ## Build a custom portfolio
 
 > In this section, we will use the data provided in the repo (CSV files under the resources directory). They are SHOP (Shopify), OTEX (OpenText), and L (Loews Corporation). We will repeat the above steps to include the new portfolio, standard deviation, sharpe ratios, Correlation, and Beta.
 > Using the results of the above analysis, we will be able to answer the question on how our custom portfolio compares to the portfoios provided.
