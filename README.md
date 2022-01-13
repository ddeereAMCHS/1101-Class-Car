# Car Class

- Create a program called `Car.java`
- The Car class should have the following data members:
  - The make
  - The model
  - The number of doors
  - The number of seats
  - The miles per gallon (as a floating point number)
  - The gas tank size in gallons (as a floating point number)
- The Car class should have the following constructors:
  - Default
  - A constructor that takes the make and model
  - A constructor that takes parameters for all six data members
- The Car class should have getter and setter methods for each data member
- The Car class should have a toString method that returns the make and model of the Car separated by a space
- The Car class should have the following other methods:
  - an isGasGuzzler method that returns true if the miles per gallon is less than 15.0
  - an isSpacious method that returns true if the number of seats is greater than 5
  - a honk method that prints "HONK" to the screen
  - a canTravelDistance that takes a double as a paramter which is the distance to be traveled and returns true if the Car can travel that distance with a full tank
- - - -
* Create a program called `CarTester.java`
* Prompt the user for a filename
* Read in all the lines in this file and store them in an array of Strings
* Create an array of Cars that is the same size as the String array
* For each element in the array of Strings, split it on commas, trim the values, and create a Car object with those values that you then store in the array of Cars
* Prompt the user for a double
  * This will be the distance to be traveled
* For each Car:
  * Print the make and model of that Car
  * Print whether the Car is or is not a gas guzzler
  * Print whether the Car is or is not spacious
  * Print the result of calling that Car's honk method
  * Print whether the Car can travel the distance the user entered

