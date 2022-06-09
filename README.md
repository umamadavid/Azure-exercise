# Azure-exercise
Azure 400 DevOps exercise to collaborate with other developers
(Steps to push to github)

1. Download git bash from http://git-scm.com/download/
install after downloading
2. Create a github account and create a new repository; give a unique name you want

3. In the git bash command window, enter each of the command below and press enter key to execute
  
	git config --global user.name "Umama David"

	git config --global user.email "umamadavid@gmail.com"

	mkdir website

	cd website

	git init

	CREATE A FOLDER (copy the url from the repository)
	git remove add origin https://github.com/umamadavid/Azure-exercise.git

	touch index.html
	git add index.html
	git commit -m "create index.html"
	git push origin master
