# Documentation

## Preparation to run locally
(Only if this is the first time you run the code) create a venv to work in, as follows:
```sh
python -m venv venv_gdg_hackathon_2025
```

Then, you need to activate the venv:
```sh
../venv_gdg_hackathon_2025/Scripts/activate.bat
```
Once the venv is active, the prompt will change to show the name of the venv. 

Then, you can install the required libraries:
```sh
pip install -r requirements.txt
pip install -r requirements_dev.txt
```

We mainly used jupyter notebook for the actual program, which you can launch in the terminal (after activating the venv) as follows:
```sh
jupyter notebook
```