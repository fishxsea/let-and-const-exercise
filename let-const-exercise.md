**Old Way**
```javascript
var PI = 3.14;
PI = 42; // stop me from doing this!
```

---

**ES2015**
```javascript
const PI = 3.14;
PI = 42; // PI cannot be reassigned anymore.
```

---

_**What is the difference between var and let?**_
- var can be reassigned or redeclared while let can only be reassigned.
- let is block scoped while var is not.

_**What is the difference between var and const?**_
- var can be reassigned or redeclared while const cannot be reassigned nor redeclared.
- const is block scoped while var is not.

_**What is the difference between let and const?**_
- let can be reassigned while const cannot

_**What is hoisting?**
- variable and function declarations are moved to the top of their containing scope during the compilation.
