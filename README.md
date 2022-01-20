
# CK108_Cluster_Champs

Repository for SIH 2020 - Problem Code : CK108 

#### ORGANIZATION :
DTE OF IT & CYBER SECURITY, DRDO
#### DOMAIN BUCKET : 
SECURITY & SURVEILLANCE
#### TEAM NAME :
CLUSTER CHAMPS
#### Problem Statement :
Clustering of air objects based on its trajectory : By DRDO
#### Problem Discription :
The position of an object in the air can be indicated by latitude, longitude
and altitude for a given time. A trajectory is a stream of such quadruples i
(time, latitude, longitude and altitude). Given a large set of such 
trajectories, without any other information, problem is to cluster them into i
meaningful objects such as Helicopter, Fighter/civilian Aircraft, UAV, Cruise 
Missile, dropped bomb, etc. An optimal scalable solution is desired using i
open source tools. Design a system to estimate location of flying object
based on its trajectory, provide guidance to missile to shoot them
depending on their location when missile will meet the object on its
trajectory. 

## Approch

We are making a web application based project which will show the clustered air object and predict its trajectory on the basis of data based on previous trajectories. The technology, we are dealing with is machine learning and neural network. Also, flask and mySQL connectivity is used in backend. 


![image](https://user-images.githubusercontent.com/44112240/150372909-ff18f2dc-5e25-4426-b2ff-a7b04ec3d6a8.png)

## Evaluation
![image](https://user-images.githubusercontent.com/44112240/150373340-b59ec314-e6f2-4d65-be56-61acd36dd16f.png)

## Student Inovation

#### Object Intention Recognition :

Air object intention recognition is the process of analysing the information of target to
explain and judge the purpose and plan of the enemy. It is based on further clustering and
sample expansion

#### Feature Extraction from Wind, temperature and convective weather:

Convolutional layers are deployed to extract feature representations from high-dimensional
weather features

#### Encoder and Decoder LSTM :

The model, used to predict the trajectory of the object integrates two modules :
1. Anencoder LSTM to embed flight plans into a fixed size feature vector and
2. Adecoder LSTM that maps the fixed size feature vector to target the flight trajectory
sequence.

## Object intention Recognization:
![image](https://user-images.githubusercontent.com/44112240/150374457-8abc2185-0136-4ff6-ad3b-cfb1931c2605.png)
## Precision for wether data
![image](https://user-images.githubusercontent.com/44112240/150374619-fbe9527b-2084-4fe4-8206-46b37d2ef2c2.png)
## Encoder Decoder LSTM:
![image](https://user-images.githubusercontent.com/44112240/150374842-29b5532b-be0e-4fbe-b050-e1debbdb21d3.png)


## Dependencies: 
Dependencies include access to the classified data
such as data of all the flying object in INDIA (latitude,
longitude, altitude and time).

## Show stopper:
The dataset for training a model has
not been provided in the description of the problem
statement so we are unable to proceed forward. As of
the theoretical part we are ready.


## Authors

- [SURYANSH TRIVEDI](https://www.github.com/skt2020)
- SANSKRITI TIWARI
- MUNEES KHAN
- ROHIT PATHAK
- SHUBHI VIJAYVERGIYA
- SANKALP PATEL





