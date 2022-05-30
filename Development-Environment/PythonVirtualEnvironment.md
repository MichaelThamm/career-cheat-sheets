# Useful commands for Venv in Python and Anaconda

## Anaconda - [Link](https://www.bing.com/images/search?view=detailV2&ccid=eUDyDtYn&id=93F6359BEB10E398132654EE0DFF17874AEEDAA6&thid=OIP.eUDyDtYnQpXq0xRPlxY35wHaLO&mediaurl=https%3a%2f%2fugoproto.github.io%2fugo_py_doc%2fimg%2fscipy_cs%2fconda-cheatsheeta.png&exph=2500&expw=1650&q=conda+cheat+sheet&simid=608053028769104000&ck=2AD0931E51441DAA1065451437314C15&selectedIndex=0&FORM=IRPRST&ajaxhist=0)

## Pycharm - [Link1](https://aaronlelevier.github.io/virtualenv-cheatsheet/), [Link2](https://docs.python.org/3/library/venv.html)

## Create/Modify Virtual Environment:
### Create a new venv
- There are 2 options here:
1. You are creating a new venv from a blank project
    - *python -m venv <env_name>*
1. You are creating a new venv inside a git clone project
    - Git runs on bash and if you run the above command in a windows terminal, it will create the venv for bash
    - To fix this, go to your interpreter and create a new virtual environment located in the root of the git clone directory
### To activate a new venv type
- *<env_name>\Scripts\activate*
### Remove a venv
- *deactivate* and delete it manually from the file manager
### List all packages in directory
- *pip list*

## Create/Import requirements.txt file
### Create the requirements.txt file
- *pip freeze > requirements.txt*
### Uninstalls all installed packages in the current working directory (if needed)
- *pip freeze > toRemove.txt*
- *pip uninstall -r toRemove.txt -y*
### Installs all packages defined in the requirements.txt file
- *pip install -r requirements.txt*
