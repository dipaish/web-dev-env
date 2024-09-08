## How to get this docker services up and running? 
- Step1: Make sure that **Docker Desktop** is running
- Step2: Download the Zipped file https://github.com/dipaish/web-dev-env/archive/refs/heads/main.zip
- Step3: Unzip it anywhere in your PC. Make sure that you don't delete this folder. 
- Step4: Start your PowerShell/Terminal and get into the folder (Step3)
- Step5: Get into the environment folder ``` cd environment ```
- Step5: Run the command in PowerShell 
  ``` docker-compose up -d ```

## After a while, all your services are ready. 

- Service 1: MySQL Database Service (6034) >> localhost:6034
- Service 2: Apache PhP Environment (Port 81) >> localhost:81
- Service 3: phpmyadmin (Port 82) >> localhost:82

## Important Folders

- **public** >> A folder where your php code is going to be located. 
A simple php code is there by default

## Notes:

- **Database Root Password**: Set your root password in the `db.env` file by replacing `password` with your own. We use a volume for data storage. Use a strong password and manage it via phpMyAdmin or the MySQL command line. Data will persist even if you rebuild the container.

- **PHP Configuration**: The `php.ini` file contains configuration settings. Make any necessary adjustments based on your app's requirements.

- **Project Files**: Place all your PHP and HTML files in the `public` folder.

## Learn Docker Compose
- **Use Docker Compose:** https://docs.microsoft.com/en-us/visualstudio/docker/tutorials/use-docker-compose 
- **Definitive Guide to Docker Compose:** https://gabrieltanner.org/blog/docker-compose



