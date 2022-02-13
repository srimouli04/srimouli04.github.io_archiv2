---
author_profile: true
layout: single
classess : wide
classes : wide 
permalink: /projects/
title: ""
excerpt: "A selection of things I've designed, illustrated, and developed."
ads: false
fullwidth: true
tiles: true
feature:
  visible: true
  headline: "Featured Work"
  category: project
---

{{ page.excerpt | markdownify }}

### Emotion Tagging in Audio Signal using Weakly Supervised Learning | Python - Pytorch | M.Tech Thesis
* The project aims at detecting human emotions Angry, Happy, Surprise, Disgust, Neutral, Fear, Sad associated with audio signal.
* The project employs Auto Encoder and CNN architecture.
* Datasets SAVEE, RAVDEES, CREMA-D and TESS were used.


### Chatterbox | Spring, AngularJS, Typescript, MongoDB, Kafka, Docker
* The application allows to communicate with instant messages across communities, individual users
* Developed a full-stack web application using Spring boot serving a REST API with Angular as the frontend
* Used Kafka as message broker to handle the users and conversations. Used MongoDB as a database

### Deep fake video generator | Python - Pytorch
* The work is based on implementing the research papers ”First order Motion for Image Animation” and ”Motion
Representations for Articulated Animation”
* Given an input video and static image the algorithm can generate deep fake video of the person in the static image
based on the input video
* Reconstruction loss was used as loss function to train the data to achieve acceptable accuracy

### Generate Graph Embeddings | Python - networkx
* The work is based on the research papers ”Node2vec” and ”Multi-Scale Attributed Node Embedding”
* The application was tested on FIFA data set and Karate club data set to identify the embedding of the nodes and
identify the similarity between them

### Image Captioning | Python - Pytorch, nltk
* The application is designed using pre trained VGG16 network, Resnet50 networks for the encoder and used GRUs for
Decoder to generate the image captions
* Flickr 8K dataset was used to perform the task

### Bloxorz Game playing Agent | Python
* The levels of the game are configurable and graph algorithms BFS, DFS, A* search are implemented to solve the
puzzle
* The automatic game playing agent takes care of the board dimensions, avoids the traps and reaches the end of the
level in optimised steps as per the algorithm chosen

### Design of Smart grid using Neural Networks | Python, C++
* Intelligent Electrical devices are connected to the electrical appliances in the building and all these IEDs are
connected to a central server
* Developed a framework to monitor the electrical usage across all the rooms in the buildings
* Developed deep learning algorithms to optimise the power consumption by switching the loads between the power
grid and solar panels