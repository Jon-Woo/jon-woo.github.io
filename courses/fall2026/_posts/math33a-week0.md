# Math 33A Week 0: Solving Systems of Linear Equations

### Linear equations
Let's start super basic with a single linear equation.

>[!note] Linear Equations
> Two variables: $ax+by=c$
> Three variables: $ax+by+cz=d$
> $n$ variables: $a_1x_1 + \cdots a_nx_n = b$

In two variables, the equation represents a line, that is solutions to the equation form a line. It is equivalent to the $y=mx+b$ form.

In three variables, the equation represents a plane. This is where the physical imagery ends, but the geometric intuition can extend to arbitrary number of variables.

The number on the right hand side (RHS) of these equations contain information about the displacement of the line/plane. For example, if the RHS is zero, then the line/plane contains the origin.


### Linear Systems

We can combine linear equations to form a systems of linear equations.

> [!note] Linear System 
> A **linear system** in $n$ variables and $m$ unknowns is a collection of $m$ linear equations, each with $n$ variables:
> $$\begin{align*}a_{11}x_1 + &\cdots + a_{1n}x_n = b_1\\ &\;\;\;\vdots \\ a_{m1}x_1 + &\cdots + a_{mn}x_n = b_m
\end{align*}$$

The solution to a linear system in $n$ variables is a point $(x_1,\dots, x_n)$ which satisfies every equation in the system. 

> [!example] Example in 2 variables
> $(1,2)$ is a solution to $$\begin{align*}6x-3y=0 \\ x+y =3\end{align*}$$

The geometric interpretation is that a system of $m$ equations is the intersection of $m$ different lines/planes. Depending on how these lines/planes intersect, we can have different number of solutions.

### Number of solutions to a linear system

* **No solutions**: If the lines/planes do not have a common intersection point, then we will have no solutions.
![Three planes with no common intersection](0soln.png)
* **Exactly one solution**: If the lines/planes all intersect in a single point, then we will only have one solution.
![Three planes with single point of intersection](1soln.png)
* **Infinitely many solutions**: If the lines/planes intersect in a line, plane, etc., then we will have infinitely many solutions.
![Three planes intersecting in a line](infsoln.png)

> [!Question] Why can't we have many solutions but not infinitely many?
> We will learn through the study of linear algebra why this is the case. For a direct answer, think about how we can get new solutions from existing ones, which will contradict finiteness of solutions. Hint: is the average of two solutions a solution?


