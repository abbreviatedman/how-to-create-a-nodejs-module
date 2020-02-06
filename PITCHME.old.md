## Converting Data Types In JavaScript

#### How And Why To Do It Manually

---
## JavaScript On Automatic


JavaScript can "implicitly convert" (or "coerce") values to different types for you.

@snap[code-noblend]
```javascript
alert("5" * "5");
// -> 25

alert('5 times 5 is ' + 25);
// -> "5 times 5 is 25"
```
@snapend

---

## This Can Be Very Helpful!

User input often comes in as type String.

When Taylor types in her age, your app receives the String **"22"**, *not* the Number **22**.

