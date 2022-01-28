# Useful commands for Venv in Python and Anaconda

## Anaconda - [Link](https://www.bing.com/images/search?view=detailV2&ccid=eUDyDtYn&id=93F6359BEB10E398132654EE0DFF17874AEEDAA6&thid=OIP.eUDyDtYnQpXq0xRPlxY35wHaLO&mediaurl=https%3a%2f%2fugoproto.github.io%2fugo_py_doc%2fimg%2fscipy_cs%2fconda-cheatsheeta.png&exph=2500&expw=1650&q=conda+cheat+sheet&simid=608053028769104000&ck=2AD0931E51441DAA1065451437314C15&selectedIndex=0&FORM=IRPRST&ajaxhist=0)

## Pycharm - [Link1](https://aaronlelevier.github.io/virtualenv-cheatsheet/), [Link2](https://docs.python.org/3/library/venv.html)

## Create/Modify Virtual Environment:
### Create a new venv
- *python -m venv <env_name>*
### To activate a new venv type
- *<scriptName>\Scripts\activate* or folder path to venv
### Remove a venv
- *deactivate* and delete it manually from the file manager
### List all packages in directory
- *pip list*

## Create/Import requirements.txt file
### Install pipreqs to create the requirements.txt file
- pip freeze > requirements.txt
- *pip install pipreqs*
#### Set the path of the requirements.txt file
    - *pipreqs </path/to/project>* 
### Uninstalls all installed packages in the current working directory (if needed)
- *pip freeze | xargs pip uninstall -y*
### Installs all packages defined in the requirements.txt file
- *pip install -r requirements.txt*
