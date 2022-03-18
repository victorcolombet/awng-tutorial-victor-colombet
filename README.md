# Empty project to follow the Django 4 official tutorial

Note: this project contains a `.gitignore` file, so that you will only share *source* code on GitHub. 
In particular it ignores:

- Compiled Python code (.pyc files)
- VS Code IDE stuff (.vscode/ subdir)
- SQLite data base content
- etc.

## How to use this project

1. Fork and then clone this project (see https://docs.github.com/en/get-started/quickstart/fork-a-repo)
2. In your local project directory, create a virtual environment and install Django (see next section)
3. Launch VS Code and open the local directory

## Install Django in a virtual environment

### On Linux or macOS

Open a terminal in your local directory, then:

```bash
$ python -m venv venv
$ source venv/bin/activate
(venv) $ pip install Django==4
```

### On Windows

Run a Powershell console **as an administrator**, go to the local project directory, then:

```powershell
$ py -m venv venv
$ venv\Scripts\activate
(venv) $ pip install Django==4
```
