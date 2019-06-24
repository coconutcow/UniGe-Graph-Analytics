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

## The Dataset

RyanAir, Lufthansa, American Airlines, Qatar ?
These are all popular names that are discussed from time to time, and form an integral part of this globalized world.
Airports, Airlines, and Routs, can all play important roles in deciding which country do we go to next. This is an initiative to plot the airports, airlines, and their consequent routes on a global map. The dataset has been keenly observed, and for my purpose has been tailored using python to satisfy the intent. Additionally, the modifications have been made in order to provide the best form of representation of the idea behind this implementation.
There is no need for you to download the dataset.

* Nodes: Airports
* Edges: Airline route

## Wanderlust or Wander-lost

Implementing the code gives us interesting results.
The red dots represent the airports, and the black lines represent the routes between two airports.

### Part One
#### We initially try and understand the specifics of what happens when networks lose nodes or edges. The effects are understood with the below two graphs

#### Below is a fully connected graph of 20 nodes
<br>![alt text](https://github.com/coconutcow/UniGe-Graph-Analytics/blob/master/ImageSources/Image4.png "Graph One")

##### Graph Metrics: Before the attack

<table class="tg" >
  <tr>
    <th class="tg-yw4l" align="left"><b>Diameter of Network</b></th>
    <th class="tg-yw4l" >1</b></th>
  </tr>
  <tr>
    <td class="tg-yw4l"><b>Degree Centrality of Node 0</b></td>
    <td class="tg-yw4l">1</td>
  </tr>
  <tr>
    <td class="tg-yw4l"><b>Clustering Coefficient of Node 0</td>
    <td class="tg-yw4l">1</td>
  </tr>
</table>

#### What happens when we drop some edges and nodes?
<br>![alt text](https://github.com/coconutcow/UniGe-Graph-Analytics/blob/master/ImageSources/Image4.png "Graph One")

##### Graph Metrics: After the attack
<table class="tg">
  <tr>
    <th class="tg-yw4l" align="left"><b>Diameter of Network</b></th>
    <th class="tg-yw4l">2</b></th>
  </tr>
  <tr>
    <td class="tg-yw4l"><b>Degree Centrality of Node 0</b></td>
    <td class="tg-yw4l">0.43</td>
  </tr>
  <tr>
    <td class="tg-yw4l"><b>Clustering Coefficient of Node 0</td>
    <td class="tg-yw4l">0.93</td>
  </tr>
</table>

### Part Two
#### How would dropping nodes affect our communication between countries, consequently the people living in those countries ? The visualized results tend to show us how important it is to remain connected, and how different would the world look like losing communication points. The below outputs look like what the world must've been about 20 years back, with minimal advancements in airspace.

<br>![alt text](https://github.com/coconutcow/UniGe-Graph-Analytics/blob/master/ImageSources/Image5.png "Graph One")

<br>![alt text](https://github.com/coconutcow/UniGe-Graph-Analytics/blob/master/ImageSources/Image6.png "Graph Two")
