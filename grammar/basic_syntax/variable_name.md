### Variable Naming in b2  

In *b2*, variable names can range from short, single letters to descriptive, multi-word names. Following specific rules ensures compatibility and avoids errors.  

---

### Rules for Naming Variables  
1. **Start with a Letter or Underscore**  
   Variable names must begin with a letter (A-Z, a-z) or an underscore (`_`).  

2. **Cannot Start with a Number**  
   A variable name cannot begin with digits (0-9).  

3. **Allowed Characters**  
   Only alphanumeric characters and underscores are permitted (`A-Z`, `a-z`, `0-9`, `_`).  

4. **Case-Sensitive**  
   Variable names are case-sensitive. For example, `age`, `Age`, and `AGE` are distinct variables.  

5. **Avoid Keywords**  
   Variable names cannot use reserved *b2* keywords.  

---

### Examples  

**Legal Variable Names:**  
```b2
myvar := "bittu"
my_var := "bittu"
_my_var := "bittu"
myVar := "bittu"
MYVAR := "bittu"
myvar2 := "bittu"
```

**Illegal Variable Names:**  
```b2
2myvar := "bittu"  // Cannot start with a number
my-var := "bittu"  // Hyphen is not allowed
my var := "bittu"  // Spaces are not allowed
``

---

### Multi-Word Variable Naming Styles  

To improve readability, you can use these conventions for multi-word variable names  

1. **Camel Case**  
The first word starts with a lowercase letter; subsequent words start with an uppercase letter  
```b2
myVariableName := "bittu"
```

2. **Pascal Case**  
Each word starts with an uppercase letter  
```b2
MyVariableName := "bittu"
```

3. **Snake Case**  
Words are separated by underscores  
```b2
my_variable_name := "bittu"
```  

By following these conventions and rules, you can write clear and maintainable *b2* code.