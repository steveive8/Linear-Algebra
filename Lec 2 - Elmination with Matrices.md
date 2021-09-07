# Lec 2.Elimination with Matrices

## Linear Algebra, Gilbert Strang. MIT Lecture 2005 Spring

## Edited By Steve Ive
This article is based on Gilbert Strang's lecture script. The article will be described according to the flow of the lecture.

---

Today on the Lecture, we are going to solve a system of equations with the method called 'Elimination'. The Elimination method is a way many computer package solve the equations, and well, if it succeeds, it gets the answer. Otherwise, we could fail to elimination and fail to find the answer. So we are going to talk about when the elimination succeed or fail. Also, to complete the answer, there's an obvious step called "back substitution". The part that I want to show you is the elimination expressed in matrix language, and one of the operations, of course, that we'll meet is how do we multiply matrices and why. So, let's dive in it with example.

---

### The Things we are going to cover this lecture

#### Elimination

- When the Elimination success

- When the Elimination fail

#### Back-Substitution

#### Elimination Matrices

#### Matrix Multiplication

---

Okay, so there's a system of equations. Three equations and three unknowns. 

![](./imgs/lec2/2-1.svg)

![](./imgs/lec2/2.svg)

![](./imgs/lec2/3.svg)

---

And there's the matrix, the three by three matrix.

![](./imgs/lec2/4.svg)

So this is the system Ax = b.

This is our system to solve, Ax equal the right-hand side is that vector 2, 12, 2. Okay.

## Elimination

Now, when I describe elimination, it gets to be a pain to keep writing the equal signs and the pluses and so on.

It's that matrix that totally matters. Everything is in that matrix. But behind it is those equations.

So what does elimination do? What's the first step of elimination?

![](./imgs/lec2/2-1.svg)

We accept the first equation, it's okay.

I'm going to multiply that equation by the right number, the right multiplier and I'm going to subtract it from the second equation.

With what purpose? So that will decide what the multiplier should be.

![](./imgs/lec2/29.svg)

![](./imgs/lec2/30.svg)
