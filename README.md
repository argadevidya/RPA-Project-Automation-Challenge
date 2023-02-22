# RPA-Project-Automation-Challenge
RPA Solution to the automation challenge by www.rpachallenge.com using UiPath

### Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Demo Video](#demo-video)
  * [Steps in the project execution](#steps-in-the-project-execution)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  

### Overview 
The goal of this online RPA challenge website is to create a workflow that will input data from a spreadsheet into the form fields on the web page screen. And of course, it sounds really easy, however, the tricky part here is that the form fields will change its position in every submission round, not to mention that those fields’ identifier is dynamic too.
<img width="941" alt="Screenshot 2023-02-22 181551" src="https://user-images.githubusercontent.com/122998236/220623610-cbdd6f7e-ff1e-43fd-90cc-cc79a6a92f20.png">

Instructions to solve Challenge:
1. The goal of this challenge is to create a workflow that will input data from a spreadsheet into the form fields on the screen.</br>
2. Beware! The fields will change position on the screen after every submission throughout 10 rounds thus the workflow must correctly identify where each spreadsheet record must be typed every time.</br>
3. The actual countdown of the challenge will begin once you click the Start button until then you may submit the form as many times as you wish without receiving penalties.</br>

### Motivation
The motivation is to build a robot to solve this challenge with 100% accuracy in a very less time.
### Demo Video

### Steps in the project execution
1.Read excel file data values using read range activity</br>
2.Open browser to visit "www.rpachallenge.com"</br>
3.Use anchor base activity->find element and type into activity to input form fields</br>
4.Use anchor base for all the form fields</br>
5.Use click activity to click on submit botton</br>
6.Use loop(step 3- step 5) to type into all fields for every round</br>
7.after all 10 rounds, the web site will show you the result with achieved accuracy and time</br>

### Technical Aspect
Dependencies:
![alt text](https://github.com/argadevidya/RPA-Project-Clothing-Consultant/blob/main/dependencies.png)
### Installation
### Steps:
#### Step 1: Installation of UiPath Studio Community Edition
Let us walk through the steps to install UiPath Studio Community Edition. 
Let us start by going to the UiPath Community edition page at www.uipath.com/developers/community-edition
1.	Go to the “Start Trial” or “Get Community Edition” options. 
2.	Look for “Community cloud” and click on “Try it” 
3.	Sign-up/Register with Uipath by providing the information. Once you submit the information, it would open up the UiPath portal. 
4.	In the left pane, choose “Resource Center” and then Download the “Community Edition” as shown above.
5.	An executable setup file (UiPathStudioSetup.exe) would download.
6.	Go ahead and double click this installable to install the UiPath community edition Studio. 
7.	When you get to the License screen, click on ‘Activate Community Edition’. The licenses for UiPath Studio and Robot will be activated. 
8.	Congrats! A browser tab should open up indicating that UiPath has been installed. 
9.	Go to Windows “Start” and look for “UiPath Studio”. Click on it to open the Studio.
#### Step 2: Download project folder "Project-RPA Challenge.zip", Unzip project folder
#### Step 3: Open "www.rpachallenge.com" , Click on "Download Excel" to download excel file
#### Step 4: Open UiPath Studio and open project file from folder
#### Step 5: Open main workflow:In Excel application scope,enter the path of downloaded excel file.
#### Step 6: Save process and run file and see the result.
