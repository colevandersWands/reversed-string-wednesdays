## Copy last letter to next space

```
function reversed_string(string_arg)
  returner <- ""
  
  for letter in string_arg (back to front)
    returner += letter

  return returner
END function
```

---

### Strategy explanation

We will copy the last letter from the string argument into the next available slot
on our returner until there are no more letters left to copy.

---

### Comparison

We came up with multiple versions of this strategy, but we consolidated them all into this file.  
The only other significantly different strategy we found was to map the letters to numbers,
reverse the numbers, and map back to letters.
