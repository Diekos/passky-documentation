Website
=======

The Passky Website is the web client of the Passky password manager.

You can host this application yourself in docker to connect to your Passky instance with a web browser of your choice.

Install Docker and Docker Compose
---------------------------------

See the official `Docker documentation <https://docs.docker.com/engine/install/#server>`_ and follow the installation instructions for your distribution.


Download Passky Website
-----------------------

Download the `Docker Compose <https://raw.githubusercontent.com/Rabbit-Company/Passky-Website/main/docker-compose.yml>`_ file to your server, for example in /opt/passky/website/.


Run the Docker container
------------------------

Run the container using the command: ::

    docker-compose up -d
