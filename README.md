![intro](http://www.mf-data-science.fr/images/projects/intro.jpg)

# Machine Learning - Stackoverflow tags generator API

## Table of contents
* [General information](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## <span id="general-info">General information</span>
This API entry point extends the Tag generator project for Stackoverflow questions using simple Machine Learning algorithms (https://github.com/MikaData57/Analyses-donnees-textuelles-Stackoverflow). The official API documentation is available through Heroku: https://stackoverflow-ml-tagging.herokuapp.com/apidocs/

	
## <span id="technologies">Technologies</span>
Project is created with:
* Flask and Flask_RestFul
* Swagger
* Python 3.7 *(Numpy, Pandas, Sklearn, NLTK, Spacy ...)*

	
## <span id="setup">Setup</span>
To query the API via Curl, send the question to tag as 
```text
curl -X GET "https://stackoverflow-ml-tagging.herokuapp.com/autotag/Test%20with%20Python%20question%20or%20Javascript%20with % 20pipeline "-H" accept: application / json "
```