# Building regression models
_by Keren Vivas_

Many of the articles I've come across highlight the complexities of choosing variables when building regression models, emphasizing the critical nature of this step in the modeling process. Variable selection is a nuanced process, and it hinges on a firm grasp of **data understanding**, **statistical techniques**, and **domain knowledge**. In fact, I believe that _without a solid foundation in these three key areas, there's a significant risk of making incorrect selections_.

While various authors have discussed both traditional and innovative methods to tackle this challenge successfully, I'd like to share my approach in the following section. I will explain how I would address this challenge and provide recommendations for the techniques that I find most effective.

## How I would plan to determine to variables to use in a regression model?
1. Normally, I start thoroghly consider which of the variables would provide me useful insigths to my research obejctives if they are added into my regression model, which of them willprovide answers to my research questions.
2. I develop a exploratory data analysis once I read my dataset into the program, to examine and understand the structure of the data, type of variables, and how the variables are distributed using contigency tables or visualizations.
3. In case that the data is new for me, I look for information to leverage my domain knowledge and be able to identify meaningful variable to use in the regrssion modeling.
4. Before going into modeling regression and maybe go variables that do not provide good fit due to multicollinearity, I perform correlation analysis to identify variables with high correlations may be strong candidates for inclusion in the model. But being cautious of multicollinearity, where predictors are highly correlated with each other which explain the same thing.
Overall, choice of technique depends on factors like the dataset size, the presence of multicollinearity, and the importance of interpretability. 

## What variable selection techniques do I prefer and why?
Honestly, before this class I used to use only R-adjested squared and select the variables that provide me with the best R-adjusted squared. I did not about all traditional or alternative variable selection techniques. Before, no idea about Forward Selection (FS), Backward Elimination (BE), Stepwise (SW), Lasso regression, ridge regression, recursive feature elimitation, principal componen analysis, random forest or mutual information. There is a lot, am I rigth?. knowing now all of these possibles ways to identify acquare variables and going into the specification of all of them, I understand that  their application depends on the nature of the enalysis of I want to perform. It is not a "best" variable selection technique that applies to all situations. In general cases, I would feel biased for stepwise regression techniques like forward selection and backward elimination can help me systematically add or remove variables based on statistical criteria like AIC, BIC, or adjusted R-squared. This technique in combination with cross-validation techniques to assess the model's performance when using different sets of variables. This help me to identify the combination of variables that provides me with the best out-of-sample performance.

But, general taling, the choice of the best technique depends on your specific problem, the nature of your data, and your objectives. It's often a good practice to try several methods, compare their results, and consider domain knowledge to make an informed decision on variable selection.

However, . However, I feel atracted 
