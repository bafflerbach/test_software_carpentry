---
title: "Ethical Data Cleaning"
teaching: 15
exercises: 20
questions:
- "When is it appropriate to modify data used in machine learning modeling?"
- "When / What types of modifications are not OK?"
objectives:
- "Students learn about responsible conduct of research practices when determining what data you can exclude in fitting and assessment with machine learning."
keypoints:
- "Removing or ignoring data simply because it performs poorly is not appropriate"

---
## Background  

We may not often think about it, but there are some important ethical issues when it comes to handling data, figures, and images. Here we will focus on ethical issues surrounding the practice of data cleaning in the context of machine learning where you are using computational algorithms to make predictions based on their experience with training datasets. 
  
  
Obviously, fabricating data is wrong, but sometimes it may seem fuzzier when considering whether an action is data falsification. For instance, you may have what you believe to be outlier data points in a dataset. If you were an experimentalist and there is a clear documented reason (for instance a comment in your lab notebook about high room temperature due to broken HVAC in the building, a sample contamination, or a power fluctuation during data collection), then it is reasonable to exclude the data points corresponding to the documented problem. However, it can be a bit more challenging to know whether it is appropriate to exclude certain data points when you are using someone else’s data in a machine learning context. Nonetheless it is an important consideration and one that must be taken just as seriously as the experimentalist so that you are handling data in an ethical manner.
  
  
Imagine that you had concerns about some data points in a dataset you are using for training. Or you find that your model is identifying unanticipated problems with a few of the data points used during training. Ideally you would contact the individual(s) who provided the data to ask them about the details. If this is published data then you would identify the corresponding author of the publication. This individual can be contacted with questions about the paper if you are delving deeply into its content. Often on the first page, but sometimes at the end of the article, you will find contact information for the corresponding author. This contact information should not be used frivolously, but if you have a serious question that you have not been able to find the answer to in any other way, it is reasonable to contact the corresponding author. A conversation with a person more deeply knowledgeable about the data may provide you with the added insights you need in order to know how to handle it properly.
  
  
In other cases, you may be pooling data from a variety of sources and find a discrepancy. In this case you might find that there are multiple, widely varying values given for the same material conditions. It may be difficult or impossible to judge whether one (or more) of them is in error. If you have many values for the condition and one value appears to be an outlier, then you may be able to show statistically that the outlier does not fall within the data population thus giving you justification to exclude it (although you should report any statistical exclusions that you made when writing about your methods). If you only have a few values for the condition and they vary widely from each other, then you should exclude all of them rather than selecting the one that seems to “fit” or excluding the one that seems “suspicious” without any justification. 
  
  
A common situation where data cleaning comes up is when a model has trouble fitting certain data points. For example, a model might give large errors when predicting values when the data points are left out during a cross validation test as validation data of, or even when included in, the training data. Let us call this set of points P, for “problematic”. It might be tempting to identify P as somehow incorrect and remove them. However, it is not usually clear if the large prediction errors in P are a sign of problems in the data or in the model. It is therefore not ethical to simply remove P. What is ethical is to look again at P to see if there might be good reasons to exclude them or correct them based on factors that might cause them to be wrong, e.g., errors in data entry, experimental methods, etc. It is also ethical to hypothesize that these data points might have errors and fit a model to the data without P and present these results, with clear statement that you have excluded P and that you are doing so based only on a speculative hypothesis, along with the fits to the data including P. By supplying this information, the user of your model can assess if they think your exclusion is reasonable and make an informed decision about whether to choose your model. 
  
  
These are just a few examples that you may run into, but there are others. Your primary goal is to treat the data you are working with ethically and not do anything that others might construe as data manipulation. If in doubt, consult your mentor about how data should be handled when you are unsure.
  
> ## Activity: Reflect on actions in "Introduction to Citrination" module  
> In the Introduction to Citrination activity you were instructed to remove a handful of points from the fatigue strength dataset to practice this skill.  
>  
> * Identify a possible justification for removing these data points and then describe your cleaning process as if you were explaining it to another researcher or colleague.  
> * Describe two examples of when the removal of these data points would be considered unethical data manipulation. 
{: .discussion}
  
Reference:  W.C. Crone, Introduction to Engineering Research, Morgan & Claypool Publishers (2020).  
(Note: This book is available as a free PDF download from the university library.)

{% include links.md %}
