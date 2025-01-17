# build123d from scratch

This is to help setup build123 under vscode

build123d requires python version >= 3.10

## Step 1 Install VSCode

Multiple install options.

Including portable version.

## Step 2 Open new project and grab files from this repository

Create a empty folder for your build123d project. Then grab the following files from this repo and place it your folder.

- **helloworld.py**
- **pyproject.toml**

In addition, create a folder called **.vscode** .  Inside that folder should be a file called **extensions.json**. Get that file from this repo. 

Then in VSCode, open that folder File->Open Folder, or run 

```sh
code .
```

inside your folder

## Step 3 Install VSCode extensions

When VSCode opens your project for the first time, it will recommend certain extensions to be installed. Install them.

Just note that the OCP CAD Viewer is quite aggressive, you may want to disable it when not editing build123d projects.

## Step 4 Install python dependencies

Depends on whether you want to use a virtual environment(recommended) or use your system pythons or any python version that VSCode can find on your system. Managing python is beyond the scope of this readme.

#### Install In virtualenv(recommended)

This can be done entirely in VSCode using Command Palette(F1 or View->Command Palette), then **Python:Select intepreter**, then **Create Virtual Environment**, then **Venv**, then your python version, and you should be good to go.

