## Examples

### Example 1.3.4 Functions and Relations on Finite Sets

Let `A = {2, 4, 6}` and `B = {1, 3, 5}`. Consider three relations `R`, `S`, and `T` from `A` to `B`:

* `R = {(2, 5), (4, 1), (4, 3), (6, 5)}`
* `S`: Defined by `(x, y) ∈ S` if `y = x + 1`
* `T`: Represented by the arrow diagram (insert diagram PNG here)

**Analysis:**

* `R` is **not a function**. Element `4 ∈ A` is related to both `1` and `3` → violates uniqueness.
* `S` is **not a function**. Element `6 ∈ A` has no image in `B` → violates existence.
* `T` **is a function**. Each element of `A` is mapped to exactly one element of `B`:

```
T(2) = 5
T(4) = 1
T(6) = 1
```

**Observation:** Several domain elements can map to the same co-domain element; this does not violate the definition of a function.

---

### Example 1.3.5 Functions on Sets of Strings

Let `A = {a, b}` and let `S` be the set of all strings over `A`.

1. **Length Function `L`:**
   Define `L : S → Z_nonneg` such that `(s, n) ∈ L` if `n` is the length of string `s`.

```
L(abaaba) = 6
L(bbb) = 3
```

2. **Concatenation Function `C`:**
   Define `C : S → S` such that `(s, t) ∈ C` if `t` is the string obtained by prepending `a` to `s`.

```
C(abaaba) = aabaaba
C(bbb) = abbb
```

**Observation:** Both `L` and `C` satisfy the properties of a function. Each string has exactly one length, and each string is uniquely mapped to another string via prepending.