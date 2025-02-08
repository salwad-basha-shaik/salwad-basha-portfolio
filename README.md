# DevOps-Portfolio 

| **Licence**  | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)  |
|---|---|

A website to showcase DevOps professional portfolio
# Project Title

A personal prject to create a portfolio website for a DevOps Engineer

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
See deployment for notes on how to deploy the project on a live system.
To get started clone the repository and start coding.

install nginx
sudo apt-get install nginx

clone repository and make changes
git clone  https://github.com/salvathshaik/salwad-basha-portfolio.git

copy all static files to /html folder
sudo cp -pr * /var/www/html/

Now you can access your portfolio

Optional!!!!!!
If you want enable HTTPS for your portfolio website 

apt update
apt dist-upgrade
sudo add-apt-repository universe
sudo apt-get update
apt-get install certbot
apt-get install pytho3-certbot-nginx
certbot --nginx -d <your http website without http mentioned> ex: salwadbashashaik.cloud
systemctl restart nginx

if you want to deploy into apache and enable HTTPS, follow
apt-get install apache2
sudo cp -pr * /var/www/html/
apt-get install python3-certbot-apache
certbot --apache -d salwadbashashaik.cloud

Note: make sure you have enabled the required ports in your cloud provider security group.

Thank you !!!!!!!!!!
