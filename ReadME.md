### End to End ML Project
### created a new environment
```
conda create -p venv python==3.8
```
### now activate the environment
```
conda activate venv/
```
### install all the necessary libraries
```
pip install -r requirements.txt
```
### when we have to convert the project into package then we have to do setup.py
### after converting into package we can install it into pypi or somethingelse
### in requirements.txt there is (-e .) this means to trigger the setup.py