# Part 2: Geometry Functions

### JavaScript:

1. In mathematics the term Delta (∆) means _difference_. Create a JavaScript function `delta(a, b)` which _returns_ the value of `a - b`.  

2. Slope of a line is calculated as $m= {\Delta{y} \over \Delta{x}}$. Create the function `slope(x1, y1, x2, y2)` which receives the points (x1, y1), (x2, y2) and _returns_ the slope. Do not round the result.
You must use your `delta` function from #1 for this.

3. The average of two numbers is as simple as $\frac{n1+n2}{2}$  
Create the function `average(n1, n2)` which _returns_ the average of the two numbers.

4. The [length of a line segment](https://study.com/skill/learn/how-to-use-the-distance-formula-given-the-graph-of-a-line-segment-to-determine-its-length-explanation.html) is extremely similar to Pythagoras' Theorem:  $l={\sqrt{(\Delta{x})^2+(\Delta{y})^2}}$  
Create the function `length(x1, y1, x2, y2)` which receives the points (x1, y1), (x2, y2) and _returns_ the distance between the two points. Do not round the result.  
You must use your `delta` function from #1 for this.

### HTML:

**Note:** The HTML for this next portion has _not_ been completed for you. Utilize your lessons and [the existing HTML on the page](../index.html) to assist you.

5. Add four input boxes, one each for `length`, `width`, `height`, and `radius`. You should give them meaningful ids.  

6. Add a "Rectangular Prism Volume" button to the page. Create a `rect_prism_volume()` function which utilizes the contents of `length`, `width`, and `height` to calculate the volume of a rectangular based prism with these dimensions, _rounded to the requested number of decimals_. Output the result to the user in a pleasing manner (note - do **not** use the `quadratic_output` location for this).

7. Add a "Rectangular Prism Area" button to the page. Create a `rect_prism_area()` function which does the same as above but calculates the Surface Area of the prism.

8. Add "Sphere Volume" and "Sphere Area" buttons. Create `sphere_volume()` and `sphere_area()` functions accordingly which utilize the `radius` input box.

9. Add a section to the page where a user can enter values for two points (x1, y1) (x2, y2). You will need four input boxes, one for each value. Make sure the user understands what they are being asked to enter. Utilize headings or similar to inform the user.

10. Add "Slope" and "Length" buttons to the page which utilize the input boxes from #5 and display the result in a neat fashion **rounded to the requested number of decimals**.

11. The _midpoint_ of a line segment is easily calculated as $M=(\frac{x1+x2}{2},\frac{y1+y2}{2})$  
Add the button "Midpoint" and create the function `midpoint()` which uses the input boxes from #9 above to neatly print the midpoint of the line section with values rounded to the requested number of decimals. If done correctly, you should use your `average(n1, n2)` function from #3 above.

---

#### Table of Contents
- [README](../README.md)
- [Part 1: Quadratics](./PART1.md)  
- [Part 3: Extra](./PART3.md)