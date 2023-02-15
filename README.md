## 1. Open the terminal and go to project's base folder and create a python virtual environment using venv and activate it:
"python -m venv **name-of-env**" 

"**name-of-env**/Scripts/Activate.ps1" // For powershell

## 2. Install python dependencies using the following command:
"pip install -r requirements.txt"

## 3. Set kernel to to the created python environment  

** If there are new depencies installed use the following command to store the dependecies to the list.

"pip freeze > requirements.txt"  

** Creating python virtual environment guide for VSCode:
https://code.visualstudio.com/docs/python/environments