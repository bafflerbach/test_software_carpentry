---
title: "Addressing Model Limitations"
teaching: 15
exercises: 20
questions:
- "How do I properly assess my model's performance and limitations when making new predictions?"
objectives:
- "Students learn about the ethical limits of model applicability"
keypoints:
- "The data used to train a ML model can impart implicit bias into the models predictions"
- "Considering how representative the training data is of predictions that we want to make can help us understand where it is appropriate to make predictions"

---
## Background  

Responsible conduct of research requires that scientists and engineers uphold ethical standards in every aspect of their work. 
Although you are at the beginning of a research career at this point, the work you do will likely go on to have an impact on the field and the world around you. 
The long-term outcomes may have significant ramifications for products, structures, and people’s lives. 
As a young professional in your field you must attend to ethical standards for the societal good and for the sake of yourself and your coworkers. 
Not only is a negligent individual placing their own reputation at risk, but they can also damage the reputations of their colleagues and the broader researcher community.  
  
In machine learning you will need to both understand and be forthright about the limits of your model. 
For instance, if a company developing machine learning for their self driving cars only trained its model on highway driving datasets, you would not be very comfortable getting in this car and letting it drive you through city streets. 
Driving is occurring in both circumstances, but we know from our personal experience that these two types of driving are quite different from each other. 
So you would not want the company to claim that their car is capable of self driving everywhere if their training set was limited to highway driving.  
  
Another example to think about is the pricing of houses. 
If you were to develop a model predicting the sale price of houses in a medium sized city in the Midwestern U.S. (like Madison, WI), you would expect it would be quite an accurate model in that locale. 
If you used that same model on another Midwestern city with a large urban population (like Chicago, IL) then you would expect that model to be less predictive. 
You would expect even worse performance if you used this model on a city on the East Coast with an even larger urban population (like New York, NY). 
So even though your model is good in the vicinity of your training dataset, once you go outside that vicinity your model is no longer reliable.    
Because you will inevitably run into roadblocks and obstacles and you will have to think of creative ways to get around, over, or through them, 
it is important to develop a collection of strategies that might be useful to you in different situations and identify which ones would be best to try first and which to save to last.  

Machine learning cannot be ethically used to make predictions outside of its training scope. 
Consider mammography databases that are used diagnostically for breast cancer in women. 
These databases usually contain mammograms from disproportionately more white women than black women. 
If a machine learning model were developed to predict breast cancer by training on such a database, it would not predict as equitably for all patients (Stewart, 2019). 
For this reason, recent research using machine learning to detect breast cancer is training on data from both white women and black women. 
This is particularly important given that black women are 42% more likely to die from breast cancer (Conner-Simons and Gordon, 2019).  

As you consider the data sets that you are employing, take the time to think about the applicability of the model you are developing and its limitations.
  
> ## Activity: Reflect on actions in "Introduction to Citrination" module  
> Think about other situations in which models may be outside of their training scope. 
> Add below with an example of a situation in which a model might be outside the scope of it’s training data. 
> This may come from a personal experience, previous activities you’ve worked on, or an area of interest you’d like to work on in the future.  
{: .discussion}
  
References:  

Jeffrey Dastin, "Amazon scraps secret AI recruiting tool that showed bias against women,"
Reuters, October 10, 2018. https://www.reuters.com/article/us-amazon-com-jobs-automation-insight/amazon-scraps-secret-ai-recruiting-tool-that-showed-bias-against-women-idUSKCN1MK08G  

Adam Conner-Simons and Rachel Gordon, "Using AI to predict breast cancer and personalize care," MIT News, May 7, 2019. https://news.mit.edu/2019/using-ai-predict-breast-cancer-and-personalize-care-0507  

Matthew Stewart, “The Limitations of Machine Learning,” Medium, July 29, 2019. https://towardsdatascience.com/the-limitations-of-machine-learning-a00e0c3040c6  

W.C. Crone, Introduction to Engineering Research, Morgan & Claypool Publishers (2020).
(Note: This book is available as a free PDF download from the university library.)  
{% include links.md %}
