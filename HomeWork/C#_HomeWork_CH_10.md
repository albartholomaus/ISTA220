# **Turn in:** **C#_HomeWork_CH_10**
### **Name:** *Anthony Bartholomaus*
### Professor: *Mr. Carter*

1.  ##### What does an array look like in memory?
- *reference types, refers to a contiguous block in memory.*
---
2.  ##### Where is memory allocated to hold an array, on the stack or on the heap?
- *On the heap.*
---
3.  ##### Where is memory allocated to hold an array reference, on the stack or on the heap?
- *on the stack, memory is not allocated for the object until you create the instance by using new.*
---
4.  ##### Can an array hold values of different types? This is a trick question, the answer is, “It depends.” What determines the types that an array can hold?
- *it is determined at runtime if it needs to.*
---
5.  ##### Describe the syntax of the condition for a foreach loop.
- *it describes the iteration variable and the type.*
---
6.  ##### How do you make a deep copy of a array?
- *make 2 arrays of identical length, then use a for loop to copy the contents.*
---
7.  ##### What is the difference in the syntax between a multi-dimensional array and an array of arrays?
- *The difference in syntax is that I multi dimensional arrays are packed where jagged arrays need more elements to the code.*
---
8.  ##### What is the difference in the uses for a multi-dimensional array and an array of arrays? In other words, what determines whether you would use one as opposed to the other?
- *.*
---
9.  ##### How do you “flatten” a multidimensional array? In other words, take something that looks like a 1 2 3 matrix 4 5 6 and turn it into an array [1, 2, 3, 4, 5, 6, 7, 8, 9]? Write the code to do this in English.
- *step 1: We access the 2D array's total element count—the Length property on a 2D returns this value.
Step 2: We copy the 2D array elements into a 1D array. We loop over each dimension.*
---
10. ##### (Thought question) When we use a for loop, we can change the values of the array elements inside the loop. When we use a foreach loop, we cannot change the values of the array elements inside the loop. Why not? How is for different from foreach?
- *foreach is read only .*
---
