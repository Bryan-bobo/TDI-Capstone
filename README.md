# TDI-Capstone
TDI Capstone project

Title
A news-based stock prediction/warning system

Summary
The project I was doing is about a stock prediction/warning system for investor who are interested in semiconductor industries. Based this system, I can first provide a reference for investor about the approximate increase/decrease values. And furthermore, help the investor build up a protection for possible trading curbs based on the tech news information.
Problem Statement
For an investor, the biggest concern is to make money and avoid big collapse in the market. We all know that the tech news is highly related to the stock circumstance and sometimes can even dominate the stock trend. So, I need to dig into those news contents. By looking into the historical stock data, we need to know that with what information we got from tech news could be a clear signal to predict an upcoming stock collapse in semiconductor industries.
Project
The project has 2 parts. The first part is dealing with the historical stock value data for the 10 biggest semiconductor companies in Nasdaq for the past 5 years. This part can be the resource for me to build up the machine learning models like classification and rolling window time series analysis. The second part is about NLP based stock collapse warning system. In this part, the news data is from techcrunch.com. I conducted NLP such as tokenizing and word frequency counting. With the established dictionary of most appeared word in news before the collapse, each word inside the dictionary can be the warning alarm for the upcoming possible semiconductor collapse. As a result, besides predicting the semiconductor industrial stock value, the project also summarized the 20 most-appeared tech news word that might be highly correlated with collapse. This can help semiconductor investor to make decision for the next step.

Deliverables
The code and results can be found: https://github.com/Bryan-bobo/TDI-Capstone.git

1.	The first part with machine learning and prediction: Stock data loading and prediction
2.	The second part with NLP and resulting word frequency dictionary: Parse Website News Title
