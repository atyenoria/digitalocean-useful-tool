# Digital Ocean Useful Tool
If you have some bothersome about handling droplets or setting ssh-config,  
 consider this tool.

## Overview
### ocean
	componet:tugboat
	
	functionality
	1: take snapshot droplets. after succeeding it, these are destroyed
	2: delete all droplets
	3: delete predetermined numbers of images
	4: create droplets from newest images
### 	ssh-config
	componet:ruby-2.2.2
	functionality:
	1: replace ssh-config's specific host block at once
## Assumption
	only for mac osx mavericks
	tugboat, terminal-notifier(mac os x) must be installed

## Install
	echo "export PATH=~/digitalocean-useful-tool:\$PATH" >> ~/.bashrc
	source ~/.bashrc
	mkdir ~/digitalocean-useful-tool
	cd ~/digitalocean-useful-tool
	git clone https://github.com/atyenoria/digitalocean_cli_useful.git
	chmod +x ocean ssh-config
	./ocean  # obey instruction after this
	./ssh-config  # obey instruction after this
	
## Licence
Of course
[MIT-Lincence](http://rem.mit-license.org/)
