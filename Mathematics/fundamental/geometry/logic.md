---
description: Statements, logical connectives, and proofs.
---

# Logic

## Statements

**Logic** is a [two-valued system](#user-content-fn-1)[^1]. In logic, statements are sentences that can _either_ have the value true or the value false. Statements can be closed or open.

**Open statements** are ambiguous, making their truth value dependent on the substitution or variable; the substitutions that make the open statement true are part of the solution set. **Closed statements**, on the other hand, have a definite truth value. Closed statements cannot have a solution set because they always have _one_ truth value.

Statements can also be **negated**, in which their truth value will flip[^2]. In English-language statements, this is generally indicated with either the word “not” or the phrase “it is not the case that.” The symbol for negation in its [shortened format](#user-content-fn-3)[^3] is generally a $$\text{}\neg{}$$ that will come right before the statement.

### Compound Statements

**Simple statements** are [statements with only one letter or boolean](#user-content-fn-4)[^4]. **Compound statements**, however, consist of one or more simple statements and _at least_ one **connective**.

### Truth Tables

A **truth table** shows all the possible truth value combinations for a compound statement. All simple and compound statements are given columns. The cases for compound statements are determined by the truth values for the cases for simple statements. Truth tables are used to help find statements with logical equivalence. Two statements are **logically equivalent** if they have identical truth values.

There are two special cases inside truth tables. **Tautologies** are when statements are _true_ in _every_ case. **Contradictions** are when statements are _false_ in _every_ case.

## The Junction Connectives

There are two different types of junction connectives.

The **conjunction** is the logical “and” operator. The conjunction can only be true if _**both**_ simple statements are true; it is, otherwise, false. The symbol for conjunctions in its [shortened format](#user-content-fn-5)[^5] is with a $$\land{}$$ that is between the simple statements.

The **disjunction** is the logical “or” operator. The conjunction will be true if _**at least one**_ of the simple statements is true; if both are false, the disjunction is false. The symbol for disjunctions in its [shortened format](#user-content-fn-6)[^6] is with a $$\lor{}$$ that is between the simple statements.

{% hint style="info" icon="circle-info" %}
Compound statements can have more than one connective (i.e. $$p \land{}(q\lor{}r)$$).
{% endhint %}

## The Conditional Connective

A **conditional** is when the former statement _necessarily implies_ the latter statement. The former statement is called the **antecedent**. The latter statement is called the **consequent**. In English-language statements, this is generally indicated with the layout “If \_\_\_, then \_\_\_.” The symbol for conditionals in its [shortened format](#user-content-fn-7)[^7] is with a $$\text{}\rightarrow{}$$ that is between the simple statements.

The conditional is true if _**both**_ the antecedent and consequent are true _or_ if the antecedent is _false_. This is because a true antecedent and a false consequent would break the conditional. The antecedent necessarily implies the consequent, so the consequent must be true if the antecedent is true. If the antecedent is false, however, whether the consequent if true or false, the conditional will always be true. This is because of **vacuous truths**.

{% hint style="info" icon="circle-question" %}
If the antecedent is false, the conditional will _not_ break regardless of the consequent's truth value. The statement is true in either instance by _virtue_ of the false antecedent.

In other words, the antecedent necessarily implies the consequent, but the consequent doesn't imply the antecedent.
{% endhint %}

## Logical Order of Operations

The order in which logical operations are performed are as follows...

1. Parentheses
2. Negations
3. Conjunctions
4. Disjunctions
5. Conditionals

## Conditional Cases

### Converse, Inverse, and Contrapositive

If you were given the base conditional $$J\rightarrow{}M$$, the following would be true.

The **inverse** of the statement would be the result of _negating_ both the antecedent and consequent, resulting in $$\neg{}J\rightarrow{}\neg{}M$$.

The **converse** of the statement would be the result of _swapping the positions of_ both the antecedent and consequent, resulting in $$M\rightarrow{}J$$.

The **contrapositive** of the statement would be the result of _both negating and swapping positions of_ both the antecedent and consequent, resulting in $$\neg{}M\rightarrow{}\neg{}J$$.

{% hint style="info" icon="circle-info" %}
The base conditional and its contrapositive are logically equivalent. The inverse and converse of the base conditional are also logically equivalent.
{% endhint %}

### The Hidden Conditional Cases

**Hidden conditionals** are written as English-language statements, but are actually conditional statements. The cases are listed as follows...

<details>

<summary><i class="fa-note">:note:</i> The When Case</summary>

**Example:** “I bring my own bags when I go to the grocery store.”

**Converted:** “If I go to the grocery store, then I bring my own bags.”

**Template:** “\[consequent] when \[antecedent].”

</details>

<details>

<summary><i class="fa-note">:note:</i> The Unless Case</summary>

**Example:** “I won’t plant anything unless the soil tests well.”

**Converted:** “If the soil doesn’t test well, then I won’t plant anything.”

**Template:** “\[negated consequent] unless \[negated antecedent].”

</details>

<details>

<summary><i class="fa-note">:note:</i> The Only If Case</summary>

**Example:** “I cry only if I’m sad.”

**Converted:** “If I’m sad, then I cry.”

**Template:** “\[consequent] only if \[antecedent].”

</details>

<details>

<summary><i class="fa-note">:note:</i> The Every Case</summary>

**Example:** “Every NBA player is taller than me.”

**Converted:** “If they are an NBA player, then they are taller than me.”

**Template:** “Every \[antecedent] is \[consequent].”

</details>

<details>

<summary><i class="fa-note">:note:</i> The Not x If y Case</summary>

**Example:** “No wild grizzly bears live in New York.”

**Converted:** “If it is a grizzly bear, then it doesn’t live in New York.”

**Template:** “No \[antecedent] \[negated consequent].”

</details>

These conditionals are hard to discern, so beware of them.

## The Biconditional

The **biconditional** is when both statements necessarily imply each other. In English-language statements, this is generally indicated with the phrase [“if and only if.”](#user-content-fn-8)[^8] The symbol for biconditionals in its [shortened format](#user-content-fn-9)[^9] is a $$\text{}\leftrightarrow{}$$ that is in between the simple statements.

The biconditional is only true if both statements are true _or_ both statements are false. In short, both simple statements must be the same truth value for the biconditional to be true, meaning they must be logically equivalent.

## Arguments

A set of statements is an **argument** if and only if it includes at least one **premise** and exactly one **conclusion**. In English-language statements, this is generally indicated with the word “therefore” right before the conclusion. The symbol for arguments in its shortened format is ∴ that is in between the simple statements. One example is the following...

$$
A\land{}B \\ A\rightarrow{}C \\ \neg{}B \\ \therefore{}C
$$

An argument is **valid** if and only if its premises necessarily imply its conclusion. An argument is **sound** if and only if it is valid _and_ its premises are true.

## Rules and Laws

The following list of rules and laws will help prove different arguments.

<details>

<summary><i class="fa-note">:note:</i> DeMorgan's Laws</summary>

If a junction is inside negated parentheses, each simple statement is negated and the junction symbol is switched to the other.

$$\neg{}(A\land{}B) \\ \therefore{}\neg{}A\lor{}\neg{}B$$

$$\neg{}(P\lor{}\neg{}Q) \\ \therefore{}\neg{}P\land{}Q$$

</details>



<details>

<summary><i class="fa-note">:note:</i> Modus Ponens</summary>

If a conditional is true and its antecedent is true, the consequent must also be true.

$$Z\rightarrow{}\neg{}G \\ Z \\ \therefore{}\neg{}G$$

</details>

<details>

<summary><i class="fa-note">:note:</i> Modus Tollens</summary>

If a conditional is true and its consequent is false, the antecedent must also be false.

$$Q\rightarrow{}R \\ \neg{}R \\ \therefore{}\neg{}Q$$

</details>

<details>

<summary><i class="fa-note">:note:</i> Chain Rule</summary>

If a first statement implies a second statement and the second statement implies a third statement, the first statement will also imply the third statement.

$$A\rightarrow{}B \\ B\rightarrow{}C \\ \therefore{}A\rightarrow{}C$$

</details>



<details>

<summary><i class="fa-note">:note:</i> Conjunction Rule</summary>

If two statements are true, the conjunction of those two statements is also true.

$$A \\ B \\ \therefore{}A\land{}B$$

</details>

<details>

<summary><i class="fa-note">:note:</i> Conjunction Elimination Rule</summary>

If a conjunction is true, the two statements are also true.

$$X\land{}Y \\ \therefore{}X \\ \therefore{}Y$$

</details>



<details>

<summary><i class="fa-note">:note:</i> Disjunction Introduction Rule</summary>

If a statement is true, any disjunction containing the statement is true.

$$A \\ \therefore{}A\lor{}B$$

</details>

<details>

<summary><i class="fa-note">:note:</i> Disjunctive Syllogism Rule</summary>

If a disjunction is true and one of the statements is false, the other statement is true.

$$W\lor{}\neg{}E \\ E \\ \therefore{}W$$

</details>



<details>

<summary><i class="fa-note">:note:</i> Double Negation Rule</summary>

A statement that has been negated twice is equivalent to the original statement.

$$\neg{}\neg{}X \\ \therefore{}X$$

</details>

<details>

<summary><i class="fa-note">:note:</i> <a data-footnote-ref href="#user-content-fn-10">Law of the Contrapositive</a></summary>

If a conditional is true, its contrapositive is also true.

$$P\rightarrow{}\neg{}Q \\ \therefore{} Q\rightarrow{}\neg{}P$$

</details>

## Writing Proofs

### Direct Proofs

**Direct proofs** are given in the following two-column format.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/The Thick Document of High School Courses (1).png" alt="" width="563"><figcaption><p><strong>Image 1</strong> — How to write a direct proof.</p></figcaption></figure></div>

In the event that an argument is given with English-language statements, a key may be given where each simple statement is represented by a letter. Those letters can then be used to prove the argument.

### Indirect Proofs

[**Indirect proofs**](#user-content-fn-11)[^11] prove an argument implicitly by assuming the conclusion is false. After this assumption leads to a contradiction, the conclusion is therefore proven to be true.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/The Thick Document of High School Courses (2).png" alt="" width="563"><figcaption><p><strong>Image 2</strong> — How to write an indirect proof.</p></figcaption></figure></div>

Both proofs are good methods in proving an argument.

[^1]: Consisting of true and false.

[^2]: True to false or false to true.

[^3]: i.e. $$\neg{}p$$.

[^4]: i.e. $$p$$ or “Roses are red.”

[^5]: i.e. $$p\land{}q$$.

[^6]: i.e. $$p\lor{}q$$.

[^7]: i.e. $$p\rightarrow{}q$$.

[^8]: Or the shortened form “iff” (intentionally with two letter f's).

    $$\text{}$$

    Mathematicians are lazy, so they used this shortened form more often.

[^9]: i.e. $$p\leftrightarrow{}q$$.

[^10]: Also called the Contraposition Rule.

[^11]: Also known as proofs by contradiction.
