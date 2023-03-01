# Week 1 — App Containerization

# Week 1 — App Containerization

This was the week of Containerization, played with docker alot. Initially most of the information during the live was beyond my understanding but I did gone through a crash course related to Docker from KodeKloud by Mumshad.

The tasks carried out during this week was writing docker files for Frontend as well as Backend. Few questions which were highlighted during the live that caught my attention was 
1. Why do the Dockerfile doesnt have any extension associated with it?
A. So this is what I found dockerfile is a text file responsible for writing a sequence of commands needed to build a image. As docker daemon under the docker engine looks for the name Dockerfile for building an image either directly through a command or from a redirected point from docker-compose/ docker compose

2. Why docker-compose and as well as docker compose ?
A. Docker and docker-compose were initially two different projects with an intention to make parallel image building by caching layer by layer architecture and were then migrated to another base technology (Go). A more detailed answer would be <a href="https://stackoverflow.com/a/66516826">here</a>

#Did the additional tasks assigned of creating the notification services at backend and frontend:
This task included creating an app route for the notifications feed for a user (Currently the user login info is managed through cookies). It was simple task of populating the json at backend to the notification page at front end. 

For this I did followed the additional video uploaded by Andrew for creating the notification_service also updated the api documentation for the API. This was a bit new thing for me. It was similar to creating a dashboard for APIs. [sorry for the irrelevant comparison]

Other Additional tasks mentioned were about adding the PLSQL and Dynamodb Local Docker container through docker compose.

Honestly speaking, I was unaware till the moment about adding the PLSQL client to gitpod for using it over CLI for docker. Overall the output at the end of the weekend was something like this

FRONTEND:

  -HOME PAGE
  ![image](https://user-images.githubusercontent.com/112432267/222167942-a04f7136-5735-45fc-9413-53ab1cb07910.png)
  
  -NOTIFICATIONS FEED
  ![image](https://user-images.githubusercontent.com/112432267/222168077-82958228-1dca-4620-a7c1-2b0d82ba1e58.png)
  
 
