# OOP Workout

## Completed Challenges

I completed the OOP workout challenges in the `oop_workout` folder:

* Challenge 1: Vehicle class
* Challenge 2: FuelTank with encapsulation
* Challenge 3: Inheritance for vehicle types
* Challenge 4: ElectricCar and polymorphism
* Challenge 5: Dunder methods
* Challenge 6: Fleet manager

## Pair Programming

For the earlier challenges, I discussed the approach and compared ideas with classmates while working through the structure. The later challenges were completed individually, using the previous files as a base.

## Difficulties Encountered

The first two challenges were easier to follow because they focused on one class at a time. The more difficult parts started from Challenge 3, especially understanding how `FuelledVehicle` inherits from `Vehicle` and how `Car`, `Truck`, and `Motorcycle` reuse that shared logic.

Another difficult part was understanding when to use inheritance and when to use composition. For example, the fuelled vehicles use a `FuelTank` object, while the electric car has a battery instead of a tank.

I also had some trouble with making sure failed operations did not change the object state. For example, if a vehicle does not have enough fuel or charge, the kilometres should not increase. This helped me understand why it is important to validate first and only change attributes after the checks pass.

The Fleet challenge was the most complex because it connected all earlier classes together. It helped me understand polymorphism better, because the fleet can call `drive()` on different vehicle types without needing separate code for each type.

Overall, this exercise helped me practise classes, constructors, methods, private attributes, inheritance, `super()`, method overriding, dunder methods, and working with multiple Python files.
