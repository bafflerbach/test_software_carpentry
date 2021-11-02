---
title: "Modifying Machine Learning Workflows with MAST-ML"
teaching: 15
exercises: 120
questions:
- "How can we use MASTML quickly to investigate different options within a machine learning workflow?"
objectives:
- "Students learn how to modify different steps of a machine learing workflow within MAST-ML."
- "Students are able to recreate workflows from other machine learning software (like Citrination)."
keypoints:
- "MASTML is divided into seperate modules which focus on key steps in a workflow. By changing individual steps with a few lines of code we can change settings and configurations at each step."

---
## Background
MAST-ML is a machine learning workflow software package built in python that leverages several other underlying python libraries to enable users to build and test models. This activity shows how we can setup and perform a machine learning workflow and also gives an opportunity to modify this workflow.  
  
> ## Readings
> For more detailed information on the structure of MAST-ML please see the [MAST-ML Documentation](https://mastmldocs.readthedocs.io/en/latest/).
> There are also several other Jupyter Notebooks included there that demonstrate additional functionality in MAST-ML that is not covered in this module.
{: .callout}
  
> ## Activity: Modifying Machine Learning Workflows with MASTML
>  
> We will be using Google Colab to perform all of our computing so to begin download the the 
> [.ipynb notebook file](https://drive.google.com/file/d/14fVhdKl8eWxl-G_sJ1L7spmdGAJaLu1N/view?usp=sharing), 
> [the bandgap_data_v2.csv](https://drive.google.com/file/d/1aQtXzo7wiHCpWQZTp4xOkA25Swxx9Gn8/view?usp=sharing), 
> and the [generated_features.xlsx](https://docs.google.com/spreadsheets/d/10Oy_XdH51db9e769OqKtD9-agHk1L6ug/edit?usp=sharing&ouid=110973014880550868255&rtpof=true&sd=true) 
> files to your local computer.   
>  
> Then upload the notebook file using the File dropdown menu option “upload notebook”, or the popup you get when first opening [Colab](https://colab.research.google.com/).  
>  
> With the notebook running then upload the data file “bandgap_data_v2.csv” and “generated_features.xlsx” using the upload button highlighted in red below.  
>  
> ![Uploading Data to Colab](../fig/workflows_1.png "Uploading data to Colab")    
>  
> All further instructions are contained within the notebook file directly.  
>  
> > ## Note
> >  
> > For this activity I am referencing a previous workflow that was performed in the [ML lab activity hosted on nanohub](https://nanohub.org/tools/intromllab)   
> > If you haven’t gone through that activity it may be useful to go through both side by side. One goal of this activity is to show how MASTML can be used to mirror previous machine learning workflows, so seeing them both happen side by side could be a useful way to interact with both.  
> {: .solution}  
{: .challenge}
  
{% include links.md %}

