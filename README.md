# linux_server_config

## Introduction
The following is my submission for the Linux Server Configuration project for the Full Stack Developer Nano-Degree program.
The site being hosted is a clone of my Item Catalog project with a few minor modifications.* It is being served via Apache and the WSGI Mod for Apache. All data is being saved to a PostgreSQL server.

## Info:
#### IP Address and SSH port 
52.60.230.102:2200


#### WEB URL 
http://ec2-52-60-230-102.ca-central-1.compute.amazonaws.com

#### Software used to configure this server:
Apache2
Mod_Wsgi
Python
Flask
PostgreSQL
Flask
open2auth

#### Third-Party References and Guides
http://amunategui.github.io/idea-to-pitch/ - good alternative guide to running a flask application on ubuntu

*The main change that's occured between this deployment and the original source code is that the connection string that sqlalchemy loads it's engine for has been switched from one referencing a local sqlite database to the PostgreSQL database living on the same server. That change has occured on every python file that relies on the sqllchemy engine.
