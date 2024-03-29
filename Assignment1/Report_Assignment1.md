# GraphAnalytics: Assignment One

## Brace, breath, and begin

#### Objective:
Create and analyze your own graph. Understand the underlying concepts concerning Graphs, and be able observe the effects, benefits, and perils of a widely distributed network. 

#### Programming Language:
Python, compiled using Jupyter Notebook

#### Libraries used:
* NetworkX
* Pandas
* MatplotLib
* Numpy
* Random
* Urllib.request

#### Data Source:
[OpenFlights](https://openflights.org/data.html "OpenFlights")

<br>I have used a library named 'urllib.request' in order to extract the file straight from the url thus making this project light, quick, and more efficient to execute.

## The Dataset

RyanAir, Lufthansa, American Airlines, Qatar ?
These are all popular names that are discussed from time to time, and form an integral part of this globalized world.
Airports, Airlines, and Routs, can all play important roles in deciding which country do we go to next. This is an initiative to plot the airports, airlines, and their consequent routes on a global map. The dataset has been keenly observed, and for my purpose has been tailored using python to satisfy the intent. Additionally, the modifications have been made in order to provide the best form of representation of the idea behind this implementation.
There is no need for you to download the dataset.

* Nodes: Airports
* Edges: Airline route

## This world is our stage

Implementing the code gives us interesting reults.
The red dots represent the airports, and the black lines represent the routes between two airports.

### The first output looks slightly crude, and difficult to interpret. 
![alt text](https://github.com/coconutcow/UniGe-Graph-Analytics/blob/master/ImageSources/Image1.png "Graph One")
### Voila! Doesn't it look beautiful ? I have utilised some functions provided by the NetworkX and MatplotLib libraries. We have now reproduced all airports that exist globally, and their consequent airline routes. Incidently, the outcome also looks like the map of the planet earth - thus encompassing us with the idea that most of the globe does remain connected, but there is, yet, room for development.
![alt text](https://github.com/coconutcow/UniGe-Graph-Analytics/blob/master/ImageSources/Image2.png "Graph Two")

