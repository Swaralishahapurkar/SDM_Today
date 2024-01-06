1. Make new folder sdmexam etc
2.Make repo on git and add readme file and add Node into gitignore
3.In folder on cmd- clone your repo
4.create new folder public  (je sagla karel te clone keleya repo cha aat asla pahije)
		-can add image/Index/Aboutus/contactus in  it
5.open folder in vs code and copy server.js there
6.Open terminal in vs code and give command - npm init
											-npm install express
											-node server.js 
											on chrome localhost:port number
7.on notepad "Dockerfile" -save as all types
8.to push all this in your repo=-git status
								-git add .
								-git status
								-git commit -m "added"
								-git push 
9.now open aws and launch ec2 instance
	-ubuntu
	-launch
		-security -security group link
		-edit inbound rules
		-add rules
		-all traffic ,ipv4
		-save rules
		-launch instance
10.on aws console-
	-sudo apt update
	-mkdir myapp
	-cd myapp/
	-git clone our repo
	-ls
	-cd sdmexam
	-sudo apt install docker.io
	-sudo systemctl --type=service --state=running
	-cntrl+c to exit
	-sudo docker build -t swara .
	-ll
	-sudo docker run -d -p portno:portno swara
	-copy public ip and paste on google : port number

