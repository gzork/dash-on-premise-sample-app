## Dash On-Premise Sample Jnius App

This repository contains a simple Dash app that interacts with code from Java using [Pyjnius](http://pyjnius.readthedocs.io/en/latest/).

The expected end result here is the same as [Dash On-Premise Sample app](https://github.com/plotly/dash-on-premise-sample-app) except that the header is "This is JAVAAA!" instead of "Sample App"

#### Local Deployment Instructions

1- Install Cython: `sudo pip install cython`.

2- Install OpenJDK 8:
	`sudo add-apt-repository ppa:openjdk-r/ppa`
	`sudo apt-get update`
	`sudo apt-get install openjdk-8-jdk`.

3- Add JAVA_HOME ENV variable: (e.g. `export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64`)

#### Dokku Deployment Instructions

