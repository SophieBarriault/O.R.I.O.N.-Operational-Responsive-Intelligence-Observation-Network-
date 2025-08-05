F<!--
Hey, thanks for using the awesome-readme-template template.  
If you have any enhancements, then fork this project and create a pull request 
or just open an issue with the label "enhancement".

Don't forget to give this project a star for additional support ;)
Maybe you can mention me or this repo in the acknowledgements too
-->
<div align="center">

![Logo](assets/Hardware_Image_1.png)

# O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network- 

A J.A.R.V.I.S.-inspired AI assistant for smart task automation and conversational support. 


[![Contributors](https://img.shields.io/github/contributors/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-)](https://github.com/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-)(https://github.com/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-)
[![Forks][https://img.shields.io/github/forks/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-](https://github.com/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-/network/members)
[![Stars](https://img.shields.io/github/stars/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-)](https://github.com/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-/stargazers)
[![Issues](https://img.shields.io/github/issues/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-)](https://github.com/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-/issues)
[![License](https://img.shields.io/github/license/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-.svg)](https://github.com/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-/blob/main/LICENSE)

[View Demo](https://drive.google.com/file/d/1wByr87FT2HsipwZgwH-gzBg_70QS4TUb/view?usp=sharing) ·
[Documentation](https://github.com/SophieBarriault/Dispenser/blob/main/README.MD)  ·
[Report Bug](https://github.com/SophieBarriault/Dispenser/issues) ·
[Request Feature](https://github.com/SophieBarriault/Dispenser/issues)

 
</div>

---

# 📔 Table of Contents

- [About the Project](#-about-the-project)
  - [Demo Video](#-screenshots)
  - [Tech Stack](#-tech-stack)
  - [Features](#-features)
  - [Color Reference](#-color-reference) 
- [Getting Started](#-getting-started)
  - [Prerequisites](#-prerequisites) 
  - [Run Locally](#-run-locally)
  - [Deployment](#-deployment) 
- [FAQ](#-faq) 
- [Contact](#-contact)
- [Acknowledgements](#-acknowledgements-) 


---

## 🌟 About the Project

O.R.I.O.N. is an AI-powered assistant inspired by J.A.R.V.I.S. from the Marvel Cinematic Universe — a fictional AI known for its intelligence, conversational ability, and seamless control over complex systems. While not quite at Tony Stark levels (yet), this project aims to bring a real-world version of that vision to life by integrating modern AI tools, natural language processing, and task automation into a single intelligent system.

Built with Python and powered by tools like large language models, speech recognition, and customizable workflows, O.R.I.O.N. is designed to assist with real-time tasks, manage information, and act as a voice-activated, personalized digital assistant.

Whether you're using it to control your desktop, retrieve web data, automate coding tasks, or just have a natural conversation, O.R.I.O.N. brings a piece of sci-fi inspiration into practical, everyday AI.
To create an accessible, intelligent system that ensures patients take the correct medications at the correct times — reducing errors, improving adherence, and offering peace of mind for caregivers and family members. 

**Goal:**
O.R.I.O.N. is an AI-powered assistant inspired by J.A.R.V.I.S. from the Marvel Cinematic Universe — a fictional AI known for its intelligence, conversational ability, and seamless control over complex systems. While not quite at Tony Stark levels (yet), this project aims to bring a real-world version of that vision to life by integrating modern AI tools, natural language processing, and task automation into a single intelligent system.

Built with Python and powered by tools like large language models, speech recognition, and customizable workflows, O.R.I.O.N. is designed to assist with real-time tasks, manage information, and act as a voice-activated, personalized digital assistant.

Whether you're using it to control your desktop, retrieve web data, automate coding tasks, or just have a natural conversation, O.R.I.O.N. brings a piece of sci-fi inspiration into practical, everyday AI.
To create an accessible, intelligent system that ensures patients take the correct medications at the correct times — reducing errors, improving adherence, and offering peace of mind for caregivers and family members. 



**Core Features:**

 - Image recognition model to verify whether medication has been taken correctly.

 - OCR + NLP (Named Entity Recognition) to extract dosage instructions from prescription labels.

 - Arduino-controlled dispensing system triggered by AI verification and scheduled reminders.

 - Mobile + Desktop interface (via Toga framework) for caregiver monitoring and remote updates.

 - Video evidence recording for accountability and patient monitoring. 



**Recognition:**  

 - Filed for a provisional patent for the design and idea December 2024 

 - Selected for the Massachusetts Science & Engineering Fair (MSEF) Regional Round

 - Advanced to the MSEF State Level Competition as a Finalist

 - Praised for its real-world impact, interdisciplinary approach, and scalable potential



---

### 📷 Demo Video 

Click to watch the demo here! 

[![Watch the Demo Video](assets/to_demo.png)](https://drive.google.com/file/d/1wByr87FT2HsipwZgwH-gzBg_70QS4TUb/view?usp=sharing) 


---

### 👾 Tech Stack

- **Python** – Core programming language for the application

- **Toga** – GUI framework for building cross-platform desktop and mobile apps 
- **Buildozer** - GUI framework for both Android and IOS compatibility 

- **OpenCV** – Real-time image processing and integration with camera for pill verification

- **Tesseract OCR** – Optical Character Recognition for extracting text from prescriptions

- **spaCy** – Custom Named Entity Recognition (NER) model to extract dosage/frequency info

- **YOLOv8** – Object detection model to monitor pill intake and hand movement

- **Flask** – Lightweight server to handle requests between the app and ML models

- **PySerial** – Communication between the Python app and the Arduino board

- **Arduino** – Controls pill dispensing mechanism (via servo motors, etc.)

- **Git & GitHub** – Version control and project collaboration

---

### 🎯 Features

- **Automated Pill Dispensing** 
  Dispenses the correct medication at the right time using an Arduino-controlled mechanism, reducing the risk of missed or incorrect doses.

- **Real-Time Pill Intake Monitoring** 
  Utilizes a YOLOv5-based image recognition system to track the sequence: pill present → pill taken → hand empty — confirming successful medication intake.

- **Custom OCR Processing** 
  Uses Tesseract OCR to extract medication names, dosages, and instructions from images of prescriptions or labels.

- **Medical NER Model** 
  A custom-trained spaCy Named Entity Recognition (NER) model processes OCR output to identify key medical information like dosage frequency and medication schedules.

- **Cross-Platform Interface (Toga + Buildozer)** 
  Built using the Toga framework for both desktop and mobile (Android and IOS) platforms, allowing caregivers and users to interact with the system easily.

- **Flask-Based Communication** 
  A lightweight Flask server connects the app to backend ML models, ensuring fast and reliable processing of user input and image recognition results.

- **Emergency Alert System** 
  If a user fails to take their medication within a set time frame, the system plays an audio alert and notifies a connected caregiver.

- **Time-Based Triggers** 
  The application runs on a schedule, automatically activating the camera and dispenser based on predefined medication times.

- **PDF Report Generation** 
  Extracted text from prescriptions is automatically saved and compiled into a downloadable PDF for easy recordkeeping and sharing with healthcare providers.


--- 


<!-- Getting Started -->
## 	:toolbox: Getting Started

<!-- Prerequisites -->
### :bangbang: Prerequisites

This project uses a variety of modules and libraries 

```bash
 cd Dispenser 
 pip install -r requirements.txt 
```
<!-- Run Locally -->
### :running: Run Locally

Clone the project

```bash
  git clone https://github.com/SophieBarriault/Dispenser.git 
```

Go to the project directory

```bash
  cd Dispenser 
```

Install dependencies

```bash 
  pip install -r requirements.txt 
```

<!-- Deployment -->
### :triangular_flag_on_post: Deployment

To deploy the mobile application simulation software, run: 

```bash 
  cd Dispenser/App/andriod_app
  python app.py 
```

To deploy the medication dispenser software, run: 

```bash 
  cd Dispenser/App
  python App_For_Monitering.py 
``` 

<!-- FAQ -->
## :grey_question: FAQ

- **Who is the project designed for?** 

  + It’s primarily designed for elderly patients, individuals with memory challenges, high-risk patients, such as those recovering from an addition, under-staffed healthcare facilities, and caretakers who need remote monitoring tools for medication adherence/patients who live alone.

- **How is medication intake verified?** 

  + The image model uses a 3-step detection process:

    1. Detects the presence of a pill

    2. Checks if it’s picked up

    3. Confirms the hand is empty (pill was consumed). 
      If not, an alert is triggered. 


- **How does the dispenser work?** 

  + A built-in camera detects if a pill is taken using a YOLO image recognition model.

  + OCR and NER extract dosage info from prescription labels.

  + The system activates an Arduino-controlled dispenser and verifies intake.

  + Caretakers can view updates via a mobile app.





 
<!-- Contact -->
## :handshake: Contact

Sophie Barriault - [Linkedin](www.linkedin.com/in/sophie-barriault) - sophiebarriaultofficial@gmail.com 

Project Link: [https://github.com/SophieBarriault/Dispenser/tree/main](https://github.com/SophieBarriault/Dispenser/tree/main)


<!-- Acknowledgments -->
## :gem: Acknowledgements 

Useful resources and libraries that I've used in my project: 


 - Link to all technical sources used: https://drive.google.com/drive/folders/1BSqckdxfqDh0ZibXCd9fYPzXVN9h-TSW?usp=drive_link 
 - [Shields.io](https://shields.io/)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#travel--places)
 - [Readme Template](https://github.com/othneildrew/Best-README-Template) 





































