---
description: 'Timestamp: 3:25'
---

# Basic Counting

**Counting** is one of the most basic tasks in mathematics. The mail goal is to—obviously—tell how many objects there are without actually [counting them one by one](#user-content-fn-1)[^1].

{% hint style="info" %}
## Important Applications

1. Counting the number of steps of algorithms.
2. Computing probabilities.
{% endhint %}

## Rule of Sum

<details>

<summary><i class="fa-note">:note:</i> Rule of Sum</summary>

If there are $$n$$ objects in the first set and $$k$$ objects in the second set, then there are $$n+k$$ objects in total.



{% hint style="info" %}
## Example

If we have 3 red apples and 8 green apples, we have 11 apples in total.
{% endhint %}

</details>

### Wrong Applications

If the sets overlap, then the result of applying the Rule of Sum is inflicted, being higher than the actual answer.

{% hint style="info" %}
## Example

What if we were asked to **count all the integers from 1 to 10 that are divisible by 2 or by 3**.

1. There are _5 integers_ from 1 to 10 that are divisible by 2: $$\{2,4,6,8,10\}$$.
2. There are _3 integers_ from 1 to 10 that are divisible by 3: $$\{3,6,9\}$$.

Applying The Rule of Sum

If we apply the Rule of Sum, we get $$5+3=8$$. That must mean that there are 8 integers from 1 to 10 divisible by 2 or 3.

Counting Directly

If we count directly, we get that 7 integers are divisible by 2 or 3: $$\{2,3,4,6,8,9,10\}$$. This contradicts the usage of the Rule of Sum because 6 is in both sets and is counted twice when using the Rule of Sum.
{% endhint %}

[^1]: Though this works for small sums, calculating the larger sums takes too long.

    ㅤ

    If only there was a quicker way...
