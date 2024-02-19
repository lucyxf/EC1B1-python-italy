EC1B1 Coursework | 2024		 

					 

										 

(i)  A notebook containing all code and outputs as a .ipynb file 								 

(ii)  A pdf file containing the answers to all the questions presented in ‘Section 5 - Questions and Discussion’  

								 

							 

			 

Data Cleaning Guidance  

					 

Downloading the Data  

					 

Navigate to the International Monetary Fund’s “International Financial Statistics” website. Down- load monthly data from January 1960 to December 1990 for the country you have been assigned. It will be easiest to do this with the ‘Query’ function. In particular, download the series for: 			 

												 

(i)  Industrial production (Index)  

												 

(ii)  Exchange rates per US dollar (Period Average)  

												 

(iii)  Consumer prices (All items), index  

												 

(iv)  International Reserves and Liquidity (Reserves, Official Reserve Assets, US Dollar)  

												 

– Also download the data for consumer prices and international reserves for the United States for the same time period.  

												 

Cleaning the data  

							 

Import the dataset of variables for your country into Python. Import the dataset of consumer prices and international reserves for the United States. Merge these datasets together in Python.  

							 

Construct variables for your country for:  

											 

(i)  The monthly growth in the nominal exchange rate 						 

(ii)  The real exchange rate 						 

(iii)  The monthly growth in the real exchange rate 						 

(iv)  The monthly inflation rate 						 

(v)  The monthly growth in industrial production 						 

(vi)  The growth in industrial production versus 12 months ago (i.e. January 1971 versus January 1970 etc 

(vii)  An index of the value of international reserves (value of reserves at January 1960 = 100) 				 

– When determining the real exchange rate, be clear what the nominal exchange rate data you already have is in terms of and, in your code comments, clearly explain how you calculating the real exchange rate growth.  

					 

4.2 				 

- Also, for the US, construct:  

(i) The monthly inflation rate 					 

(ii) An index of the value of international reserves (value of reserves at January 1960 = 100) 3 	 

 

							 

Identify outliers - is there a small number of implausibly extreme observations within any of the data series? Identify the outliers in each data series and set them to missing.  

Interpolate missing data - for each series, replace any gaps in the data (including the data you set to missing because they were outliers) with the mean of the value of the series before and after the gap. 

Format the month and year variable into a date format.  

						 

										 

					 

4.3 End Product					 

							 

Print in your Jupyter notebook (or similar) the full merged dataset.  

								 

				 

					 

5  

					 

5.1				 

					 

Questions and Discussion  

					 

Comprehension and Warm Up  

					 

What was the Bretton Woods system? Did it have any clear advantages over the previous gold standard system? 				 

What disadvantages did it have and to what extent did the gold standard system suffer from similar issues? 				 

The IMF was established during the Bretton Woods Conference in 1944. Briefly explain its role and how it contributed to the functioning of the Bretton Woods system. 				 

What was the date that your country left the Bretton Woods system? Explain how you determined this. 					 

 If two dates seem plausible, pick one and explain why you’re chosen that particular date. Describe the sense in which the departure from Bretton Woods represents a “natural experiment” about the effects of real exchange rate fluctuations on the macroeconomy. 				 

			 

			 

				 

					 

5.2 Cleaning  

					 

												 

How many monthly observations are there in your dataset? Is this the number you were expecting?  

Why are we studying monthly data? Why not some lower-frequency such as quarterly or annual data? 										 

What is industrial production? Why are we studying industrial production instead of another series, such as GDP? 

Why are you dropping outliers? 

Discuss some pros and cons of the interpolation procedure we are using.  

							 

5.3 Analysis  

							 

For all graphs in 5.3, ensure you clearly indicate the time at which your country left the Bretton Woods system and show the relevant series for every month from the start to the end of your dataset.  

						 

					 

					 

5.3.1 Exchange Rate and International Reserve Graphs 
- Plot a time series graph of the monthly growth in nominal exchange rates of your country, versus  

the US dollar.  

Plot a time series graph of the monthly growth in real exchange rates of your country, versus the US dollar.  

Plot a time series graph of the real exchange rate level of your country, versus the US dollar. • Why is it useful to plot both real and nominal exchange rate growth?  

				 

									 

Was the US dollar over or undervalued in the Bretton Woods system? Refer to data or figures in your answer.  

Plot a time series graph of the monthly indexed value of international reserves of your country and the US from January 1960 until the exit of the US from Bretton Woods.  

					 

Using your above figures, explain one reason for the US’s departure from the Bretton Woods sys- tem.  

					 

5.3.2 Inflation and Industrial Production Graphs  

					 

Plot a time series graph of monthly inflation.						 

Plot a time series graph of the monthly growth in industrial production. 			 

Plot a time series graph of the growth in industrial production versus 12 months ago.  

Why are your results for the monthly versus 12 monthly growth in industrial production so dif- ferent? Which measure is more useful?  

						 

					 

					 

5.3.3 Comparison Statistics  

															 

Separately for both the period before and after Bretton Woods, calculate the standard deviation of:  

							 

– The monthly growth of nominal exchange rates versus the US dollar. 
 – The monthly growth of real exchange rates versus the US dollar. 
 – The inflation rate in your country. 
 – The difference between the inflation in your country versus the United States. – The 12-monthly industrial production growth.  

										 

						 

(When you calculate the standard deviation of variables before Bretton Woods, include data up to 07/1971.) (When you calculate the standard deviation of variables after Bretton Woods, only include data from 01/1973.)  

										 

Report these numbers in a suitably formatted table, as well as the ratio of the standard deviation of each variable before and after Bretton Woods.  

Why might it be a good idea to exclude data from 08/1971 to 12/1972 for the above calculations?  

						 

					 

					 

5.4 Conclusion & Extension  

															 

Taken together, what do your results imply about the effect of real exchange rate fluctuations? Is there a reason why your results are particularly compelling? 		 

												 

It is perhaps more natural to consider changes in levels rather than changes in volatility.  

Is there evidence that the average level of nominal and/or real exchange rates changed markedly post Bretton Woods?  

What about the average levels of inflation and production?  

What could be some pitfalls of using this to infer causal changes in the level of industrial production or inflation due to exchange rate differences?  

				 

					 

				 

			 

			 

				 

					 

 

				 

			 

		 

	 
