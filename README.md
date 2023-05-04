Download Link: https://assignmentchef.com/product/solved-csci321-project-eight-greatest-common-divisor
<br>
<strong>Objectives</strong>

<ol>

 <li>Implement Euclidean algorithm to find Greatest Common Divisor</li>

 <li>Implement Euclidean algorithm using Recursive thinking</li>

 <li>Apply loop</li>

 <li>Apply recursive thinking</li>

 <li>Apply Irvine32.inc library</li>

 <li>Write user defined procedure and call user defined procedure</li>

</ol>

<strong>Problem Description:</strong>

The greatest common divisor (GCD) of two integers is the largest integer that will evenly divide both integers. The GCD algorithm involves integer division in a loop, described by the following pseudocode:

int GCD (int x, int y){

x = abs(x)    // absolute value

y = abs(y)

do{

int n = x % y

x = y

y = n

}while (y &gt; 0)

return x

}

Implement this function in assembly language. Then go online find its recursive version and implement it in assembly language too. Then write a test program that calls your two GCD procedure five times each, using the following pairs of integers (5, 20), (24, 18)_, (11, 7), (432, 226), and (26, 13). After each procedure call, display the GCD




You may refer to Programming Exercise #6 on page 285 and Programming Exercise #7 on page 350.




<strong>Sample Run:</strong>




Due Date:

Turn in YourNameProj8.asm via Blackboard. Due date will be announce on Blackboard.