![X](logo.jpg)

# Polytechnique [INF581-2021](https://moodle.polytechnique.fr/course/view.php?id=9352)

## Moodle

[Moodle Link](https://moodle.polytechnique.fr/course/view.php?id=9352)

### Welcome to INF581!

Machine learning is an increasingly important area, and it has provided many of the recent advances behind applications of artificial intelligence. It is relevant to a plethora of application domains in science and industry - including in finance, health, transport, linguistics, media, and biology. Lectures will cover the many of the main concepts and algorithms. We will cover in some degree all the main paradigms of machine learning: supervised learning (regression, classification), unsupervised learning, and reinforcement learning. Among many learning algorithms we will look at: least squares, logistic regression, k-nearest neighbors, neural networks and deep learning, decision tree inducers, kernel methods, PCA, k-means clustering, and Q-learning. In the labs, we will implement many of these, and investigate their use in different applications. Programming will be done in Python with scientific libraries such as numpy and scikit-learn. The main grading component is a team project, as well as several in-class tests.

**Course Outline**: A working outline can be found as topics below. This is subject to minor changes as the course progresses. 

**Some recommended literature:**

TODO...

**Lab sessions:**

Jupyter Notebooks can either be executed on Google Colab (works nicely with Google Drive), MyBinder (don't forget to regularly save your work) or locally, in which case Anaconda (2019.10 or above ; Python 3.7 or above) is strongly recommended.
If the conda command does not work, it's that conda is not in the PATH environment variable. You may add it with the command:

`export PATH="/usr/local/Anaconda3-2019.10/bin:$PATH"`

`conda init`

If you choose the "Local" version of the lab sessions, right click on the link > Save Link as...
If you wish to execute the notebooks on the machines of the Salle d'Informatique, download [this conda_environment.yml](conda_environment.yml) file open a terminal prompt and enter:

`conda env create -f conda_environment.yml`

`python -m ipykernel install --user --name inf581 --display-name "Python (inf581)"`

This will install all dependencies in a new conda environment named inf581. Once on the Notebook, don't forget to use Kernel > Change Kernel to use the Python (inf581) environment.
If the conda environment inf581 already exists, you may delete it with the following command:

`conda remove --name inf581 --all`

To launch Jupyter, use:

`jupyter-notebook --ip=0.0.0.0 --port=8080`

## Lab sessions

## Lab session 4: Dynamic Programming

### Subject:

TODO...

### Solution:

- Open in Google Colab: https://colab.research.google.com/github/jeremiedecock/polytechnique-inf581-2021-admin/blob/master/lab4_rl1_dynamic_programming_answers.ipynb
- Open in MyBinder: https://mybinder.org/v2/gh/jeremiedecock/polytechnique-inf581-2021-admin/master?filepath=lab4_rl1_dynamic_programming_answers.ipynb
- Open in NbViewer: https://nbviewer.jupyter.org/github/jeremiedecock/polytechnique-inf581-2021-admin/blob/master/lab4_rl1_dynamic_programming_answers.ipynb
- Download the notebook file: https://github.com/jeremiedecock/polytechnique-inf581-2021-admin/raw/master/lab4_rl1_dynamic_programming_answers.ipynb
