## part2-question1:
Line 12 will output:

3

Variables defined by var are accessible throughout the whole function so i can be accessed after the for loop ends and be printed.

## part2-question2:
Line 13 will output:

150

Variables defined by var are accessible throughout the whole function so discountedPrice can be accessed after the for loop ends and be printed. It is calculated as prices[i] * (1 - discount) so it will be 300 * (1-0.5) = 150
## part2-question3:
Line 14 will output:

150

Variables defined by var are accessible throughout the whole function so finalPrice can be accessed after the for loop ends and be printed. It is calculated as Math.round(discountedPrice * 100) / 100; so it will be Math.round(150 * 100) / 100 = 150
## part2-question4:
It returns the discounted array which is [ 50, 100, 150 ]. All the prices passed a parameter to the function have been decreased by 50%, rounded and pushed to the discounted array. 
## part2-question5:
This causes a ReferenceError since i was declared using let, which is block scoped, in the for loop. Once the for loop is exited the scope of i ends and if we try to access it we will get an error which is what happened here.
## part2-question6:
This causes a ReferenceError since discountedPrice was declared using let, which is block scoped, in the for loop. Once the for loop is exited the scope of discountedPrice ends and if we try to access it we will get an error which is what happened here.
## part2-question7:
The output of line 14:

150

Since finalPrice was declared outside the loop using let, it has the scope of the entire function and can be accessed from anywhere within the function.
## part2-question8:
It returns the discounted array which is [ 50, 100, 150 ]. All the prices passed a parameter to the function have been decreased by 50%, rounded and pushed to the discounted array. 
## part2-question9:
This causes a ReferenceError since i was declared using let, which is block scoped, in the for loop. Once the for loop is exited the scope of i ends and if we try to access it we will get an error which is what happened here.
## part2-question10:
The output of line 12 is

3

While const variables are also block scoped, length was declared outside of the loop so it can be accessed within the function. It prints the number of prices which is 3.
## part2-question11:
It returns the discounted array which is [ 50, 100, 150 ]. All the prices passed a parameter to the function have been decreased by 50%, rounded and pushed to the discounted array.
## part2-question12:
A. student.name

B. student["Grad Year"]

C. student.greeting()

D. student["Favorite Teacher"].name

E. student.courseLoad[0]
## part2-question13:
A. '3' + 2

Output: '32'

Explanation: 2 mapped to its exact string representation and concatenated with 3

B. '3' - 2

Output: 1

Explanation: Here 3 mapped to its exact int representation as subtraction only works for numbers

C. 3 + null

Output: 3

Explanation: null is treated as a 0 so 3 + 0 = 3

D. '3' + null

Output: '3null'

Explanation: null mapped to its exact string representation and concatenated with 3

E. true + 3

Output: 4

Explanation: since true maps to 1, 1 + 3 = 4

F. false + null

Output: 0

Explanation: both false and null map to 0 so it will be 0 + 0 = 0

G. '3' + undefined

Output: '3undefined'

Explanation: undefined mapped to its exact string representation and concatenated with 3

H. '3' - undefined

Output: NaN

Explanation: undefined maps to NaN during subtraction

## part2-question14:
A. '2' > 1

Output: true

Explanation: 2 mapped to its exact number representation and 2 > 1 is true

B. '2' < '12'

Output: false

Explanation: each charachter in a string is compared and '2' is greater than '1' which is what gets compared first. Since that is false the output is false

C. 2 == '2'

Output: true

Explanation: 2 mapped to its exact string representation as == operator allows type coercion

D. 2 === '2'

Output: false

Explanation: both value and type is checked and the types do not match

E. true == 2

Output: false

Explanation: true maps to 1 which is not equivilant to 2

F. true === Boolean(2)

Output: true

Explanation: Boolean(2) is true so both sides have the same value and type
## part2-question15:
=== operator compares values without type conversion and checks both the value and type while == operator compares values after type coercion
## part2-question16:
JS file named part2-question16.js has been added to the expose/javascript directory
## part2-question17:
The output will be [ 2, 4, 6 ]. The doSomething function multiplies each of the numbers with 2 and the modifyArray function applies that function to all the elements in the array.
## part2-question18:
JS file named part2-question18.js has been added to the expose/javascript directory
## part2-question19:
Output:
1
4
3
2

1 prints first, then 4 immediately. 3 prints after the zero delay timeout, and 2 prints last after 1 second.