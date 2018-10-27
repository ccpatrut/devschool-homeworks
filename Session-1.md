
## Barking dog
 We have a dog that likes to bark. We need to wake up if the dog is barking at night!
* Write a method bark that has 2 parameters.
* 1st parameter should be of type boolean and be named barking, it represents if our dog is barking. 
* 2nd parameter represents the hour of the day and is of type int with the name hourOfDay and has a valid range 0-23. 
* We have to wake up if the dog is barking  before 08:00 am and after 22:00 hours so in that case return true.
* In all other case return false.  If the hourOfDay parameter is less than 0  or greater than 23 return false.
* Example:  
    * bark(true, 1)should return true
    * bark(false, 2) should return false since the dog is not barking.
    * bark(true, 8) should return false, since it's not before 8:00AM
    * bark(true, -1) should return false because the hourOfDay parameter needs to be in range 0-23.
    
    
    
## Equal Sum Checker
* Write a method hasEqualsSum with 3 parameters of type int.
* The method should return boolean and it needs to return true if sum of first and second parameter is equal to third parameter. Otherwise return false.
* Examples:
    * hasEqualSum(1, 1, 1);  should return false since 1 + 1 is not equal to 1
    * hasEqualSum(1, 1, 2);  should return true since 1 + 1 is equal to 2
    * hasEqualSum(1, -1, 0);  should return true since 1 + (-1) is 1 - 1 and is equal to 0
    
    
## Minutes To Years and Days Calculator
* The method should not return anything (void) and it needs to calculate the years and days from the minutes parameter. 
* If parameter is less than 0, print text "Invalid Value".
* Otherwise if parameter is valid then it needs to print a message in the format "XX min = YY y and ZZ d".
* XX represents the original value minutes. YY represents the calculated years. ZZ represents the calculated days.

* EXAMPLES:
    * printYearsAndDays(525600); should print "525600 min = 1 y and 0 d"
    * printYearsAndDays(1051200); should print "1051200 min = 2 y and 0 d"
    * printYearsAndDays(561600); should print "561600 min = 1 y and 25 d"

* TIPS:

    * Be extra careful about spaces in the printed message.
    * Use the remainder operator 
        * hour = 60 minutes
        * 1 day = 24 hours
        * 1 year = 365 days
        
## Inheritence
* Start with a base class of a Vehicle, then create a Car class that inherits from this base class.
* Finally, create another class, a specific type of Car that inherits from the Car class.
* You should be able to hand steering, changing gears, and moving (speed in other words).
* You will want to decide where to put the appropriate state and behaviours (fields and methods).
* As mentioned above, changing gears, increasing/decreasing speed should be included.
* For you specific type of vehicle you will want to add something specific for that type of car.
