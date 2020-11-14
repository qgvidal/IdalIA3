# BATMOBILE: AN INTRODUCTION TO OOP WITH PYTHON
### TEAM: Data Killers!!! (Andrés Espinosa Sanfiel, Héctor Escribano Campos, Quique García Vidal)

In this notebook we will solve an exercise proposed in the Master in AI and Advanced Analytics (IDAL, UV). A useful and creative aproximation on how to apply object oriented programming

![alt text](https://github.com/qgvidal/batmobile/blob/main/images/batmobile.jpg)

Hi Guys Cristopher Nolan is here. Don't talk about this, but I am making a new Batman movie and I need your help to design the new Batmobile. For this ocassion I would like you to design it as several Python Classes.
- Design the main Batmobile class with the following attributes: Pilot (It could be Batman or Robin), number of batrockets loaded, number of pem (this are electromagnetic pulses to counter the Joker weapons) uses left, liters of gas left in the batmobile.
- Add the following methods to the Batmobile class: A method to accelerate the batmobile and drive for some distance, a method to activate the turbo and drive for some distance faster than the normal method, a method to launch a rocket to a Joker colleague, a method to launch a pem use.
- Create the following classes to interact with the Batmobile: Joker, Joker Villain, Rocket, PEM Pulse.
- The Joker and Jokker Villain class should have a parameter called KO which will turn to True when they receive a Rocket. They also have a parameter called Weapon which should turn to false if they receive a PEM Pulse.
- The Rocket and PEM Pulse are the ammunition of the Batmobile, the car can only use the weapons if it has ammunition in the arsenal.


First step to defeat joker's team is creating a strategy: 

![alt text](https://github.com/qgvidal/IdalIA3/blob/main/batmobile-main/images/BatmobileDiagram.png)

The players will introduce who they want to attack. Then, will answer the question about the weapon they want to use and finally, before starting the game, they will choose if turbo or not. In case they decide to use it, gas will decrease quicker (by a factor of 3 compared to not using it). The game will end in two different ways: you win if you are able to kill both, the villain and the joker or losing, if you run out of ammunition or gas. Let's start the game...
