---
title: "Modifying Machine Learning Workflows with MAST-ML"
teaching: 15
exercises: 120
questions:
- "How does MASTML enable users to investigate different options within a machine learning workflow?"
- "Specifically, how do users change the model type, hyperparameters, and define a grid search of hyperparameters?"
objectives:
- "Students will recreate workflows in MAST-ML from other machine learning software in (like Citrination or other base ML software packages like scikit-learn)."
- "Students will practice modifying the model type and hyperparameters within a machine learning workflow in MAST-ML by editing code in a Jupyter Notebook."
- "Students will compare a random forest model that's coded into the Jupyter Notebook to a model of their choice and assess the relative performance of the model types."
keypoints:
- "MASTML is divided into seperate sections which execute key steps in a machine learning workflow. By changing individual steps with a few lines of code we can change settings and configurations at each step."
- "In the exercises we demonstrate changes to the model type and hyperparemeters. Additionally changes can be made to data cleaning, feature generation/engineering, model assessment by making similar edits in the notebook."

---
## Background
This module serves as a more detailed exploration of MAST-ML that was introduced in Module 3: Introduction to MAST-ML. In that module students learn the basics of running MAST-ML through a Jupyter Notebook.
In this module we will expand upon that initial understanding and practice making the kinds of edits and modifications to a workflow that one would make when using MAST-ML in a research project.

  
The MAterial Science Toolkit for Machine Learning (MAST-ML) is a machine learning workflow software package built in python that leverages several other underlying python libraries to enable users to build and test models with little to no python background.
The toolkit generates common outputs such as parity plots, learning curves, and standard error metrics which enables new users to easily get to the information needed to make informed decisions about how their models are performing.
Google Colab is a cloud computing resource that allows us to run software on the cloud instead of our local laptops, giving access to more computing power and a standardized computing environment.
We're going to use Google Colab to run the the MAST-ML software in a series of tutorials that demonstrate how to perform a basic machine learning workflow.
  
MAST-ML is divided into a number of sections which allow users to perform ML workflows. These include: Data Importation, Data Cleaning, Feature Generation, Feature Engineering, Data Splitting (Train/Test/Validation), Model Assessment, and Model Optimization
By giving the user freedom to choose methods at each of these workflow steps MAST-ML is a extremely customizable in it's use, compared to some other software tools which are much more structured in the methods used. 
For example the [Citrination](https://citrination.com/users/sign_in){:target="_blank"} web tool which focuses on random forest models.
    
If you have a little more programming background you may be interested to check out the [github page](https://github.com/uw-cmg/MAST-ML){:target="_blank"} for the code below to see a bit about how it’s structured. There is usually ongoing efforts in the Skunkworks to improve and add features to MAST-ML so if this is something you might be interested in let us know!  
  
> ## Readings
> For more detailed information on the structure of MAST-ML please see the [MAST-ML Documentation](https://mastmldocs.readthedocs.io/en/latest/).
> There are also several other Jupyter Notebooks included there that demonstrate additional functionality in MAST-ML that is not covered in this module.
{: .callout}
  
> ## Activity: Modifying Machine Learning Workflows with MASTML
> For this activity we will set up a notebook in Google Colab and demonstrate how to call the MAST-ML package to perform machine learning and data science workflow steps.
> We will then go through how to make edits to this notebook that enable users to modify each step in the workflow.
>  
> 1. We will be using Google Colab to perform all of our computing so to begin download the the 
> [.ipynb notebook file](https://drive.google.com/file/d/14fVhdKl8eWxl-G_sJ1L7spmdGAJaLu1N/view?usp=sharing){:target="_blank"}, 
> [the bandgap_data_v2.csv](https://drive.google.com/file/d/1aQtXzo7wiHCpWQZTp4xOkA25Swxx9Gn8/view?usp=sharing){:target="_blank"}, 
> and the [generated_features.xlsx](https://docs.google.com/spreadsheets/d/10Oy_XdH51db9e769OqKtD9-agHk1L6ug/edit?usp=sharing&ouid=110973014880550868255&rtpof=true&sd=true){:target="_blank"} 
> files to your local computer.   
>  
> 2. Login to [Google Colab](https://colab.research.google.com/){:target="_blank"} in your browser. NOTE: Each time you return to Google Colab you will need to rerun the setup instructions as Colab will delete your previous work after signing off.
>  
> 3. Upload the notebook file using the File dropdown menu option “upload notebook”, or the popup you get when first opening [Colab](https://colab.research.google.com/){:target="_blank"}.  
>  
> 4. With the notebook running then upload the data file “bandgap_data_v2.csv” and “generated_features.xlsx” using the upload button highlighted in red below.  
>  
> ![Uploading Data to Colab](../fig/workflows_1.png "Uploading data to Colab")    
>  
> 5. All further instructions are contained within the notebook file directly. You can begin running code in the notebook by pressing "shift+enter" when selecting any of the code cells.  
>  
> > ## Note
> >  
> > For this activity there are references to a previous workflow that was performed in the [ML lab activity hosted on nanohub](https://nanohub.org/tools/intromllab){:target="_blank"}   
> > If you haven’t gone through that activity it may be useful to go through both side by side. One goal of this activity is to show how MASTML can be used to mirror previous machine learning workflows, so seeing them both happen side by side could be a useful way to interact with both.  
> {: .solution}  
{: .challenge}
  
{% include links.md %}

