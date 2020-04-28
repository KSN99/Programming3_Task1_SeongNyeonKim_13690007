# Java Based Traffic Simulator
## Program Working Document

### Specification
The problem is that a traffic simulator is needed, which should not violate road rules. 
The program will be designed to simulate various situations to solve this problem

### Decomposition
The objects included:
-	Car
-	Traffic Light
-	Road

#### Car
The car object will be responsible for adjusting the vehicle length and tracking the car position.
The traffic light object will contain a Boolean than prevents and allows the car object from moving one road object to another. 
The car class requires a variety of attributes(length, distance, on_Road)), 
including the size of the car, the length of the bus and motorcycle, 
the distance depending on the location of each vehicle as it passes through the road section, 
and the on-road to track which road the car is on. This class will interact with the traffic light class and the road class. 
This class interacts with traffic light and Road classes.

##### Bus
The bus class will be a subclass of car, describing a large road vehicle. It will inherit its attributes and behaviour from  
Car except its length will be defined as being three times that of the car’s length. 

#### Road
The road object will include segments that allow the car to drive the road until it meets an intersection.
 The Road class attributes length and road_num. 
 The length of the road depends on the length of the car. 
 Road numbers only identify road objects from other road objects. 
 The car will include a section to monitor itself on the road. 
 The path will include the gaiter, setter, and constructor of the initial value.
 
#### Traffic Light
 The traffic light object will contain a Boolean than prevents 
 and allows the car object from moving one road object to another. 
 The TrafficLight class contains a Boolean attribute that determine the lights color. 
 It will determine whether the car can move, mainly related to the car.
### Main
The main class depends on the simulation class. 
The main class location where the program will be executed. 
Control vehicle movement, declaration of road object, storage, etc.
 in simulation. 
 It interacts with all classes to ensure that 
 classes are interconnected and "communicated to produce programs.

