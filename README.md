# Covid19-Susceptibility-Prediction
Analyzed Covid 19 data to predict which disease affected people are more prone to Covid-19.

In this project, the dataset called "COVID-19 Open Research Dataset" (CORD-19) [1] from the Allen Institute for AI has been used. The CORD-19 dataset contains metadata from over 1.8 million scholarly articles, preprints and other materials related to COVID-19. 

The aim of this project is to analyse those data and find out which disease affected people are more prone to be affected by covid-19.
To do this, Logistic Regression has been used because it is a binary classification problem. As in this project, it's been tested whether a person is more susceptible to be covid 19 positive or negative based on existing attributes, logistic regression is a good fit for the problem. Because, Logistic regression is a method used for binary classification tasks, as it models the probability of the outcome variable (in this case, the probability of being COVID-positive) as a function of the predictor variables (in this case, the underlying health conditions). Logistic regression is also known for its simplicity, interpretability, and ability to handle both numerical and categorical input features [2]. 

After training the model we have taken underlying health conditions as user input and finally predicted the result. 

[1] Wang, L.L., Lo, K., Chandrasekhar, Y., Reas, R., Yang, J., Eide, D., Funk, K., Kinney, R., Liu, Z., Merrill, W., Mooney, P., Murdick, D., Rishi, D., Sheehan, J., Shen, Z., Stilson, B., Wade, A.D., Wang, K., Wilhelm, C., Xie, B., Raymond, D.M. & Weld, D.S. (2020). CORD-19: The Covid-19 Open Research Dataset. arXiv preprint arXiv:2004.10706.
[2] Menard, S. (2002). Applied logistic regression analysis. Sage Publications. 
