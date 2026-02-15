---
description: Triangle congruence postulates and theorems, cevians, and equidistance.
---

# Triangle Congruence

## Fundamentals

Polygon congruence has a definition which states that two polygons are congruent if and only if all of their _**corresponding parts**_ are congruent. Corresponding parts, similar to corresponding angles are **either side lengths or interior angle measures** that are equivalent. Say we have two congruent triangles, each with side lengths of 7, 3, and 5. The side lengths of 3 are both corresponding parts.

Every $$n$$-gon has $$2n$$ parts, consisting of $$n$$ segments and $$n$$ angles. The parts that correspond depend on the order of the name of the polygon; this is **very** important! For example:

<p align="center"><span class="math">\triangle{ABC}\cong{}\triangle{PST} \\ \therefore{}\angle{A}\cong{}\angle{P}, \\ \therefore{}\angle{B}\cong{}\angle{S}, \\ \therefore{}\angle{C}\cong{}\angle{T}, \\ \therefore{}\overline{AB}\cong{}\overline{PS}, \\ \therefore{}\overline{BC}\cong{}\overline{ST}, \\ \therefore{}\overline{CA}\cong{}\overline{TP}</span></p>

If we were to conclude in this way, we would get **six conclusions from only one premise**! However, if we tried to prove triangle congruence, we would need to first prove six premises.

## Triangle Congruence Shortcuts

### Triangle Congruence Postulates

In order to speed up the process, a few shortcuts (in the form of postulates and theorems) can be used. The following three are all postulates:

<details>

<summary><i class="fa-note">:note:</i> SSS Postulate (Side-Side-Side)</summary>

Two triangles are congruent if and only if they have three pairs of congruent corresponding sides.

</details>

<details>

<summary><i class="fa-note">:note:</i> SAS Postulate (Side-Angle-Side)</summary>

Two triangles are congruent if and only if two pairs of corresponding sides and the included angle of those sides are congruent.

</details>

<details>

<summary><i class="fa-note">:note:</i> ASA Postulate (Angle-Side-Angle)</summary>

Two triangles are congruent if and only if two pairs of corresponding angles and the included side of those angles are congruent.

</details>

### Triangle Congruence Theorems

The following four are all theorems related to proving triangle congruence and concluding from it:

<details>

<summary><i class="fa-note">:note:</i> AAS Theorem (Angle-Angle-Side)</summary>

The AAS Theorem can be proven using the ASA Postulate. And it states that two triangles are congruent if and only if two pairs of angles and the following side are congruent.

</details>

<details>

<summary><i class="fa-note">:note:</i> CPCTC</summary>

Corresponding parts of congruent triangles are congruent.

</details>

<details>

<summary><i class="fa-note">:note:</i> Isosceles Triangle Theorem</summary>

If two sides of a triangle are congruent, then the opposite angles are also both congruent; the vice versa is also true.

</details>

<details>

<summary><i class="fa-note">:note:</i> HL Theorem (Hypotenuse-Leg)</summary>

If two _**right triangles**_ have congruent hypotenuses and one congruent leg, then they are congruent.

</details>

{% hint style="info" %}
## Notes

1. CPCTC is used to conclude the congruence of _**any**_ two corresponding parts from a triangle congruence statement.
2. At first, the Isosceles Triangle Theorem may not look like a theorem that can help with triangle congruence, but this theorem can help speed up the process in proving triangle congruence.
{% endhint %}

## Cevians

A cevian is a line that is dropped from an angle in a triangle down to its opposite side. There are three types of special cevians:

<details>

<summary><i class="fa-note">:note:</i> Median</summary>

A cevian is a median if and only if it intersects the opposite side at the **midpoint**; the vice versa is also true.

</details>

<details>

<summary><i class="fa-note">:note:</i> Altitude</summary>

A cevian is an altitude if and only if it is **perpendicular** to the opposite side; the vice vera is also true.

</details>

<details>

<summary><i class="fa-note">:note:</i> Angle Bisector</summary>

A cevian is an angle bisector if and only if it **bisects** the angle it originates from; the vice versa is also true.

</details>

All triangles can have cevians drawn relative to them, so they can be drawn to help with proofs.

### Uniform Cevian Cases

All three specials cevians are the exact same in only two cases:

1. Any special cevian from _**any angle**_ in any **equilateral triangle** will be the same as every other special cevian in the same triangle from the same angle.
2. Any special cevian from _**only the**_ [_**apex angle**_](#user-content-fn-1)[^1] in any **isosceles triangle** will be the same as every other special cevian in the same triangle from the same angle.

{% hint style="warning" %}
## Warning

When a special cevian is told to be "the same as every other special cevian in the same triangle from the same angle", it means that any median, altitude, or segment bisector from an angle is the same as the other two.

This **does not** mean that there are no other cevians possible for that angle in the same triangle. This holds true for all other angles in triangles with uniform special cevians.
{% endhint %}

{% hint style="success" %}
## Tip

If there are $$n$$ cevians drawn in a triangle, there are $$n+1$$ new triangles as a result.
{% endhint %}

### Special Cases of Altitudes

#### Boundary Altitude Case

In _**right triangles only**_, the altitude dropped from the right angle is always inside the triangle; the other two altitudes are the sides adjacent on either side of the right angle. These altitudes lie _**exactly**_ on the side lengths, and are called boundary altitudes.

#### External Altitude Case

In _**obtuse triangles only**_, the altitude dropped from the obtuse angle is always inside the triangle; the other two altitudes are completely outside of the triangle. These are called external altitudes.

{% hint style="warning" %}
## Warning

These two types of altitude cases are abnormal. Don't forget that they are still altitudes!
{% endhint %}

## Perpendicular Bisector

The perpendicular bisector is a combination of a segment bisector and a perpendicular line. A line is a perpendicular bisector to another line if an only if it is perpendicular to the line _**and**_ bisects the line.

## Equidistance

The distance from a point to a line is measured via the shortest possible way to reach the line. The new line formed by the shortest path is **always** perpendicular to the original line; it is called the perpendicular distance.

Equidistance is when the distance from one point to two separate points are equal in measure. For example, the midpoint of a segment is equidistant from both ends of the segment.

### Equidistance Theorems

There are two important unnamed theorems when talking about equidistance:

<details>

<summary><i class="fa-note">:note:</i> Equidistance From The Endpoints of a Segment</summary>

A point is equidistant from the endpoints of a segment if and only if it lies on the **perpendicular bisector** of the segment.

</details>

<details>

<summary><i class="fa-note">:note:</i> Equidistance From The Rays of an Angle</summary>

A point is equidistant from the rays of an angle if and only if it lies on the **angle bisector** of the angle.

</details>

[^1]: This may also be called the vertex angle.
