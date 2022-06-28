#!/bin/bash
su betty to change user to betty
whoami
whoami prints effective username of current user
groups prints all groups the user is part of
chown changes owner of fille hello to the user betty
sudo chown betty hello
sudo chown betty hello changes owner of hello file to betty 
touch hello to create a new file called hello
chmod u+x hello grants execute permision to owner of the file
chmod u+x,g+x,o+r hello
