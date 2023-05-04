Download Link: https://assignmentchef.com/product/solved-cs52-assignment-3-pointers-arrays-strings-recursion-files
<br>



<ol>

 <li>Write a comment at the top that contains the following information</li>

</ol>

<h2>// Your Name // CS 52 // Assignment #3</h2>

<ol start="2">

 <li>Properly indent, format and comment your code as necessary</li>

 <li>Problem 1                               Matrix</li>

</ol>

Create a 5×5 matrix of int values as shown below. Write a program that finds the minimum, maximum, and average value of all values in the matrix. Create a function for each value that is computed (max, min, avg).  Print out the results (limit the average to two decimal points!).

Matrix: [ 7, 2, 10, 3, 6],

[ 1, 12, 2, 0, 20],

[ 3,14,19, 5, 4],

[ 6, 0, 17, 18, 8],

[ 1, 13, 10, 9, 11];

Example: Min: 0, Max: 20, Avg: 8.04

Problem 2                               Dynamically Allocated Arrays

Write a program that dynamically allocates an array based on a size determined by the user. You must declare the array as a pointer to get full credit! The program then uses a pointer to initialize each element in the array with a value that is also entered by a user. Finally, sort the array and print it to the console.




<table width="624">

 <tbody>

  <tr>

   <td rowspan="2" width="288">Example:Enter a size: <strong>5</strong>Item 1: <strong>3</strong>Item 2: <strong>8</strong>Item 3: <strong>5</strong>Item 4: <strong>2</strong>Item 5: <strong>9</strong>Sorted: 2, 3, 5, 8, 9</td>

   <td colspan="2" width="336">Example 2:</td>

  </tr>

  <tr>

   <td width="48">   </td>

   <td width="288">Enter a size: <strong>3</strong> Item 1: <strong>15 </strong>Item 2: <strong>3</strong>Item 3: <strong>7</strong>Sorted: 3, 7, 15</td>

  </tr>

  <tr>

   <td width="288"> </td>

   <td width="48"> </td>

   <td width="288">1</td>

  </tr>

 </tbody>

</table>

Santa                                                                                       Monica                                                                                       College

CS                                                                                            52                                                                                             –                                                                                          C++                                                                                 Programming

Problem 3                               First Non-repeated char

<strong> </strong>Write a program that prompts the user for a string (the string may consist of multiple words). Implement a function that finds and returns the first non-repeated <em>char</em> in the string. The program calls the function and prints out the returned <em>char</em>.

<strong> </strong>Problem 4                               Count Chars In File

<strong> </strong>Write a program that counts the number of upper case letters, lower case letters, digits, spaces, and any other chars in a file. The program prompts the user to enter a file name (including file path). The program then opens the file and counts each of the before mentioned categories, then prints the output.

Hint:

<ul>

 <li>Use the        library  #include&lt;fstream&gt;</li>

 <li>Create a variable             of          type      ifstream              with      the        file        name   passed in           as              argument,        g.       ifstream myFile(filename);</li>

 <li>Use getline(cin, string);  function            to              read     an         entire   line       including              whitespace</li>

</ul>




Example:

Enter a file: <strong>/Users/kalisch/Desktop/sample.txt </strong>

File contains

Lowercase letters: 1938

Uppercase letters: 128

Digits: 17

Spaces: 35


