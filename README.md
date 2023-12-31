# DDS-Project-2
# Executive Summary for DDS Project 2

## Link to github website: https://tskunz.github.io/
## Link to Presentation: https://youtu.be/M3x2dqi9RGY
## Link to Rshiny App: https://tkunz.shinyapps.io/fritolayattritionshiny/

### Frito-Lay Executive Leadership wants to understand attrition at the company. After analysis of the data DDSAnalytics has found an attrition rate at Frito-Lay of 15.91%. This project will explore the correlations between attrition and other variables, as well as provide models to predict attrition. A K-NN model and linear regression model will be used to predict attrition, and the models will be fit using the top two positive and negative correlated variables to attrition. The variables fit to the models with their respective correlation values are Overtime (+0.27), Employee Age Below 30 (+0.17), Job Involvement (-0.18), and Job Level (-0.16).
### Both models were iterated over 100 iterations and the Accuracy, Sensitivity, and Specificity were stored to measure model performance. While the models were evaluated on all three metrics, the most weight was given to Sensitivity. Sensitivity predicts the true positive class, which in the scope of this analysis is attrition, while specificity would predict the true negative class being not attrition. The K-NN model had median accuracy, sensitivity, and specificity of 68.97%, 66.99%, and 69.25% respectively, while the linear regression model had median values of 70.88%, 70.45%, and 70.95% respectively. Both models achieved the deliverable of 60% Sensitivity and Specificity; however, the linear regression model was selected to use as the model to predict attrition.
### An R Shiny dashboard was developed using the regression model to allow executive leadership the ability to access this model anywhere with an internet connection to assist with their workforce planning needs. This dashboard allows the user to enter real or hypothetical data into the model and it will provide dynamic predictions for attrition.

