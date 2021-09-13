 # Lec 1. Multiplication and Inverse Matrices

## Linear Algebra, Gilbert Strang. MIT Lecture 2005 Spring

## Edited By Steve Ive
This article is based on Gilbert Strang's lecture script. The article will be described according to the flow of the lecture.

---

I've been multilplying matrices already, but certainly time for me to discuss the rules for matrix multiplication. The interesting part is there are many ways you can do it, and they all give the same answers and they are all important.


---

### The Things we are going to cover this lecture

#### Matrix Multiplication

#### Inverse

---

## How to multiply two matrices

### First way

The first way is a standard rule that people think of multiplying matrices.

![](./imgs/lec3/3-1.svg)

---

### Second Way

The other way of looking at whole columns and whole rows.

![](./imgs/lec3/3-2.svg)

- matrix times first column produces first column of C.
- matrix times second column produces second column of C.

#### Columns of C are combinations of columns of A

You can just think of having several columns multiplying by A and getting the columns of the answer.

---

### Third way

The third way is looking at it by rows.

![](./imgs/lec3/3-3.svg)

#### Rows of C are combinations of rows of B.

---

### 4th Way (***Important***)

#### Columns x rows

Ther regular way was row x columns and it gaves a number.

> now I want to ask column x rows.

#### Column of A (m x 1) x Row of B (1 x p) = m x p

![](./imgs/lec3/3-4.svg)

- columns of matrix is multiplying of ![](./imgs/lec3/234.svg)

- rows of matrix is multiples of ![](./imgs/lec3/16.svg)

#### AB = sum of (cols of A) x (rows of B)

![](./imgs/lec3/3-5.svg)

> The row space, which is like all the combinations of the rows is just a line for this matrix. The row space is the line through the vector ![](./img/lec3/16.svg). All the rows lie on that line.

> The column space is also a line. All the columns space is also a line. All the columns lie on the line through the ![](./img/lec3/234.svg)

---

### Block Multiplication

![](./imgs/lec3/3-6.svg)

#### All 5 ways we're doing the same multiplication