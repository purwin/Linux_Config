# Linux Configuration Project

This is an Amazon Lightsail–hosted Linux server featuring my [`Udacity_Catalog`](https://github.com/purwin/Udacity_Catalog) CRUD web app.

## Server Location

1. Static IP Address: 54.211.2.80
2. SSH Port: 2200

## URL

1. Here's a link for the web app URL: http://54.211.2.80.xip.io

## Setup Summary

1. Amazon Lightsail
    * Created an account
    * Created an Ubuntu OS instance
    * Set up a static IP
    * Configured available ports
    * Used a key pair to SSH into the server on my computer

2. Ubuntu Linux server
    * Checked for server updates
    * Installed requisite applications listed below
    * Configured UFW firewall ports
    * Enabled firewall
    * Created requested user
    * Gave requested user admin privileges
    * Set up key pair for created user

3. Apache HTTP server
    * Installed Apache
    * Configured the WSGI to import and run the web app

4. PostgreSQL database
    * Created a books database to store catalog data
    * Set up a db user based on given requirements
    * Updated web app configuration to connect to database

5. Flask
    * This web app features a Flask framework, with an SQLAlchemy ORM

## Third-Party Resources

1. Amazon Lightsail hosting
2. xip.io (http://xip.io/) for IP address handling
3. Git for cloning the web app
4. Google oAuth authentication
5. GitHub oAuth authentication
6. Book catalog data retrieved from Penguin Random House