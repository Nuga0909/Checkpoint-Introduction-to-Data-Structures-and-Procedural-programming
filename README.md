# Checkpoint-Introduction-to-Data-Structures-and-Procedural-programming

## Checkpoint Objective
At this checkpoint you are asked to write an algorithm that fulfills the following description:

## Description:

### Problem 1 
Given two sets of elements, find the sum of all distinct elements from the set. In other words, find the sum of all elements which are present in either of the given set.
Example:
Set 1 : [3, 1, 7, 9], Set 2: [2, 4, 1, 9, 3]
Output: 13 (distinct elements 4, 7, 2 )
Give a solutions to this problem, using arrays

 
### Problem 2 
You are asked to write an algorithm that fulfill the following: 

Name: Dot product
Description:
Write a procedure, called dot_product which calculates in the variable ps, the dot(scalar) product of v1 and v2 (v1 and v2 are vectors of IR)
Write an algorithm which determines, for n pairs of given vectors, whether two vectors of given IR are orthogonal, by calling the procedure defined in the previous question. The dot product of two orthogonal vectors is zero.
Modify the previous algorithm if you use a dot_product function instead of a procedure.


## Instructions
Problem 1
Solution  with an array.

Initialize sum = 0. 
Compare each element of set one with the second set and if element is not present then add that element to sum. 
Then do the vice versa to add elements from the second set.

Problem 2
While creating your algorithm, you should: 

Use array for presenting the vector.
Use nested loop (a loop inside another if you want)
Use different types of passing parameters
