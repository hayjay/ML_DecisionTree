# Installation and Setup

Install Jupyter Notebook here on [Jupyter](https://jupyter.org/install.html).

## How can this be tested ?

Problem Definition : First of, It is important to know and Understand the problem at hand. This ML Algorthm uses the Decision Tree in deciding the kind of music a user would like to listen to, based on his or her age and gender group.

After successful installation of Jupyter notebook on your machine, follow the below steps:

1. Clone this [Repository](https://github.com/hayjay/ML_Models.git).
2. Type this command on a terinal or a command line interface ```jupyter-lab```
3. Step 2 is expected to display and open your installed Jupyter notebook in a new browser tab by default, its usually on localhost:8888 as the case may be.
4. Open the music_prediction.ipynb file and run the python code.
5. When you run this the music-recommender.dot file will be created (if not already created).
6. To See the result and performance of our model, drag and drop the ```music-recommender.dot``` file into a vscode editor window then install the dot extension in vscode so that vscode can read and interprete the content of this .dot file.
7. When step 6 is completed, in vscode, right click the ```music-recommender.dot``` file and click on "Open preview to the side" then the result and the music prediction result gets displayed.

Here is what the result the model looks like when it's given the age and gender of a user from age 30 and below and also from age 25 and below the screenshot of the output below also took into consideration female genders using the <= 0.5 criteria to identify those in that group:
![Optional Text](music_decisiontree_result.png)