 # Lec 1. Multiplication and Inverse Matrices

## Linear Algebra, Gilbert Strang. MIT Lecture 2005 Spring

## Edited By Steve Ive
This article is based on Gilbert Strang's lecture script. The article will be described according to the flow of the lecture.

---

I've been multilplying matrices already, but certainly time for me to discuss the rules for matrix multiplication. The interesting part is there are many ways you can do it, and they all give the same answers and they are all important.


---


## Matrix Multiplication

I'll begin with how to multiply two matrices. 
 
First way, okay, so suppose that I have a matrix A, multiplying a matrix B and giving me a result a matrix C.



<a href="https://www.codecogs.com/eqnedit.php?latex=\fn_phv&space;{\color{Cyan}&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\end{bmatrix}\cdot&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\end{bmatrix}=&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\end{bmatrix}}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\fn_phv&space;{\color{Cyan}&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\end{bmatrix}\cdot&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\end{bmatrix}=&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\end{bmatrix}}" title="{\color{Cyan} \begin{bmatrix} & & & \\ & & & \\ & & & \\ & & & \end{bmatrix}\cdot \begin{bmatrix} & & & \\ & & & \\ & & & \\ & & & \end{bmatrix}= \begin{bmatrix} & & & \\ & & & \\ & & & \\ & & & \end{bmatrix}}" /></a>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; A &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  B &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  C = AB


So, let me just review the rule for this entry.

<a href="https://www.codecogs.com/eqnedit.php?latex={\color{Cyan}&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\end{bmatrix}\cdot&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&C_i_j&space;\\&space;&&space;&&space;&&space;\end{bmatrix}=&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\end{bmatrix}}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?{\color{Cyan}&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\end{bmatrix}\cdot&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&C_i_j&space;\\&space;&&space;&&space;&&space;\end{bmatrix}=&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\end{bmatrix}}" title="{\color{Cyan} \begin{bmatrix} & & & \\ & & & \\ & & & \\ & & & \end{bmatrix}\cdot \begin{bmatrix} & & & \\ & & & \\ & & &C_i_j \\ & & & \end{bmatrix}= \begin{bmatrix} & & & \\ & & & \\ & & & \\ & & & \end{bmatrix}}" /></a>

That's the entry in row i and column j. So, that's the i j entry. The <a href="https://www.codecogs.com/eqnedit.php?latex={\color{Cyan}&space;C_i_j}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?{\color{Cyan}&space;C_i_j}" title="{\color{Cyan} C_i_j}" /></a>.

We always write the row number and then column number. 

So maybe I take it <a href="https://www.codecogs.com/eqnedit.php?latex={\color{Cyan}&space;C_3_4}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?{\color{Cyan}&space;C_3_4}" title="{\color{Cyan} C_3_4}" /></a>, just to make it specific.

<a href="https://www.codecogs.com/eqnedit.php?latex={\color{Cyan}&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\end{bmatrix}\cdot&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&C_3_4&space;\\&space;&&space;&&space;&&space;\end{bmatrix}=&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\end{bmatrix}}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?{\color{Cyan}&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\end{bmatrix}\cdot&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&C_3_4&space;\\&space;&&space;&&space;&&space;\end{bmatrix}=&space;\begin{bmatrix}&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\\&space;&&space;&&space;&&space;\end{bmatrix}}" title="{\color{Cyan} \begin{bmatrix} & & & \\ & & & \\ & & & \\ & & & \end{bmatrix}\cdot \begin{bmatrix} & & & \\ & & & \\ & & &C_3_4 \\ & & & \end{bmatrix}= \begin{bmatrix} & & & \\ & & & \\ & & & \\ & & & \end{bmatrix}}" /></a>

So where does this come from, The <a href="https://www.codecogs.com/eqnedit.php?latex={\color{Cyan}&space;C_3_4}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?{\color{Cyan}&space;C_3_4}" title="{\color{Cyan} C_3_4}" /></a> entry?

It comes from row 3, and column 4 as you know. Let just write down the formula for it.

<a href="https://www.codecogs.com/eqnedit.php?latex={\color{Cyan}&space;C_3_4}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?{\color{Cyan}&space;C_3_4}" title="{\color{Cyan} C_3_4}" /></a> = (row 3 of A) <a href="https://www.codecogs.com/eqnedit.php?latex={\color{Cyan}&space;\cdot&space;}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?{\color{Cyan}&space;\cdot&space;}" title="{\color{Cyan} \cdot }" /></a> (Column 4 of B)

If we look at the whole row and the whole column, the quick way for us to say it is row 3 of A, I can use dot product (I won't often use that, actually) Dot column 4 of B.

But this gives us a chance to just like, use a little matrix notation.

What are the entries? What's the first entry in row three?