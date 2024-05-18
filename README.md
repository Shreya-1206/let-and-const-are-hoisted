# Let And COnst Are Hoisted ☑️

## Index.js

### we can see that we got an Reference Error saying cannot access b before intialization. ☠️
### but we know that incase of var we get a special keyword undefined. 😃
### But using debugger we can easily see let b is hoisted but in Script scope.
### And in memory phase we see value unavailable or undefined before intialization.

### So let and const are also allocated memory but in different memory space.

### Temporal dead zone  - the time since the let b was hoisted and  til when it was intialized  with some value is temporal dead zone.

### We can chk with window that var z is attached with global space but let is not there in global space .... 😁
