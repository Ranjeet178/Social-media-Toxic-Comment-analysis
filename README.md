# Socila-media-Toxic-Comment-analysis
## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  * [Run](#run)
  * [Deployement on GAE](#deployement-on-gae)
  * [To Do](#to-do)
  * [Technologies Used](#technologies-used)



## Demo
[![]()]()

## Overview
The dataset has been taken form Kaggle "https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge". The focus of this project is to analyse the toxicity of the  comments on social media platform. The comment is classified into six different categories and based on comment it assign its category to either one or more category. After modelig a flask app has been developed. Which takes input as the comment and response category as the output.
## Motivation
The motivation is to develope muti-lable and muti-level NLP application with help of machine learning and flask.

## Technical Aspect
This project is divided into two part:
1. Training a machine learning model and then saving the model.
2. Developing a flask app and uplaoding the saved machine learning model.
    - The user has to specify Comment form the UI.
    - Based on the user input it will return the category or toxicity of the comment.
    

## Installation
The Code is written in Python 3.7. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
bash
pip install -r requirements.txt


## Run
> STEP 1
#### Windows User
> Install python 3.7 from (https://www.python.org/downloads/)
> For IDE install visual code studio.
> To insatll all the requirements write pip install -r requirements.txt


_Attention: Please perform the steps given in these tutorials at your own risk. Please don't mess up with the System Variables. It can potentially damage your PC. __You should know what you're doing_. 
- https://www.tenforums.com/tutorials/121855-edit-user-system-environment-variables-windows.html
- https://www.onmsft.com/how-to/how-to-set-an-environment-variable-in-windows-10

> STEP 2

To run the app in a local machine, shoot this command in the project directory:
bash
gunicorn wsgi:app

![]()

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.




## To Do
1. Add a better UI for the application.

## Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/Ranjeet178/Social-media-Toxic-Comment-analysis/issues/new) by including your search query and the expected result.

## Technologies Used
- Python 3.7
- Flask
- Javascript, HTML and CSS


## Authors
- LinkedIn - [Ranjeet Singh Yadav](https://www.linkedin.com/in/ranjeet-singh-yadav-b5183b118/)

## Acknowledgements
This project is completed by me from scratch.
