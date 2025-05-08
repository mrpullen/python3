# Python 3 Instructions

## Getting Started

### Download Tools

First thing todo is to download the necessary python and IDE tools that we will use to learn python

* Download Python3 [Python 3.13.3 Download](https://www.python.org/ftp/python/3.13.3/python-3.13.3-amd64.exe)
* Download VSCode [VSCode](https://code.visualstudio.com/download)
* Install Git for Windows [Git for Windows](https://gitforwindows.org/)

*Python interpreter should get added to windows PATH - but if your py files won't execute check there first.*

### Configure Tools

#### Download the github repository to your machine by

1. Open the command line (powershell, cmd)

``` powershell

    cd $env:USERPROFILE\Desktop
    git clone https://github.com/mrpullen/python3
    cd python3
    vscode .
```

Once you've completed that - you should have this repository cloned down to your localhost - and vscode opened in the python3 directory. You can reference this readme.md file in vscode once you install the markdown extension in the steps below

#### Install Markdown extensions if you want to be able to read the instruction files in vscode

Open the extensions marketplace in vscode and enter the text markdown in the search box.

* markdown preview enhanced - provides a preview of a markdown file -

#### Install python extensions in vscode which will make running python files easier

* vs-code-runner - allows for us to run python and other code from the vscode IDE

* python debugger - allows for us to set breakpoints in python code

* python - language support for python in vscode

* pylance - feature rich language support - better autocomplete etc

![alt text](./images/python-extensions.png)

## Lessons

Each lesson will be in it's own directory within this repository - lessons that require you to write code to complete will have stubbed files - with completed answer files in to help you if you get stuck. Please note that answer files are not the only way to solve a particular coding challenge. If your code doesn't match - it doesn't mean that it's incorrect - it very well may be better than the answer provided.

### Lesson 1 Hello World

To start the first lession open the Lesson 1 directory - there is a single file with named hello-world.py The .py extension indicates that this is a python file.

#### Purpose

The purpose of this lesson is to get familiar with running a .py file - some very basic syntax and to ensure your environment is operating correctly.

#### Steps

1. Open the hello-world.py file
2. Click Play / Run button above the hello-world.py file content in the command / tab bar.
3. Verify you have "Hello World" text printed out on the command line.
![Result of running hello-world.py](./lesson1/images/hello-world.png)

#### Troubleshooting

1. If the hello-world program doesn't run - check your windows %PATH% to ensure they python3 exe file is on the path.
2. If you don't see the Play / Run > button ensure you've installed the vscode extensions

### Lession 2
