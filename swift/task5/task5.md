# TASK5
1. Write a function named __parse(digit:)__ that takes a string with one character as parameter.
   The function should return "a digit" if the character was digit, or "not a digit" otherwise. Hint: parse(digit: String) -> String
   
### EXAMPLE
INPUT:
```swift
	let stringResult = parse(digit: "b")
	let digitResult = parse(digit: "4")
```
RESULT:
```swift
	stringResult = "not a digit"
	digitResult = "a digit"
```
 
 2. Write a function named __timeDifference__. It takes as input four numbers that represent two times in a day and returns the difference in minutes between them.
   The first two parameters __firstHour__ and __firstMinute__ represent the hour and minute of the first time. The last two __secondHour__ and __secondMinute__ represent the hour and minute of the second time.

 3. Write a function named __verify__ that takes a string expression of open and closed parentheses ((, )) and returns true if they are correctly paired and false otherwise.
 
### EXAMPLE
INPUT:
```swift
	let checkCorrect = verify("(())")
	let checkIncorrect = veriy(")(())")
```
RESULT:
```swift
	checkCorrect = true
	checkIncorrect = false
```

4.  __queue__ is a data structure that can perform two operations:
      push which takes a value and adds it at the end of the queue
	  pop which returns the value from the start of the queue and removes it from the queue
    Your task is to implement the push and pop operations. The most simple way to represent a queue is using an array. Here are some example operations:

```swift
// here we define an empty queue
var queue: [Int] = []

// add 1 in the queue
push(1, &queue) // queue = [1]

// add 2 in the queue
push(2, &queue) // queue = [1, 2]

// pop the first element
pop(&queue) // 1, queue = [2, 3]

// add 3 in the queue
push(3, &queue) // queue = [2, 3]

// pop the first element
pop(&queue) // 2, queue = [3]

// pop the first element
pop(&queue) // 3, queue = []

// pop the first element 
pop(&queue) // returns nil because there are no elements in the queue
// queue = []
```

5. A stack is a data structure that can perform three operations:
	push adds a value on the top of the stack
	top returns the value from the top of the stack
	pop returns the value from the top of the stack and removes it from there
  Your task is to implement the push, top and pop operations. The most simple way to represent a stack is using an array. Here are some example operations.
```swift
var stack: [Int] = []

push(1, &stack) // stack = [1]

push(2, &stack) // stack = [1, 2]

pop(&stack) // 2, stack = [1]

push(3, &stack) // stack = [1, 3]

pop(&stack) // 3, stack = [1]

pop(&stack) // 1, stack = []

pop(&stack) // returns nil because there are no elements in the stack
// stack = []
```

6. Write a function named __mult__ that takes two numbers as arguments and returns multiplication of these numbers. Do not use * sign, or loops.

7. Write a function named applyKTimes that takes an integer K and a closure and calls the closure K times. The closure will not take any parameters and will not have a return value.

## EXAMPLE1
Function call:
```swift
applyKTimes(3) { 
    print("We Heart Swift")
}
```
Output:
```swift
We Heart Swift
We Heart Swift
We Heart Swift
```

8. You are given an array of integers named __numbers__. Find the largest number from the given array and print it. Use built-in __reduce__ method to solve this exercise.
9. You are given an array of integers named __numbers__. Find the sum of the squares of all the odd numbers from the given array. Use built-in methods map, filter and reduce to solve this problem.
