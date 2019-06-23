# GraphAnalytics: Assignment Two

## Brace, breath, and begin

#### Objective:
Investigate the robustness of networks, and implement some changes on your network to visualize, and assess, the magnanimity of attacks on connected networks. 

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

### The Dataset

RyanAir, Lufthansa, American Airlines, Qatar ?
These are all popular names that are discussed from time to time, and form an integral part of this globalized world.
Airports, Airlines, and Routs, can all play important roles in deciding which country do we go to next. This is an initiative to plot the airports, airlines, and their consequent routes on a global map. The dataset has been keenly observed, and for my purpose has been tailored using python to satisfy the intent. Additionally, the modifications have been made in order to provide the best form of representation of the idea behind this implementation.
There is no need for you to download the dataset. 

## Wanderlust or Wander-lost

Implementing the code gives us interesting reults.
The red dots represent the airports, and the black lines represent the routes between two airports.

### Communication routes look robust at this stage
![Graph Image 2](https://imgur.com/1MJWA9M)

### But what would it look like if we lost, say, communication with about 6000 of them. How well connected would we continue to be ?

![Graph Image 3](https://imgur.com/xN8igvm)
![Graph Image 4](https://imgur.com/vDcJNgG)
![Graph Image 5](https://imgur.com/SCEvEsm)
![Graph Image 6](https://imgur.com/F5zJDqa)
![Graph Image 7](https://imgur.com/WGsYrmr)
