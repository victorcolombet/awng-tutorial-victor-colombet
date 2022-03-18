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

The following commands create a `venv` virtual environment in your local copy of the project. Open a terminal in your local directory (it can be VS Code integrated terminal), then:


### On Linux or macOS

```bash
$ cd /path/to/project
$ python -m venv venv
$ source venv/bin/activate
(venv) $ pip install Django
```

### On Windows

```powershell
$ cd \path\to\project
$ py -m venv venv
$ venv\Scripts\activate
(venv) $ pip install Django
```

Warning: `activate` might not work on Windows, complaining about some "execution policy" matter. In that case, open a powershell console, run `Set-ExecutionPolicy -scope CurrentUser`, answer `bypass` and `A` (yes to all).

## Use the virtual environment afterwards

Every time you will use a *new* terminal/console to type python or Django commands, you will need to reactivate the virtual environment by calling the `activate` script. Actually, you need to run the `activate` script if you do not see `(venv)` before the shell prompt.

For instance, every time you restart VS Code to work on the project, you will have to go to the project local directory if needed, and then to activate `venv` :

```bash
$ cd /path/to/project
$ source venv/bin/activate
(venv) $ 
```

or:

```powershell
$ cd \path\to\project
$ venv\Scripts\activate
(venv) $ 
```

