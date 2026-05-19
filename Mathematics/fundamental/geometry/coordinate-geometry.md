---
description: >-
  The Cartesian plane, parallel lines, perpendicular lines, distance formula,
  midpoint formula, circles, and scaling line segments.
tags:
  - tag: unfinished
    primary: true
---

# Coordinate Geometry

Up until now, we have been looking at figures[^1] at a geometric perspective called **synthetic geometry**. A plane with figures overlayed on top; in the case of a solid, its plane on top of planes. What if we took this and put it on the **Cartesian plane**?

{% hint style="success" icon="lightbulb" %}
The Cartesian plane is named after its inventor, Rene Descartes.
{% endhint %}

<details open>

<summary><i class="fa-ruler-triangle">:ruler-triangle:</i> Synthetic Geometry</summary>

A representation of geometry that depends on logical thinking, like proofs. Coordinates are dismissed.

</details>

<details open>

<summary><i class="fa-chart-sine">:chart-sine:</i> Coordinate Geometry</summary>

A representation of geometry that is fundamental to analytic geometry, as it links algebra and geometry. In this form, you are to actually graph figures by placing points on a plane.

</details>

<details open>

<summary><i class="fa-magnifying-glass-chart">:magnifying-glass-chart:</i> Analytic Geometry</summary>

A representation of geometry that depends on algebraic methodology and coordinate locating. Formulas and equations are commonplace.

</details>

## Fundamentals of the Cartesian Plane

A Cartesian plane contains infinitely many points, four quadrants, and two axes. Equally spaced horizontal and vertical lines help readers analyze geometric figures on the plane. The points where grid lines meet are called **lattice points**.

### Lines

Lines on planes have a **slope** defining how steep its orientation is in regards to the axes and grid lines. The slope is defined as the ratio of vertical measure to the ratio of horizontal measure between any two points on the line.

{% hint style="success" icon="lightbulb" %}
Don't forget that a right triangle can be created from the two points on the line, with the actual segment of the line between the points being the hypotenuse.

Thus, the slope a line is the ratio of the length of its leg parallel to the y-axis to the length of its leg parallel to the x-axis.
{% endhint %}

Almost every line meet _both_ axes _exactly_ once. There are two exceptions. A line with a slope of 0 _only_ meets the y-axis. A line with an undefined slope _only_ meets the x-axis.

When a line intercepts the x-axis, the point in which they meet is called the x-intercept. When a line intercepts the y-axis, the point in which they meet is called the y-intercept.

Recall that Euclid's first postulate states that a line can be drawn through any two points. In synthetic geometry, the line through points $$A$$ and $$B$$ is $$\overleftrightarrow{AB}$$. In analytic geometry, the line through points $$A(0,1)$$ and $$B(3,7)$$ is defined as all of the following including its variants[^2]...

|    $$y=2x+1$$    |
| :--------------: |
|    $$2x-y=-1$$   |
|   $$y-1=2x$$\*   |
| $$y-7=2(x-3)$$\* |

{% hint style="info" icon="asterisk" %}
The starred equations are both variations of the same form of graphing the line. Each equation just uses each of the two points with the slope.
{% endhint %}

The equation of a line is commonly written in the three formats below...

| Slope-Intercept Form | $$y=mx+b$$         |
| -------------------: | ------------------ |
|        Standard Form | $$Ax+By=C$$        |
|     Point-Slope Form | $$y-y_1=m(x-x_1)$$ |

In slope-intercept form, $$m$$ is the slope and $$b$$ is the y-intercept. In standard form, $$A$$, $$B$$, and $$C$$ are constants. In point-slope form, $$m$$ is the slope and $$(x_1,y_1)$$ are the coordinates of a point on the line.

{% hint style="success" icon="fire-flame-curved" %}
Rearranging the equation for slope-intercept form, we find that the x-intercept is $$-\frac{b}{m}$$.
{% endhint %}

In standard form, the slope is $$-\frac{A}{B}$$, the y-intercept is $$\frac{C}{B}$$, and the x-intercept is $$\frac{C}{A}$$.

{% hint style="success" icon="fire-flame-curved" %}
To differentiate between the x-intercept and y-intercept in standard form, note that the x-intercept is found with $$\frac{C}{A}$$, where $$A$$ is the coefficient for the $$x$$ term. The same goes for the y-intercept.
{% endhint %}

## Parallel and Perpendicular Lines

<details>

<summary><i class="fa-note">:note:</i> Definition of Parallel (<span class="math">\text{}\parallel{}</span>) Lines on a Plane</summary>

On a plane, two lines are parallel if and only if they have the same slope.

{% hint style="info" icon="vial-vertical" %}
If we have two lines with a slope of $$-\frac{2}{3}$$, then they would be perpendicular because they have the same slope.
{% endhint %}

</details>

<details>

<summary><i class="fa-note">:note:</i> Definition of Perpendicular (<span class="math">\text{}\perp{}</span>) Lines on a Plane</summary>

On a plane, two lines are perpendicular if and only if the product of their slopes is -1.

{% hint style="info" icon="vial-vertical" %}
If we have a line with a slope of $$-\frac{2}{3}$$ and a line with a slope of $$\frac{3}{2}$$, then they would be perpendicular because $$-\frac{2}{3}*\frac{3}{2}=-1$$.
{% endhint %}

</details>

## Fundamental Formulae

The **Distance Formula states** that the distance between any two points $$(x_1,y_1)$$ and $$(x_2,y_2)$$ is $$\sqrt{(x_1-x_2)^2+(y_1-y_2)^2}$$.

The Midpoint Formula states that the midpoint of any two points $$(x_1,y_1)$$ and $$(x_2,y_2)$$ is located at $$(\frac{x_1+x_2}{2},\frac{y_1+y_2}{2})$$.

## Circles

On a plane, the equation of a circle in **standard form**, where $$(h,k)$$ is the center of the circle and $$r$$ is the radius, is $$(x-h)^2+(y-k)^2=r^2$$.

On a plane, the equation of a circle in **standard form**, where $$(h,k)$$ is the center of the circle and $$r$$ is the radius, is $$x^2+y^2+Dx+Ey+F=0$$.

## Scaling Line Segments

In order to scale segments, create two _similar_ right triangles. [When the midpoint is asked for](#user-content-fn-3)[^3], use the formula. But otherwise, do this...

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Screenshot 2026-05-19 at 7.50.56 PM.png" alt="" width="563"><figcaption><p>Image 1 — Example of scaling line segments. You are given A's and B's existence and location;<br>K's existence; and the ratio between <span class="math">\overline{AK}</span> and <span class="math">\overline{KB}</span>. Find the coordinates of K.</p></figcaption></figure></div>

### Scaling Formula

Alternatively, you may also use the formula...

The location of the point $$K$$ which divides the segment with endpoints $$A(x_1,y_1)$$ and $$B(x_2,y_2)$$ such that $$AK:KB=p:q$$ is $$K(\frac{qx_1,px_2}{p+q},\frac{qy_1+qy_2}{p+q})$$.

## Proofs in Coordinate Geometry

Use the [new theorems and definitions learned here](#user-content-fn-4)[^4] to complete proofs.

{% hint style="success" icon="fire-flame-curved" %}
It is recommended to complete coordinate geometry proofs in paragraph form. Write it out like you were to explain it to someone.
{% endhint %}

[^1]: Points, lines, polygons, solids, etc...

[^2]: An equivalent variation of the equations below found using algebra.

[^3]: The ratio of each segment is 1 to 1.

[^4]: The formulae, parallel, perpendicular, etc...
