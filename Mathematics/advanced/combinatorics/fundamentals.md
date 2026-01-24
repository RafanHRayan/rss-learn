# Fundamentals

## Factorials

A **factorial** is the product of all the positive integers from the number taken factorial of to 1. For example, $$5!=5*4*3*2*1=120$$. In other words, $$n! = n*(n-1)*(n-2)*...*1$$.

#### Factorials in Combinatorics

1. The number of ways of arranging $$n$$ objects in a line is $$n!$$.
2. The number of ways of arranging $$n$$ objects in a circle where rotations of the same arrangement aren't considered distinct is $$(n-1)!$$.
3. The number of ways of arranging $$n$$ objects in a circle where rotations of the same arrangement aren't considered distinct and reflections of the same arrangement aren't considered distinct is $$\frac{(n-1)!}{2}$$.

## Permutations

A **permutation** is a possible arrangement of objects in a set where the order of objects matter. The number of ways to arrange $$r$$ objects out of $$n$$ total objects is...

<p align="center"><span class="math">_nP_r = \frac{n!}{(n-r)!}</span></p>

{% hint style="success" %}
## Tip

Usually, the words "permute" and "order does matter" imply permutation. On the other hand, the words "choose", "select", and "order doesn't matter" imply combination.
{% endhint %}

## Word Rearrangements

The number of ways to reorder a word is...

$$
\frac{n!}{d_1!*d_2!*d_3!*...}
$$

where $$n$$ is the number of letters and $$d_1,d_2,d_3...$$ are the number of times each of the letters that occur more than one time appear in the word.

{% hint style="success" %}
## Tip

This isn't just for words! The number of ways of arranging anything else is also the same.&#x20;
{% endhint %}

## Combinations

A combination is a possible arrangement in a collection of items where the order of the selection does not matter. The number of ways to choose $$r$$ objects out of a total of $$n$$ objects is...

$$
\binom{n}{r}=\frac{n!}{r!*(n-r)!}=\frac{n*(n-1)*...*(n-r+1)}{k!}
$$

The notation at the start is typically read as "$$n$$ choose $$r$$".

{% hint style="success" %}
## Tip to Save Time

Notice that $$\binom{n}{r}=\binom{n}{n-r}$$. This is true because we can see choosing $$r$$ objects on the left hand side is equivalent to choosing the $$n-r$$ objects that will not be selected on the right hand side.
{% endhint %}

### Probability

The chance that an outcome will occur out of a number of outcomes. This means that...

$$
\text{probability} = \frac{\text{total number of desired outcomes}}{\text{total outcomes}}
$$

## Subsets

The number of subsets of a set of size $$n$$ is $$2^n$$. There are two choices for each element in the set: part of the set or not part of the set. Since there are $$n$$ elements in the set, the total number of subsets is $$2*2*2*...*2 \hspace{0.2cm} \text{(}n\text{ times)}$$.

{% hint style="warning" %}
## Warning

This would mean that there is an empty subset, which is the scenario in which every element is not part of the set. Remember to check whether this empty subset is counted as valid or not.
{% endhint %}

***

{% hint style="danger" %}
This page is incomplete and is under construction!
{% endhint %}
