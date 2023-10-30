# Building regression models:
Many of the articles I've come across highlight the complexities of choosing variables when building regression models, emphasizing the critical nature of this step in the modeling process. Variable selection is a nuanced process, and it hinges on a firm grasp of **data understanding**, **statistical techniques**, and **domain knowledge**. In fact, I believe that _without a solid foundation in these three key areas, there's a significant risk of making incorrect selections_.

While various authors have discussed both traditional and innovative methods to tackle this challenge successfully, I'd like to share my approach in the following section. I will explain how I would address this challenge and provide recommendations for the techniques that I find most effective.

## How I would plan to determine to variables to use in a regression model?
Normally, I consider which of the variables and their type would provide me useful insigths to my research obejctives if they are added into my regression model. So, for this step, I develop a exploratory data analysis once /i read my dataset into the program. 
Then, I check correlation between variables to see if there are some that with explain the same and will reduce time computation.
The choice of technique depends on factors like the dataset size, the presence of multicollinearity, and the importance of interpretability. 
Selecting the most suitable technique often requires a combination of domain knowledge and empirical testing to see which approach best fits your data and research goals.


## What variable selection techniques do I prefer and why?
Honestly, before this class I used to use from the traditional (Forward Selection (FS), Backward Elimination (BE), Stepwise (SW), R-squared (R-sq), and All-possible Subsets), I used R-adjested squared  
