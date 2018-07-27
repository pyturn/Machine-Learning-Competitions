# [Steps to follows]:

	1. Make sure you have the specified python version installed in your system.(3.6.5)
	2. Make sure you have installed all the modules specified in requirement.txt.
	3. Now run jupyter-notebook using the command on the terminal:
	4. Open Terminal/Shell run the command
		--$ jupyter-notebook
	5. Now get to the location where you have stored the ipython notebook in your filesystem.
	6. Open the file and run all the blocks of the code to generate the output submission file.
	7. Make sure that you have all the files of the dataset in the same folder as that of your code file.
	
# Problem Statement
	
	Mekktronix is a global premium electronics manufacturing companies provides electronic devices across globe through their large 	distributor channel. Recently company is observing lot of fluctuations in their demand forecasting across geographies affecting 	their revenue. The company has reached out to build a machine learning driven forecasting solution to predict sales accurately.
	
	Feature Description
	Year: Year
	Month: Month
	Week: Week Number
	Sales: Price in Local Currency (Target Variable)
	Mechant_ID : Distributor ID
	Product_Types: Product category
	County: Country name
	
	The company has requested to generate monthly forecast at Country X Product_ID resolution.

# Approach
	
	There is a heavy correlation between expense price and sales price data. So I used DECISION TREE WITH ARIMA MODEL for predictions 	  because decision tree fits the data well and ARIMA is used to predict where we do not have expense price.
	
	LeaderBoard Score : 1.83009
	LeaderBoard Rank : 21
	Leaderboard Link : https://www.hackerearth.com/challenge/competitive/zs-data-science-challenge-2018/
	Competition Link : https://www.hackerearth.com/challenge/competitive/zs-data-science-challenge-2018/problems/


