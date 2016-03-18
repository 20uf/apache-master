Docker ubuntu apache master
============

Simple ubuntu docker images with apache


Usage
-----

To create the image `apache-master` with lasted Ubuntu release, 
execute the following commands on the apache-master folder:

    git checkout master
    docker build -t 20uf/master-apache

Running debian-ssh
--------------------

To run a container from the image binding it to port 80 in all interfaces, execute:

	docker run -d -p 80:80 20uf/master-apache

