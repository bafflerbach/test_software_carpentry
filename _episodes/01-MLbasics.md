---
title: "Basics of Machine Learning"
teaching: 25
exercises: 120
questions:
- "What type of research problems can machine learning solve, and what approach do models use to accomplish this?"
- "How does a machine learning model make predictions from its inputs?"
- "What are a set of key steps (also called a workflow) for solving a machine learning research problem?"
  
objectives:
- "Students can describe the structure of several basic machine learning model types, the types of predictions that can be made, and metrics for assessing regression and classification performance"
- "Students will practice using jupyter notebooks to execute machine learning workflows on cloud computing platforms which they can transfer to other projects."
- "Students will assess model performance on two potential applications and justify which task the model is appropriate for" 
  
keypoints:
- "Machine learning (specifically supervised learning) can be used to model complex materials properties that are hard to obtain experimentally"
- "Machine learning models make predictions by learning relationships and patterns from existing data, and use those learned patterns to make predictions of properties of new materials"
- "A workflow for building machine learning models can be broken down into key steps: Data Cleaning, Feature Generation, Feature Engineering, Model Assessment, Model Optimization, and Model Predictions"
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
> 1. With your notebook open (by clicking the launch tool button) make a copy if you haven’t already using the File drop down menu in the top left. 
> 2. The copy will open in a new tab in your browser. Save the copy by clicking “save and checkpoint” under the File drop down menu in the new tab.
> 3. At this point you may close the original tab as we won't use it anymore. 
> 4. To find the newly copied file (to download or open it up later) we will use the [Jupyter tool](https://nanohub.org/tools/jupyter) on Nanohub. Launch this tool which will give us access to the virtual computer that Nanohub is hosting for us. 
> 5. Navigate to the folder “data/results/####/intromllab/bin/”. Note: the number will be a unique number associated with your session. Pick the most recent one if there are multiple (or an older one if you are looking for an older saved file).
> 6. Double click the notebook file “intromllab-Copy1.ipynb” to launch your saved notebook. This is the newly copied notebook file that you just created.
> 7. You can now save this notebook freely, and to return to this notebook later launch the same tool as step 2 and follow the instructions from there.
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

