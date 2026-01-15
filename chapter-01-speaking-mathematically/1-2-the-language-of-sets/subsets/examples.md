## Examples

### Example 1: Evaluating Subset Statements

Let:

* `A = Z+` (positive integers)
* `B = {n ∈ Z | 0 ≤ n ≤ 100}`
* `C = {100, 200, 300, 400, 500}`

Evaluate the following:

1. `B ⊆ A` → **False**
   Zero is in B but not in A.

2. `C` is a proper subset of `A` → **True**
   All elements of C are in A, but A contains elements (like 1) not in C.

3. `C` and `B` have at least one element in common → **True**
   Example: 100 is in both sets.

4. `C ⊆ B` → **False**
   200 is in C but not in B.

5. `C ⊆ C` → **True**
   Every set is a subset of itself.

---

### Example 2: Distinguishing ∈ and ⊆

Determine which statements are true:

a. `2 ∈ {1, 2, 3}` → **True**
b. `{2} ∈ {1, 2, 3}` → **False**
c. `2 ⊆ {1, 2, 3}` → **False**
d. `{2} ⊆ {1, 2, 3}` → **True**
e. `{2} ⊆ {{1}, {2}}` → **False**
f. `{2} ∈ {{1}, {2}}` → **True**

**Explanation**:

* (b) `{2}` is a set, not an element of `{1, 2, 3}`.
* (c) 2 is a number, not a set, so subset notation does not apply.
* (e) `{2}` is not equal to either `{1}` or `{2}`, so it is not a subset.