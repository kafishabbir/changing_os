# Setup Github
In home launch this
##
        ssh-keygen -t ed25519 -C "your_email@example.com"
        
Print the contents of the public file
##
        cat .ssh/id_ed25519.pub
        
Hit this, see some message, "reply yes"    
##
        ssh -T git@github.com

##
        git config --global user.email "you@example.com"

##
        git config --global user.name bluekafi

        
# The steps when changing operating system

## General Steps
1. Save Bookmarks
1. Save passwords
1. save authentication keys
1. Copy all files

## List of main folders
1. Documents
2. Pictures
3. Repo
4. Videos

## List of apps to reinstall
Update and upgrade 
##
	sudo apt update && sudo apt upgrade -y

GIT
##
	sudo apt install git

MAKEFILE
##
	sudo apt install make 

1. telegram (Downloaded file)
2. libre
##
	sudo apt install libreoffice
        
3. vlc
##
	sudo snap install vlc
        
4. geany
##
	sudo apt-get install geany
5. obs
##
	sudo apt install obs-studio
6. gimp
##
	sudo apt install gimp
        
7. transmisison
##
	sudo apt install transmission
        
8. chrome
##
	sudo apt install -y chromium-browser

9. authenticator: download or appstore

10. latex
##
        sudo apt-get install texlive-full
        
11. shotwell for cropping pic
##
        sudo snap install shotwell
        
        
12. virtual environment 
### Go to project directory
##
	cd my-python-project

### Create the virtual env
##
	python3 -m venv venv

### Activate it
##
	source venv/bin/activate

### Install some packages
##
	pip install requests

### Deactivate
##
	deactivate
	
### To see the requirements
##
	pip freeze > requirements.txt
or
##
	pip freeze 
	
### Install from a list of requirements
##
	pip install -r requirements.txt


