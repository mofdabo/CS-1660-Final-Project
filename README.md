# CS 1660 - Course Project #1 (Data Science Toolbox) 


Microservices-based  application where there is one main microservice that acts as the main application showing a User Interface.

**This project was tested on a Windows machine.**

## Prerequisites

Have **Docker Desktop** and an **X11** forwarding software (such as **XLaunch**) installed and opened on your host machine.

## Instructions

- Clone this repository to your local machine
- Navigate to the location of the directory on your command line
- In the ***docker-compose.yml*** file, change the DISPLAY variable on line 8 to:

```bash
DISPLAY=<your-ipv4>:0.0
```

- Run the command:
```bash
docker-compose up
```

#### Give the application some time to pull and download all the images required. Once finished, the ***Data Science Toolbox*** GUI should appear.

## Usage
Click on the button of the microservice you would like to launch.

The microservices listed below require additional steps to use:
- Orange
  - Password: orange
- Tensorflow
  - If asked for a password/token, scroll down to the bottom of the page where it says **Setup a Password**, create token and a new password, and use either the token or password to log in.

Once finished with the application, go to your command line and press: CTRL+C


## Not Supported
These are the following applications that are currently not supported:
- Apache Hadoop
- SonarQube & SonarScanner (or SonarCloud)


## Demo Video
[Demo](https://google.com/)