# Apply  the following command after using this template

## First of all open the bash terminal and run the following command
1. python template.py
    1. give the project name
    2. add the packages name as per your project needs in the requirements.txt file
    3. in setup.cfg : edit your REPO NAME
    4. in setup.py : Update your repo name, author name, email id.

2. bash init_setup.sh   (this will help to install python3.8 and all its dependencies)
    1. Now uncomment all the lines of file: ci.yml, docs.yml, python-publish.yml

3. activate your virtual environment
    1. conda activate ./env
    2. pip list

4. tox      (install the python and its dependies)