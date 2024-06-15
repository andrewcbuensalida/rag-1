based on https://www.youtube.com/watch?v=yfHHvmaMkcA&list=PPSV
create openai token
create astra datastax vector db
connect openai with astra using token


To get started

## Create a virtual environment

```bash
python -m venv .venv
```

Activate the virtual environment (mac/linux):

```bash
source .venv/bin/activate
```

For Windows
```bash
.venv\Scripts\activate.bat
```

In the future, to deactivate venv
```bash
.venv\Scripts\deactivate.bat 
```

## Install dependencies
pip install -r requirements.txt

## To save dependencies into requirements.txt
pip freeze > requirements.txt