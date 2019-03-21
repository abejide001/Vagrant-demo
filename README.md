# Vagrant-demo
creating a server with apache
## Getting started

These instructions will get you a copy of the project up and running on your local machine for development purposes.

## Prerequisites
To work with this project you need to have the following installed on your local machine

1. [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2. [Vagrant](https://www.vagrantup.com/)
3. [Vscode](https://code.visualstudio.com/download)

## Install and run locally

```bash
$ git clone https://github.com/abejide001/Vagrant-demo.git
$ cd Vagrant-demo
```
To start the box you need to run the command
```bash
$ vagrant up 
```
ensure it is running in virtual box
<img width="1077" alt="Screen Shot 2019-03-21 at 7 58 46 PM" src="https://user-images.githubusercontent.com/6943256/54777960-cbdf2800-4c13-11e9-97f7-197c3932843e.png">
open ```localhost:8080``` in the browser to the view the page, you should see a page like the one in the image below
<img width="1402" alt="Screen Shot 2019-03-19 at 10 48 33 PM" src="https://user-images.githubusercontent.com/6943256/54778333-a868ad00-4c14-11e9-85fb-4ef4cd3ef802.png">

the box can be stopped the with the command
```bash
$ vagrant halt
```
and the box can be destroyed with
```bash
$ vagrant destroy
```
