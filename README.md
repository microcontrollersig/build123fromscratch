# build123d from scratch

This is to help setup build123 under vscode

build123d requires python version >= 3.10

## Step 1 Install VSCode

Multiple install options.

Including portable version.

## Step 2 Get files from this repository

Create a empty folder for your build123d project. Then grab the following files from this repo and place it your folder.

- **helloworld.py**
- **pyproject.toml**

In addition, create a folder called **.vscode** .  Inside that folder should be a file called **extensions.json**. Get that file from this repo. 

Then in VSCode, open that folder File->Open Folder, or run 

```sh
code .
```

inside your folder.

Alternatively, you can git clone this repo.
This can be done inside vscode on the Welcome screen(Help->Welcome screen->Clone Git repository... and type the url of this git repo **https://github.com/microcontrollersig/build123fromscratch**) 

## Step 3 Install VSCode extensions

When VSCode opens your project for the first time, it will recommend certain extensions to be installed. Click **Install** .

![recommended extensions](https://raw.githubusercontent.com/microcontrollersig/workshop/master/images/build123d-1.jpg)

Just note that the OCP CAD Viewer extension is quite aggressive, you may want to disable it when not editing build123d projects.

## Step 4 Install python dependencies

Depends on whether you want to use a virtual environment(recommended) or use your system pythons or any python version that VSCode can find on your system. Managing python is beyond the scope of this readme.

#### Install In virtualenv(recommended)

This can be done entirely in VSCode using Command Palette(F1 or View->Command Palette), then **Python:Create Environment**, then **Venv**, then your python version, and you should be good to go.

## Step 5 Get OCP Viewer

When OCP CAD Viewer is installed, you can see OCP entry in left sidebar.

You know when OCP CAD Viewer works,  the logo is visible. 

![recommended extensions](https://raw.githubusercontent.com/microcontrollersig/workshop/master/images/build123d-2.jpg)

![recommended extensions](https://raw.githubusercontent.com/microcontrollersig/workshop/master/images/build123d-3.jpg)

For me, the logo didn't appear the first time.
I close the preview window. Then reopened, then it showed.
