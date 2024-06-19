---
title: "AI connected medical insoles"
description: "I solved a problem that 600+ MILLION people suffer from using AI"
dateString: Oct 2023
draft: false
tags: ["AI", "IOT", "AWS", "AWS", "EY", "Innovation", "Python", "Challenge", "ML", "DL", "Recommendations System", "models"]
weight: 101
cover:
    image: "/projects/SciaTech/SciaTech-logo.jpg"
---


# Introduction
The project  Scia-Tech is a project combining the power of two powerful technologies: AI and IOT. Scia-Tech's smart insoles are designed to enhance the user's daily life. These smart insoles not only track your physical activities, but also offer a unique solution for individuals suffering from sciatica. By closely monitoring their walking patterns, sitting habits, heavy lifting, intense workouts, posture, and any movement. Scia-Tech aims to identify behaviors that may trigger sciatica pain, allowing you to take proactive steps to manage and mitigate discomfort. 

![](/projects/SciaTech/SciaTech%20DEMO.mp4)
<video width="700" height="300" controls>
  <source src="/projects/SciaTech/SciaTech DEMO.mp4" type="video/mp4">
</video>

# Deeper dive
Scia-Tech offers:
- **Sensor Technology:** It provides cutting-edge sensor technology to revolutionize pain management and improve health.
- **Data Analysis and Machine Learning:** Collected data from the sensors is processed and the models predict the movement patterns and postures, then this output is fed to other models to forecast potential pain triggers before they strike. The recommendation system then provides personalized insights, guiding the user towards a life free from discomfort.
- **Personal Space:** All of this information and more is sent to the user's account on the mobile application. The user can find reports, get notifications, report pain manually, manage their profile, see the timer predicting when sciatica pain may occur.


# Technical Aspect
The ESP32, equipped with our sensors, sends real-time data to AWS IoT Core using MQTT protocol. 

This raw data undergoes transformation using ML and DL models to predict position,posture and expected sciatica pain onset. 

With personal data from the mobile app (from the user’s account including age, gender, weight, height..), real-time pain reports (from the user reporting they’re currently experiencing sciatica pain), and continuous IoT data streaming (used to predict the posture, position, movement and any excessive weight lifted), we create personalized AI-generated recommendations crafted specifically to you.

Let's break it down - Scia-Tech's system, powered by cloud-based microservices, efficiently manages batch oriented workflows and streaming data to process it and generate the adequate outputs.

Personalized recommendations mean the system learns from the user's unique data, not only giving you tailored guidance but also improving our general AI recommendation system. 

## 1. Input Data
**From the mobile application:**
When creating their account, the user enters the following information that we take into consideration when training the models.
These inputs are: Age, Gender, Weight, Height.

![](/projects/SciaTech/userflow.png)

**From the sensors:**
The insoles are equipped with different sensors including: ESP32 microcontroller,FSR01 load cell and MPU6050 Sensor,

- MPU: Sx, Sy, Sz, Qx, Qy, Qz, Ww, FPS (for each feet)
- Pressure: P0, P1, P2, P3, P4 (for each feet)

![](/projects/SciaTech/MPU.png)
![](/projects/SciaTech/Pressure.jpg)


## 2. How it works
### Data Generation and Research
Having worked on an innovative project, finding data to train the models was pretty challenging. I couln't find any data for movement, activity or posture prediction from sensors installed in insoles. I couldn't even find data collected the sensors we had combined. The unique combination of sensors in insoles to predict pain made finding the data a real obstacle, especially free and open source data. Collecting data from hospitals wasn;t an option either because it's confidential. The solution was **generating my own dataset** and that's exactly was I did. I generated a dataset of douzains of people using the insoles in different positions and postures, doing various activities such as walking, sitting, running, jumping, lifting heavy weights,... 
I worked alongside a doctor, I got all the information necessary and, throught weekly meetings, kept iterating my models, feature engineering and experimenting to increase the performance. The results can never be perfect because in the medical field it's very hard to predict the future because nature cannot be predicted, people are all different and unique and no case is like the other. The goal was not to get perfect results but to increase the probablities accuracy based on all the elements we could have. More data could've been beneficial but the goal was to implement the project using insoles and insoles only because that was our innovative approach.
This project required a lot of research, from domain research about sciatica, medical conditions, exceptions, and parameters, to technical research when deciding on the right models, the right features, reading similar research papers and more.


### The pipeline
The ESP32, equipped with our sensors, sends real-time data to AWS IoT Core using MQTT protocol. This raw data undergoes transformation first using AWS Lambda functions for pre-processing tasks, distribution of inputs into different databases such as AWS S3 and AWS DynamoDB, and posture and movement prediction using an ML pre-trained model stored in a Lambda function. The processed data is then ingested as an input of the sciatica pain predictive model using AWS SageMaker. The outputs are then sent to our mobile application for display.

![](/projects/SciaTech/pipeline.png)

## 3. Output Data
The output of this project is:
- Pain Prediction: The app features AI technology integrated with smart insole data to display a timer predicting when sciatica pain may occur. You can also manually log pain incidents, specifying whether they occurred during sitting, standing, or heavy activity.
- Reports: Access daily, weekly, and historical reports of your activities and pain incidents.
- Notifications: Receive reminders and notifications to help you manage your daily routines and avoid pain triggers.
- Profile Management: Update and modify your profile information as needed.

![](/projects/SciaTech/product1.jpg)
![](/projects/SciaTech/product2.jpg)

