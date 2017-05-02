# Linux-Server-Configuration
 A baseline installation of a Linux server. Secure my server from a number of attack vectors, install and configure a database server. 
 
 This project show a simple configuration when deploying a python Flask web application to Amazon AWS
 - IP address: 35.162.159.229:2200
 - URL: ec2-35-162-159-229.us-west-2.compute.amazonaws.com
 - Project deployed is Item Catalog, please refer to its repository for more details https://github.com/daikikuchi/Item-Catalog
 - Requirements to be installed on server instance to run the application
 `python 2.7`
`python-pip`
 `Flask`
`Flask-Login`
`httplib2`
`Jinja2`
`oauth2client`
`requests`
- Web server has been configured to serve the Item Catalog application as a WSGI app.
- The web server responds on port 80
- Only allow connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).
- All system packages have been updated to most recent versions.
- Key-based SSH authentication is enforced.
