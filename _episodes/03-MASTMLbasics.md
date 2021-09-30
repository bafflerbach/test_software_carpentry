---
title: "Introduction to MAST-ML"
teaching: 15
exercises: 120
questions:
- "How can I use MAST-ML to execute machine learning workflows?"
objectives:
- "Students are introduced to the MAST-ML software and given a few sample workflows to run on their dataset. The models generated here can then be compared against those previously generated with Citrination."  
- "Students explore various cross validation methods in MAST-ML"
keypoints:
- "MAST-ML is a machine learning workflow package that enables rapid iteration of model building and analysis"
---

**MAST-ML on Google Colab Introduction**  

MAST-ML is a machine learning workflow software package built in python that leverages several other underlying python libraries to enable users to build and test models with little to no python background.  

If you have a little more programming background you can check out the github page for the code below to see a bit about how it’s structured. There is usually ongoing efforts in the skunkworks to improve and add features to MAST-ML so if this is something you might be interested in let us know!  

[MAST-ML on Github](https://github.com/uw-cmg/MAST-ML)  

[MAST-ML Documentation](https://mastmldocs.readthedocs.io/en/latest/)  

**Your First MAST ML Run**  

It’s time to conduct your very first MAST-ML run! For this first run, we will set up a notebook in Google Colab and demonstrate how to call the MAST-ML package to perform machine learning and data science workflow steps.



1. Navigate to [Google Colab](https://colab.research.google.com/) in your browser. NOTE: Each time you return to Google Colab you will likely need to rerun the setup instructions as Colab is fairly aggressive about deleting and shutting down the backend that runs all of the code.  
2. Download the [MASTML_Colab.ipynb](https://drive.google.com/file/d/1Bi4WDCUR_kX5TgZvUwyCTmcjyaTEAkvB/view?usp=sharing) notebook to your local computer. This notebook contains python code to install MAST-ML in the Colab environment and introduces you to the basic ways we can interact with MAST-ML to perform machine learning workflows.  
3. Upload the MASTML_Colab.ipynb file to Colab using File -> Upload Notebook.  
4. With the notebook uploaded you should see something like this, from here you should be able to follow along with the instructions in the notebook:  


![Introduction to MAST-ML Notebook](../fig/intro_mastml_sample.png)  


{% include links.md %}

