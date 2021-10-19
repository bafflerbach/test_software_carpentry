---
title: "Basics of Machine Learning"
teaching: 25
exercises: 120
questions:
- "What is an example of a research problem machine learning can solve?"
- "How does machine learning approach solving this kind of problem?"
- "What are the inputs of a machine learning model called?"
- "What types of outputs (predictions) can machine learning models make?"
- "what is the basic structure of a decision tree or random forest model?"
- "How does a machine learning model make predictions from its inputs?"
- "What are key steps in a workflow for solving a research problem (from the first question)?"
- "How can we use Jupyter Notebooks to run python code to complete this workflow?"
objectives:
- "Students can describe the structure of several basic machine learning model types, the types of predictions that can be made, and metrics for assessing regression and classification performance"
- "Students will create an account on Nanohub and learn how to run Jupyter Notebook tools hosted there"
- "Students can define assessment metrics and describe which should be maximized or minimized to improve model performance"
- "Students will practice saving and interacting with tools on Nanohub"
- "Students can describe the difference between training/testing/validation data"
- "Students can assess model performance via parity plots of training/testing/validation data"
- "Students will compare model predictive capabilities for two potential model use cases"
- "Students can execute a predifined workflow for data cleaning, feature generation, feature engineering, model assessment, model optimization, and model predictions"
keypoints:
- "Machine learning (specifically supervised learning) can be used to model complex materials properties that are hard to obtain experimentally"
- "Machine learning models do this by learning relationships and patterns from existing datasets, and use those learned patterns to make predictions of properties of new materials"
- "Inputs to machine learning models are called features. Some datasets may come with features, other times they need to be generated using knowledge of the specific dataset"
- "Machine learning models can make predictions of continuous variables (regression) or classes of data (classification). Different model types are suited to different types of predictions"
- "A decision tree / random forest model can be thought of as a series of sequential binary splits being made on a dataset, which each split further reducing the amount of data in a *branch* until a *leaf* is reached and a prediction made for the data in that *leaf*"
- "A machine learning model learns patterns and relationships from its input features and uses those patterns to make predictions of an output"
- "The workflow or process for building machine learning models is broken down into key steps: Feature Generation, Feature Engineering, Model Assessment, Model Optimization, and Model Predictions"
---

## Background
  
In this introductory lecture lecture we give a summary of basic machine learning model types, descriptions of input features, data types, classes of models, and a description of several overarching ideas in machine learning. 
  
[Recorded Lecture](https://drive.google.com/file/d/1ZKl3toDN5FO01keG_e_HFMRPjk_EmAk0/view?usp=sharing)
  
You may also view the [Lecture Slides](../files/Intro to ML.pptx) and [Lecture Notes](../files/Module 1 Lecture Notes.pdf) in addition to the recorded lecture.
  

  
> ## Readings
> Here are a few nice introductory articles discussing machine learning basics. 
> They cover the topic from slightly different perspectives, and go into some concepts which will be covered in more detail in other modules.
>  
> [Towards Data Science Article](https://towardsdatascience.com/machine-learning-basics-part-1-a36d38c7916)
>  
> [Machine Learning Mastery Article](https://machinelearningmastery.com/basic-concepts-in-machine-learning/)
{: .callout}
  
> ## Activity: Introduction to Machine Learning for Materials Science
> 
>  This activity will give a hands on example of executing a machine learning workflow for training a model to predict materials properties.
> The activity runs through a Jupyter Notebook hosted on the Nanohub platform. 
> This notebook contains instructions, code, and exercises to read, execute, and answer within the notebook itself. 
> You can begin the activity by Launching the tool on Nanohub [Here](https://nanohub.org/tools/intromllab/).
> In order to complete this activity you will need to either create an account or log in with an existing google account to be able to run the tool.
>  
> If you'd like you may also follow along with a [video walkthrough](https://www.youtube.com/playlist?list=PLUDGrMBDVGZlmFW1kbmq9NI2cMs2eCRON) which discusses the main sections of the notebook activity.
>  
> **Important!**  
> Saving your work in Nanohub is a bit tricky. Follow these instructions to create a copy of the notebook once you've launched the tool via the link.
>  
> 1. With your notebook open (by clicking the launch tool button) make a copy if you haven’t already using the File drop down menu in the top left. Then save the copy by clicking “save and checkpoint”.
> 2. Open the Nanohub Jupyter tool by hitting launch tool here: https://nanohub.org/tools/jupyter
> 3. Navigate to the folder “data/results/####/intromllab/bin/”. Note the number will be a unique number associated with your session. Pick the most recent once if there are multiple (or an older one if you are looking for an older saved file).
> 4. Double click the notebook file “intromllab-Copy1.ipynb” to launch your saved notebook.
> 5. You can now save this notebook freely, and to return to this notebook later launch the same tool as step 2 and follow the instructions from there.
>  
> **Note: do not move the notebook or save to another location on nanohub's virtual computer or else some aspects of the code will break.**
>  
> Follow the [Link](https://nanohub.org/tools/intromllab/) to get started if you did not click above.
>  
>  
> > ## Extra Help
> > 
> > If you are starting with little python backgroud you may find it useful to review the introductory module on python programming via [software carpentry](https://drive.google.com/drive/folders/1o9nzKC2fXTaKIHXot-WLBcZkM1lKAhOj?usp=sharing).
> >  
> > 
> {: .solution}
{: .challenge}



{% include links.md %}

