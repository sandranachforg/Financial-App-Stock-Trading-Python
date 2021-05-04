 <img src= "https://user-images.githubusercontent.com/49343277/117007629-e079bf80-acb7-11eb-971b-5a92feacadaa.png" width = "250">

# Financial Application - Stock Trading

APIS: IEX CLOUD, YAHOO
  
**What inspired you to create this project?**

Trading is ubiquitous nowadays because of the advancement of technology. With a click on our phone you can buy a stock and earn or lose money. Noone wants to lose money, so we wanted to create a program that would help you make trading decisions that maximize the potential to get a return and beat the market! All you have to do with our program is enter the stock you are interested in, and it will predict the closing price of the stock over the next 7 days, which gives the user a better chance to come in at a position where they make money. We were also inspired to create this project after attending yesterday’s workshop about IEX Cloud and APIs. We were truly amazed by how easy it is to utilize an API, and we wanted to do so with financial data. 
<br />

**Who created the project?**

This project was created by Sandra Nachfoerg, Samantha Tavares, and Daniel Gurvich, three Computer Information Systems students at Baruch College.
<br />

**What does your project actually do?**

Our project analyzes the growth of the stock that the user inputs, the risk of holding the stock, and future growth potential with a linear regression model. Our project provides insight into the stock performance in relation to the market, and checks the beta and alpha values of the stock to let the user know whether the stock is aggressive or defensive. 
<br />

**How did you build your project?**

We mainly worked with Python for this data analysis. We took advantage of the following libraries: pandas, numpy, sci-kit learn, and matplotlib. We also used the token provided by IEX Cloud to import the stock data. To measure the risk of holding a specific stock, we had to calculate the beta value and standard deviation of the stock. A beta value greater than 1 means that the stock behaves aggressively when compared to the S&P 500. A beta value less than 1 signals that a stock behaves defensive. This can help to measure risk. When a stock is aggressive, the stock typically outperforms the value of S&P 500 in both directions. If you are risk-averse you may want to purchase defensive stocks but the returns will typically be lower.
<br />

**Tag the technologies you used throughout your project.** 

We used the IEX Cloud API, Jupyter Notebook, Google Colab, GitHub, and Python machine learning and data science libraries such as Pandas, NumPy, Matplotlib (pyplot module), and Scikit-learn. 
<br />

**What challenges did you face?**

We found it difficult to develop an accurate linear regression model that predicts the closing price for the day of a specific stock mainly because we used the API sandbox (except for data that we imputed from Yahoo Finance), which yields unrealistic data. Thus, our data was not fully accurate, but when we use true data in the future, it will be much easier. Lastly, we were unable to build the API due to time constraints, but we are planning to implement this in the future. 
<br />

**What accomplishments are you proud of?**

We are proud of working together effectively as a team and putting a project together within just a few hours. By extensively browsing through resources, programming, and troubleshooting problems with our code, we were able to thoroughly analyze, predict, and visualize stock data for the past five years. Our regression has up to 95% accuracy for some stocks!
<br />

**What did you learn?**

We learned how to include IEX cloud into data analysis projects and how to import data directly from it. We also learned that it is extremely simple and efficient to build an API. Most importantly, we gained experience in working together in a fast-paced environment on a fun, challenging project. 
<br />

**What is next for your project?**

We are excited to build on the foundations of this project! Our plan is to create a user interface for it and actually host this as a live application on the web for anyone in the world to use for free.
<br />

*Sources*

https://analyticsindiamag.com/hands-on-guide-to-using-yfinance-api-in-python/
https://plotly.com/python/financial-charts/
https://secure.devpost.com/users/register?return_to=https%3A%2F%2Fdevpost.com%2Fsoftware%2Ftesla_stock_analysis%2Fmembers%2Faccept%3Fflow%255Bdata%255D%255Binvitation_key%255D%3DDkDce3hzd5uQ68C2LK3Q%26flow%255Bname%255D%3Daccept_software_invitation%26ref_content%3Dnew_user_added_to_software_team%26ref_feature%3Dportfolio%26ref_medium%3Demail%26utm_campaign%3Dsoftware%26utm_content%3Dinvitation_to_join_software_team%26utm_medium%3Demail%26utm_source%3Dtransactional
