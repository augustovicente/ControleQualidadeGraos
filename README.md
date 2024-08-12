# Grain Quality Control

The **Grain Quality Control** project aims to automate the classification of grains, a process that was previously done manually and was susceptible to fraud. 
This automation is achieved through an application that communicates with an IoT device via Bluetooth.
The device collects grain classification information through serial communication and sends it to the connected app.
The app then saves the data in a database, including observations and images, and prints a ticket via Bluetooth to a serial printer.

## Prerequisites

* NPM 6.4.1
* Ionic 3.20.0
* Apache Server

## Installing

* Clone the folder
* Install all dependencies: npm i
* Move the files: "Conexao.php", "persistencia.php", "webservice.php" to the apache server folder

## Running

* Run "ionic cordova build android" at the prompt in the cloned folder
