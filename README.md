<!--
Hey, thanks for using the awesome-readme-template template.  
If you have any enhancements, then fork this project and create a pull request 
or just open an issue with the label "enhancement".

Don't forget to give this project a star for additional support ;)
Maybe you can mention me or this repo in the acknowledgements too
-->
<div align="center">


![Logo](assets/ORION.gif)

# O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network- 

A J.A.R.V.I.S.-inspired AI assistant for smart task automation and conversational support. 


[![Contributors](https://img.shields.io/github/contributors/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-)](https://github.com/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-)](https://github.com/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-)
[![Forks](https://img.shields.io/github/forks/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-)](https://github.com/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-/network/members)
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

O.R.I.O.N. is a fully voice-activated desktop AI assistant designed to create a seamless and natural human-computer interaction experience through speech recognition, real-time response generation using large language models, and visual feedback via a graphical user interface. The project integrates speech-to-text, text-to-speech, and Hugging Face’s transformer-based NLP models to simulate an intelligent, responsive, and personalized AI system inspired by fictional virtual assistants like J.A.R.V.I.S. from Iron Man, MCU.

 - **The objective of O.R.I.O.N. is to:** 

 - Develop a continuously running desktop assistant that can detect a wake word ("Orion"), listen for commands, and generate meaningful, human-like responses.

  - Leverage modern NLP models (e.g., Mistral-7B) via Hugging Face for lightweight and efficient LLM integration without relying on OpenAI's API.

 - Provide clear visual feedback through a debug console and dynamic animated elements to enhance accessibility and user interaction.

 - Create a customizable foundation for further expansion into more advanced AI features, such as system control, file management, or smart home integration.


---

### 📷 Demo Video 

Click to watch the demo here! 

[![Watch the Demo Video](assets/to_demo.png)](https://drive.google.com/file/d/1wByr87FT2HsipwZgwH-gzBg_70QS4TUb/view?usp=sharing) 


---

### 👾 Tech Stack

**Voice Interface:** 

 - SpeechRecognition – For real-time voice input and speech-to-text conversion.

 - PyAudio – Microphone audio capture.

 - pyttsx3 – Offline text-to-speech (TTS) engine for natural voice responses.

**Natural Language Processing (NLP):** 

 - Hugging Face Transformers – For hosting and interacting with LLMs (e.g., mistralai/Mistral-7B-Instruct-v0.1).

 - huggingface_hub.InferenceClient – Lightweight client for querying models without GPU dependency. 
 - (Previously supported: OpenAI GPT-4, now replaced for quota-free operation.)

**Graphical User Interface:** 

 - tkinter – Built-in Python GUI toolkit for a lightweight debug console and visual feedback.

 - Pillow (PIL) – For loading and animating GIFs inside the UI.

**Concurrency** 

 - threading – To keep speech listening responsive while updating the GUI.

**Optional Enhancements:** 

 - Custom animated GIFs – For a dynamic, sci-fi-inspired UI aesthetic.

 - Wake word detection – Keyword-triggered listening loop (e.g., "Orion").



---

### 🎯 Features

**Voice-Activated Wake Word:**
 - Automatically activates when you say "Orion", no buttons needed.

**Speech Recognition:** 
 - Converts your spoken words into text using SpeechRecognition and PyAudio.

**Conversational AI:** 
 - Processes questions and commands using Hugging Face’s Mistral-7B-Instruct model (fully customizable).

**Text-to-Speech Response:** 
 - ORION responds with a natural-sounding voice using pyttsx3.

**Dynamic UI Console:** 
 - Displays real-time updates, user inputs, and responses with animated GIF integration via tkinter.

**Continuous Listening Loop:** 
 - After responding, ORION returns to standby and waits for the next command.

**Customizable Wake Word & Voice Settings:** 
 - Easily change the assistant’s wake word, voice, rate, and language settings in the source code.

**Privacy-First:** 
 - No user data is stored by default. All processing is ephemeral unless logging is added intentionally.




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
  git clone https://github.com/SophieBarriault/O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-.git 
```

Go to the project directory

```bash
  cd O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network-
```

Install dependencies

```bash 
  pip install -r requirements.txt 
```

<!-- Deployment -->
### :triangular_flag_on_post: Deployment

To deploy the mobile application simulation software, run: 

```bash 
  cd O.R.I.O.N.-Operational-Responsive-Intelligence-Observation-Network- 
  python main.py 
```

<!-- FAQ -->
## :grey_question: FAQ

- **What is O.R.I.O.N.?** 

  + O.R.I.O.N. (Operational Responsive Intelligence Observation Network) is a Python-based desktop voice assistant inspired by J.A.R.V.I.S. It combines voice activation, natural language understanding via Hugging Face models, and a responsive GUI to perform tasks and respond intelligently to user queries. 

- **What can O.R.I.O.N. do?** 

  - O.R.I.O.N. can:

     - Listen for a wake word (“Orion”)
 
     - Understand natural language commands
 
     - Respond verbally using TTS (text-to-speech)
 
     - Display a real-time debug console with an animated UI
 
     - Answer questions, tell jokes, and more using an LLM from Hugging Face


- **Does O.R.I.O.N. store any of my data?** 

  + No, by default O.R.I.O.N. does not store voice recordings or responses. You can optionally add logging if you wish to track conversations for debugging. 





 
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





































