#  explainable AI disease diagnosis using trained neural network model of Hypothyroid disease dataset 

When AI is used in decision making for critical use cases like diagnosis  loan approval, financial predictions it becomes important for the stakeholders to ensure reliability in the decision process based on AI.Explainable AI (XAI) is the need of the time.

In this tutorial, we will be learning the code and workflow to identify features used by the AI algorithm to make diagnosis predictions.


1. Start by creating a virtual environment for installing the libraries.

```python3 -m virtualenv venv```

**Note:** If you have not installed the virtualenv library, you can do so by running:

```python3 -m pip install --user virtualenv```

2. Activate the environment.

	For Windows:

	```
	cd venv/Scripts
	activate
	```

	For MacOS/Linux:

	```source env/bin/activate```

3. Go back to the root directory and install the requirements.txt.

```pip install -r requirements.txt```

4. We will be using Jupyter Notebook to run our code. You can install it using pip.

```pip install notebook```

4. The `diagnose_hypothyroid_explain_XAI.ipynb` file contains the code for Diagnosing Hypothyroid disease using Deep Learning. The code itself contains the necessary instructions and comments for running it. 

To run the notebook, run the following command at the Terminal (Mac/Linux) or Command Prompt (Windows):

```jupyter notebook```

### Prerequisites

1. Programming knowledge in Python.
2. Basic knowledge of Jupyter Notebook, Deep Learning, Keras.

### Python Libraries used

1. Numpy: For mathematical operations
2. Pandas: For data loading and processing 
3. Plotly: For data visualization/plots
4. Keras:To load saved model
5. Scikit-learn: To perform data pre-processing
6. Pickle: For saving the trained model
7. Dalex: To explain model with plots 

### Results

Using the mechanism, we can understand major features used by the model to perform the diagnosis or decision making

### Citations

- The dataset for training our model was derived from [here](https://www.kaggle.com/nguyenthilua/hypothyroidcsv).
-The model was trained as per the tutorial https://blog.learningdollars.com/2020/11/09/how-to-diagnose-hypothyroid-disease-using-deep-learning/#   e x p l a i n a b l e - A I - d i s e a s e - d i a g n o s i s  
 