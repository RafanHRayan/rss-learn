---
description: Ratio proportionality, ...
tags:
  - tag: unfinished
    primary: true
---

# Similar Polygons

We have previously learned that polygons are congruent if and only if all of their corresponding parts are congruent. Polygons are **similar** if and only if all of their corresponding _angles_ are congruent and all of their corresponding _sides_ are **proportional**.

$$
\triangle{ABC} \sim{} \triangle{DEF} \\ \therefore{\angle{A}\cong{}\angle{D}}, \\ \therefore{\angle{B}\cong{}\angle{E}}, \\ \therefore{\angle{C}\cong{}\angle{F}}, \\ \therefore{\frac{AB}{DE}=\frac{BC}{EF}=\frac{AC}{DF}}
$$

## Ratio Proportionality

<details>

<summary><i class="fa-note">:note:</i> <a data-footnote-ref href="#user-content-fn-1">Congruent Height Proportionality Theorem</a></summary>

If two triangles have the same height, then the ratio of their _bases_ is equivalent to the ratio of their _areas_.

</details>

<details>

<summary><i class="fa-note">:note:</i> Triangle Proportionality Theorem</summary>

A line which meets two sides of a triangle divides those sides proportionally if and only if it is parallel to the third side.

<div data-with-frame="true"><figure><img src="https://homework.study.com/cimages/multimages/16/tripropthm1321525356847303701.jpg" alt=""><figcaption></figcaption></figure></div>

</details>

<details>

<summary><i class="fa-note">:note:</i> Angle Bisector Theorem</summary>

If an angle bisector is drawn in a triangle, it divides the opposite side such that the pieces are proportional to the other two sides.

</details>

### Proportions

An equation is a **proportion** if and only if it states that two ratios are equivalent. Assuming we know that...

$$
\frac{a}{b}=\frac{x}{y}
$$

The following are true...

* The **means** and **extremes** of the proportion are below.
  * $$b$$ and $$x$$ are the means of the proportion.
  * $$a$$ and $$y$$ are the extremes of the proportion.
* Multiply the means together, multiply the extremes together, and set the two products to be equivalent to each other. Solve for the desired variable; the solutions for all four are below.
  * $$a=\frac{bx}{y}$$
  * $$b=\frac{ay}{x}$$
  * $$x=\frac{ay}{b}$$
  * $$y=\frac{bx}{a}$$

{% hint style="info" icon="circle-info" %}
The means and extremes of a proportion can flip, as long as they are [on opposite sides of the fraction bar from each other](#user-content-fn-2)[^2].
{% endhint %}

### Scale Factors

A constant is the **scale factor** of two similar polygons if and only if it is the ratio of any pair of corresponding side lengths.

## Radicals

Radicals are the _inverse_ of exponents.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/download.png" alt="" width="169"><figcaption><p><strong>Image 1</strong> — The parts of a radical.</p></figcaption></figure></div>

The **radical sign** is the actual √. The **radicand** is the number under the radical symbol. The **index** is the small superscripted number.

The index tells what exponentiation base to find. For example, if it is attempted to solve for  $$\sqrt[3]{8}$$, the answer would be 2, as $$2*2*2=2^3=8$$.

Radicals can also have a coefficient with them, as in $$2\sqrt{24}$$.

### Operations With Radicals

To add or subtract radicals together, treat the radicals as variables. [In radicals with a like radicand and index, the coefficients can be added or subtracted from each other](#user-content-fn-3)[^3].

To multiply radicals together, [multiply the coefficients together and the radicands together](#user-content-fn-4)[^4]. Only radicals of like indexes can be multiplied.

### Simplifying Radicals

To simplify radicals, find two factors that multiply to the radicand such that one or both of the factors are perfect squares. Thus, you can [simplify the perfect square](#user-content-fn-5)[^5].

## Similarity Postulates

<details>

<summary><i class="fa-note">:note:</i> AA Similarity Postulate</summary>

If two triangles have two pairs of congruent corresponding angles, then they are similar.

</details>

<details>

<summary><i class="fa-note">:note:</i> SAS Similarity Postulate</summary>

If two triangles have two pairs of proportional corresponding sides and congruent included angles, then they are similar.

</details>

<details>

<summary><i class="fa-note">:note:</i> SSS Similarity Postulate</summary>

If two triangles have all of their corresponding sides proportional, then they are similar.

</details>

## Right Triangle Trigonometry

### Composition of a Right Triangle

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/pythag02.gif" alt="" width="224"><figcaption><p><strong>Image 2</strong> — The composition of a right triangle.</p></figcaption></figure></div>

### The Right Triangle Altitude Theorem

There are three paths/versions of this theorem, all of which are essential to understanding right triangles. All three are derived after dropping an altitude down to the hypotenuse form the right angle.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image.png" alt="" width="444"><figcaption><p><strong>Image 3</strong> — A right triangle with an altitude dropped down to the hypotenuse.</p></figcaption></figure></div>

<details>

<summary><i class="fa-note">:note:</i> Path of Similarity</summary>

If an altitude is drawn to the hypotenuse of a right triangle, then the two resulting triangles are each similar to each other and the original triangle.

<p align="center"><span class="math">\triangle{ABC}\sim{}\triangle{ACD}\sim{}\triangle{CBD}</span></p>

</details>

<details>

<summary><i class="fa-note">:note:</i> Path of Altitude as a Geometric Mean</summary>

If an altitude is drawn to the hypotenuse of a right triangle, then its length is the geometric mean of the sections of the hypotenuse.

<p align="center"><span class="math">\frac{CD}{AD}=\frac{BD}{CD}</span></p>

</details>

<details>

<summary><i class="fa-note">:note:</i> Path of Legs as Geometric Means</summary>

If an altitude is drawn to the hypotenuse of a right triangle, then its legs are the geometric mean of the hypotenuse and the section of the hypotenuse that is adjacent to the leg.

<p align="center"><span class="math">\frac{AC}{AB}=\frac{AD}{AC}</span>, <span class="math">\frac{BC}{AB}=\frac{BD}{BC}</span></p>

</details>

[^1]: This name is made up. Do not use it officially.

[^2]: i.e. one mean is the _numerator_ of the first ratio and the other is the _denominator_ of the second ratio.

[^3]: You can simplify these...

    $$3\sqrt{12}+8\sqrt{12}=11\sqrt{12}$$,

    $$7\sqrt{5}-\sqrt{5}=6\sqrt{5}$$,

    $$5\sqrt{6}-8\sqrt{7}+2\sqrt{6}=7\sqrt{6}-8\sqrt{7}$$,

    ㅤ

    ...but not these...

    $$2\sqrt{7}+\sqrt{3}$$,

    $$8\sqrt{16}-12\sqrt{5}$$.

[^4]: You can simplify these...

    $$3\sqrt{3}*6\sqrt{2}=18\sqrt{6}$$,

    $$2\sqrt{7}*\sqrt{11}=2\sqrt{77}$$,

    ...but not this...

    $$\sqrt[3]{11}*4\sqrt{7}$$.

[^5]: $$\sqrt{75}=\sqrt{25}\sqrt{3}=5\sqrt{3}$$.
