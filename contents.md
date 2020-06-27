Arrays
Objects
Bracket Notation
Dot Notation ----- To access the properties of an object.
property add,update,delete in both notations
Anonymous fn can add to the key.
has own property.

Array is an object.
Array methods---push,pop,slice,shift,unshift,indexof,splice


adding elements:
  1. push
2. splice

finding elements(Primitive types)
1.indexof()   returns -1 if the element is not there
3.lastIndexof()
2.includes()  returns false, if the element is not there.
REFEReNCE elements
1.includes
how to find object in an array
1.find()        expects fn as an argument and calls the fn for each element in the fn and returns the value if its get true otherwise it returns undefined.
2. findIndex() method

arrow fn ni oka variable ki assign cheskovachu.
( )=>{ }     --------anonymus fn shorthand(arrow fn)
function( ){ }  --------anonymus fn

let a=()=>{} ---- fn expression

predicate fn / callback fn


removing elements:
1. pop()
2. shift()
3. splice()

emptying an array:
1. numbers=[]
2. array.length=0
3. splice()
4. pop()   ///not recommended as it takes more time if there is many elements.

Memory Management:
1. malloc()
2. free()

combining arrays:
1. concat
if elements in an array are values like 1,2,3... then the values will be copied.
if elements in an array are objects like [{a:1},[0.1]]... then the references will be copied.
2. splice()
3. spread operator
slice will copy the same array with different references;

a) Combining Arrays
b) Slicing an Array
c) The Spread System




ITERATING AN ARRAY:
1. for of
2. for in
3. forEach(number,index) method

JOINING ARRAYS:
1. join() method     ///array to string

how to split a string to produce an array:
1. split() method ---- str to array    //// string method


SORTING  ARRAYS:
1. sort( )----- comparision btwn strings.
2. arr.sort(comparefn) ----- comparision btwn numeric values.

TESTING THE ELEMENTS OF AN ARRAY:
1. every() method  accepts a fn as argument
2. some() method 

FILTERING AN ARRAY:
1. filter() 
2. Mapping an array

REDUCING AN ARRAY:

1. Reduce()



further course:
objects
forms
events
asynchronous & synchronous events
node js
animations using js
react js
event loops
 
