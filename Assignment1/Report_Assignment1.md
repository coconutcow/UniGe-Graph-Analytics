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
openflights.org/data.html

### The Dataset

RyanAir, Lufthansa, American Airlines, Qatar ?
These are all popular names that are discussed from time to time, and form an integral part of this globalized world.
Airports, Airlines, and Routs, can all play important roles in deciding which country do we go to next. This is an initiative to plot the airports, airlines, and their consequent routes on a global map. The dataset has been keenly observed, and for my purpose has been tailored using python to satisfy the intent. Additionally, the modifications have been made in order to provide the best form of representation of the idea behind this implementation.
There is no need for you to download the dataset. I have used a library named 'urllib.request' in order to extract the file straight from the url thus making this project light, quick, and more efficient to execute.

## This world is our stage

Implementing the code gives us interesting reults.
The red dots represent the airports, and the black lines represent the routes between two airports.

![Graph Image 1](https://imgur.com/QUII3h9)

![Graph Image 2](https://imgur.com/1MJWA9M)
![Graph Image 3](https://imgur.com/xN8igvm)
![Graph Image 4](https://imgur.com/vDcJNgG)
![Graph Image 5](https://imgur.com/SCEvEsm)
![Graph Image 6](https://imgur.com/F5zJDqa)
![Graph Image 7](https://imgur.com/WGsYrmr)


Thanks to this script you will be able to reproduce a Social Contagion on your Graph. First of all, the Graph will be printed:

![Graph Image 1](https://i.imgur.com/72EXAqG.png)

You can modify colors, nodes, scales and so on. The png images will be numbered from 1 (the first) to the last one and they represent the days of the contagion. For eample the second one look like this:

![Graph Image 2](https://i.imgur.com/iEAn7r7.jpg)

Where red nodes represent the infected ones. At the end, if the contagion parameters are good enough, you will get this:

![Graph Image 2](https://i.imgur.com/xf5u7Hv.png)

Every node is red, this means that you infected the whole graph. Sometimes the graph is so big that you cannot visualize all the nodes and maybe there are blue nodes hidden behind the reds. So you can check on terminal because at the end the list of remaining nodes to infect will be printed and if it is empty, it means that you did a good work.

## Authors

* **Riccardo Basso** - *Università degli studi di Genova*
