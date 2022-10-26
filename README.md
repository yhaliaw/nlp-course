Natural Language Processing with Neural Networks for Beginners
===

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yhaliaw/nlp-course/master) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yhaliaw/nlp-course/blob/master/)


This course will focus on the basic of Natural Language Processing with Neural Networks with emphasis on implementing theories and concepts learned into code. This course is designed with no prior knowledge in NLP or Neural Networks in mind.

This course is in development.

#### Table of Contents:

Completed:
- 0    NLP and Data Preprocessing
- 1    Language Model
- 2    Neural Network
- 3    Backpropagation
- 4.a  Training of Neural Network
- 4.b  Implementation of Neural Network Training

Planned:

- 5    Word Embedding
- 6    Recurrent Neural Network
- 7    Seq2Seq
- 8    Attention for Seq2Seq
- 9    Transformer

Jupyter Notebook will be used for this course. The solutions to the exercises are at the end of each course.

Run with Binder:
---

Binder let you run a fully functional Jupyter notebook in the cloud.

Click the badge to run: 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yhaliaw/nlp-course/master)

##### Binder can take a while to load.

1. After some loading, a web browser should appear with a list of files.
2. Open a jupyter notebook file (.ipynb) to begin. The filenames of notebook starts with chapter numbering.

View on nbviewer:
---

nbviewer let you view Jupyter notebook but not run them.

[Click here to view](https://nbviewer.jupyter.org/github/yhaliaw/nlp-course/tree/master/)


Installation:
---

#### 1. Install Anaconda 3:
Download the Anaconda 3 for your platform (Windows/macOS/Linux) [here](https://www.anaconda.com/distribution/).

Install the according to the instruction here: [Windows](https://docs.anaconda.com/anaconda/install/windows/), [macOS](https://docs.anaconda.com/anaconda/install/mac-os/), [Linux](https://docs.anaconda.com/anaconda/install/linux/)

#### 2. Create the environment:

For Windows: Open `Anaconda Prompt`.

For macOS/Linux: Open a terminal.

1. Create a environment with: `conda create -n nlp-course python=3.7`
2. Activate the environment with: `conda activate nlp-course`
3. Install the packages with: `conda install jupyter matplotlib scikit-learn spacy nltk pandas seaborn`
4. Install PyTorch with:

    Windows/Linux: `conda install pytorch torchvision cpuonly -c pytorch`

    macOS: `conda install pytorch torchvision -c pytorch`

#### 2. Download this repository

For Windows: Install and run [git bash](https://git-scm.com/downloads)

For Mac/Linux: Install git and open a terminal.

1. Download this repository with: `git clone git@github.com:yhaliaw/nlp-course.git`

#### 3. Run the Jupyter Notebook

For Windows: Open `Anaconda Prompt`.

For Mac/Linux: Open a terminal.

1. Change working directory with `cd` command to the `nlp-course` directory.
2. Activate the environment with: `conda activate nlp-course`
3. Start the jupyter notebook with: `jupyter notebook`
2. After some loading, a web browser should appear with a list of files.
3. Open a jupyter notebook file (.ipynb) to begin. The filenames of notebook starts with chapter numbering.

