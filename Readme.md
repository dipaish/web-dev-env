## How to get this docker services up and running? 
- Step1: Make sure that **Docker Desktop** is running
- Step2: Download the Zipped file https://github.com/dipaish/php-course/archive/refs/heads/master.zip
- Step3: Unzip it anywhere in your PC. Make sure that you don't delete this folder. 
- Step4: Start your PowerShell and get into the folder (Step3)
- Step5: Run the command in PowerShell 
  ``` docker-compose up -d ```

## After a while, all your services are ready. 

- Service 1: MySQL Database Service (6034) >> localhost:6034
- Service 2: Apache PhP Environment (Port 81) >> localhost:81
- Service 3: phpmyadmin (Port 82) >> localhost:82
- Service 4: Wordpress (Port 83) >> localhost:83

## Important Folders

- **src** >> A folder where your php code is going to be located. 
A simple php code is there by default

- **wordpress** >> folder for your wordpress site

## To get started with wordpress
- Step 1: Get to **phpmyadmin** and create a database as below:
  Database Name: wordpress
  Database User: wordpress
  Database Password: wordpress
```
 phpmyadmin >> user accounts >> Add User Account >> Type the username and password as above
Just make sure that you check the following options
Database for user account
 Create database with same name and grant all privileges. 
``` 
- Step 2: Get to the browser and type **localhost:83**
- Step 3: Follow the installation Process



