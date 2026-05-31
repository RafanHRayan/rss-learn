---
tags:
  - tag: unfinished
    primary: true
---

# Transformations

A **transformation** is some change to a plane. A transformation can manipulate points, lines, and figures.

When a figure is transformed, the **preimage** is the original figure before the transformation, and the **image** is the resulting figure after the transformation.

A transformation is an [**isometry**](#user-content-fn-1)[^1] if and only if it [preserves length](#user-content-fn-2)[^2].

## Reflections

A **reflection** is when a figure produces a _mirror image_ about [a specified focus](#user-content-fn-3)[^3].

### Line Reflections

A **line reflection** is when a figure is reflected about a specified line.

<details>

<summary><i class="fa-note">:note:</i> Line Reflection Notation</summary>

To denote a line reflection, use the following notation...

<p align="center"><span class="math">r_{y}(A)=A'</span></p>

Where $$r$$ denotes the type of transformation, $$y$$ denotes the equation that makes the line of reflection, $$A$$ is the preimage, and $$A'$$ is the image.

{% hint style="info" icon="vial-vertical" %}
The transformation $$r_{y=0}(A)=A'$$ would denote a line reflection about the x-axis of $$A$$ to get $$A'$$.

The transformation $$r_{y=2x+3}(A)=A'$$ would denote a line reflection about the line $$y=2x+3$$ of $$A$$ to get $$A'$$.
{% endhint %}

</details>

When a point is reflected over a line it _does not_ lie on, the line of reflection is the perpendicular bisector of the segment which joins the preimage and image. When a point is reflected over a line it _does_ lie on, the image is the same point as the preimage.

The line that any figure is reflected over is called the **line of reflection**.

### Point Reflections

A **point reflection** is when a figure is reflected about a specified point.

<details>

<summary><i class="fa-note">:note:</i> Point Reflection Notation</summary>

To denote a point reflection, use the following notation...

<p align="center"><span class="math">r_{(x,y)}(A)=A'</span></p>

Where $$r$$ denotes the type of transformation, $$(x,y)$$ denotes the point of reflection, $$A$$ is the preimage, and $$A'$$ is the image.

{% hint style="info" icon="vial-vertical" %}
The transformation $$r_{(2,3)}(A)=A'$$ would denote a point reflection about $$(2,3)$$ of $$A$$ to get $$A'$$.
{% endhint %}

</details>

The point that any figure is reflected over is called the **point of reflection**.

To perform a point reflection, perform the reflection of the horizontal line followed by that of the vertical line that intersect at the point of reflection. In simpler terms, a point is reflected over the point of reflection when the point of reflection is the midpoint of the preimage and the image.

## Compositions

A **composition** is a transformation that consists of two or more compositions. It is denoted as follows...

$$
r_{x=0}\circ{}r_{y=0}(A)=A'
$$

Compositions are performed in reverse order of that which they are written. Thus, in this case, the reflection over $$y=0$$ would be performed first.

{% hint style="success" icon="lightbulb" %}
A point reflection is the composition of two reflections in which the two lines of reflection intersect.
{% endhint %}

## Translations

A **vector** is an object with a magnitude[^4] and a direction, but no fixed location. The **head** of a vector is where the arrow is, and the **tail** of the vector is where it came from. A vector is defined by an $$x$$ and $$y$$ value, where $$\langle{}x,y\rangle{}$$ denotes the amount the vector moves from the tail to the head.

A **translation** is when a figure is shifted by a vector.

<details>

<summary><i class="fa-note">:note:</i> Translation Notation</summary>

Do denote a translation, use the following notation...

<p align="center"><span class="math">T_{x,y}(A)=A'</span></p>

Where $$T$$ denotes the type of transformation, $$x,y$$ denotes the vector, $$A$$ is the preimage, and $$A'$$ is the image.

{% hint style="info" icon="vial-vertical" %}
The transformation $$T_{3,-2}(A)=A'$$ would denote a translation by the vector $$\langle{}3,-2\rangle{}$$ of $$A$$ to get $$A'$$. This is the same as a shift of $$A$$ three units to the right and two units down.
{% endhint %}

</details>

When a point is translated by some vector, the tail of the vector is the preimage and the head of the vector is the image.

## Rotations

A **rotation** is when a figure is manipulated around a point.

The point in which a figure is rotated is the **center of rotation**. The amount in which a figure is rotated is the **degree of rotation**.

<details>

<summary><i class="fa-note">:note:</i> Rotation Notation</summary>

Do denote a rotation, use the following notation...

<p align="center"><span class="math">R_{(x,y),\theta{}\degree{}}(A)=A'</span></p>

Where $$R$$ denotes the type of transformation, $$(x,y)$$ denotes the center of rotation, $$\theta{}$$ denotes the degree of rotation, $$A$$ is the preimage, and $$A'$$ is the image.

{% hint style="info" icon="vial-vertical" %}
The transformation $$R_{(7,-4),-90\degree{}}(A)=A'$$ would denote a 90° rotation around the point $$(7,-4)$$ of $$A$$ to get $$A'$$.
{% endhint %}

</details>

When the degree of rotation is positive, it denotes a _counterclockwise_ rotation. When the degree of rotation is negative, it denotes a _clockwise_ rotation.

A rotation—where $$O$$ denotes the center of reflection, $$\theta{}$$ denotes the degree of rotation, $$A$$ is the preimage, and $$A'$$ is the image—is defined such that $$OA=OA'$$ and that $$\text{m}\angle{AOA'}=\theta{}\degree{}$$.

{% hint style="success" icon="fire-flame-curved" %}
To perform a rotation by multiples of 90, use your knowledge of perpendicular lines on Cartesian planes.
{% endhint %}

## Mapping

Two figures are congruent if and only if there exists a composition of isometries that maps one to the other.

## Dilations

A **dilation** is when a figure is shrunk or grown about a point.

{% hint style="success" icon="fire-flame-curved" %}
A composition consisting of [only one unique transformation](#user-content-fn-5)[^5] is able to disregard the order in which they are completed, _except_ for dilations.
{% endhint %}

[^1]: It may also be called a rigid motion.

[^2]: This means that the preimage is congruent to the image.

[^3]: This can be a line or a point.

[^4]: Essentially length.

[^5]: For example, three reflections.
