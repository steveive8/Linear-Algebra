# Lec 1. The Geometry of Linear Eqautions

## Linear Algebra, Gilbert Strang. MIT Lecture 2005 Spring

## Edited By Steve Ive
This article is based on Gilbert Strang's lecture script. The article will be described according to the flow of the lecture.

---

What's in the first lecture? The fundamental problem of linear algebra, which is to solve a system of linear equations. So Let's start with a case when we have some numbers of equations, say **n equations and n unknowns**. So the equal number of equations and unknowns. That's the normal nice case. And what I want to do is with examples, of course to describe, first, what I call the **Row picture**. That's the picture of one equation at a time. It's the picture you'be seen before in two by two equations where lines meet. So in a minute, you'll see lines meeting. 

The second picture, I'll put a star beside that, because that's such an important one. And maybe new to you is the picture -- a column at a time, the **Column Picture**. And those are the rows and columns of a matrix.

So the third -- the algebra way to look at the problem is the **matrix form** and using a matrix that I'll call A.

The core of the thing is that we will see through problem with the new sight of **Column Picture** which is the ***linear combination*** of the columns of matrix.

---

### The Things we are going to cover this lecture

#### The pictures of how to see the problem.

- Row Picture

- **Column Picture**

- Matrix Form

#### Can I solve Ax = b for every b? 
(every b means the all the bs in three dimentional space)

- Singular, non-Singular

#### The way of matrix mulitplication

- Row picture: The Dot Product

- Column Picture: **The Linear Combination**.


So, let's take an example.

---

## 2 equations, 2 unknowns

![](./imgs/lec1/2x-y=0.svg)

![](./imgs/lec1/-x+2y=3.svg)

At above, we can see the problem that consists two equations and two unknowns.

**Before the picture of it**, Let just first describe this as matrix form.

![](./imgs/lec1/2by2.svg)

Anyway what is the matrix though?

The matrix is **just a rectangular array of numbers.**

Here, we have the coefficient matrix on the left side, We'll call it ***A***.

Also, we have the vector that contains two components, the unknowns x, y. We will call this as ***X***.

On the right side hand, we have the vector that contains 0 and 3. And we will call this as ***b***

So, We can describe this though.

![](./imgs/lec1/ax=b.svg)

So the linear equations are now the form of ***AX = b***.

The idea now, is that to solve this particular problem, and then step back to see the bigger picture. 

Okay. What's the picture for this example, the Row Picture?


## Row Picture

Okay, so here comes the Row picture. 

The Row Picture means that I **take one row at a time**. It means that we will focus on the row of the matrix, which also mean that we foucs on one equation at a time.

So let's dive in to this two equations and let's find some points that satisfy those equations.

**Equation 1**

![](./imgs/lec1/2x-y=0.svg)

**Equation 2**

![](./imgs/lec1/-x+2y=3.svg)

The points that satisfying the equation 1.

- x = 0, y = 0
- x = 1, y = 2

The points that satisfying the equation 1.

- x = -1, y = 1
- x = -3, y = 0

So there's the points that solve these equation and I could put in more points. But, let me put in all the points at once, because they all lie on a straight line.

![](./imgs/lec1/graph2.svg)

As above, the point that lies both lines is the important thing, the solution.

**Solution**
- x = 1, y= 2

So, the first thing we've done for n equal 2, two equations and two unknowns, we've seen the row picture and it's the right place to start.

Okay. We've got the solution that the point that lies on both lines.

Now can I come to the column picture?

Pay attention, this is the key point.

So the column picture.

## Column Picture

I'm now going to look at the columns of the matrix.

We can describe the problem the combination of the columns. And we call it the ***Linear Combination***.

![](./imgs/lec1/columnpicture.svg)

And it's the most fundamental operation in the whole course.

**It's a linear combination of the columns.**

The thing we are going to do is just find appropriate x and y to produce the right right-hand side vector, the [0,3].

So let's go to the geometry of this.

![](./imgs/lec1/graph3.svg)

As above, we can describe the two columns.

By **Linear Combination**, we will solve this by multiplying some appropriate numbers to these columns, and adding it.

![](./imgs/lec1/graph4.svg)

As above, we can get the right answer, the b of [0,3] by multiplying and adding two columns.

So, now, we can think about can we get all the xs and ys to all the bs in the 2-dimension?

It means, that, can we get the result of xs and ys that can pointing all the points in this 2-dimension?

It is important to think that. We will cover that later.

So, Let's go to the next example, the 3 equations, and 3 unknowns.

## 3 equations, 3 unknowns

![](./imgs/lec1/graph5.svg)

![](./imgs/lec1/graph6.svg)


