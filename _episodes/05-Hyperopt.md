---
title: "Optimizing Model Predictive Ability via Hyperparameter Optimization"
teaching: 15
exercises: 120
questions:
- "How can we change the hyperparameters of a model?"
- "What is a strategy for improving model predictive ability through hyperparameter optimization?"
objectives:
- "Students learn about how model hyperparameters can affect performance and are introduced to some basic ideas on how these hyperparameters can be optimized."
- "Students familiarize themselves with a hyperparameter optimization landscape and explore various methods of searching for a global minimum in model errors and avoiding getting trapped in a local minimum."
- "Students familiarize themselves with neural networks, what they are, how to use them, and how to optimize them."
keypoints:
- "A sequential grid search of candidate hyperparameter values can progressively search for the best combination of model hyperparameters"
- "Often time multiple grid searches are required to fully explore a space in sufficient detail"
- "If exploring higher numbers of hyperparameters (>4 or so) it may be better to use more sophisticated search techniques as a full grid search takes much more computational time."

---
## Background 
During other modules included in this curriculum we’ve introduced the basic idea of optimizing models through modifying hyperparameters of the model. 
Hyperparameters are parameters that affect how the model learns and put constraints on the learning process. 
In other activities this optimization step has usually been limited to a single optimization step in which a grid of an example hyperparameter is generated and the best performing model from that grid is identified as the optimized model.   
  
In this module we’ll spend a bit more time looking in more detail at an optimization procedure that goes beyond the very basic introduction. 
The main activity of this module will use the MAST-ML software, and we’ll be primarily working with the multi-layer perceptron neural network model from Scikit-learn.  
  
> ## Readings
> If you haven’t worked with neural networks before I’d recommend reviewing this very nice [introduction series](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) from the youtube channel 3blue1brown which not only covers the basic structure of neural networks but also how they learn while walking through a nice example problem.    
{: .callout}
  
> ## Activity
> This activity is broken down into two parts. The first is an introduction to Neural Networks which we will then use in the second part to explore optimizing a neural network.
>  
> 1. For an interactive way get to know neural networks better also visit this neural network demo by tensorflow: https://playground.tensorflow.org/   
>     1.1. Complete the activities related to the playground included in the ML crash course by google here: https://developers.google.com/machine-learning/crash-course/introduction-to-neural-networks/playground-exercises  
>     1.2. (Optional) If you are looking to practice some programming you can also continue on to the related “programming exercise” that they include which will link you to google colab and provide its own instructions.  
> 2. Colab activity
> We will be using Google Colab to perform all of our computing so to begin download the the  
> [.ipynb notebook file](https://drive.google.com/file/d/1texODGqPo2Dg-5MnPjbxhT5hmWiAFeV3/view?usp=sharing),  
> [the bandgap_data_v2.csv](https://drive.google.com/file/d/1BfQtOX2QnOzRjrTlYxUJ3ks2AteXlSMD/view?usp=sharing),  
>     2.1. First start by uploading the .ipynb file to Colab  
>     2.2. Then upload the data files to a folder in your google drive called “MASTML_colab”  
>     2.3. The rest of the instructions for this activity are included within the notebook itself.
>  
> > ## Note 
> >  
> > if you just completed the modifying workflows activity you may have this setup already and do not need to download or upload the data files as they already exist in your MASTML_colab folder  
> {: .solution}
>  
{: .challenge}
  
{% include links.md %}
