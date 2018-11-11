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
