# MTA Trains Application - JavaScript Manipulation
Create a program that models a simple subway system.

## Project Goals
* Build a web application from scratch, and apply knowledge of Javascript to solve a real world problem. Get really good at array manipulation.
* Separate HTML, CSS, and JavaScript files in the application
* Build a dynamic application that a user can select an input (train station, train line) and output directions that the train will take to get to destination. 
* Craft a readme.md file that explains this app to the world

## The Application 
* The program takes the line and stop that a user is getting on at and the line and stop that user is getting off at and prints the journey and the total number of stops for the trip in the console:
planTrip('N', 'Times Square', '6', '33rd'); // This is only a suggested function name and signature.
// console.log() shows output similar to this: // "You must travel through the following stops on the N line: 34th, 28th, 23rd, Union Square." // "Change at Union Square." // "Your journey continues through the following stops: 23rd, 28th, 33rd." // "7 stops in total."

* There are 3 subway lines: The N line has the following stops: Times Square, 34th, 28th, 23rd, Union Square, and 8th The L line has the following stops: 8th, 6th, Union Square, 3rd, and 1st The 6 line has the following stops: Grand Central, 33rd, 28th, 23rd, Union Square, and Astor Place.

* All 3 subway lines intersect at Union Square, but there are no other intersection points. (For example, this means the 28th stop on the N line is different than the 28th street stop on the 6 line, so you'll have to differentiate this when you name your stops in the arrays.)

* Tell the user the number of stops AND the stops IN ORDER that they will pass through or change at.


## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## Prerequisites
Ensure that you have the following installed on your local machine:

[Python](https://www.python.org/downloads/)  


## Installation 
Clone the repo:

```
git clone https://github.com/lukemico/mtatrains.git

cd mtatrains
```

then follow instructions in the Running section.


## Steps for Running read-only access
To start the python server, run the following via the Command Line:

```
python -m SimpleHTTPServer 8000
```

Open [http://localhost:3000](http://localhost:8000) and take a look around.

## Usage 
* 


## Deployment
View the [Live Demo](https://mtatrains.herokuapp.com/) here.


## Built With
[JavaScript](https://developer.mozilla.org/bm/docs/Web/JavaScript) - to handle the data and its inputs/ outputs. 
[HTML](https://www.w3.org/html/) - the framework that pulls together  
[CSS](https://www.w3.org/Style/CSS/) - the styling of the document. 


## Versioning
GitHub used for versioning. For the versions available, see the tags on this repository.

## Authors
Luke Mico

## License
Source code distributed under the MIT license. Text, imagery and other assets copyright resource11, all rights reserved.



