# Lec1. The Geometry og Linear Equations

MIT 18.06 Gilbert Strange, Linear Algebra, Spring 2005

This doucment is edited by Steve Ive based on Youtube Lecture.

Following script is described as the Gilbert Strangs' speech.


---

## Row Pictures, Matrix Form, and the *Column Picture

The fundamental problem of Linear Algebra, which is to solve a system of linear equations.

So let's start with a case when we have some number of equations, say

- n equations
- n unkowns

So an equal number of equations and unknowns. That's the normal, nice case.

What I want to do is to describe, first what I call the **Row Picture**.

---

#### Row Picture

It's a picture of one equation at a time. It's the picture you've seen before in two by two equations where lines meet. So, in a minuite, you'll see lines meeting.

#### *Columnn Picture

The second picture, I'll put a star beside that, because that's such an important one. And maybe new to you is the picture, **a column at a time**. And those are the rows and columns of a matrix. 

#### Matrix Form

So the third, the algebra way to look at the problem is the matrix form an using a matrix that I'll call A.

---

So let's go with an example.

### Two eqautions, two unknowns.

> 2x - y = 0

> -x + 2y = 3

What's the matrix, that is what's the coefficient matrix of upon?

The matrix that involves those numbers, a matrix is ***just a rectangular array of numbers.*** Here it's two rows and two columns, so 2 and -1 in the first row, -1 and 2 in the second row, that's the matrix. 

And the right-hand, there are two unknowns. So we've got a **vector**, with two components, x and y, and we've got two right-hand sides that go into a vector [0, 3].


matrix picture.

### [2 -1]
### [1  2]



I couldn't resist writing the matrix form, right even before the pictures.

So I always will think of this as the matrix A (the matrix of coefficients), then there's a vector of unknowns. Here we've got only two unknowns. Later we'll have any number of unknowns. And that vector of unknowns, well'll often make that X. And the right-hand side is also a vector that I'll always call b.


So linear eqautions are **AX = b** and the idea now is to solve this particular example, and then step back to see the **bigger picture**.

---

Okay, what's the picture for this example, the **Row Picture**?

### Row Picture

Row picture means that I take one row at a time, and I'm drawing here the xy plane and I'm going to plot all the points that satisfy that first equation. 


plane


So'm looking at all the points that satisfy 2x-y = 0.

It's often good to start with which point on the horizontal line. On the horizontal line, y is zero. The x axis has y as zero, and that in this case, actually, then x is zero.

origin picture plane

So the point, the origin - the point with coordinates (0,0) is on the line. It solves that equation. 

Another point that solves this same equation, let me suppose x is 1, and y should be 2. 