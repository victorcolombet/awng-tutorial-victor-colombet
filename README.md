# Empty project to follow the Django 4 official tutorial

Note: this project contains a `.gitignore` file, so that you will only share *source* code on GitHub. In particular it ignores:

- Compiled Python code (`.pyc` files)
- VS Code IDE stuff (`.vscode/` subdir)
- SQLite database content (`db.sqlite3` file)
- etc.

## Get your own local copy of this project

1. Fork and then clone this project, following and adapting the instructions of https://docs.github.com/en/get-started/quickstart/fork-a-repo
2. Add your teachers as members of **your** project:
   1. Go to Settings / Collaborators on your project's GitHub page
   2. Use Add Collaborator for each teacher (type its GitHub identifier)
4. Launch VS Code and open the local directory
5. In your local project directory, create a virtual environment and install Django (see next section)


## Install Django in a virtual environment

### On Linux or macOS

Open a terminal in your local directory (it can be VS Code integrated terminal), then:

```bash
$ python -m venv venv
$ source venv/bin/activate
(venv) $ pip install Django
```

### On Windows

Run a Powershell console **as an administrator** (you cannot use VS Code integrated terminal yet), go to the local project directory, then:

```powershell
$ py -m venv venv
$ venv\Scripts\activate
(venv) $ pip install Django
```
