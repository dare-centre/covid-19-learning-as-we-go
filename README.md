# Covid-19 Model Evaluations
Repository for placing code related to COVID-19 model evaluations. The purpose is to evaluate the predictive capability
of the models currently being used to predict deaths and medical resources needed.

- [Paper Evaluation IHME – arXiv](https://arxiv.org/abs/2004.04734)

## Installation

### Pre-requisits

1) You require Python 3 to run the backend analytics and Postgresql to handle the database.
    
    Ubuntu
    ```
    sudo apt-get install python3
    sudo apt-get install python3-pip
    ```
    
    MacOS
    ```
    brew install python3
    ```
   
2) Best practice is to use a virtual environment to ensure all packages are compatible with the specific version of the code:

    ```
    pip3 install virtualenv
    cd <project-path>
    virtualenv -p python3 <project-path>
    source <project-path>/bin/activate
    ```

3) Download Python package requirements, which are detailed in the "requirements.txt" file. These
dependencies can be installed by executing:

    ```
    cd <project-path>
    pip install -r requirements.txt
    ```

## Excecution

```
cd <project-path>
python main.py
```
