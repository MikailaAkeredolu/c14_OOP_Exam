# c14_OOP_Exam
- Leverage UML below to answer the questions below.
- MUST submit repo by 3:45pm (No extenions)
- Asuume, Getters, Setters, Constructors and anything else you may need to get the output printed!

![Screen Shot 2023-10-06 at 6 29 23 AM](https://github.com/MikailaAkeredolu/c14_OOP_Exam/assets/10773482/d398923e-bf7f-4a59-8625-65f84e92280c)

### Assuming that a vehicle is something that can transport a passenger or passengers
- Therefore, ALL vehicles will ALWAYS qualify for a 10% discount by default. However, cars ALWAYS get an EXTRA 5% discount.

> Do the following inside the class that contains your main method (psvm)

- Create an intance of each Vehicle ..meaning create a vehicle of every Type.
- Create an instance of a Drone
- Create a Flying Car
- Create an ArrayList of Vehicles and add all your vehicles to the list
- Use your printListOfVehiclesNames(List<Vehicle>) to print the names of each vehicle in your ArrayList of Vehicles
- Below is a sample output
  
```
Mustang
Concord
SeaHorse
GM
M2
```

<br />

- Create a List of Flyable Objects and add all objects that are flyable to it
- Use your printListOfFlyableObjects(List<Flyable>) method to print the list of flyable objects
- Below is the sample output:

```
Drone{name='DroneX'}
Plane{speed=2000, price=180000.0, engine=Engine{size=L}, TAX_AMT=0.1}
FlyingCar{speed=1020, price=1000000.0, engine=Engine{size=L}, TAX_AMT=0.1}

```

<br />

- Note that every passsenger's Entry contains a key(number) and a value for their name(text) as seen below!.
- Use a Map to create two different passengers as seen below (hint)

```
(57, "wesley snipes)
(007, "james bond) 

```

<br/ >

- Invoke passenegNumbers() to print out only the passengers numbers  such as 7 and 57
- Below is the sample output:

```
7
57
```

<br/ >

- Sort DriveAbleVehiclesBySpeed
- Below is the sample output:

  ```
  
    Boat{engine=Engine{size=S}, speed=60, price=50000.0, engine=Engine{size=S}, TAX_AMT=0.1}
    Truck{speed=120, price=80000.0, engine=Engine{size=L}, TAX_AMT=0.1}
    Car{extraDiscount=0.05, speed=280, price=80000.0, engine=Engine{size=M}}
    FlyingCar{speed=1020, price=1000000.0, engine=Engine{size=L}, TAX_AMT=0.1}

```
