# GraphAnalytics: Assignment Three

## Brace, breath, and begin

#### Objective:
Observe the concept of infecting networks, or in other words Social Contagion. How can infections in networks spread ? Can we visualize them ? Let's find out!

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

## What can we perceive ?
### An infection is not just a biological term. In essence, we are trying to convey that how can a network be impacted by change in one area of a network, and what can be the extent of the effect. 

With the below outputs we can observe the true essence of the meaning of infections, particularly noticing the changes in node colors, edges, and increase in sizes of nodes, by specifying conditions - which in the real world could be drops in communication lines, cyber attacks, terror attacks, energy outages, and so on.

Implementing the code gives us interesting results.
The red dots represent the airports, and the black lines represent the routes between two airports.


#### Our graph in it's initial form
<br>![Graph1](ImageSources/Image1.png)

#### Now let's visualize what would the impact be across the globe if two prominent airplane services such as Lufthansa and American Airlines get affected by any change in dynamics such as a server outage, a terror attack, a cyber attack, or even something as trivial as the company deciding to stop operations in another country - the extent is alarming, and magnanimous, to say the least.

<br>![Graph Image 2](https://lh3.googleusercontent.com/x0ExyXKAOYDF21n9GfAIoGNho9DxrTImSwwC0tinUUQ5q8ZROGdKJQFDlF2cZbnPOXualiOo1Jlk9d9ltEX7Th327lLLkKSfQyDFSar3p0NBwTwcUkqbIy0s_CGpmLXoGJ83-wakgBXcvVmqi2XJuApxEdX4fUqBuJIA-r7PIkwGLGwou6O7rpOBMluZ1aZQ2y3aWVnMHUx5Z8KEy0munwi2_mjSNjA096HorFA1wDHs7RnjWZjVbWypYyWy3yLI3guPOkO6sqxbIZApeC3KKWqzatbimFutn8Dae0t-9y0KEDsi4JIlNZVnGQdYrusYgiszUWaTiIZnOMdesqtfcELtGWbJ18exynoMt-kjaJxh9adzfH_-QPRfHAIRwcK1M5w718MZZ7fs7_2On3QmiV_YTWbKpXGuQR9h0kYPLbiXUdUB42Fh7_mtm8XZPHfkf6M4U9csojY8qRTVp3bAKFFbFuqozUxtit2HJU4d5QoOV63BnlFqNp_HThsZ_kbaLKefCQQLGNNAEyspaXzl6RXEZtcGnwT9bv4tlonbC5F4xvHDiUnPe580ws4kKHiOg5Sc90iMCNqJ40VpWDCj3SkRld3Nx2eOT0Pm5i4-R-JZZotrNAGpMAUlhZV2MAy0-bUEsr9_Qwm3wtgUxCD9zKs_swj2lQ=w1018-h745-no)

##### In the above graph, the following changes have been made:
* All airports have been colored based on their region such as Europe, Asia, America, etc.
* All airports have been resized based on their centrality. Higher the centrality, larger is the node size - thus highlighting their importance in this graph.
* All routes of Lufthansa Airlines and American Airlines have been highlighted with thicker lines, and alternative shades to the rest to highlight how impactful can the routes across the world be in case something goes wrong with these specific airline carriers.

