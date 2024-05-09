Django is a free and open-source, Python-based web framework that runs on a web server.
Django's primary goal is to ease the creation of complex, database-driven websites. 
With Django, making a professional website is very easy. This tutorial will walk you through making a simple website

# Getting started

What you will need in this tutorial is listed below:
- Latest version of Python
- VSCode (recommended)

Useful plugins for VSCode:
- [Django](https://marketplace.visualstudio.com/items?itemName=batisteo.vscode-django)
- [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
# First project

## Setup

First of all, create a folder for the project and open it, next create a python environment.
`python 3 -m venv .venv`
Next, activate the environment:
- Windows: `source .venv\Scripts\activate`
- Linux: `source .venv/bin/activate`

Installing Django is as easy as this:
`python3 -m pip install Django`

To verify the installation open a python interactive shell with `python3`
and type these commands:
`import django`
`print(django.get_version())`

Exit the shell with `quit()`

Final step: Create the necessary files for the project with this command:
`django-admin startproject [name of the project]`


