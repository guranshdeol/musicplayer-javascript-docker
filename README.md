![stars](https://img.shields.io/github/stars/Open-Source-Chandigarh/project-template)
![forks](https://img.shields.io/github/forks/Open-Source-Chandigarh/project-template)
![issues](https://img.shields.io/github/issues/Open-Source-Chandigarh/project-template)
![Visitor count](https://shields-io-visitor-counter.herokuapp.com/badge?page=Open-Source-Chandigarh.project-template)
![GitHub contributors](https://img.shields.io/github/contributors/Open-Source-Chandigarh/project-template)



# How to Containarize a Music Player using JavaScript and Docker


## Technical Stack

- **HTML**
- **CSS**
- **JAVASCRIPT**
- **httpd** : The Apache HTTP Server Project
- **Docker**

<!---
## How it works?

- Add architecture diagram
- Show detailed information on how it works
--->

## Prerequisite

- [Docker Desktop](https://www.docker.com/products/docker-desktop) / [Play With Docker](https://labs.play-with-docker.com/)
- Basic Knowledge of Docker Commands.

## Steps


### Step 1 - Clone the repository

```
 git clone https://github.com/Open-Source-Chandigarh/musicplayer-javascript-docker
```

### Step 2 - Change directory to projectname

```
 cd musicplayer-javascript-docker
```

### Step 3 - Create docker image

```
docker build -t musicplayer .
```

### Step 4 - Run it on server

```
 docker run -dit --name musicplayer -p 8080:80 musicplayer
```

## Screenshots
![image](https://user-images.githubusercontent.com/91736425/184574629-be76544c-a8bb-42eb-a777-3367d70c4da7.png)

![image](https://user-images.githubusercontent.com/91736425/184574445-5ba8aa3d-ccb2-4c94-8243-d98c0f0ad367.png)
 

## References

* I took help from **collabnix.com** 's **Docker Labs 101** Tutorial while learning.
Do check it out at [Collabnix.com](https://www.collabnix.com)



