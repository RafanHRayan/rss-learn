---
description: >-
  Special quadrilaterals, midsegments, medial triangles, triangle area, and
  quadrilateral area.
---

# Quadrilaterals

<details>

<summary><i class="fa-note">:note:</i> Definition of a Diagonal</summary>

A line is a diagonal if and only if it connects two non-consecutive points in a polygon.

</details>

<details>

<summary><i class="fa-note">:note:</i> Definition of a Quadrilateral</summary>

A polygon is a quadrilateral if and only if it is has four distinct sides and four distinct angles.

</details>

{% hint style="success" icon="fire-flame-curved" %}
Knowing these two definitions, a quadrilateral is essentially two _triangles_ that share a side, that being the diagonal of the quadrilateral.
{% endhint %}

There are many quadrilaterals that have special properties. These special properties are useful in proofs.

## Parallelograms

A quadrilateral is a parallelogram if and only if...

* [...its two pairs of opposite _sides_ are parallel.](#user-content-fn-1)[^1]
* ...its two pairs of opposite _sides_ are congruent.
* ...its two pairs of opposite _angles_ are congruent.
* ...every pair of consecutive _angles_ is supplementary.
* ...the _diagonals_ bisect each other.
* ...one pair of opposite _sides_ is both parallel _**and**_ congruent.

Since these are all viable definitions of a parallelogram, they can also be concluded from the premise that a quadrilateral is a parallelogram. For example, you can conclude that both pairs of opposite sides in a quadrilateral are congruent knowing that the quadrilateral is a parallelogram.

A parallelogram also has all the properties of a [trapezoid](quadrilaterals.md#trapezoids), as it is one.

## Rectangles

A quadrilateral is a rectangle if and only if it is a parallelogram and has _**at least one**_ right angle.

The properties of a rectangle include...

* ...all the properties of a parallelogram, as it is one.
* ...the property of _**all**_ angles being right angles.
* ...the property that its diagonals are congruent.

## Rhombi

A quadrilateral is a rhombus if and only if it is a parallelogram and has a pair of consecutive congruent sides.

The properties of a rhombus include...

* ...all the properties of a parallelogram, as it is one.
* ...the property of _**all**_ sides being congruent.
* ...the property that its diagonals are perpendicular to each other.
* ...the property that its diagonals bisect their angles.
* ...the property of kites, as it is one ([kites](quadrilaterals.md#kites)).

## Squares

A quadrilateral is a square if and only if it is either a rectangle with a pair on consecutive congruent sides, or a rhombus with _**at least one**_ right angle.

The properties of a square include...

* ...all the properties of a parallelogram, as it is one.
* ...all the properties of a rectangle, as it is one.
* ...all [the properties of a rhombus](#user-content-fn-2)[^2], as it is one.

## Kites

A quadrilateral is a kite if and only if one of its diagonals is the perpendicular bisector of the other.

## Trapezoids

A quadrilateral is a trapezoid if and only if it has _**at least one**_ pair of opposite parallel sides.

Note that parallelograms[^3], rectangles[^4], rhombi[^4], and squares[^5] are all trapezoids as well.

The _bases_ of a trapezoid are the two **parallel** sides. The _legs_ of a trapezoid are the two _**non-parallel**_ sides.  A base angle pair is a pair of two angles that is included by a base in a trapezoid. Every trapezoid has _**exactly**_ two base angle pairs.

### Isosceles Trapezoids

A trapezoid is an isosceles trapezoid if and only if it has congruent base angle pairs.

{% hint style="warning" icon="circle-exclamation" %}
From knowing a trapezoid is isosceles, you can prove that the legs of that trapezoid are congruent. Despite this, you _**cannot**_ prove that a trapezoid is isosceles _**because**_ the legs are congruent.
{% endhint %}

## Midsegments

### Midsegments in a Triangle

A segment drawn in a _**triangle**_ is a midsegment if and only if it connects the _midpoints_ of two sides.

If a midsegment is drawn in a triangle, then...

* ...it is parallel to the [third side](#user-content-fn-6)[^6].
* ...its length is half of the length of the third side.

### Midsegments in a Trapezoid

A segment drawn in a _**trapezoid**_ is a midsegment if and only if it connects the _midpoints_ of both the legs.

If a midsegment is drawn in a triangle, then...

* ...it is parallel to both the bases.
* ...its length is the _average_ of the lengths of the bases.

## Medial Triangles

A medial triangle is the triangle formed by the midsegments of another triangle.

{% hint style="success" icon="fire-flame-curved" %}
The medial triangle is similar (with a [scale factor](similar-polygons.md#scale-factors) of $$\frac{1}{2}$$) to the original triangle and rotated 180°. Medial triangles also split any larger triangle into four congruent, smaller triangles.
{% endhint %}

## Special Theorem

<details>

<summary><i class="fa-note">:note:</i> <a data-footnote-ref href="#user-content-fn-7">Transversal Splice Congruence Theorem</a></summary>

If a set of parallel lines cuts one transversal into congruent parts, then it cuts _**every**_ transversal into congruent parts.

</details>

## Area

You should know what area is; if you are stupid, area is the amount of 1 un<sup>2</sup> squares that can fit inside of a region. Here are the different formulae to find the area of all of the special quadrilaterals.

{% hint style="info" icon="circle-question" %}
## Assuming that...

* $$b$$ is the length of the base of a quadrilateral.
* $$h$$ is the length of the height of a quadrilateral.
* $$s$$ is the length of any side in a square.
* $$d_1$$ is the length of the first diagonal in a quadrilateral.
* $$d_2$$ is the length of the second diagonal in a quadrilateral.
* $$m$$ is the length of the midsegment of a trapezoid.
{% endhint %}

{% tabs %}
{% tab title="Parallelograms" %}
* $$bh$$
* $$mh$$
{% endtab %}

{% tab title="Rectangles" %}
* $$bh$$
* $$mh$$
{% endtab %}

{% tab title="Rhombi" %}
* $$bh$$
* $$mh$$
* $$\frac{1}{2}(d_1d_2)$$
{% endtab %}

{% tab title="Squares" %}
* $$s^2$$
* $$bh$$
* $$mh$$
* $$\frac{1}{2}(d_1d_2)$$
{% endtab %}

{% tab title="Trapezoids" %}
* $$mh$$
* $$\frac{1}{2}(d_1d_2)$$
{% endtab %}

{% tab title="Kites" %}
* $$\frac{1}{2}(d_1d_2)$$
{% endtab %}
{% endtabs %}

{% hint style="success" icon="fire-flame-curved" %}
Don't forget that the area of a triangle is found using $$\frac{1}{2}bh$$.
{% endhint %}

[^1]: This item is the **accepted** definition of a parallelogram, as all of the other plausible items use the starred one to be proven true.

    $$\text{}$$

    This means that all the other definitions can be considered as _properties_ and _theorems_ as well.

[^2]: This includes the property of a kite, as rhombi are kites.

[^3]: As they have two pairs of parallel sides.

    $$\text{}$$

    A trapezoid has _**at least**_ one pair of parallel sides, not exactly.

[^4]: As they are parallelograms.

[^5]: As they are rectangles and rhombi.

[^6]: The third side refers to the side of the triangle that is **not** connected to the midsegment.

[^7]: I made this name up. Don't use it officially.
