## Problem01
---

**Function `fun(w, x)`**

* Set `y = 0`
* **If** `x` is divisible by `w` **OR** `w` is divisible by `x`:

  * Add 1 to `y`
* **Else**:

  * Add 10 to `y`
* Print the value of `y`

**Call** `fun(40, 4)`

---

**Step-by-step Evaluation:**

* `x = 4`, `w = 40`
* Check if:

  * `4 % 40 == 0` → False
  * `40 % 4 == 0` → True
* Since **one** of the conditions is true (using OR), the `if` condition is satisfied.
* So `y = y + 1 → y = 1`
* Print `1`

---

**Output:**

```
1
None
```

