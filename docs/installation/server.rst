Server
======

The server is the core of Passky. It uses a MySQL database for the credentials and users.

TODO: Explain what the server is and how it works.

Install Docker and Docker Compose
---------------------------------

See the official `Docker documentation <https://docs.docker.com/engine/install/#server>`_ and follow the installation instructions for your distribution.


Download Passky and extract
---------------------------

Download the Passky archive and extract it to a location, for example /opt/passky/server ::

    mkdir -p /opt/passky
    cd /opt/passky
    wget https://github.com/Rabbit-Company/Passky-Server/releases/latest/download/passky-server.tar.xz
    tar -xf passky-server.tar.xz
    cd passky-server

Make the bash scripts executable. ::

    chmod +x installer.sh installerGUI.sh

Run the installer script. ::

    ./installerGUI.sh

Fill in the requested information, and the script will create a .env file for you.

Finally, create and run the containers with the following command. ::

    sudo docker-compose up -d
