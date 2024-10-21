# Part 1: Quadratics



At this point in your math career, I'm sure you've seen **the quadratic formula:** $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$  
It is a way of discovering the zeros of a quadratic. But did you know that **you can also use it to find the vertex**?

#### Vertex Formula
The $\frac{-b}{2a}$ portion of the quadratic formula provides us with the x-value of the vertex!  
From there we just need to plug the x-value of the vertex into the quadratic itself to get the y-value!

**Example:**
```Math
y = -2x^2 + 10x - 9
\\\text{The x-value of the vertex is: }\,x=\frac{-(10)}{2(-2)}
\\x=2.5
\\\text{}
\\\text{Plug } x=2.5 \text{ into the equation:}
\\\begin{aligned}
\\y&=-2(2.5)^2+10(2.5)-9
\\y&=-2(6.25)+25 - 9
\\y&=3.5
\end{aligned}
\\\text{}
\\\text{So the vertex is at } (2.5, 3.5)
```

The majority of [the HTML](../index.html) has been completed for you, along with the skeleton [JavaScript functions](../main.js).

### Your Job:

Make it so that the input boxes for `a`, `b`, and `c` are used and:
1. When a user clicks `Find the Zeros`, the quadratic formula is used to calculate the zeros and displays them _neatly_ in the `<div>` with id `quadratic_output`. Print the output to the console as well.
2. When a user clicks `Find the Vertex`, the vertex is discovered and displayed _neatly_ in the `<div>` with id `quadratic_output`. Print the output to the console as well.

**Your outputs should always be rounded to the number of decimals selected in the `rounding` input box.**

---

#### Back to the [README](./README.md)