# Final Portfolio - Interactive Visualization

- [electrical.html](https://daveedgit.github.io/finalproject2021/electrical.html)
- [sunburst.html](https://daveedgit.github.io/finalproject2021/sunburst.html)

# Exploratory
The visualization project intends to evaluate the relationship between the type of car owned by a household (electric and non- electric) in the State of California and their socio-economic profile. The later years have seen a dramatic decrease in price for electric vehicles, which diminishes the purchasing gap between households with different characteristics. I am looking to find out what factors play the main role when selecting electric over the traditional choice in the US? The CSV was obtained from the National Center for Sustainable Transportation website leaded by UC Davis and other universities in California. The target public for this visualization will be car buyers, government officials in charge of sustainability, climate advocates, car makers, electric battery manufacturers, technology journalists, car engineers and the general public. I am hoping this data set will be enough for my purposes but I might explore data sets with information on battery performance.

![sketch](https://user-images.githubusercontent.com/60953851/112066004-000bbd00-8b3c-11eb-91cf-a5fd8ab9ea30.JPG)

## Brainstorming and sketches
The data for this project is mostly quantitative. The data will be representaed in bar graphs, pie charts and scatter plots, and a correlation heat map, since the data set has a good number of variables that could relate. I'm interested in visualizing aspects related to income, like the level of studies, if the car is used mostly for commuting to work or vacation purposes and house ownership.  However, to create better engagement with the viewer I'd like to create a sunburst graph to visualize and compare household incomes and the types of car batteries they own. The idea would be to create groupings of similar incomes in the base node and then create partitions coming from each to illustrate what car they owned, what type of battery did they switched to and how compromised are they with the environment. I will have to make clear that the State of California provides buyers with subsidies of at least $7000 when buying clean energy cars. This latter information is not included on the data set. 

Please see the result of a recent brainstorming sessions with colleague sstudent Kai 

![David   Kai (1)](https://user-images.githubusercontent.com/60953851/113631058-dc19a280-9636-11eb-9ebc-c7ed487c2aa7.jpg)

## first Iteration
[Exploratory_1.pdf](https://github.com/Daveedgit/finalproject2021/files/6550032/Exploratory_1.pdf)

Critique: The first critique went well and some good comments came out it. The data set is pretty interesting and very complete. For the same reason it can be complex to choose a specific topic to focus on. There were some comments about changing the background color, focusing on the sunburst chart, and eliminating the scattered plot. In the initial sunburst chart I intended to create a relatinship between income, environment concern, type of car and education. At the end I eliminated education and centered on the relationship between income and concern for the environment.
 
 
# Narrative
The sunburst chart illustrates the different choices of clean energy cars that new buyers of Fuel Cell Vehicles opted for in the past. The exploratory visualization investigates whether the income of the household or concern for the environment weighted in strongly towards acquiring a specific vehicle.

The data to create the chart was transformed from a CSV format to a hierarchical JSON in order to create levels. The innermost ring represents 5 different income groups, separated by their respective tax bracket from 2018. The following ring illustrates the concern for the environment that each household expressed during the survey. And the outer most ring shows the different clean energy vehicles: Battery Electric Vehicles (BVEs), Plug-in Hybrid vehicles (PHEVs), Hybrid Vehicles (HEVs) and Compressed Natural Gas vehicles (CNGs).

It is evident that the choice for clean energy cars is fueled by the concern that each household has for the environment. The HEVs and BEVs were the most purchased, independently of income. It is also necessary to note that the State of California, where the survey took place, subsidizes up to $7000 when acquiring a clean energy vehicle.
 
## first sketch
![Narrative sketch](https://user-images.githubusercontent.com/60953851/119743233-6ae8b580-be57-11eb-8837-44768ddc4677.JPG)
