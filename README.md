# TEAM_CASCADE-AI-HEALTH-CHECKER-HACKTHESPACE

Link to view the web app:

<a href="https://kushalguha5.github.io/TEAM_CASCADE-AI-HEALTH-CHECKER-HACKTHESPACE/">https://kushalguha5.github.io/TEAM_CASCADE-AI-HEALTH-CHECKER-HACKTHESPACE/</a>

#### TEAM CASCADE : SHAYANTANI KAR, KUSHAL GUHA

#### TRACK : HEALTH

## Problem statement

Lack of awareness of the symptoms often lead to greater complications. People often fail to consult on time due to negligence, cost factor , time constraints, financial matters and many more. Getting an appointment from doctor takes weeks even after having all reports at hand. Fake news make it more complicated to diagnose by yourself. Seeing your weight on scales can be frustrating, which is also a major part of diseases, so a little fun game to incorporate concept of space which checks your weight in different planets.


### Space Weight 
 Know your weight in different planets,if your earth weight haunts you. A fun little web app that tells your weight in diffrent planet if you were ever curious about that

- Uses simple gravitational laws to calculate weight on diffrent planets
- Formula: `weight on any planet = ((your weight on earth/earth gravitaional pull)* that planets gravitaional pull)`
- Example on moon `weight on moon =((67/9.8)*1.62) = 10.24`


### Deployment

This disease prediction webapp was developed using Flask Web Framework and was deployed on Heroku server. The models used to predict the diseases were trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Diseases:
* Diabetes
* Breast Cancer
* Heart Disease
* Kidney Disease
* Liver Disease
* Corona Virus
* Pneumonia

The pnuemonia datset being huge could not be uploaded on github. So here is the link: (https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

- User can easily download the prediction report after the algorithms redirects to the result page.

## Tech Stack Used
-PYTHON 3
-TENSORFLOW
-KERAS
-LOGISTIC REGRESSION, DEEP LEARNING, CNN
-FLASK, DJANGO
-HEROKU (for deployment of the frontend of Predictions)
-JAVASCRIPT, JQUERY
-HTML,CSS,BOOTSTRAP
-SCIKIT LEARN, NUMPY, PANDAS, PIL
-JUPYTER NOTEBOOK
-PICKEL


## Models with their Accuracy of Prediction
Disease | Type of Model | Accuracy
--- | --- | ---
Diabetes | Machine Learning Model | 98.25%
Breast Cancer | Machine Learning Model | 98.25%
Heart Disease | Machine Learning Model | 85.25%
Kidney Disease | Machine Learning Model | 99%
Liver Disease | Machine Learning Model | 78%
Corona Virus | Machine Learning Model | 95%
Pneumonia | Deep Learning Model(CNN) | 95%


## Steps to run the WebApp in local Computer
**Step-1:** Download the files in the repository.<br>
**Step-2:** Get into the downloaded folder, open command prompt in that directory and install all the dependencies using following command<br>
```python
pip install -r requirements.txt
```
**Step-3:** After successfull installation of all the dependencies, run the index.html file.

