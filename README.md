# Convert Units into Percentage

You can convert any unit value into a percentage of a base value.

---

## Step 1: Define the base
Example:
```js
let width = 1200;
let getting = 310;
//percentage = (getting / width) * 100
let percentage = (getting / width) * 100; 
// 25.833333...
//avoid to choose out of range
percentage = Math.max(0, Math.min(percentage, 100));
// if you want to make it round
percentage = Math.round(percentage); 
// 26%
