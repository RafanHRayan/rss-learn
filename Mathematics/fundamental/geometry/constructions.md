---
description: Tools in constructions, fundamentals of circles, length operation, ...
---

# Constructions

## Tools in Constructions

To **construct** geometric figures, mathematicians require...

* ...a pencil[^1].
* ...a **straightedge**.
  * In order to construct lines and segments.
* ..a **compass**.
  * In order to draw circles.
  * In order to store lengths[^2] and distances.

## Fundamentals of Circles

A plane figure is a **circle** if and only if it is the set of all points equidistant from a fixed point. This point is known as the **center**. This set of points forms the **circumference**. Two or more shapes are **concentric** if and only if they have the same center.

The distance from the center to any point on the circle is the **radius**. Two circles are congruent if they have the _same_ radius. A segment is a **diameter** if and only if it connects two points on a circle _**and**_ passes through the center of the _same_ circle.

A circular **arc** is a _part_ of a circle.

## Length Operation

As mentioned previously, you can use a compass to store lengths and distances. This can be used to create [a segment that is the result of operations upon other segments](#user-content-fn-3)[^3]. Create a line as a workstation to perform segment operations. We will call this line the workspace line.

{% hint style="warning" %}
### Warning

Make sure this line is _**long**_, or you may not have enough space to construct your segment.
{% endhint %}

To **add**, adjust the compass to match the length of the first addend segment. Go on your workspace line and place the needle on one endpoint of the segment. Make a small arc to mark where the length of the first addend segment ends. Do the same for the second addend segment, placing the needle where the first addend segment length ends. The combined length is the length of the resulting segment.

To **subtract**, adjust the compass to match the length of the minuend[^4] segment. Go on your workspace line and place the needle on one endpoint of the segment. Make a small arc to mark where the length of the minuend segment ends. Do the same for the subtrahend[^5] segment, placing the needle on the same endpoint. The length of [the region where the lengths don't overlap](#user-content-fn-6)[^6] is the length of the resulting segment.

To **multiply**, adjust the compass to match the length of the factor segment. Go on your workspace line and place the needle on one endpoint of the segment. Make a small arc to mark where the length of the first instance ends. Do the same for the [each repetition](#user-content-fn-7)[^7], placing the needle where the previous segment length ends. The combined length is the length of the resulting segment.

## Fundamental Constructions

These constructions are the most basic—yet most important—constructions that require little to no background knowledge.

{% hint style="success" %}
## Tip

Though it is helpful to see the whole diagram, you do not need to draw the whole circle every time. You may draw arcs (portions of circles) on the [places where you need them](#user-content-fn-8)[^8].
{% endhint %}

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Constructing an Equilateral Triangle</summary>



**Prelude:**

* Draw $$\overline{AB}$$.

**Construction:**

1. Draw a circle centered at $$A$$ such that the radius is $$AB$$.
2. Draw a circle centered at $$B$$ such that the radius is $$AB$$.
3. Mark $$C$$ as one of the intersections of circle $$A$$ and circle $$B$$.
4. Draw $$\overline{AC}$$ and $$\overline{BC}$$.

**Result:**

* $$\triangle{ABC}$$ is an equilateral triangle.
  * $$\overline{AB} \cong{} \overline{BC} \cong{} \overline{AC}$$.

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Constructing a Perpendicular Bisector</summary>



**Prelude:**

* Draw $$\overline{AB}$$.

**Construction:**

1. Draw a circle centered at $$A$$ such that the radius is $$AB$$.
2. Draw a circle centered at $$B$$ such that the radius is $$AB$$.
3. Mark $$C$$ and $$D$$ as the two intersections of circle $$A$$ and circle $$B$$.
4. Draw $$\overline{CD}$$.
5. Mark $$X$$ as the intersection between $$\overline{AB}$$ and $$\overline{CD}$$.

**Result:**

* $$\overline{CD}$$ is the perpendicular bisector of $$\overline{AB}$$.
  * $$\overline{AX} \cong{} \overline{XB}$$.
  * $$m\angle{AXC} = m\angle{CXB} = m\angle{BXD} = m\angle{AXD} = 90\degree{}$$.

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Constructing a <a data-footnote-ref href="#user-content-fn-9">Perpendicular Line</a></summary>



**Prelude:**

* Draw $$\overline{AB}$$.
* Mark $$C$$ such that it is not on $$\overline{AB}$$.

**Construction:**

1. Draw a circle centered at $$A$$ such that the radius is $$AC$$.
2. Draw a circle centered at $$B$$ such that the radius is $$BC$$.
3. $$C$$ is one of the intersections of circle $$A$$ and circle $$B$$. Mark $$D$$ as the other.
4. Draw $$\overline{CD}$$.
5. Mark $$X$$ as the intersection between $$\overline{AB}$$ and $$\overline{CD}$$.

**Result:**

* $$\overline{CD}$$ is the perpendicular bisector of $$\overline{AB}$$.
  * $$\overline{AX} \cong{} \overline{XB}$$.
  * $$m\angle{AXC} = m\angle{CXB} = m\angle{BXD} = m\angle{AXD} = 90\degree{}$$.

{% hint style="info" %}
## Note

This is also how to construct an altitude of a triangle.
{% endhint %}

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Constructing an Angle Bisector</summary>



**Prelude:**

* Draw $$\overrightarrow{AB}$$ and $$\overrightarrow{AC}$$.

**Construction:**

1. Draw a circle centered at $$A$$ of any radius, $$\theta{}$$, as long is it will intersect both rays.
2. Mark $$L$$ as the intersection between $$\overrightarrow{AB}$$ and circle $$A$$.
3. Mark $$M$$ as the intersection between $$\overrightarrow{AC}$$ and circle $$A$$.
4. Draw a circle centered at $$L$$ of radius, $$\theta{}$$.
5. Draw a circle centered at $$M$$ of radius, $$\theta{}$$.
6. Mark $$N$$ as the intersection between circle $$L$$ and circle $$M$$.
7. Draw $$\overrightarrow{AN}$$.

**Result:**

* $$\overrightarrow{AN}$$ bisects $$\angle{LAM}$$.
  * $$\angle{LAN} \cong{} \angle{NAM}$$.

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Copying an Angle</summary>



**Prelude:**

* Draw $$\overrightarrow{AB}$$ and $$\overrightarrow{AC}$$.
* Draw $$D$$.

**Construction:**

1. Draw a circle centered at $$A$$ of any radius, $$\theta{}$$, as long is it will intersect both rays.
2. Mark $$L$$ as the intersection between $$\overrightarrow{AB}$$ and circle $$A$$.
3. Mark $$M$$ as the intersection between $$\overrightarrow{AC}$$ and circle $$A$$.
4. Draw $$\overline{BC}$$.
5. Draw a ray in any direction with $$D$$ as the endpoint.
6. Draw a circle centered at $$D$$ of radius, $$\theta{}$$.
7. Mark $$E$$ as the intersection between $$\overrightarrow{D}$$ and circle $$D$$.
8. Draw a circle centered at $$E$$ of radius, $$\overline{BC}$$.
9. Mark $$F$$ as the intersection between cicle $$D$$ and circle $$E$$.
10. Draw $$\overrightarrow{DF}$$.

**Result:**

* $$\angle{BAC} \cong{} \angle{FDE}$$.

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Constructing a <a data-footnote-ref href="#user-content-fn-10">Parallel Line</a></summary>



**Prelude:**

* Draw $$\overleftrightarrow{AB}$$.
* Mark $$C$$ such that it is not on $$\overleftrightarrow{AB}$$.

**Construction:**

1. Draw a circle centered at $$B$$ of radius, $$\overline{AC}$$.
2. Draw a circle centered at $$A$$ of radius, $$\overline{AB}$$.
3. Mark $$D$$ as the intersection between circle $$A$$ and circle $$B$$ that is on the same side of $$\overleftrightarrow{AB}$$ as $$C$$.
4. Draw $$\overleftrightarrow{CD}$$.

**Result:**

* $$\overleftrightarrow{AB} \parallel{} \overleftrightarrow{CD}$$.

{% hint style="success" %}
## Alternate Method

You may also construct a parallel line by copying an angle to make congruent corresponding angles.
{% endhint %}

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Dividing a Segment Into Congruent Parts</summary>



**Prelude:**

* Draw $$\overline{AB}$$.
* Assume that the goal of this construction is to divide $$\overline{AB}$$ into $$n$$ congruent segments.

**Construction:**

1. Draw a ray from $$A$$ such that the measure of the resulting angle is less than 90°.
2. Draw a circle centered at $$A$$ of a radius, $$\theta{}$$, ensuring that $$\theta{}$$ is approximately less than $$\frac{1}{n}$$ of $$\overline{AB}$$. Mark $$N_1$$ as the point of intersection from the ray drawn in step 1.
   1. Do this step $$n$$ times starting at the previously constructed point each time and creating new points ($$N_2, N_3, N_4, ... , N_n$$).
3. Draw $$\overline{BN_n}$$.
4. Copy $$\angle{AN_nB}$$ at every other iteration point of $$N$$ ($$N_1,...,N_{n-1}$$).
5. Mark iterations of $$P$$ ($$P_1,...,P_n$$) as the intersections between the iterations of $$N$$ and $$\overline{AB}$$.

**Result:**

* $$\overline{AP_1} \cong{} \overline{P_1P_2} \cong{} ... \cong{} \overline{P_{n-1}P_n}$$.

{% hint style="info" %}
## Clarification

The diagrams above assume $$n=3$$, that being splitting $$\overline{AB}$$ into 3 congruent segments.
{% endhint %}

</details>

## Advanced Constructions

These constructions require well understanding of the [fundamental constructions](constructions.md#fundamental-constructions) in order to properly and precisely perform.

The constructions are grouped—along with definitions—by relation or clarification...

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Constructing a Rhombus</summary>



**Prelude:**

* Draw $$\overline{AB}$$.

**Construction:**

1. Construct $$\overline{CD}$$ as the perpendicular bisector of $$\overline{AB}$$.
2. Draw $$\overline{AC}$$, $$\overline{BC}$$, $$\overline{BD}$$, and $$\overline{AD}$$.
3. Mark $$X$$ as the intersection between $$\overline{AB}$$ and $$\overline{CD}$$.

**Result:**

* $$ABCD$$ is a rhombus.
  * $$\overline{AC} \cong{} \overline{BC} \cong{} \overline{BD} \cong{} \overline{AD}$$.
  * $$X$$ is the midpoint of $$\overline{AB}$$.
  * $$X$$ is the midpoint of $$\overline{CD}$$.

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Constructing a Rectangle</summary>



**Prelude:**

* Draw $$\overline{AB}$$.

**Construction:**

1. Construct $$\overline{AC}$$ as the perpendicular bisector of $$\overline{AB}$$.
2. Construct $$\overline{BD}$$ as the perpendicular bisector of $$\overline{AB}$$.
3. Draw $$\overline{CD}$$.

**Result:**

* $$ABCD$$ is a rectangle.
  * $$\overline{AB} \cong{} \overline{CD}, \overline{AC} \cong{} \overline{BD}$$.
  * $$\overline{AB} \parallel{} \overline{CD}, \overline{AC} \parallel{} \overline{BD}$$.
  * $$m\angle{ABC} = m\angle{BCD} = m\angle{DAB} = m\angle{BCA} = 90\degree{}$$.

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Constructing a Parallelogram</summary>



**Prelude:**

* Draw $$\overleftrightarrow{AB}$$.

**Construction:**

1. Draw a circle centered at $$A$$ of any radius, $$\theta{}$$.
2. Draw a ray from $$A$$ and mark $$C$$ as the intersection between $$\overrightarrow{A}$$ and circle $$A$$.
3. Draw a circle centered at $$B$$ of radius, $$\theta{}$$.
4. Draw a ray from $$B$$ by copying $$\angle{A}$$ and mark $$D$$ as the intersection between $$\overrightarrow{B}$$ and circle $$B$$.
5. Draw $$\overleftrightarrow{CD}$$.

**Result:**

* $$ABCD$$ is a parallelogram.
  * $$\overline{AB} \cong{} \overline{CD}, \overline{AC} \cong{} \overline{BD}$$.
  * $$\overline{AB} \parallel{} \overline{CD}, \overline{AC} \parallel{} \overline{BD}$$.

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Constructing a 45° Angle</summary>



**Prelude:**

* Draw $$\overleftrightarrow{AB}$$.

**Construction:**

1. Construct $$\overleftrightarrow{CD}$$ as the perpendicular bisector of $$\overleftrightarrow{AB}$$.
2. Mark $$X$$ as the intersection between $$\overleftrightarrow{AB}$$ and $$\overleftrightarrow{CD}$$.
3. Construct $$\overrightarrow{XY}$$ as the angle bisector of $$\angle{CXB}$$.

**Result:**

* $$m\angle{CXY}=m\angle{YXB}=45\degree{}$$, since it is the result of bisecting a 90° angle.

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Constructing a Median</summary>



**Prelude:**

* Draw $$\triangle{ABC}$$.
* Assume that the goal is to find the median dropped from $$\angle{ABC}$$.

**Construction:**

1. Construct $$\overleftrightarrow{DE}$$ as the perpendicular bisector of $$\overleftrightarrow{AC}$$.
2. Mark $$X$$ as the intersection between $$\overleftrightarrow{AC}$$ and $$\overleftrightarrow{DE}$$.
3. Draw $$\overline{BX}$$.

**Result:**

* $$\overline{BX}$$ is a median of $$\triangle{ABC}$$.

</details>



<details>

<summary><i class="fa-memo-pad">:memo-pad:</i> Definition of an Inscribed Polygon</summary>

A polygon is inscribed in a circle if and only if all of its vertices lie on the circumference of the circle.

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Inscribing an Equilateral Triangle in a Circle</summary>



**Prelude:**

* Draw circle $$O$$.
* Mark $$A$$ as any point on the circumference of circle $$O$$.

**Construction:**

1. Draw $$\overrightarrow{AO}$$.
2. Mark $$X$$ as the intersection between $$\overrightarrow{AO}$$ and circle $$O$$.
3. Draw a circle centered at $$X$$ such that the radius is $$XO$$.
4. Mark $$B$$ and $$C$$ as the intersections between circle $$X$$ and circle $$O$$.
5. Draw $$\overline{AB}$$, $$\overline{BC}$$, and $$\overline{AC}$$.

**Result:**

* $$\triangle{ABC}$$ is an equilateral triangle.
  * $$\overline{AB} \cong{} \overline{BC} \cong{} \overline{AC}$$.
* $$\triangle{ABC}$$ is inscribed in circle $$O$$.

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Inscribing a Square in a Circle</summary>



**Prelude:**

* Draw circle $$O$$.
* Mark $$A$$ as any point on the circumference of circle $$O$$.

**Construction:**

1. Draw $$\overrightarrow{AO}$$.
2. Mark $$X$$ as the intersection between $$\overrightarrow{AO}$$ and circle $$O$$.
3. Draw a circle centered at $$X$$ such that the radius is $$XO$$.
4. Construct $$\overline{CD}$$ as the perpendicular bisector of $$\overline{AB}$$.
5. Mark $$Y$$ and $$Z$$ as the intersections between $$\overline{CD}$$ and circle $$O$$.
6. Draw $$\overline{AY}$$, $$\overline{BY}$$, $$\overline{BZ}$$, and $$\overline{AZ}$$.

**Result:**

* $$AYBZ$$ is a square.
  * $$\overline{AY} \cong{} \overline{BY} \cong{} \overline{BZ} \cong{} \overline{AZ}$$.
  * $$m\angle{AYB} = m\angle{YBZ} = m\angle{BZA} = m\angle{ZAY} = 90\degree{}$$.
* $$AYBZ$$ is inscribed in circle $$O$$.

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Inscribing a Hexagon in a Circle</summary>



**Prelude:**

* Draw circle $$O$$.
* Mark $$A$$ as any point on the circumference of circle $$O$$.

**Construction:**

1. Draw $$\overrightarrow{AO}$$.
2. Mark $$B$$ as the intersection between $$\overrightarrow{AO}$$ and circle $$O$$.
3. Draw a circle centered at $$A$$ such that the radius is $$AO$$.
4. Mark $$C$$ and $$D$$ as the intersections between circle $$A$$ and circle $$O$$.
5. Draw a circle centered at $$B$$ such that the radius is $$BO$$.
6. Mark $$E$$ and $$F$$ as the intersections between circle $$B$$ and circle $$O$$.
7. Draw $$\overline{AD}$$$$\overline{}$$, $$\overline{DF}$$, $$\overline{BF}$$, $$\overline{BE}$$, $$\overline{CE}$$, and $$\overline{AC}$$.

**Result:**

* $$ADFBEC$$ is a regular hexagon.
  * $$\overline{AD} \cong{} \overline{DF} \cong{} \overline{BF} \cong{} \overline{BE} \cong{} \overline{CE} \cong{} \overline{AC}$$.
* $$ADFBEC$$ is inscribed in circle $$O$$.

</details>



<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Locating the Circumcenter of a Triangle</summary>



**Prelude:**

* Draw $$\triangle{ABC}$$.

**Construction:**

1. Construct the perpendicular bisector of $$\overline{AB}$$.
2. Construct the perpendicular bisector of $$\overline{BC}$$.
3. Construct the perpendicular bisector of $$\overline{AC}$$.
4. Mark $$X$$ as the intersection between all three perpendicular bisectors.

**Result:**

* $$X$$ is the circumcenter of $$\triangle{ABC}$$.

</details>

<details>

<summary><i class="fa-memo-pad">:memo-pad:</i> Definition of a Circumcircle</summary>

A circle is the circumcircle of a triangle if and only if all three points of the triangle lie on the circumference of the circle.

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Constructing the Circumcircle of a Triangle</summary>



**Prelude:**

* Draw $$\triangle{ABC}$$.

**Construction:**

1. Locate the circumcenter of $$\triangle{ABC}$$. Mark the circumcenter as $$X$$.
2. Draw a circle centered at $$X$$ such that the radius[^11] is $$AX$$, $$BX$$, or $$CX$$.

**Result:**

* $$X$$ is the circumcenter of $$\triangle{ABC}$$.
* Circle $$X$$ is the circumcircle of $$\triangle{ABC}$$.

</details>



<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Locating the Incenter of a Triangle</summary>



**Prelude:**

* Draw $$\triangle{ABC}$$.

**Construction:**

1. Construct the angle bisector of $$\angle{ABC}$$.
2. Construct the angle bisector of $$\angle{BCA}$$.
3. Construct the angle bisector of $$\angle{CAB}$$.
4. Mark $$X$$ as the intersection between all three angle bisectors.

**Result:**

* $$X$$ is the incenter of $$\triangle{ABC}$$.

</details>

<details>

<summary><i class="fa-memo-pad">:memo-pad:</i> Definition of an Incircle</summary>

A circle is the circumcircle of a triangle if and only if it is tangent to every side of the triangle.

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Constructing the Incircle of a Triangle</summary>



**Prelude:**

* Draw $$\triangle{ABC}$$.

**Construction:**

1. Construct the angle bisector of $$\angle{ABC}$$.
2. Construct the angle bisector of $$\angle{BCA}$$.
3. Construct the angle bisector of $$\angle{CAB}$$.
4. Mark $$X$$ as the intersection between all three angle bisectors.
5. Construct a line perpendicular to any one of the sides of $$\triangle{ABC}$$, ensuring that $$X$$ is on it.
6. Draw a circle centered at $$X$$ such that the radius is the length of this perpendicular line.

**Result:**

* $$X$$ is the incenter of $$\triangle{ABC}$$.
* Circle $$X$$ is the incircle of $$\triangle{ABC}$$.

</details>



<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Locating the Orthocenter of a Triangle</summary>



**Prelude:**

* Draw $$\triangle{ABC}$$.

**Construction:**

1. Construct the altitude of $$\angle{ABC}$$.
2. Construct the altitude of $$\angle{BCA}$$.
3. Construct the altitude of $$\angle{CAB}$$.
4. Mark $$X$$ as the intersection between all three altitudes.

**Result:**

* $$X$$ is the orthocenter of $$\triangle{ABC}$$.

</details>

<details>

<summary><i class="fa-compass-drafting">:compass-drafting:</i> Locating the Centroid of a Triangle</summary>



**Prelude:**

* Draw $$\triangle{ABC}$$.

**Construction:**

1. Construct the median of $$\angle{ABC}$$.
2. Construct the median of $$\angle{BCA}$$.
3. Construct the median of $$\angle{CAB}$$.
4. Mark $$X$$ as the intersection between all three medians.

**Result:**

* $$X$$ is the centroid of $$\triangle{ABC}$$.

</details>

{% hint style="success" %}
## Fun Fact

In the real world, the centroid is the center of mass. If you were to take an actual object that shape of a triangle, locate the centroid, and balance it on that point, the triangle would balance!
{% endhint %}

[^1]: Obviously...

[^2]: Specifically lengths of segments.

[^3]: For example, you may be asked to draw a segment $$\overline{XY}$$ such that $$XY=AB+2(CD)-3(EF)$$, and be given all the segments _**to scale**_.

[^4]: The minuend of a subtraction equation is the number that is subtracted _from_. In $$6-2=4$$, the minuend is $$6$$.

[^5]: The minuend of a subtraction equation is the number that the minuend is subtracted _by_. In $$6-2=4$$, the minuend is $$2$$.

[^6]: Essentially, the **difference** of the lengths.

[^7]: If asked to find the length 3 times that of a segment, add the segment's length 3 times. And so on...

[^8]: i.e. points of intersection.

[^9]: Given a line and a point not on the line, create a line that is perpendicular to the original line and passes through the point.

[^10]: Given a line and a point not on the line, create a line that is parallel to the original line and passes through the point.

[^11]: $$AX \cong{} BX \cong{} CX$$. Thus, it doesn't matter which length you reference as the radius for circle $$X$$.
