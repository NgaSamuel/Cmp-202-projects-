Array Rotation
Description

This Java exercise rotates the elements in an array.

Group Members/Contributors
Hanior Nabem Nathaniel - BHU/22/04/09/0074
Ezekiel Oyidih - BHU/22/04/05/0026
Ngakilahyel Samuel - BHU/22/04/10/0019
Caleb Joshua Fuojima - BHU/22/04/05/0018
Precious Oguntuase Toluwalope - BHU/22/04/05/0070
Method

A left rotation operation on an array shifts each of the array elements 1 unit to the left. More details in question.txt

Algorithm

Define the function rotLeft and pass int 'a' and int 'd' as parameters with an integer array as a return type.
Initialize a variable 'n_elements' to store the length of array 'a'.
Create a new integer array 'rot' with the same length as array 'a'.
Loop through the original array 'a';
Calculate the index for the rotated array ('rot') using the formula '(i + (n_elements - d)) % n_elements'.
Assign the value of 'a[i]' to the calculated index in the rotated array.
End the loop.
