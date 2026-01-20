## Examples

### Negation and grouping

Let `p` be the statement "It is raining" and `q` be the statement "It is cold."

* `∼p ∧ q` means “It is not raining and it is cold.”
* `∼(p ∧ q)` means “It is not the case that it is raining and cold.”

These two statements are not equivalent, showing why parentheses are essential.

---

### Translating English words

Many English constructions correspond directly to logical connectives.

* “but” translates the same as “and” when joining independent clauses.
  “It is hot but it is sunny” is logically the same as “It is hot and it is sunny.”

* “neither nor” expresses a conjunction of negations.
  "Neither `p` nor `q`" means "not `p` and not `q`."

**Example**

Let `h` represent "It is hot" and `s` represent "It is sunny."

* “It is not hot but it is sunny” becomes `∼h ∧ s`.
* “It is neither hot nor sunny” becomes `∼h ∧ ∼s`.

---

### Compound statements with inequalities

Logical connectives are embedded in standard mathematical notation.

If `x`, `a`, and `b` are specific real numbers, then:

* `x ≤ a` means "`x < a` or `x = a`"
* `a ≤ x ≤ b` means "`a ≤ x` and `x ≤ b`"

An inequality like `2 ≤ x ≤ 1` is always false because it requires both `2 ≤ x` and `x ≤ 1` to be true simultaneously, which is impossible for any real number.

---

### Symbolic inequalities

Suppose `x` is a particular real number and let:

* `p` represent `0 < x`
* `q` represent `x < 3`
* `r` represent `x = 3`

Then:

* `x ≤ 3` can be written as `q ∨ r`
* `0 < x < 3` can be written as `p ∧ q`
* `0 < x ≤ 3` can be written as `p ∧ (q ∨ r)`

These examples illustrate how compound statements capture mathematical conditions precisely using logical connectives.