# AUMB Score Tracker
This is a Python Application that tweets final score updates for the Auburn Men's Basketball team while also texting the results to my phone.

## Table of contents
* [General info](#general-info)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Language details](#Language-details)
* [Contact](#contact)

## General info
This is a project I decided I wanted to do in order to familiarize myself with Python Automation. It runs on my RaspberryPi and tweets/text me the final score to the Auburn Men's Basketball games. The Twitter account associated with this project can be found [here](https://twitter.com/AumbScore). If you have a Twilio account, this script can be run to text the scores to any phone number using the setup below.

## Setup
In order to run this application you will need a Twitter Developer Account and a Twilio account. It is recommended that you use environment variables or an authentication file to store your account credentials, but you can also hard code them if you would like. A link on setting up environment variables can be found [here](https://www.twilio.com/blog/2017/01/how-to-set-environment-variables.html). <br/>
Once you have your Twilio account set up, clone this repo onto your local machine and navigate to the project folder. <br/>
First activate the python virtual environment with the command:
>source env/bin/activate

In order to use this application with the texting feature the run.sh script with the command:
>./run.sh [phone number]

Example:
>./run.sh '+13345550198'

In order to use this application with only the Twitter feature the run.sh script with the command:
>./run.sh

The application is now running, and will provide updates for the final scores of the Auburn Men's Basketball games.

## Features
Implemented:
* Twilio
* Gets final score
* Text final score
* Tweets final scores

## Status
Project is: _finished_

## Language details
Language used: Python </br>
Version used: 3.8

## Contact
Created by [@cameronmathis](https://github.com/cameronmathis/) - feel free to contact me!