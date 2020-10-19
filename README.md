# Hacks - Week One Task
<!-- Headings -->

# Discriminant and Nature of Roots
### Our aim is to develop system which finds the discriminant of the quadratic equation and finds its nature.
---
## Discriminant
<p> The discriminant of a polynomial is a quantity that depends on the coefficients and determines various properties of the roots. The discriminant of a polynomial is generally defined in terms of a polynomial function of its coefficients. </p>

---

## Nature of Roots
<p>The discriminant determines the nature of the roots of a quadratic equation. The word 'nature' refers to the types of numbers the roots can be — namely real, rational, irrational or imaginary.</p>


##  if D>0: "the roots are real and distinct."

<!-- GitHub Markdown -->

<!-- Code Blocks -->
``` python  
if d > 0:
 d**=0.5
 r1 = (-b+d)/(2*a)
 r2 = (-b-d)/(2*a)
 print("The roots are real and distinct")
 print("The roots are : {}, {}".format(r1,r2))
```
<!-- Images -->

![Distinct Roots Graph](https://d138zd1ktt9iqe.cloudfront.net/media/seo_landing_files/mahima-quadratic-equations-v2-03-1595909613.png)
## if D=0: "the roots are real and equal."
<!--- Code Blocks -->
```python
elif d == 0:
 r = (-b)/(2*a)
 print("The roots are real and equal")
 print("The roots are : {}, {}".format(r,r))
```
![real and equal Roots Graph](https://d138zd1ktt9iqe.cloudfront.net/media/seo_landing_files/mahima-quadratic-equations-v2-06-1595909654.png)

## if D<0: "the roots are imaginary."
<!-- Code Blocks -->
```python
else:
 d = ((4*a*c)-(b**2))**0.5
 r = (-b)/(2*a)
 i = (d)/(2*a)
 print("Imaginary roots")
 print("The roots are : {}+{}i, {}-{}i".format(r,i,r,i))
```
![Imaginary Roots Graph](https://d138zd1ktt9iqe.cloudfront.net/media/seo_landing_files/mahima-quadratic-equations-v2-07-1595909690.png)


   


