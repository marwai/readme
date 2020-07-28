## Vagrant
inside our VM machine 16.04sudo apt-get install -y
- where am I - pwd
- who am I - whoami
- what do I have available in current dir - ls
- how can I find out the name of the system I am using
- How do I find out my current OS - uname
- clear command clears the current whole screen
- How do we create a file - touch "name of file"
- How to create a directory - mkdir "name of directory"

## excercise create two folders: dir1 and dir2
1. in each dir create two files: test1 and test2.txt
2. check the current dir location and document the command to access the dir and exit 

## Terminology 
- cd .. - navigate back to previous folder 
- cd - move to folder
- rm - remove file or dir
- sudo su - change to root user
- id - check who is using the machine 
- echo - print command line 
- exit - go back to user 

- install packages - sudo apt-get install nginx
- check status or programs - 
- Launch nginx in browser            

## Steps to install              
- vagrant up 
- vagrant ssh
- sudo apt-get update -y
- sudo apt- get instal nginx
- systemctl status nginx  

# Starter-code
## Day 2 

- In order to understand it fully we can ask following questions:
```
Communication is the key to succesful projects communications between Dev-Ops-Tester-QA and DevOps
What language is used to build this app?
What framework has been used?
Are they any dependencies to be installed together 
What will the app looklike?
```

1. 
2. Node app requires nodes to be installed. 
3. Ruby to be installed to run the tests 

## install bundle 
- gem install bundler 
- bundle 

## Steps
RAKE SPEC
- rake spec runs the the test written in ruby in the rakefile 
- tests fail 
- install packages for success
- inside vm run:
	- sudo apt-get update
	- sudo apt-get install nginx 
	- systemctl status nginx (checks status)
	- sudo apt-get upgrade
	
	- __install node js__
	- pm2 
	- sudo apt-get install -y nodejs
	- run in root sudo su
	- npm install pm2 -g  

	- cd app 
	- npm install in the app folder 
	- development.localhost:3000
	
	- touch nginx_installation_script.sh
	- chmod +x turns files into executable 
	- chmod +x nginx_installation_script.sh	

# Provisioning with bash scripts
## launch node app
###running tests
- top command```top```

```ps``` command give ProgramID
- ```chmod +x file_name.sh```
- 

### Exercise to find the linux codes to assign permission 
