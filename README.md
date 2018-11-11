# JavaScript Clean Code
## Best Practices

**What is clean coding?**

Clean coding means that your first priority is writing code for yourself and for your co-workers to easily understand and read and not for the machine.

### What's the best naming convention for variables?

**Use intentional names** and don't worry if your variable names are long.

```
// DON'T
let d
let elapsed
const ages = arr.map((i) => i.age)

// DO
let daysSinceModification
const agesOfUsers = users.map((user) => user.age)
let name
let user
```
**Make your variable names easy to pronounce**

When code reviews are being done, these names are easier to reference.

```
// DON'T
let fName, lName
let cntr

let full = false
if (cart.size > 100) {
  full = true
}

// DO
let firstName, lastName
let counter

const MAX_CART_SIZE = 100
// ...
const isFull = cart.size > MAX_CART_SIZE
```
