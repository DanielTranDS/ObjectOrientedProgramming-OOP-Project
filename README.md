# PandemicSimulation-OOP-Project
Pandemic Simulation with Object-Oriented Programming

In this project, with only very basic Python libraries like math, random, matplotlib, I will try to create a simple Simulation of how a Pandemic Spread, with some specified rules that are closely resembled those in reality. At the end, I visualize the results obtained from the simulation, based on different input scenarios, to highlight some key insights regarding social distancing and patient zero health. This project heavily makes use of Object Oriented Programming to create the classes needed to run the simulation.

Viral Epidemics like the 1918 influenza pandemic, or more recently Covid19 pandemic, got out of hand. I would like to simulate the way such diseases spread, in order to better understand how this happens.

In this project, there are 3 main tasks. Firstly, I will create the necessary data structure (classes) to simulate social links from the data file "Network data.txt" and disease transmission between people. Then, I will simulate infections among the population over a period of time. Lastly, I plot graphs to determine whether an outbreak is contained or not, based on different input scenarios.

The data file used for this project is "Network data.txt", which contains 200 unique records. Each record is on its own line in the file, consisting of a person's name, together with the names of that person's friends, whom they are in regular contact with. Each person has at least 1 friend, and each of the person's friends has also named that person as a friend.
