---
title: "AWS Conference Report"
author: Gerard Walsh
date: 2019-07-23
draft: true
tags: ['aws', 'cloud', 'serverless', 'amazon', 'conference', 'data science']
---

## Introduction

On July the 11th, I attended the Amazon Web Services (AWS) Summit in Cape Town. The Summit served to expose attendees to the latest trends and technologies in AWS as well as some interesting applications utilizing their services. This report serves to summarize my thoughts on the day as a junior data scientist.

## Key take-aways

* The conference has grown from 300 to 4000 people in 4 years. The interest and demand for serverless computing is growing exponentially. 
* Serverless computing is no longer only a hardware solution, but solves many software challenges too - i.e. Amazon Machine Images (basic unit of deployment on EC2) allow a user to provision a server with a software environment in minutes. AWS Lamba's event driven computing handles scaling of infrastructure. 
* The set of AWS services give the user the power to create an entire solution (storage, database, compute, services). The question is no longer how, but rather what to build.
* Opportunities to innovate - Old Mutual rolled out a chatbot in the last quarter of 2018 (quite late to the party). How many other companies can benefit from mature technologies like chatbots, recommender systems etc?
* An AWS region is to be provisioned in Cape Town in early 2020 (EC2 was born in Cape Town!). It will provide lLow latency and will solve some issues relating to data regulation (in some cases, SA regulation requires data to not leave the country).

## Interesting talks

* **Tyme bank**: A [digital bank (slide 60)](https://emea-resources.awscloud.com/summit-cape-town-2019/2019-cape-town-summit-keynote) that runs entirely in the cloud. Using serverless computing allows them to quickly scale their platform (which is important since they took on 500 000 customers since January 2019). It also allows them to abstract key components into microservices helping with development time and software maintenance. Creating an account takes 5 minutes, can be done at most PnP's and uses only fingerprint biometrics. For citizens who don't have easy access to traditional banking services, this signup process saves vast amounts of time. 
* **Cape Town commuters are getting home with the help of AWS analytics and Machine learning** (presentation N/A): A proof of concept by Dimension Data where wifi hotspots at taxi ranks helped Dimension Data capture data of the taxi users. Some basic video analysis was also done on taxi overloading and number plate recognition - safer travelling for taxi users. A dashboard was built for the City that allows them to determine commuter numbers, amongst other metrics, and manage their resources accordingly.

## Interesting technologies

* **AWS Sagemaker**: Machine learning platform in the cloud, with three levels of abstraction. Top layers allows Machine Learning novices to use standard tools (text sentiment analysis, object detection in images, recommender system) in their applications. Middle layers has 'algorithm marketplace' - pre-trained models to do various tasks in Machine learning, can submit one's algorithm. Lower layer for practioned users - optimization of algorithms. Sagemaker is available through Jupyter notebooks and makes deployment easy (through a web service for instance). 

