<h1 align="center">todo cli</h1>

Todo cli created by typer library using MVC architecture, on database as a json file


## Get started

**Requirements**

1- create virtual env
`python -m venv ./venv`

2- install requirements
`python -m pip install -r requirements.txt`

## Functionality
get version

`python -m todo -v`


help

`python -m todo --help`


run tests

`python -m pytest tests/`


init database

`python -m todo init`


add task, arguments task name and priority 

`python -m todo add finish mlh application  -p 1`


list tasks

`python -m todo list`


complete task based on id

`python -m todo complete 1`

