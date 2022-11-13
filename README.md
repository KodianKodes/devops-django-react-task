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
sudo apt-get update && \
        sudo apt-get upgrade
```
Create a user
```
sudo adduser [user account name]
sudo chmod -aG sudo [user account name ] to grant user a root privilage
```
> login to the user account 
> clone your repo project 
> 

> To create a new user, Run the following command



> Clone your project to your instance 
