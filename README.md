# capstone-cs

Below are the steps to access the web application. Please follow these steps listed below to access the web application.
1.	Ensure the browser and computer system is current and updated.
2.	Go to https://theekrystallee.github.io/capstone-cs 
3.	There will be a login page that requires a username and password, use “admin” for both of those fields. It is case-sensitive. If login fails, proceed to step 4: 
4.	Go to the GitHub repository here: https://github.com/theekrystallee/capstone-cs
5.	There are step by step directions in the README file. 
6.	First thing is to create a local directory to clone the repo
7.	Open terminal and type “cd” to change directory then type “cd desktop” 
8.	In terminal type “mkdir capstone”
9.	Navigate to the cloned directory named “capstone” and type “git clone https://github.com/theekrystallee/capstone-cs “
10.	In the “capstone” local directory, run the following commands to create a virtual environment and install the dependencies to be able to start the application: <br> <br>
    a.	python3 -m venv venv <br>
    b.	cd <br>
    c.	cd desktop/capstone <br>
    d.	source venv/bin/activate <br>
    e.	pip install -r requirements.txt <br>
    f.	pip install appmode <br>
    
11.	Now type “jupyter notebook” in the terminal where the virtual environment is activated  and hit enter. The directory will open in a web browser.
12.	Click on “computer-visionML.ipynb”
13.	Start the application by clicking on the “Appmode” button at the top right corner

14.	Once the Binder page has loaded, which could take up to a few minutes, press the “Appmode” button located near the top. Shown in above figure.
15.	Once the Appmode has been pressed, the dashboard will be opened in a new tab but can take up to a few minutes. 
16.	Once you have access to the web application, at the top there will be a drop down for the parking vacancy detection system. You can select a row number from it, then it will automatically display how many parking spaces are available in the row number you selected in real-time. An example of this is show in the figure below. 
