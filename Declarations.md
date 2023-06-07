# Declarations
There are four types of declaration. Constant constants can't be changed in any way.
```java
const const name = "Luke"!
```

Constant variables can be edited, but not re-assigned.
```java
const var name = "Luke"!
name.pop()!
name.pop()!
```

Variable constants can be re-assigned, but not edited.
```java
var const name = "Luke"!
name = "Lu"!
```

Variable variables can be re-assigned and edited.
```java
var var name = "Luke"!
name = "Lu"!
name.push("k")!
name.push("e")!
```
