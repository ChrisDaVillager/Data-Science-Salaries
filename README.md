# Data-Science-Salaries

Author: **Chris Puccetti**

**Overview**

We will be taking a dive into a dataset that provides insight about the salary of Data Science careers. Our goal is to make predictions as to what the salaries of Data Scientists by utilizing specific features given in our dataset. Features will include Experience Level, Employment Type, Job Title, Employee Residence, Remote Ratio and Company Size. The provided dataset is a small dataset, so we will have little room to work with. 

**Data Visualization**

To further understand the dataset that we are working with, I have provided univariate and multivariate visualizations for better understanding. 

![image](https://user-images.githubusercontent.com/97495724/193087833-7e4328f9-0d98-46c8-bce0-553c4f85a713.png)

* *Displayed above are the salaries of our Data Science careers from 2020 to 2022. For those looking to become Data Analysts/Scientists, we can see their salaries have either remained steady or increased over the past few years. Data Analysts have seen a big increase in salary, now sitting around $100k.*

![image](https://user-images.githubusercontent.com/97495724/191973642-656eb2c9-59ff-4aaf-9ba3-7985205e93d6.png)

* *To further understand how the Data Science industry is working, I wanted to gain insight on much of an impact working from home has made. From where our dataset started gathering information, around half of our data was fully remote in 2020. Remote work saw a 21.7% increase in just 2 years. Although remote work has increased, working in the office is still seeing a steady increase.* 

**Modeling**

Now that we have visualized our dataset and understand it better, model creation is our next step. The dataset is a mixture of integers and strings. To ensure no data leakage, we have scaled and one hot encoded our data. Fit them into a pipeline and moved forward with model creation. Random Forest and a K-Nearest Neighbors Models are the two models I decided to run. With the small amount of data provided, our models did not seem to do well. 

![image](https://user-images.githubusercontent.com/97495724/193094397-054cd68a-8905-4d4a-b801-a65d025531a5.png)

* *When creating models for predictions, our "best" model would be our Random Forest Model. Our Random Forest Model, as displayed above, provides us with the best testing score of 42%. The testing score tells us how well our model will be able to predict the future salaries of Data Science Careers. This Random Forest Model, although performed the best out of our models, would not be best used for production.*

**Recommendations**

If one is looking to earn a consistent increasing salary, job seekers should look into becoming Data Scientists, Data Analysts and Data Engineers. Machine Learning Scientist salaries look to be decreasing. For those who have experience, Directors of Data Science and Principal Data Scientists tend to make the most out of all the careers in Data Science. 

**Contact Information**

Additional questions, reach me at:

* E-mail: villager.2855@gmail.com
* LinkedIn: linkedin.com/in/chris-puccetti
