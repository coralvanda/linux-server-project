# What is it?
This is a project created for the Udacity Full-stack Web Developer
Nanodegree.  It uses custom-configured Linux server hosted on Amazon Web
Services (AWS) to run a website.

## Set-up Instructions:
To view the front-end of the website, simply direct a browser to
http://ec2-35-160-17-177.us-west-2.compute.amazonaws.com/.

To access the server, SSH using port 2200 to the following IP address:
35.160.17.177.  An rsa key file is required, and will be provided as part
of the project submission, along with the name of the user to connect as.

### Software installed:
 - libapache2-mod-wsgi
 - libapache2-mod-wsgi python-dev
 - postgresql
 - postgresql postgresql-contrib
 - git
 - sqlalchemy
 - python-pip
 - psycopg2
 - python psycopg2
 - libpd-dev
 - virtualenv
 - Flask
 - ntp
 - httplib2
 - requests
 - flask-seasurf
 - oauth2client

### Configurations
 - users added according to project specifications
 - sudo permission assigned as required
 - remote login of root disabled
 - SSH set to require rsa key for user connection
 - SSH port set to 2200
 - UFW refuses all connections except SSH, HTTP, and NTP
 - local timezone set to UTC
 - PostgreSQL user 'catalog' added with permission to the project database
 - ownership and group of project files/folders assigned to server user
 'catalog'
 - apache2 server configured to host custom wsgi app
 - virtual environment set up to install Python modules necessary for the
 project without altering server Python modules