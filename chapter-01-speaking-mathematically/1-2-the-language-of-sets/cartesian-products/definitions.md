## Definitions

### Ordered Pair

> Given elements `a` and `b`, the **ordered pair** `(a, b)` consists of `a` as the first element and `b` as the second element.

Equality of ordered pairs:

```
(a, b) = (c, d) ⇔ a = c and b = d
```

### Ordered n-tuple

> For a positive integer `n` and elements `x1, x2, …, xn`, the **ordered n-tuple** `(x1, x2, …, xn)` preserves order and multiplicity.

Equality of n-tuples:

```
(x1, x2, …, xn) = (y1, y2, …, yn) ⇔ x1 = y1, x2 = y2, …, xn = yn
```

* 2-tuple → ordered pair
* 3-tuple → ordered triple

### Cartesian Product

> Given sets `A1, A2, …, An`, the **Cartesian product** is:
>
> ```
> A1 × A2 × … × An = { (a1, a2, …, an) | a1 ∈ A1, a2 ∈ A2, …, an ∈ An }
> ```

* The Cartesian product of two sets `A × B` contains all ordered pairs `(a, b)` with `a ∈ A` and `b ∈ B`.
* Products can be nested: `(A × B) × C` forms pairs whose first element is itself a pair.
* `R × R` represents the Cartesian plane, mapping points `(x, y)` to the plane.

### Strings

> A **string of length n over a set A** is an ordered n-tuple of elements of `A` written without parentheses or commas.

* The elements of `A` are called **characters**.
* The null string, denoted `λ`, has length 0.
* If `A = {0, 1}`, strings are called **bit strings**.