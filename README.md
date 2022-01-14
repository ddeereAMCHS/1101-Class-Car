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
  - a maximumDistance method that returns the maximum distance the Car can travel with a full tank of gas
  - a honk method that prints "HONK" to the screen
  - a canTravelDistance that takes a double as a parameter which is the distance to be traveled and returns true if the Car can travel that distance with a full tank of gas
- - - -
* Create a program called `CarTester.java`
* Prompt the user for a filename
* Skip the first line of the file
* Read in all the lines in this file and store them in an array of Strings
* Create an array of Cars that will hold one more element than the String array
* For each element in the array of Strings, split it on commas, trim the values, and create a Car object with those values that you then store in the array of Cars
* For the last element in the Car array, create a Car object with the default constructor
  * Prompt the user to enter values for each data member and then use the setter methods to assign those values to the Car object
* Prompt the user for a double
  * This will be the distance to be traveled
* For each Car:
  * Print the make and model of that Car
  * Print whether the Car is or is not a gas guzzler
  * Print whether the Car is or is not spacious
  * Print the result of calling that Car's honk method
  * Print whether the Car can travel the distance the user entered

***Example Input:***\
cars1.csv\
Chevy\
Suburban\
4\
7\
21.1\
27.8\
332.5\
***Exapmle Content of cars1.csv:***\
Make, Model, NumDoors, NumSeats, MPG, GasTankSize\
Chevy, Silverado, 4, 5, 16.2, 24.8\
Ford, Mustang, 2, 4, 13.4, 16.0\
Honda, Civic, 4, 5, 27.3, 12.4\
Toyota, 4Runner, 4, 7, 14.1, 23.0\
***Example Output:***\
Chevy Silverado\
The Chevy Silverado is not a gas guzzler\
The Chevy Silverado is not spacious\
HONK\
The Chevy Silverado can travel 332.5 miles on a full tank of gas\
Ford Mustang\
The Ford Mustang is a gas guzzler\
The Ford Mustang is not spacious\
HONK\
The Ford Mustang cannot travel 332.5 miles on a full tank of gas\
Honda Civic\
The Honda Civic is not a gas guzzler\
The Honda Civic is not spacious\
HONK\
The Honda Civic can travel 332.5 miles on a full tank of gas\
Toyota 4Runner\
The Toyota 4Runner is a gas guzzler\
The Toyota 4Runner is spacious\
HONK\
The Toyota 4Runner cannot travel 332.5 miles on a full tank of gas\
Chevy Suburban\
The Chevy Suburban is not a gas guzzler\
The Chevy Suburban is spacious\
HONK\
The Chevy Suburban can travel 332.5 miles on a full tank of gas
