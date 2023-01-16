### Boston House Pricing Prediction

### Softwares and Tools Required

1. [Github Account](https://github.com)
2. [Heroku Account](https://heroku.com)
3. [VS Code IDE](https://code.visualstudio.com/)
4. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)



### Create a new environment for your project

conda create -p venv python==3.7 -y

### Activate the environment
conda activate venv/

# Step by Step Guide

1. Prepare your ML model in Jupyter Notebook
2. Create your Pickle File
3. Install GIT and create your account
4. If you do not have git insttalled in your local system, install it first (Type "Install GIT Cli" in Google)
5. Creat a repository in GIT
	5.1 - Give a name to your Repo
	5.2 - Tick on the Read.me file option
	5.3 - Click on git.ignore option and choose Python
	5.4 - Select a License type
6. Clone the Git to your Repository to your local Machine
	6.1 - Open your CMD
	6.2 - Move to your project folder (Use cd.. , D: cd <folder path>)
	6.3 - Type command git clone <https://github.com/astajyoti1/ML_Delployment_Regression.git>
7. Copy your .ipynb moel file and .pkl file to th ecloned folder
8. Now open the cloned folder in VS Code
9. Connect GIT hub with your VS Code or Sign in to your GIT hub account from your VS Code
10. Sync your Repository
11. Make sure you have anaconda installed in your system. Conda will help you in managing your virtual environment
12. Open the terminal in your VS Code and create a new environment
	conda create -p venv python==3.7 -y
13. Activate virual environment
	conda activate venv/
14. Create the requirements.txt file and write all the library name
15. Run the below command to install all the library from teh requirments.txt file
	pip install -r requirements.txt
16. Configure GIT CLI, so that you can push/commit your code to GIT Hub from VS Code
	git config --global user.name
	If you have already setup it will give output your User Name.

	
	If it is not set up earlier, then you can set the user name, using the below code
	git config --global user.name "Astajyoti Behera"

	To Setup Email Id
	git config --global user.email "astajyoti@gmail.com"
17. To Add any file to GIT
	git add requirements.txt

18. To check the status of all the file (file to be committed/Untracked/Modified) 
	git status
19. To add all the file in a single go
	git add .
20. To Commit any changes
	git commit -m "commit message"	

Check the below help page if you have any doubt
https://www.atlassian.com/git/tutorials/saving-changes/git-commit#:~:text=git%20commit%20%2Da,with%20a%20passed%20commit%20message.

21. Do GIT PUSH
	git push origin main

For help in GIT PUSH command
https://www.atlassian.com/git/tutorials/syncing/git-push#:~:text=The%20git%20push%20command%20is,exports%20commits%20to%20remote%20branches.

22. Create the Flask App - app.py
23. Create the template folder and inside create home.html
24. Write HTML coding for Home page
25. To Run your application in VS Code
	python app.py

26. Inorder to test your api, please install Postman
27. JSON Input to test your predict_api
	{
	"data": {
		"CRIM": 0.00632,
		"ZN": 18.0,
		"INDUS": 2.31,
		"CHAS": 0.0,
		"NOX": 0.538,
		"RM": 6.575,
		"AGE": 65.2,
		"DIS": 4.0900,
		"RAD": 1.0,
		"TAX": 296,
		"PTRATIO": 15.3,
		"B": 396.90,
		"LSTAT": 4.98
	}
}

28. Create the Procfile before you deploy it in Heroku. Procfile will send the command to execute when this app will start or used

29. To Create a Docker Container of the project

	1. Create a Dockerfile
	FROM 
	COPY
	WORKDIR
	RUN
	EXPOSE
	CMD


















	