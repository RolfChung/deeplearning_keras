# deeplearning_keras



<p>
Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. It was developed with a focus on enabling fast experimentation. Being able to go from idea to result with the least possible delay is key to doing good research.<br>
<a href="https://keras.io/">Keras</a> 
</p> 

<p>
Scikit is a simple and efficient tools for data mining and data analysis.
It is accessible to everybody, and reusable in various context and built on NumPy, SciPy, and matplotlib.
<br>
<a href="https://scikit-learn.org/stable/index.html">Scikit</a> 
</p> 

<p>
This project applies both machine learning packages to solve linear regression problems
and uses the KerasRegressor Wrapper of the Scikit-Learn API to integrate boths packages.
At some points evaluation is done with Scikit cross validation functionality while
deep learning algorithms provided by Keras are supplied. 
The quite arbitary chosen research goal is to predict the Salinity of the water first
with simple and then with mutiple linear regression applying the least-ordinal-regression
algorithm with scikit and deep learning models with Keras. 
It is also investigated how the performance of deep learning models varies with the number of layers
and number of epochs.
</p> 

<p>
The data set used here is the CalCOFI. It and presents the longest (1949-present) and most complete (more than 50,000 sampling stations) time series of oceanographic and larval fish data in the world. It includes abundance data on the larvae of over 250 species of fish; larval length frequency data and egg abundance data on key commercial species; and oceanographic and plankton data. The physical, chemical, and biological data collected at regular time and space intervals quickly became valuable for documenting climatic cycles in the California Current and a range of biological responses to them. For this project only a minimal domain knowlege.<br>
<a href="https://www.kaggle.com/sohier/calcofi/data#bottle.csv">
Kaggle: CalCOFI</a> 
</p>


<p>
This project in applies Matplotlib, Pandas, Scikit, Keras and other methods to the data set. 
The subsequent methods are applied:
</p>

<ul>
<li>Data import</li>  
<li>Data exploration & cleaning</li>
<li>Data visualization</li>
<li>Data import</li>
<li>Data preprocessing</li> 
<li>Train-test-split</li>
<li>Scaling</li>
<li>Random sampling</li>
<li>Data modeling with simple linear regression</li>
<li>Linear regression with scikit as base model</li> 
<li>Feature selection</li>
<li>Deep Learning models on a simple linear regression problem</li> 
<li>Creating deep learning layers with keras</li> 
<li>Compiling the models and fitting the data</li> 
<li>Earlystoppings and callbacks</li> 
<li>Plotting the graph of the model</li>   
<li>Plotting the learning curves based on model loss and mse</li>
<li>Visualization of observed, actual values and fitted, predicted values</li>
<li>Dashboard of relationships between observed and predicted values</li>
<li>Creating scikit-pipelines</li>
<li>Using the KerasRegressor wrapper for the Scikit-Learn API</li>         
<li>Model evaluation with mean-squared-error</li>
<li>Applying scikit KFold and cross validation score methods</li>    
</ul>

<p>
Comments are and explanations are given within the coding and a conclusion is made at the end.
</p>
