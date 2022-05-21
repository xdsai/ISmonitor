# IS Monitor

This is a script for monitoring changes on the notebook page on is.muni.cz and sending any changes via an embed to a discord webhook. It utilizes the requests python library and scrapes in irregular intervals. Only the czech version of is.muni is currently supported and English is not in the works.

## Installation
If you are running a Debian based distro, and don't have pip installed, you'll have to download pip before the installation - 
> apt-get install python3-pip

Then to install basic dependencies, just run the shell script - 
> sh install.sh

This will also set your keyring values of UCO and your password to be able to login on IS without you having to enter your credentials in plain text. 


### Notes
This is an alternative script you can run yourself on a home server or such, if you don't wish to have the changes forwarded to your email.
