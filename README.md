# docker-behat with html report 

This repository is the source of `haddad1/docker-behat-htmlreport` which brings:  
- a basic shell with oh-my-zsh  
- php5-cli with PHP 5.5  
- behat 3.0 / mink 1.5  
- BehatHtmlFormatterPlugin
- all needed dependencies  

## Install

 docker pull haddad1/docker-behat-htmlreport

## Usage

	docker run -ti -h docker-behat -v "$(pwd)/project":/root/project haddad1/docker-behat-htmlreport zsh

You should see a prompt containing `[ docker-behat ]` and have `behat` command available.  


Also available via [Docker Index](https://hub.docker.com/r/haddad1/docker-behat-htmlreport/).
