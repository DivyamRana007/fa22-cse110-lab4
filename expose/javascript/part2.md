## Q1
3 as it is a var so has a function wide scope and the last value checked against the condition in the for loop is for i = 3 which is false and the loop breaks. So it returns 3 

## Q2
150 as we are definining discountedPrice inside the for loop and the loop breaks at i = 2 when discountedPrice has value 150

## Q3
150 as we are definining discountedPrice inside the for loop and final price is being updated in each iteration of the loop. So, this is the last value associated with finalPrice which is displayed

## Q4
[50, 100, 150] as these are the finalPrices pushed into discounted in the iteration of the loop. First 50 was pushed, and then 100 and 150

## Q5
It would throw an error as i is of let type and it is outside of the scope of the for loop where i is defined.

## Q6
It would throw an error as discountedPrice is of let scope which is of the for loop

## Q7
150 as finalPrice is a let which is initialized at a function level scope. The last value pushed into disocunted is the value finalPrice is currently holding which is 150

## Q8
[50,100,150] as disocunted is created on a function level scope and the values pushed into it are 50, 100 and 150 based on the calculation of final price in the for loop

## Q9
Error as i is defined in a for loop level scope and outside the for loop it doesnt exist so it would throw an error

## Q10
3 as we are creating and intitializing length for the length of prices which is 3 in this case

## Q11
[50,100,150] as even if discount is defined as a const, it is a list datatype and we are not modifing it as we go. So, it just stores the values.

## Q12
### A 
student.name

### B
student['Grad Year']

### C
student.greeting()

### D
student['Favorite Teacher'].name

### E
student['courseLoad'][0]


## Q13
### A
'32' as 3 is a string, it considers 2 as a string as well and concatenated

### B
1 as it converts '3' to 3 and perform the operation which yields 1

### C
3 null maps to 0 so 3 + 0  = 3

### D
'3null' uses null as string and concatenated

### E
4 maps true to 1 and 1+3 = 4

### F
0 false maps to 0 and null to 0 so yields 0

### G
'3undefined' underfined is considered as a string and concatenated

### H
NaN undefined doesn't map to any number so it yields NaN

## Q14
### A
true as it converts '2' to number and checks

### B
false as it is comparing '2' and '1'

### C
true as string gets converted to number

### D
false as === uses data type also in comparison and datatype are not same

### E
false as true gets mapped to 0 and 0 != 2

### F
true as Boolean(2) = true which is equal to true

## Q15
== does type conversion while doing comparisona nd === doesn't do type comparison and compares taking data types into account as well

## Q17
[2,4,6] as in every iteration we are calling the callback function which is mutiplying each number by 2 so [1,2,3] = [2,4,6]

## Q19
output :
1<br>
4 <br>
3<br>
2<br>

