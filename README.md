# Sample Node.js application

This repository is a sample Node.js application for Docker's documentation.
# todoapp

This is a simple todo application built using Node.js and containerized using Docker. It allows users to create, read, update, and delete tasks.

# Usage
To run this application, make sure you have Docker installed on your system

To build the Docker Image : 

``docker build -t todoapp .``

To launch the Docker Container from the Docker Image which we have created a min ago: 

``docker run -it -d -p 3000:3000 <image ID>``

And all set.
If you're doing this on cloud platform then just copy the publi/private IP address of instance and attach the port number by colon

If you're doing this on your local machine then run : ``ifconfig`` to know the IP address of your machine, and do the same.


# Thank you !
