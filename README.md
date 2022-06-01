Create virtual environment

```bash 
conda create -n <environment name> python=3.7 -y
```

Activate enn
```bash  
conda activate <environment name>
```

Create a requirements.txt file

Install the requirements
```bash
pip install -r requirements.txt
```

download data from
https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec

git init

dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"

One line update for readme
```bash
git add. && git commit -m "update readme.md"
```

```bash
git remote add origin <url>
git branch -M main
git push origin main
```

tox command-
```bash
tox
```

for rebuilding-
```bash
tox -r
```

pytest command-
```bash
pytest -v
```

setup commands-
```bash
pip install -e .
```

building your own package commands-
```bash
python setup.py sdist bdist_wheel
```
