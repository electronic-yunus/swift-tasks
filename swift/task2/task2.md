# TASK 2
1. You are working on a smart-fridge. The smart-fridge knows how old the eggs and bacon in it are.
You know that eggs spoil after 3 weeks (21 days) and bacon after one week (7 days).
Given baconAge and eggsAge(in days) determine if you can cook bacon and eggs or what ingredients you need to throw out.
If you can cook bacon and eggs print "you can cook bacon and eggs".
If you need to throw out any ingredients for each one print a line with the text throw out _ingredient_ (where _ingredient_ is bacon or eggs) in any order.

### EXAMPLE
1. INPUT:
```swift
	var baconAge = 3
	var eggsAge = 2
```
OUTPUT:
```swift
	you can cook bacon and eggs
```
2. INPUT:
```swift
	var baconAge = 9
	var eggsAge = 20
```
OUTPUT:
```swift
	throw out bacon
```
3. INPUT:
```swift
	var baconAge = 9
	var eggsAge = 23
```
OUTPUT:
```swift
	throw out bacon  
	throw out eggs
```

2.You are given a year, determine if it’s a leap year. A leap year is a year containing an extra day. It has 366 days, instead of the normal 365 days.
	The extra day is added in February, which has 29 days instead of the normal 28 days. Leap years occur every 4 years. 2012 was a leap year and 2016 will also be a leap year.
	The above rule is valid except that every 100 years special rules apply. Years that are divisible by 100 are not leap years if they are not also divisible by 400.
	For example 1900 was not a leap year, but 2000 was. Print "Leap year!" or "Not a leap year!" depending on the case.
### EXAMPLE
1. INPUT:
```swift
	var year = 2000
```
OUTPUT:
```swift
	Leap year!
```
2. INPUT:
```swift
	var year = 2005
```
OUTPUT:
```swift
	Not a leap year!
```

3. You are given four variables __a__, __b__, __c__ and __d__. Print the value of the smallest one.

### EXAMPLE
 INPUT:
```swift
	var a = 3
	var b = 2
	var c = 6
	var d = 9
```
 OUTPUT:
```swift
	2
```
4. Test if number is divisible by 3, 5 and 7. For example 105 is divisible by 3, 5 and 7, but 120 is divisible only by 3 and 5 but not by 7.
	If number is divisible by 3, 5 and 7 print "number is divisible by 3, 5 and 7", otherwise print "number is not divisible by 3, 5 and 7".
5. Find out if the point (x, y) is inside of the rectangle with the lower-left corner in (lowX, lowY) and the upper-right in (highX, highY).
    Print "inside" or "not inside" depending on the case.

### EXAMPLE
1. INPUT:
```swift
	var x = 1
	var y = 2
	var lowX = 1
	var lowY = 1
	var highX = 3
	var highY = 3
```
OUTPUT:
```swift
	inside
```
2. INPUT:
```swift
	var x = 4
	var y = 4
	var lowX = 0
	var lowY = 0
	var highX = 3
	var highY = 5
```
OUTPUT:
```swift
	not inside
```

6. You are working on a videogame where the character has a certain number of hitpoints(HP) ranging from 0 to 100.
	100 represents full health
	0 represents dead.
	You want to add regenerating health to the game using the following rules:
	
	HP always regenerates up to numbers of the form X0 (75 -> 80 , 32 -> 40 …)
	When HP is below 20 it regenerates up to 20 (13 -> 20, 5 -> 20, …)
	If the character has 0 HP then it doesn’t regenerate life (it’s dead)
	Given the current hp of the character stored in a variable hp, print the hp the player will have after regenerating life.

### EXAMPLE
1. INPUT:
```swift
	var hp = 60
```
OUTPUT:
```swift
	60
```
2. INPUT:
```swift
	var hp = 26
```
OUTPUT:
```swift
	30
```

7. You are given 3 grades stored in 3 variables of type Double finalsGrade, midtermGrade, projectGrade.
	These grades are used to compute the grade for a class. finalsGrade represents 50% of the grade.
	midtermGrade represents 20% of the grade. projectGrade represents 30% of the final grade.
	Print the grade for the class.

### EXAMPLE
1. INPUT:
```swift
	var finalsGrade = 2.0
	var midtermGrade = 5.0
	var projectGrade = 3.0
```
OUTPUT:
```swift
	2.7
```
2. INPUT:
```swift
	var finalsGrade = 5.0
	var midtermGrade = 5.0
	var projectGrade = 5.0
```
OUTPUT:
```swift
	5.0
```

8. You have the cost of a meal at a restaurant stored in a variable mealCost of type Double.
	You would like to leave a tip of a certain percentage. The percentage is stored in a variable tip of type Int.
	Print the total cost of the meal. Hint: You should use casting to complete this task. 

### EXAMPLE
1. INPUT:
```swift
	var mealCost:Double = 3.5
	var tip:Int = 20
```
OUTPUT:
```swift
	4.2
```
2. INPUT:
```swift
	var mealCost:Double = 10.0
	var tip:Int = 10
```
OUTPUT:
```swift
	11.0
```

9. A farmer is harvesting wheat from a number of wheat fields, given in a variable __numberOfFields__ of type Int.
	Each field produces the same quantity of wheat given in a variable wheatYield of type Double.
	Sometimes the harvest is increased by 50% due to favorable weather conditions. You are given this information in a variable weatherWasGood of type Bool.
	Print the total amount of wheat that the farmer will harvest.

### EXAMPLE
1. INPUT:
```swift
	var numberOfFields:Int = 5
	var wheatYield:Double = 7.5
	var weatherWasGood:Bool = true
```
OUTPUT:
```swift
	56.25
```
2. INPUT:
```swift
	var numberOfFields:Int = 5
	var wheatYield:Double = 7.5
	var weatherWasGood:Bool = false
```
OUTPUT:
```swift
	37.5
```