
# Project 3 Blog Post
_by Keren Vivas_

Embark on a journey through our Diabetes Health Indicator Project, where we delved into the intricacies of a specialized dataset. With a blend of data manipulation, exploratory analysis, and the thrill of experimenting with various models, our mission was clear: pinpoint the ultimate model capable of predicting values with the lowest logLoss metric. The magic didn't stop there – we conquered this challenge five times over, meticulously tailoring our approach for each education level within the dataset. Curious to know more? Take a stroll through our beautifully [rendered repository](https://jgally.github.io/ST558_Project_3/) or dive into the nitty-gritty details on our trusty [GitHub repository](https://github.com/jgally/ST558_Project_3.git) for even more detail about this project.

## _**What would we do differently?**_  
We would kick off our process by confirming the absence of any pre-existing entries related to the "diabetes" condition in the entire dataset. This initial check is crucial to proactively prevent the computation of a factor with three levels. The realization of the absence of such entries occurred when errors surfaced, prompting us to take action and subsequently remove the unused levels.

## _**What was the most difficult part for us?**_ 
The most challenging aspect for us, rather than difficult, was the estimation of logLoss. Despite its apparent simplicity, it posed a significant challenge. Complexity arose when encountering NaN, NA, or Inf values in the logLoss metrics after running on the actual and predicted datasets. As a result, paying meticulous attention to the object types and sizes we were working with became crucial during our efforts. This necessitated continuous checking of what we generated and deciphering the error messages to understand their implications.

## _**What are our big take-aways from this project?**_
Our primary takeaway centers on an increased awareness of the specific data types crucial for each function or calculation in development, as well as a keen understanding of the parameters of the models and the nature of predictions obtained. Rigorous checks have become second nature to guarantee that the code chunk consistently receives the appropriate type of data.

Finally, it's noteworthy to emphasize the effectiveness of my programming classmate, highlighting their robust collaboration and support that significantly contributed to the success of the project:)
