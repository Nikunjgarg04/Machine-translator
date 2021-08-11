![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![translate 3.5.0](https://img.shields.io/badge/translate-3.5.0-darkblue.svg) ![Flask 1.1.2](https://img.shields.io/badge/Flask-1.1.2-darkred.svg)
# Machine-translator

This project will translate sentence or word or paragraph from one language to other

## How To run
* Download this project
* Unzip the project
* Open in pycharm
* Create a seperate environment
    conda create -n machine_translation python==3.6.9

* Select the same environment in pycharm

* Install the requirements files.
    pip install -r requirements.txt

* Execute main.py
* Open a postman
* Url in POSTMAN
    http://localhost:8000/predict
* Select the method as POST
* Select the Body section
* Inside the Body Section Select Raw and Select format as a JSON
* Data which we can send from the postman in this manner:
    {
    "text" : "I am going to beach today!"
}
