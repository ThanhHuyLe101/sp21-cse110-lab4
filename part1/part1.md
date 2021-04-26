 ## Part 1a
part1a-question1:
  Line 9 prints 'value added: 20'
  
part1a-question2:
  Line 13 prints 'final value: 20' since var result exists outside of the if block
  
part1a-question3:
  Line 9 prints 'value added: 20'  
  
part1a-question4:
  Line 13 should get an error 'result' is not defined because result doesn't exist outside of if block
  
part1a-question5:
  Line 9 should get an error 'Assignment to constant' because assignment to constant isn't allowed (who woulda thunk) 
  
part1a-question6:
  Line 13 should get an error 'result' is not defined because result doesn't exist outside of if block, same as let
 
 
 ## Part 1a
 
part1b-question1:
  Line 12 prints 3, because that's the value of i after the loop
  
part1b-question2:
  Line 13 prints 150, because in the last iteration of the loop, discountedPrice = 300/2 = 150
  
part1b-question3:
  Line 14 prints 150, because in the last iteration of the loop rounding discountedPrice still gives 150
  
part1b-question4:
  The function returns the list [50, 100, 150]

part1b-question5:
  Line 12 throws an error because i doesn'r exist outside the loop

part1b-question6:
  Line 13 throws an error because discountedPrice doesn'r exist outside the loop
  
part1b-question7:
  Line 14 prints 150 because finalPrice is within scope
  
part1b-question8:
  The function returns the list [50, 100, 150] because the code works, all variables are used within scope.
  
part1b-question9:
  Line 11 throws an error because i doesn'r exist outside the loop
  
part1b-question10:
  Line 12 prints 3 because length of input list is 3

part1b-question11:
  The function returns the list [50, 100, 150] because the code works, all variables are used within scope, 
  discountedPrice is created and destroyed every loop iteration.
  
part1b-question12:
  a. student.name
  b. student['Grad Year']
  c. student.greeting();
  d. student['Favorite Teacher'].name
  e. student.courseLoad[0]
  
part1b-question13:
  
  a. ‘3’ + 2 = '32', a string because string + means concatenation
  
  b. ‘3’ - 2 = 1, a number because string - number means it's converted to a number
  
  c. 3 + null = 3, a number because null gets ToNumber(), turning it to 0 
  
  d. ‘3’ + null = '3null', a string because string concatenation and null gets turned to the string 'null'
  
  e. true + 3 = 4, a number because true = 1 in arithmetic
  
  f. false + null = 0, because false and null is turned to 0 in arithmetic
  
  g. '3' + undefined = '3undefined', because string concaternation and underfined is turned to string
  
  h. '3' - undefined = NaN, the - after string turns '3' into a number but a number - undefined = NaN

part1b-question14:
  
  a. ‘2’ > 1 = true, because 2 is converted into a number
  
  b. ‘2’ < ‘12’ = false, strings are compared leter by letter, and '2' > '1' 
  
  c. 2 == ‘2’ = true, in ==, different kinds are turned to numbers, so 2 == 2
  
  d. 2 === ‘2’ = false, in ==, types must be the same. 
  
  e. true == 2 = false, true is turned to 1
  
  f. true === Boolean(2) = true, since 2 > 0, Boolean turns it to a boolean true, same type same value. 
  
part1b-question15:
  
  == compares with type conversion, so 2 == '2'
  
  === compares without type conversion, so the type must be the same as well.

part1b-question17:
 
 modifyArray([1,2,3], doSomething) would return the array [2, 4, 6] because it applies the callback function to each item of the array,
   then make a newArray using the results

part1b-question19:
 
 It outputs 1 4 3 2

