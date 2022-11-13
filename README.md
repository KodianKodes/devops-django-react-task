# devops-django-react-task

## Backend development workflow

```json
virtualenv env
source env/bin/activate
pip install -r requirements.txt
python manage.py runserver
```

## Frontend development workflow

You are to update your name in ./frontend/components/App.js

```json
npm i
npm start
```

## For deploying

```json
npm run build
```

It should look like this if successful
<img width="1440" alt="Screen Shot 2022-11-02 at 19 30 22" src="https://user-images.githubusercontent.com/66765302/199572589-43bd05b7-95a6-455c-bc25-3cd437c95339.png">

## Deploying To AWS Instance 
> Create an AWS instance and run the following code 
```
sudo apt-get update && sudo apt-get upgrade
```
Create a user

``` sudo adduser [user account name] ```
```sudo chmod -aG sudo [user account name ] ```  to grant user a root privilage

> install nginx to your server 
``` sudo apt-get install nginx ```
> install docker engine on your Ubuntu instance 
[Docker](https://docs.docker.com/engine/install/ubuntu/)
docker --verion
> login to the user account 
> clone your repo project 

#### Build Docker Image
| Description | Code |
| ----------- | ---- |
| To build docker image | ``` docker image build -t [desired image name ] [Dockerfile Location]``` |
| To run docker image | ``` docker run -d -p [port Id]:[port number] [image name]```|
| To build and run docker yaml file | ``` docker compose up -d ```|
| To check current docker images running | ``` docker ps ``` |
| To stop docker process | ``` docker stop [docker image ID] ```  |
| To check both active and non active process | ``` docker ps -a ```|

### Configure Nginx 




