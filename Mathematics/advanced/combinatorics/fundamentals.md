---
description: 'Timestamp: 23:00'
---

# Basic Counting

**Counting** is one of the most basic tasks in mathematics. The mail goal is to—obviously—tell how many objects there are without actually [counting them one by one](#user-content-fn-1)[^1].

## Rule of Sum

<details>

<summary><i class="fa-note">:note:</i> Rule of Sum</summary>

If there are $$n$$ objects in the first set and $$k$$ objects in the second set, then there are $$n+k$$ objects in total.

{% hint style="info" %}
**Example** — If we have 3 red apples and 8 green apples, we have 11 apples in total.
{% endhint %}

[Also see better definition...](https://rss-industries.gitbook.io/learn/math/advanced/combinatorics/fundamentals#rule-of-sum-in-set-language)

</details>

### Wrong Applications

If the sets overlap, then the result of applying the Rule of Sum is inflicted, being higher than the actual answer.

#### Example

What if we were asked to **count all the integers from 1 to 10 that are divisible by 2 or by 3**.

1. There are _5 integers_ from 1 to 10 that are divisible by 2: $$\{2,4,6,8,10\}$$.
2. There are _3 integers_ from 1 to 10 that are divisible by 3: $$\{3,6,9\}$$.

<details>

<summary><i class="fa-arrow-progress">:arrow-progress:</i> Applying The Rule of Sum</summary>

If we apply the Rule of Sum, we get $$5+3=8$$. That must mean that there are 8 integers from 1 to 10 divisible by 2 or 3.

</details>

<details>

<summary><i class="fa-arrow-progress">:arrow-progress:</i> Counting Directly</summary>

If we count directly, we get that 7 integers are divisible by 2 or 3: $$\{2,3,4,6,8,9,10\}$$.

This contradicts the usage of the Rule of Sum because 6 is in both sets and is counted twice when using the Rule of Sum.

</details>

{% hint style="info" icon="circle-info" %}
_**No**_ object should belong to both sets when applying the Rule of Sum!
{% endhint %}

## Sets

A **set** is an arbitrary group of arbitrary objects and tend to be denoted by capital letters. In this notation, [order doesn't matter](#user-content-fn-2)[^2]. Additionally, [repetition doesn't matter](#user-content-fn-3)[^3].

### Set Notation

Sets can be given as a list of its elements: $$S=\{1,2,3,4,5\}$$, $$P=\{2,6,1,7,12\}$$. $$S$$ and $$P$$ are both two different sets declared by their elements.

Sets can be viewed using a venn diagram, with each circle equating to a set. **Intersections** are when two sets contain common elements. The intersection of two sets is defined as the set of all elements common between those two sets: $$S\cap{}P=\{1,2\}$$.

**Unions** are when two sets are combined into a larger set. The union of two sets is defined as the set of all elements that are in _**at least one**_ of the sets: $$S\cup{}P=\{1,2,3,4,5,6,7,12\}$$.

The number of elements in a set can be denoted like this: $$|A|$$.

{% hint style="info" icon="circle-info" %}
Sets may be _infinite_ or _zero_. Sets with nothing in them are referred as an empty set: $$B = \{\emptyset{}\}$$.
{% endhint %}

## Generalizing The Rule of Sum

<details>

<summary><i class="fa-note">:note:</i> Rule of Sum (in set language)</summary>

If there is a set $$A$$ with $$n$$ elements, a set $$B$$ with $$k$$ elements, and [these sets do not have common elements](#user-content-fn-4)[^4], then the set $$A\cup{}B$$ has $$n+k$$ elements.

</details>

{% hint style="success" icon="fire-flame-curved" %}
In order to count $$|A\cup{}B|$$ where elements are common in both sets, subtract the elements that were counted twice.
{% endhint %}

## Recursive Counting

### Number of Paths

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Screenshot 2026-02-18 at 2.35.52 PM.png" alt="" width="563"><figcaption><p>Image 1 — Paths example diagram.</p></figcaption></figure></div>

<details open>

<summary><i class="fa-seal-question">:seal-question:</i> Paths Example Question</summary>

Suppose there are several points connected by arrows. The [starting point](#user-content-fn-5)[^5], $$s$$, and [final point](#user-content-fn-6)[^6], $$t$$, are denoted. How many different ways are there to get from $$s$$ to $$t$$?

</details>

You can use the Rule of Sum to answer this question.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Screenshot 2026-02-20 at 2.38.20 PM.png" alt="" width="563"><figcaption><p><strong>Image 2</strong> — Completeion of path example question.</p></figcaption></figure></div>

***

{% hint style="danger" icon="trowel-bricks" %}
This page is incomplete!
{% endhint %}

[^1]: Though this works for small sums, calculating the larger sums takes too long.

    ㅤ

    If only there was a quicker way...

[^2]: $$\{1,2,3,4\}$$ is the same set as $$\{2,4,1,3\}$$.

[^3]: $$\{1,3,2,3,4,4\}$$ is the same set as $$\{1,2,3,4\}$$.

[^4]: $$A\cap{}B=\{\emptyset{}\}$$

[^5]: Also known as the **source**.

[^6]: Also known as the **sink**.
