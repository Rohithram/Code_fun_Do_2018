# Code_fun_Do_2018

# Codefundo18
Repository for Codefundo 2018

## The problem we are trying to solve: 
Floods are the natural disasters that cause catastrophic destruction and devastation of natural life, agriculture, property and infrastructure every year. Flooding is influenced by various hydrological & meteorological factors. A number of researches have been done in flood disaster management and food prediction systems. However, it has now become significant to shift from individual monitoring and prediction frameworks to smart flood prediction systems which include stakeholders and the flood affecting people equally with help of recent technological advancements. Internet of Things (IoT) is a technology that is a combination of embedded system hardware and wireless communication network which further transfers sensed data to computing device for analysis in real-time. Researches in direction of flood prediction have shifted from mathematical models or hydrological models to algorithmic based approaches. 

## Our Approach:
During the occurence of any disaster, the most difficult part is identifying the location and citizens affected, and coordinating the rescue team's efforts. Any application which addresses these will greatly reduce casualties.
Flood data is dynamic data and non-linear in nature. To predict floods, techniques such as Deep neural networks are used to devise prediction algorithms. Here an IoT based flood monitoring and based flood prediction is designed with the aim of enhancing the scalability and reliability of flood management system. The main aim of this system is to monitor humidity, temperature, pressure, rainfall, river water level and to find their temporal correlative information (Using LSTMs,GRUs,RNNs etc.) for flood prediction analysis. The IoT approach is deployed for data collection from the sensors and communication over Wi-Fi/Bluetooth we can get UUID of victims number and an DNN approach is used for analysis of data in flood prediction.

Also The application will actively monitor the Internet to detect probable occurences of disaster. News websites, social media sites and weather reports will be monitored to detect disaster, and sentiment analysis will be done to extract features for the Deep learning model and add meta data about it (Disaster type, location, donation links etc)

The application will create a database to keep track of people. The database will be collectively maintained by reports from the victims, rescuers, bystanders, family etc. These reports can contain pictures, identifying traits, belongings, wounds, location etc. Each report will be marked with tags like (Missing,Found,Dead,Unknown, etc).We use approches like Facial Recognition and NLP to make sense out of the information received , the application will try to match different reports to figure out the status and identification of each person affected by the disaster.

Technologies we plan to use
Component 	Software
Platform 	Android
Database 	MongoDB
Coding Language Python
Deep Learning framework - pytorch/Tensorflow plus keras
Backend Server 	Linux
