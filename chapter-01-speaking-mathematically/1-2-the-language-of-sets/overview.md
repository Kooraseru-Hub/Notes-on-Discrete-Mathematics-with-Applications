# 1.2 The Language of Sets

## Introduction

A set is a well-defined collection of elements. We can think of it intuitively, following Georg Cantor, as a collection of objects such as numbers, countries, or other mathematical elements.

* **Element notation**:
  `x ∈ S` means x is an element of S
  `x ∉ S` means x is not an element of S

---

## Set-Roster Notation

A set can be written by listing all its elements in braces:

* Example: `{1, 2, 3}`
* Large or infinite sets: `{1, 2, 3, …, 100}` or `{1, 2, 3, …}`
* **Axiom of extension**: The order of elements and repetition do not change the set.

**Examples**:

* `{1, 2, 3} = {3, 1, 2} = {1, 1, 2, 3, 3, 3}`
* `{0} ≠ 0` because `{0}` is a set with one element, 0.
* `{1, {1}}` has two elements: 1 and the set `{1}`.

Special sets of numbers:

| Symbol | Set                  |
| ------ | -------------------- |
| R      | All real numbers     |
| Z      | All integers         |
| Q      | All rational numbers |

Superscripts indicate subsets:

* `R+` positive reals
* `Z_nonneg` nonnegative integers (0, 1, 2, …)

The real number line is **continuous**, while integers are **discrete**, forming the foundation of discrete mathematics.

---

## Set-Builder Notation

A set can also be defined by a property its elements satisfy:

`{ x ∈ S | P(x) }`

* Means “the set of all x in S such that property P(x) is true.”
* Must be used carefully to avoid contradictions.

**Examples**:

* `{x ∈ R | -2 < x < 5}` → all real numbers strictly between -2 and 5
* `{x ∈ Z | -2 < x < 5}` → integers -1, 0, 1, 2, 3, 4
* `{x ∈ Z+ | -2 < x < 5}` → positive integers 1, 2, 3, 4

---

## Summary

* Sets are collections of elements.
* Elements can be listed (set-roster) or defined by a property (set-builder).
* Special symbols (`R, Z, Q`) are standard for common sets of numbers.
* The distinction between continuous and discrete sets underlies discrete mathematics.