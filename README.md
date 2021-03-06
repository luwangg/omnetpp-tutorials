About OMNeT++ Tutorials
=======================

This repository contains a GitHub Pages based web site that contains tutorials
for OMNeT++. The site is made available online at https://tutorials.omnetpp.org.

Web pages in the repo are in Markdown format (.md). One way to view
them in the browser is to install a Markdown plugin into the browser;
there are such plugins both for Chrome and for Firefox. Another way
is to run the Jekyll-based GitHub Pages infrastructure on your local
system, and connect to it from your browser -- this is the recommended
way if you'd like to contribute.

To install a local GitHub Pages development environment:

First, make sure you have a working Docker environment. If you are
on Ubuntu, DO NOT INSTALL Docker from the default repository, as it
is out of date. Rather, follow the instructions on docker.com,
https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/

Then, add yourself into the docker group. That will allow you to run
docker commands without sudo. (Replace YOU with your login name.)
Note that you may need to log out and log in again for the changes
to take effect.

$ sudo usermod -a -G docker YOU

Then, pull the preconfigured GitHub Pages docker image:

$ docker pull madduci/docker-github-pages

Then run the jekyll server with the following command:

$ ./start_local_server

Open your browser on http://localhost:4000/

In case of problems, contact us.

--
Andras Varga

