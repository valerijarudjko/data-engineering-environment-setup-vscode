# Creating Python Environment for Data Engineer Tasks (VSCode)

-----
### To do:
- creating a virtual environment (venv)
- installing libraries via pip
- creating the correct project structure (src layout)
- working with .env and logging.yaml
-------
Step 1: Checking for python version
```bash
python --version
```
Step 2: Creating virtual environment (venv) | creates folder inside the project
```bash
python3 -m -venv .venv
```
Step 3: Environment activation | .venv should appear in the terminal | very important if you run multiple projects at the same time!
```bash
source .venv/bin/activate
```
Step 4: instalation of the basic tools for data engineering
```bash
pip install pandas python-dotnet PyYaml
```
- pandas → works with tables and data (the basis for ETL)
- python-dotenv → reads .env files (configurations)
- PyYAML → reads .yaml files (e.g., log settings)




