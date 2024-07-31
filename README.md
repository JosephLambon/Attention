# Attention
>### CS50AI Week 6: An AI to predict a masked word in a text sequence.

## Contents
1. [Project Synopsis](#project_synopsis)
2. [Project Resources](#project_resources)
3. [Setup and Usage](#setup)
4. [Demo](#demo)


## <a id='project_synopsis'> Project Synopsis </a>
The aim of this coursework was to utilise BERT, a transformer-based language model developed by Google, to predict a “masked” word that is missing from a sequence of text.

Having studied Context-Free Grammar, n-grams, tokenisation, Naive Bayes; looked at concepts such as Attention, and the training architecture of using Transformers in this week's lecture, this was a good opportunity to put this knowledge into practice.

In building this AI, I was able to explore Hugging Face's transformers library, offering state-of-the-art pretrained ML models to use with TensorFlow.

## <a id='project_resources'> Project Resources </a>
* [transformers](https://huggingface.co/docs/transformers/index)
> Transformers provides APIs and tools to easily download and train state-of-the-art pretrained models.

* [BERT](https://arxiv.org/abs/1810.04805)
> BERT is a transformer-based language model developed by Google in 2018.

## <a id='setup'> Setup and Usage </a>
#### [NOTE: Any lines of code included are intended for the command line]

### 1. Install prerequisites
a. Install [Python](https://www.python.org/) </br>
b. Install [virtualenv](https://virtualenv.pypa.io/en/latest/)
``` 
 pip install virtualenv
```
### 2. Setup virtual environment
* Create virtual environment </br>
```
# Run this line on the command line
# Replace 'env_name' with whatever your desired env's name is.

virtualenv env_name
```
* Start virtual environment
```
# This will activate your virtualenv.

source env_name/bin/activate
```
* Install required packages
```
# Running this in your command line will install all listed packages to your activated virtual environment

pip3 install -r requirements. txt
```
### 3. Change directory
* Change into the 'attention' folder.

### 4. Run mask.py
```
python3 mask.py 
```
You will then be prompted to input some text. This should be a sentence, including one masked word, represented with '[MASK]'. For example:
```
Text: She [MASK] walked up the hill.
```

## <a id='demo'> Demo </a>

A successul run of this python script should see command line output as such:

![Success](https://github.com/user-attachments/assets/1a550ad2-6d68-44ee-b732-5ea738e20c02)
