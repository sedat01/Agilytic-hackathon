# Agilytic-hackathon

## What is it about?

Motorways, major railway lines etc. often form a barrier for cycling, either forcing long detours or
funnelling cyclists to unsafe roads to cross the barrier. But there is no clear idea how to measure
this effect, what can be considered a sufficient density of safe crossings, or how to estimate the
necessary number of crossings when preparing a large infrastructure project.

### Method

The basic metric for determining the barrier effect in our project is the distance between crossing points. We can normalize the value of each crossing points distance to its neighbour for any given region or infrastructure type.

Then we include the population density in the calculation, so a unit of distance in densely populated area gets darker color than the same unit in less populated area. The reasoning behind this is that a large distance between crossing points in a densely populated area has a greater impact than in a less populated area.

### What we did?

We analysed the provided data and did some exploratory work. 

You can follow the analysis and exploration in the following notebooks:

1. Analysis of Ghent region for railways

* [exploration.ipynb](https://github.com/sedat01/Agilytic-hackathon/blob/main/exploration.ipynb)

2. Analysis of Flanders region for railways

* [crossing_points.ipynb](https://github.com/sedat01/Agilytic-hackathon/blob/main/crossing_points.ipynb)

3. Analysis of Benelux region for railways, roads and waterways

Finally we prepared an interactive map of the current existing crossings with color indication of how far is it from the closest neighbour. 

We uploaded this interactive map on a webserver for easy access:

* [interactive_map.html](https://github.com/sedat01/Agilytic-hackathon/blob/main/interactive_map.html)
* [interactive_map.ipynb](https://github.com/sedat01/Agilytic-hackathon/blob/main/interactive_map.ipynb)
* [Cycling crossings - Benelux](https://cycling-crossings-benelux.000webhostapp.com/)

![interactive map](https://github.com/sedat01/Agilytic-hackathon/blob/main/assets/scr.png)

### Contributors

Samuel Fooks : [LinkedIn](https://www.linkedin.com/in/samuel-fooks-972800131/)
Sedat Mehmet : [LinkedIn](https://www.linkedin.com/in/sedat-mehmed-a58851199/)
Frank Trioen : [LinkedIn](https://www.linkedin.com/in/frank-trioen-21b71135/)

