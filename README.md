# hello-fargate
Playing around with fargate

## Setup the ECS CLI
https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ECS_CLI_installation.html

https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ECS_CLI_Configuration.html

## Setup the AWS CLI
https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-linux.html

## Setup Environment (VSCode)
`python3 -m venv env`

`cntrl+shift+p` select python interpreter from `./env`

new terminal to activate the env

`pip3 install flask`

`pip3 install gunicorn`

`pip freeze > requirements.txt` to setup requirements

## Run the app from terminal
from the hello_app folder... `python3 -m flask run`