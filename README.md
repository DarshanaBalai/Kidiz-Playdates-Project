# Kidiz-Playdate-project

This is Frontend project for Kids playdate, it contains following pages
- User registration and Login page.
- View upcoming events or start a new event/playdate for kids.
- Gallery for all events

## Deployment
Github page is used for the deployment and you can find more details in github page configuration, deployed URL `https://darshanabalai.github.io/Kidiz-Playdates-Project/`

## Techstack
- HTML
- CSS
- Github page for deployment

## Screenshots
- Main Kids play page
    https://user-images.githubusercontent.com/130803590/236688693-54bf7171-a246-4d8e-87e1-2cf2115a8105.png
    https://user-images.githubusercontent.com/130803590/236688797-7bb36958-644a-40b8-8f00-9cef7f88d4c4.png

- Signup/ Login page
    https://user-images.githubusercontent.com/130803590/236688754-97c26e83-3637-4702-8ffe-652c775b2ce7.png

- Gallery for photos at the event
    https://user-images.githubusercontent.com/130803590/236688842-3b7fda97-4bba-46b9-a9f3-4dfbb6c57c96.png
    https://user-images.githubusercontent.com/130803590/236688894-1ad4356f-6c75-492f-b77c-5283eebff71a.png

- Events
    https://user-images.githubusercontent.com/130803590/236688943-32afd6bf-6c3e-4065-b044-ec5c847f806b.png

## Problems
- When running `python3 -m http.server` on codeanywhere, I got `Address already in use` error.
  Resoultion: When I researched and read about it, I came to know that it's because port issue. We are running the python
    program on 8000 port and somehow old port is still in use. I killed that process using some linux commands
    1. ps -fA | grep python - find all processes with python in name and get process id say pid
    2. Kill -9 pid (pid collected in step 1) - this will kill old process
    I referred few sources for the same, one of them was `https://stackoverflow.com/questions/4465959/python-errno-98-address-already-in-use`

- I updated some of html files but it was not reflecting and then I found I need to hard refresh the website page with (cmd + shift + r) to reload.