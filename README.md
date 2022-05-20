# AirbnbProject

This project is to analyze Airbnb listings' demand and revenue in Los Angeles areas. The main machine learning models used are XGBoost and Linear regression. Inference tools include permuataion feature importance, SHAP values and Partial Dependence Plot.

For the hosts who haven't entered the market, our model can help them gain a concrete understanding of the potential return-on-investment based on their real-estates characteristics. This includes an analysis of the impact of house size and house type on return-on-investment. For the existing hosts, our project will give them a tool to set an optimal renting price. 

To be more specific, this project analyzes return-on-investment of Airbnb hosts in Los Angeles in 2021 through Airbnb dataset. In this project, we are researching on all the different covariates that may affect revenue and build a model to predict revenue. We first observe that revenue can be decomposed of price and demand. So, we build a model to predict return-on-investment. We will define demand and return-on-investment in the following subsection. The models we considered are: ridge regression and XGBoost models. We performed cross-validation to tune hyper parameters and examine the error to decide which model to use. By the model, we are able to answer the following questions: 

1. What to improve if you want to increase return-on-investment?

2. How does location affect return-on-investment?

3. How does demand changes with booking price, assuming everything else is fixed? (Price Elasticity)

4. Where and what type of real estate to purchase for new Airbnb hosts?

5. For current Airbnb hosts, how do they set an optimal price?

Questions 1, 2, 4, and 5 are crucial to investors while question 3 has economical values.
