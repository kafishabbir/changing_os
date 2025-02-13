# Installations on a new os
##
	sudo apt update
	
##
	sudo apt upgrade
	
##
	sudo apt install build-essential

##
	sudo apt install git
	
##
	sudo apt install geany

##
	sudo apt install make 

##
	sudo apt install texlive-full
	
##
	sudo apt install libreoffice

##
	sudo apt install vlc
	
##
	sudo apt install chromium-browser
	
##
	sudo apt install transmission
	
##
	sudo apt install obs-studio

##
	sudo apt install gimp
	
##
	sudo apt install shotwell
	
##
	sudo apt install usb-creator-gtk

## Github
##
	ssh-keygen -t ed25519 -C kafiulshabbir@phystech.edu
	
##
    cat .ssh/id_ed25519.pub

##
	git config --global user.email kafiulshabbir@phystech.edu

##
	git config --global user.name kafishabbir
	

## telegram
	Download from site and run it

## update system
## update appstore

## Authenticator
Install from app center

## Import bookmarks on firefox and log in everywhere



# Back up

## General Steps
1. Save Bookmarks
1. Save passwords
1. Save authentication keys

## Files to copy
1. Documents
2. Pictures
3. Repo
4. Videos


# Instructions
## virtual environment 
Go to project directory

Create the virtual env
##
	python3 -m venv venv

Activate it
##
	source venv/bin/activate

Install some packages
##
	pip install requests

Deactivate
##
	deactivate
	
To see the requirements
##
	pip freeze > requirements.txt
or
##
	pip freeze 
	
Install from a list of requirements
##
	pip install -r requirements.txt
