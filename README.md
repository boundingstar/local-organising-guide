Local Organising Guide
============

A participatory and evolving guide for people to kickstart solarpunk aligned community organisations, and share back their learnings.

This is forked from the Common Guide, in order to expand the scope from organisational governance to encompass other aspects of group organising and better facilitate decentralised collaboration on the Guide.
 
This README is here to mainly support setting up a guide, contributing to a guide and maintaning the project.
For more information what this project is all about see /docs/index.md for a proper Welcome.

Discussions on architecture and usage of the tool are conducted on the common.guide Lumio forum, message me to request access.
# Setting up your own organisation

1. Fork this project repository
2. From your terminal run $ `./bin/setup.sh`
3. Update the .env file with information specific to your project 
4. Deploy the project to your server (See our deployment guide `DEPLOYMENT.md` for more)
5. Deploy your .env file

Joining the project as a collaborator? Ask your team mates to share their .env file (outside of Git).

# How to refresh local environment variables from .env

    $ pipenv shell  # loads env varibles from .env on launch
