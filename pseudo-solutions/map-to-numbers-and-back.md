## Map to numbers and back

```
function reversed_string(string_arg)
  returner <- ""
  
  associate each letter in the string with a number, sequentially
  
  reverse the order of the numbers
  
  map back to the number domain
  
  return returner
END function
```

___

### Strategy Explanation

We want to re-order the letters in our string, numbers are inherantly ordered.  
So we will take advantage of that by associating our letters with numbers, 
ordering the numbers, and mapping back to the letter world.  
In reversing our numbers, we are reversing our string.

___

### Strategy Comparison

This strategy is quite different from our other one. The other strategy is constructive, 
we are building up a solution incrementally. In this strategy we are taking advantage of 
a convenient property of numbers (orderedness) to do our work for us.
