# Smart-AI-Attendance-Tracker-With-AntiSpoofing

## INTRODUCTION
Face Recognition Attendance System is an attendance management system which is based on face recognition. The system uses the face recognition technology to recognize the face of each staff and mark their attendance as present. This system is a complete automated solution to other manual based attandance systems. Other existing systems are vulnerable to spoofing attacks. Staffs can easily bypass the system security by faking an attendance process showing their photos or images over their phones. So to prevent the system from such spoofing attacks and strengthen the security in biometrics system we have proposed a  liveness detection method in this system.

## REQUIREMENTS
install python 3.6
install flask
install git
opencv-python==4.2.0.34
tensorflow==2.4.0
sklearn==0.0
Pillow==8.1.0
PyMySQL==1.0.2
pandas==1.1.5
gTTS==2.2.1
APScheduler==3.7.0

## HOW TO RUN THIS PROJECT
(The code is tested and implemented in 3.6 so install python 3.6)

### 1. Install Anaconda Prompt
    https://www.anaconda.com/products/distribution

### 2. Install git (if not installed)
       https://git-scm.com/download/win
       click on 64-bit Git for Windows Setup.

### 3.  Download the repository on your local computer.

https://github.com/Sunaina60/Smart_Attendance_Tracker_with_Antispoofing_feature.git

### 4. After downloading, you have to open Anaconda prompt terminal to run this project.


### 5. Before running any files, you have to set up  virtual environment in the directory where the project is located and 
install all the dependenices required for this project.

Creating virtual environment enable us to install the dependencies virtually for this project only without affecting the python dependencies on  your computer.

A virtual environment is a tool that helps to keep dependencies required by different projects separate by creating isolated python virtual environments for them.


##### i) First of all you have to install virtual environment tool to create one.
       
##### Recommended
For installing virtual environment on Anaconda Prompt(Windows):


       conda install -c anaconda virtualenv
     
     
##### ii) After installing virtual environment, you have to install all the dependencies required to run this project in your virtual environment. For doing so you have to follow the following steps:
  
  
  First of all, you have to change your working directory to the location of this repository in your computer by using the following command:
  
  
        cd /*location to the repository */
        e.g cd E:/Smart-AI-Attendance-System-With-AntiSpoofing/ (location to the repository in local computer)
  
  
 ##### iii) After changing the working directory to the current repository/project create a virtual environment by using the following commands:
  
 #### Recommended
     On Anaconda Prompt (Windows)
     
     conda create -n "your virtual environment name" python=3.6 (The code is tested and implemented in 3.6 so install python 3.6)
     e.g.
     
     conda create -n sams python=3.6
     
     
##### iv) After creating a virtual environment in a working directory, you need to activate the virtual environment:

 
 #### Recommended
   On Anaconda Prompt (Windows):
  
     conda activate "your virtual environment name"
   
     e.g 
   
     conda activate sams

#### v) Now you need to install all the requirements and dependencies for running this project.
       
       pip install -r requirements.txt

###### Install the dependencies by seeing the requirements.txt file.

##### vi) Write command to install flask
        pip install flask
  
##### vii) Run project with command
        python attendance_with_antispoofing.py

##### viii) After that
         System shows server like http://127.0.0.1:5000/ and run command on your system, After that web interface will be there and click on let's start button 
  
### Note: The project will not work if the version of python is different. And try installing all the dependencies by following the above instructions if it does not work.

## !! IMP SETUP DATABASE BEFORE RUNNING PROGRAM
###  Install Xampp Control Panel
     https://www.apachefriends.org/download.html
After that click on Apache, MySQL then Click on admin of MYSQL, it will open new page (localhost PhpMyAdmin)

### Follow Steps to create database:
#### a) Click on new , enter the ‘recognition’ database name and enter create
#### b) After that go to import and chose recognition.sql file from project folder and click go
#### c) Hence Database created succesfully

## NOW RUN THE PROJECT WITH 
USERNAME: Admin
PASSWORD: 123

## EMAIL AUTOMATION:
 	Open event_scheduler.py from folder 
 	Enter your email id and password at required places and set your time for email automation.

## MAIN FEATURES OF THE PROJECT
•	Email Automation
 	Automatically sends day to day attendance report to the manager through an email notification. 
 	Also sends emails to absent employees regarding their absence.

•	Liveness detection method for checking the frauds
 	This project has anti spoofing features means Facial anti-spoofing is the task of preventing false facial verification by using a photo, video, mask or a different substitute for an authorized person’s face.
 
•	Do not mark attendance multiple times for the same person in the same day
 	It means suppose a staff has marked his attendance at a time then again at the same time he tries to mark attendance then system will show warning that attendance has already been marked. Staff can mark attendance again on next day only.

•	Face recognizer module recognizes the staff with showing name and id on the camera.

•	Feature of changing password and username at any time.
 	Through admin account, admin can change password and username.

•	Feature of adding, clearing, updating and deleting the employee details, and also contains the features of searching the data.

•	Attendance report shows details of employees with his present or absent status and time of attendance marked and also contains the features of searching the data.

•	Can update the photos of the staff as well.

## FOR MORE DETAILS PLEASE CHECK THE PROJECT REPORT...
