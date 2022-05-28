<h1 align="center">Face Recognition Attendance System
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/Microsoft_logo.svg/480px-Microsoft_logo.svg.png" alt="Logo" width="25" height="25">
  <img src="https://media.istockphoto.com/vectors/human-face-recognition-scanning-system-vector-illustration-vector-id1170702687?k=20&m=1170702687&s=612x612&w=0&h=9uLP7HloaQqmeI-S3R_SBB9kDgnq7oGWJlBsfPQlISc=" alt="Logo" width="25" height="25">
</h1>
<p align="center">

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#features">Features</a></li>
        <li><a href="#compatible-platforms">Compatible Platforms</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <!-- <li>
      <a href="#getting-started">Getting Started</a>
      <!-- <ul>
        <!-- <li><a href="#prerequisites">Prerequisites</a></li> -->
        <!-- <li><a href="#installation">Installation</a></li> -->
      <!-- </ul> --> 
    <!-- </li> --> -->
    <li><a href="#preview-of-the-web-application">Preview of the Web Application</a></li><ul>
        <li><a href="#register">Startup Screen</a></li>
        <li><a href="#login">Main Screen</a></li>
        <!-- <li><a href="#ui-before-uploading-the-image">UI before Uploading the image</a></li> -->
        <!-- <li><a href="#face-detection-results">Face Detection Results</a></li> -->
        <!-- <li><a href="#django-admin-user-and-web-app-data">Django Admin User and Web App Data</a></li> -->
      </ul>
    <li><a href="#shortcomings-and-future-aspects">Shortcomings and Future Aspects</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project
* Face Detection Emotion Recognition project built during Microsoft Engage 2022 program. 
* It is a PyQt5 application through which we can detect the name of the person in front of the camera based on my model created. 
* Displays the name and the 'in' and 'out' time.
* Marks the respective attendance

### Features
* Creating and deleting images, adding and removing Users,designating the accessbility of users to admin site admin(me)

### Compatible Platforms
Laptops and Tablets

### Built With

### Web Application: 
  <ol>
    <li>
      Languages,IDE and GUI
      <ul>
        <li>Python,</li>
        <li>Microsoft VS Code</li>
        <li>PyQt5-designer</li>
      </ul>
    </li>
    <li>Python Libraries</li>
      <ul>
        <li>All libraries of requirements.txt file
           <ul>
               <li>numpy ,open-cv-python-headless,Pillow,sklearn,Dlib etc...</li>
           </ul>
        </li>
      </ul>
    <li>
      Database, Code Maintainance and Backend
      <ul>
        <li>Excel(csv)</li>
        <li>Git,GitHub and GitHub Desktop </li>
      </ul>
    </li>
   
  </ol>
  
  <!-- INSTALLATIONS -->

## Getting Started
To install and run the project on your local system, following are the requirements:
### Prerequisites
Make sure to install the required dependencies 
Install Python from python.org
Install PyCharm Community Edition 2022.1.1

Install CMake first to install Dlib on windows 
```sh
  pip install dlib 
```
### Installation

* Web Application
To run the web application on your local host, perform the following steps:
Clone the GitHub Repo
Create Virtual environment
```sh
  python -m venv name_of_virtual_environment 
```
```sh
  .\name_of_virtual_environment\Scripts\activate 
```
Install and freeze Requirements
```sh
  pip install -r requirements.txt 
```
```sh
  pip freeze > requirements.txt 
```


<!-- APP TUTORIAL-->
## Preview of the Web Application

### StartUp screen

<img src="Face Recognition-Attendance system(PtQt5)-Devshree Singh/preview/start.png" alt="start" width="700"/>

### Attendance System Screen-Face recognition result

<img src="Face Recognition-Attendance system(PtQt5)-Devshree Singh/preview/s1.png" alt="attendance system" width="700"/>

### After being recognized

<img src="Face Recognition-Attendance system(PtQt5)-Devshree Singh/preview/s2.png" alt="After being recognized" width="700"/>

### Attendance sheet preview

<img src="Face Recognition-Attendance system(PtQt5)-Devshree Singh/preview/csv file.png" alt="Attendance sheet preview" width="700"/>


## Shortcomings and Future Aspects

### Shortcomings 
* It does mark the attendance from showing images to the webcam.

### Improvements
* More Relaibility
* Scalability

### Future Aspects
By improving the project on relaibility part and overall aspects,it can be used on a large scale.





