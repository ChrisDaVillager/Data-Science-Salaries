# Data-Science-Salaries

Author: **Chris Puccetti**

**Overview**

We will be taking a dive into a dataset that provides insight about the salary of Data Science careers. Our goal is to make predictions as to what the salaries of Data Scientists by utilizing specific features given in our dataset. Features will include Experience Level, Employment Type, Job Title, Employee Residence, Remote Ratio and Company Size. The provided dataset is a small dataset, so we will have little room to work with. 

**Data Visualization**

To further understand the dataset that we are working with, I have provided univariate and multivariate visualizations for better understanding. 

![image](https://user-images.githubusercontent.com/97495724/191972275-fe1bf52e-1e03-478d-8295-d9f22df7290a.png)

* *According to our univariate visualization above, our dataset has a huge range of Job Titles. One thing to keep in mind, as it stands out, the dataset has a lot of entries under the Job Titles of: 'Data Scientist', 'Data Engineer' and 'Data Analyst'.*

![image](https://user-images.githubusercontent.com/97495724/191973642-656eb2c9-59ff-4aaf-9ba3-7985205e93d6.png)

* *To further understand how the Data Science industry is working, I wanted to gain insight on much of an impact working from home has made. From where our dataset started gathering information, around half of our data was fully remote in 2020. Remote work saw a 21.7% increase in just 2 years. Although remote work has increased, working in the office is still seeing a steady increase.* 

**Modeling**

Now that we have visualized our dataset and understand it better, model creation is our next step. The dataset is a mixture of integers and strings. To ensure no data leakage, we have scaled and one hot encoded our data. Fit them into a pipeline and moved forward with model creation. Random Forest and a K-Nearest Neighbors Models are the two models I decided to run. With the small amount of data provided, our models did not seem to do well. 

![image](https://user-images.githubusercontent.com/97495724/191976878-d2af4bb0-b985-40ba-872d-a2781b86a651.png)

* When deciding on the model to push out for production, our "best" model would be our hypertuned Random Forest Model. The base Random Forest Model provided with Train/Test scores of 83%/45% respectively. After hypertuning the max_depth to 7, we saw a decrease in training score but an increase in our testing score with 74%/48%, respectively. 

**Recommendations**

Consultation with a subject matter expert could prove beneficial and being provided with a bigger dataset. Survey more employees from the industry.

**Contact Information**

Additional questions, reach me at:

* E-mail: villager.2855@gmail.com
* LinkedIn: linkedin.com/in/chris-puccetti
