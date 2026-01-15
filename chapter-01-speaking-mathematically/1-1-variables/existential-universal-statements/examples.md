## Examples

### Example 1: Positive Integer

Original statement:
`There is a positive integer that is less than or equal to every positive integer.`

Equivalent rewrites:

1. `Some positive integer is less than or equal to every positive integer.`
2. `There is a positive integer m that is less than or equal to every positive integer.`
3. `There is a positive integer m such that every positive integer is greater than or equal to m.`
4. `There is a positive integer m with the property that for every positive integer n, m <= n.`

---

### Example 2: Age in Class

Original statement:
`There is a person in my class who is at least as old as every person in my class.`

Rewrites:

1. `Some person in my class is at least as old as every person in my class.`
2. `There is a person p in my class such that p is at least as old as every person in my class.`
3. `There is a person p in my class with the property that for every person q in my class, p is at least as old as q.`

**Solution Fill-ins**

* Blank 1: `person in my class; every person in my class`
* Blank 2: `at least as old as every person in my class`
* Blank 3: `at least as old as q`

---

### Example 3: Limits of Sequences

Some of the most important mathematical concepts, such as the definition of the **limit of a sequence**, require existential universal statements combined with conditional statements.

**Statement**
Let `a1, a2, a3, ...` be a sequence of real numbers. Saying that the limit of `an` as n approaches infinity is `L` means:

* For every positive real number ε,

  * there is an integer N such that

    * for every integer n, if n > N then `-ε < an - L < ε`.

This shows how **for every**, **there is**, and **if-then** are used together in rigorous definitions.