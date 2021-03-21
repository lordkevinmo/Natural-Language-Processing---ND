# Natural-Language-Processing---ND
This repository contains the Tutorials and my solutions to the NLP Nanodegree's Projects powered by Udacity.
See [https://www.udacity.com/course/natural-language-processing-nanodegree--nd892](https://www.udacity.com/course/natural-language-processing-nanodegree--nd892)

Original source code retrieved from Udacity online environments and from the following Udacity repository:

* [NLP Exercises](https://github.com/udacity/NLP-Exercises)
* [HMM Tagger](https://github.com/udacity/hmm-tagger)
* [Machine Translation](https://github.com/udacity/aind2-nlp-capstone)
* [Speech Recognizer](https://github.com/udacity/AIND-VUI-Capstone)

## Installation Notes
I run all the code on Udacity workspace which is a docker image with all the dependencies.

The requirements to run most of the projects are python environment [see instructions](https://docs.python.org/fr/3/library/venv.html), Tensorflow [see instructions](https://www.tensorflow.org/install?hl=fr), [Keras](https://keras.io/), Pandas [see instructions](https://pandas.pydata.org/getting_started.html),
Numpy [see instructions](https://numpy.org/install/), [NLTK](https://www.nltk.org/), scikit-learn [see instructions](https://scikit-learn.org/stable/install.html), and Pomegranate [see instructions](https://pomegranate.readthedocs.io/en/latest/install.html).

You should create a Conda Virtual environments using conda env create -f conda-env.yml command. Normally the created virtual environment should contain all the required Python libraries to execute the projects. (Don't forget to activate the conda environment with conda activate nlpnd before launching Jupyter Lab)

For the 7-Project-VoiceUserInterface project, you should execute the setup_container.sh inside the virtual environment to meet the required configuration (this will downgrade the Keras version and install additional packages)
