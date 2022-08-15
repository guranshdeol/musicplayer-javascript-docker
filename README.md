![stars](https://img.shields.io/github/stars/Open-Source-Chandigarh/project-template)
![forks](https://img.shields.io/github/forks/Open-Source-Chandigarh/project-template)
![issues](https://img.shields.io/github/issues/Open-Source-Chandigarh/project-template)
![Visitor count](https://shields-io-visitor-counter.herokuapp.com/badge?page=Open-Source-Chandigarh.project-template)
![GitHub contributors](https://img.shields.io/github/contributors/Open-Source-Chandigarh/project-template)



# Title: How to Containarise a Static Website Using Docker
- Add 4-5 lines introduction to your project
- Try to elaborate on the overall project work.
- [Optional] - Add video, if possible. This video covers on how to install this app and brief explanation of the project work.



## Technical Stack

- HTML
- CSS
- JAVASCRIPT
- httpd : The Apache HTTP Server Project
- Docker

## How it works?

- Add architecture diagram
- Show detailed information on how it works


## Prerequisite

- Add what pre-requisite software is required(for example, Install Docker Desktop)

## Step 1 - Clone the repository

```
 git clone https://github.com/guranshdeol/docker-workshop-osc.git
```

## Step 2 - Change directory to projectname

```
 cd docker-workshop-osc
```

## Step 3 - Create docker image

```
docker build -t musicplayer .
```

## Step 4 - Run it on server

```
 docker run -dit --name musicplayer -p 8080:80 musicplayer
```

## Step 5: Add Screenshot 
![image](https://user-images.githubusercontent.com/91736425/184574629-be76544c-a8bb-42eb-a777-3367d70c4da7.png)

![image](https://user-images.githubusercontent.com/91736425/184574445-5ba8aa3d-ccb2-4c94-8243-d98c0f0ad367.png)
 

## Step 6. Add References

- Did you refer to any blog or tutorial or repository? If yes, then it's not a bad idea to capture it here.


## Sample Examples
 

 - [Cryptotracker](https://github.com/Open-Source-Chandigarh/Cryptotracker)
 - [The Pico Project](https://github.com/collabnix/pico)
 - [How to Build the First containerized JAVA web application](https://github.com/dockersamples/genie-website-java)

# Docker-Workshop-Osc
This Repositry was made for **Docker Workshop** and addressed by **Docker Captain Ajeet Singh Raina** organised by **Open Source Chandigarh** an open source community.
* This repositry contains a docker image file and docker container file of Music Player Webapp that i created while learning Frontend Development.
* The files here are .tar files.

## Files 
Due to SIze restriction by github it was not possible to put those files in repositry so here is the google drive link
* [Docker Image File](https://drive.google.com/drive/folders/12Rm_GO-NcbHNnm2Uq6tc6YuLWSxRRXrT?usp=sharing)
* [Docker Container File](https://drive.google.com/drive/folders/13JnwCUZns0VuFaPjCDNdOPIFoZNmeECx?usp=sharing)

## References

* I took help from **collabnix.com** 's **Docker Labs 101** Tutorial while learning.
Do check it out at [Collabnix.com](https://www.collabnix.com)

* Conversion of Docker image and container was referred from
 [dockerlabs.collabnix.com/beginners/saving-images-as-tar](https://dockerlabs.collabnix.com/beginners/saving-images-as-tar/)


## Website Repositry link: 
https://github.com/guranshdeol/music-player

