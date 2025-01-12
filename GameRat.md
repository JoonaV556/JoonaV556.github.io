---
layout: page
title: GameRAT
permalink: /gamerat/
---

# GameRAT - (Gamified Joint Rehabilitation, Analysis and Training)

[Read more at HXRC Website](https://helsinkixrcenter.com/projects/gamerat/)  
[Read more at EMIL website](https://emil-xr.eu/metropolia-uas-gamerat/)

(this project is still in development, thus no publicly playable build is available)  
[Code Samples (WIP)](https://joonav556.github.io//)

### Overview 
GameRAT, a project funded by EMIL Horizon Europe, provides an innovative remote rehabilitation system for upper-body therapy. GameRAT combines a web interface for professionals to manage exercise routines with gamified Mixed Reality Application for patients to perform exercises at home. The system features four engaging minigames, such as potion-making and rowing, which encourage therapeutic movements while collecting detailed performance and motion data. AI-driven safety features and pain estimation tools enhance the patient experience, ensuring exercises are effective and safe.

### My Role - Unity Development
[//]: # (xr app  (some important systems, busy/lots of responsibilities))

In the GameRAT project, I am responsible for developing the XR application for patients. Designed collaboratively at HXRC, I have independently developed two of the four total minigames in the application—**Froggo** and **RowTheBoat** (work in progress)—while also assisting in the development of the other two games. Beyond the games, I have implemented several core program components, including the patient movement tracking system. This system records movement data as bone orientations, stores it, and transmits it to a custom backend server for professional analysis.     

[comment]: # (minigame images)

Because of its great support for multiplatform XR applications and SDKs, we chose to build the Application with Unity Engine. The target device for the XR-app is Meta Quest 3 Mixed Reality headset. The application makes heavy use of the Meta XR SDK, utilizing features such as hand tracking, body tracking, spatial anchors etc.  

Since the application will also feature an AI-powered system for analyzing the patients movement performance and predicting possible pain inducing movements, we needed a way to record a large data-set of training data. For that purpose I developed a simple AR-tool for the Quest 3 headset which can be used to quickly record large amounts of movement data for the prementioned purpose.  

[//]: # (data recording tool image)
