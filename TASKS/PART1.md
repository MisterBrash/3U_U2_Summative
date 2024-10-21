# Part 1: Quadratics

At this point in your math career, I'm sure you've seen **the quadratic formula:** $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$  
It is a way of discovering the zeros of a parabola. But did you know that you can also use it to find the **vertex**?

### Preamble - Vertex Formula
The $\frac{-b}{2a}$ portion of the quadratic formula provides us with the $x$-value of the vertex!  
From there we just need to plug-in the $x$-value of the vertex to the quadratic itself to get the $y$-value!

**Example:**

$$
\begin{gather*}
y = -2x^2 + 10x - 9\\
\text{The x-value of the vertex is: }x=\frac{-(10)}{2(-2)}\\
x=2.5\\
\text{Plug } x=2.5 \text{ into the equation:}\\
\end{gather*}
$$
$$
\begin{aligned}
y&=-2(2.5)^2+10(2.5)-9\\
y&=-2(6.25)+25 - 9\\
y&=3.5\\
\end{aligned}
$$
$$
\begin{gather*}
\therefore\text{ the vertex is at } (2.5, 3.5)
\end{gather*}
$$



### Your Job:

The majority of [the HTML](../index.html) has been completed for you, along with some skeleton [JavaScript functions](../main.js).

### JavaScript:
1. The input box `rounding` will contain how many decimals the user wants for anwers. We will use this a lot, so we should make a function to help ourselves. Create the function `round_user(value)` which takes the `value` and rounds it to the user's request number of decimals, _returning_ the answer.  
For example, if the user has `4` in the `rounding` input box and we call `round_user(Math.PI)` we _get back_ `3.1416`.  

2. Create the function `y_quad(a, b, c, x)` which takes the coefficients `a`, `b`, and `c` for a standard form quadratic along with a value for `x` and _return_ the value for `y`, not rounded.  
For example:  `y_quad(-1, 2, 3, 5)` is equal to $y=-1x^2+2x+3$ where $x=5$ such that $y=-1(5)^2+2(5)+3$ and the answer is $-12$ so your function should return `-12`.

### HTML:

Make it so that the input boxes for `a`, `b`, and `c` are used and:

3. When a user clicks `Find the Zeros`, the quadratic formula is used to calculate the zeros and displays them _neatly_ in the `<div>` with the id `quadratic_output`. Print the output to the console as well. Round values to the selected number of decimals in the `rounding` input box.  

4. When a user clicks `Find the Vertex`, the vertex is discovered and displayed _neatly_ in the `<div>` with the id `quadratic_output`. Print the output to the console as well. Round values to the selected number of decimals in the `rounding` input box.  
If done correctly, you should use your `y_quad()` function from #2 above. **Note** if you were unsuccessful in creating the `y_quad` function, then complete this _without_ using it.  

<br>

---

#### Table of Contents
- [README](../README.md)
- [Part 2: Geometry Functions](./PART2.md)  
- [Part 3: Extra](./PART3.md)
