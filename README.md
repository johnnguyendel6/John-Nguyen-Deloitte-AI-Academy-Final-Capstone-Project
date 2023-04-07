# Predicting 2023 Tech & Non-Tech Industry Profit Margins
## Using 2021-2022 Fortune 100 Company data (revenue & expenses) to predict 2023 industry health

### Project Summary: 
By acquiring the revenue and expenses for both Tech and Non-Tech Fortune 100 companies, logistic regression can be used to predict the health (profit margin) of a sector for 2023. In this file it will highlight the three major steps for implementing this type of machine learning algorithm as well as hightlight the basic Data Science techniques necessary to take for a valid and repeatable solution. This project matters because consulting firms need to adjust the way they approach their sales/pursuit efforts in the tech and non-tech sectors during a volatile market.

<table width = "100%">
    <tr>
        <td>
            <img src="\John-Nguyen-Deloitte-AI-Academy-Final-Capstone-Project\Images\Capture.PNG"/> 
        </td>
        <td>
            <img src="\John-Nguyen-Deloitte-AI-Academy-Final-Capstone-Project\Images\Capture1.PNG"/>
        </td>
        <td>
            <img src="\John-Nguyen-Deloitte-AI-Academy-Final-Capstone-Project\Images\Capture3.PNG"/>
        </td>
         <td>
            <img src="\John-Nguyen-Deloitte-AI-Academy-Final-Capstone-Project\Images\Capture4.PNG"/>
        </td>
    </tr>
</table>
**Companies Revenue, Profit, & Expenses Source:** https://www.kaggle.com/datasets/ramjasmaurya/fortune-1000-companieslatest

### Table Of Contents
1. [Pre-Processing](#pre-processing)
2. [Analysis](#analysis)
3. [Modeling](#modeling)
4. [Working Directory](#working-directory)
5. [References](#references)

### Pre-Processing
* Pull Fortune 1,000 Company Data in 2021 & 2022 
* Minimize the data set from 1,000 to 100
* Classify each company by Industry “Tech or Not”



### Analysis
* Wide distribution of revenue/expense against profit = varying and potentially unpredictable market for stable profit margins.

* When looking at total market value there is “OK” potential value.

* High precision & accuracyin the distribution of revenue/expense against profit = predictable market for stable profit margins.

* When looking at total market value there is high potential value.

* The R^2 score referenced in the each of the linear regression models showcases the coefficient of determination which is a statistical way of measuring how well a model can predict. It is rated out of 1(from 0-1) the closer it is to 1 the more accurate. Each of these Models when graphed had a calculated coefficent of 1.



### Modeling
* Linear regression analysis is used to predict the value of a variable based on the relationship between input and output.

* The linear regression model could be used to predict the either the rise or fall of profits in relation to revenue and expenses.

* We utilized linear regression because we’re working with 1 or more variables to predict an outcome.

* This model could be used for years beyond 2023 if you consider a similar economic environment.




### Working Directory
```
.
│   README.md    
│
└───Data(Pre-Processed)
│   │   Non Consolidated 2021 Data_fortune 1000.csv
│   │   Non Consolidated 2022 Data_fortune 1000.csv
│   │   ...
│   └───Processed data 
│       │   Fortune 100 Company Data (2021).csv
│       │   Fortune 100 Company Data (2022).csv
│       │   ...
│   
└───Images
│   │   Capture.png
│   │   Capture1.png
│   │   Capture3.png
│   │   Capture4.png
│   │   ...
│   
└───Notebooks
│   │   Project Notebook.ipynb
│   │   ...
│  
└───.ipynb_checkpoints
    │   Project Notebook-checkpoint.ipynb
    │   ... 
│  
└───John's AI Academy Apprenticeship - Final Capstone Project Proposal Template.pdf
│  
└───John's Final Capstone Presentation.pptx
│  
└───John's Final Capstone Presentation.pdf
    
```

### References
https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html
https://stephenallwright.com/cross_val_score-sklearn/https://stephenallwright.com/cross_val_score-sklearn/
Dataset:
https://www.kaggle.com/datasets/ramjasmaurya/fortune-1000-companieslatest

