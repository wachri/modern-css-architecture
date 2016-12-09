## Specificity problems


---
### The specificity war
You increase and increase the specificity to get your styles
applied to your element.

---
### The unsinkable titanic
http://jsfiddle.net/wachri/5011bu2c/

---
### 1 id vs 1000 classes
http://jsfiddle.net/csswizardry/0yb7rque/

---
### Working with high specificity

Bootstrap navbar example:
```
.navbar-default .navbar-nav>.active>a
```

Every time you like to override something you have to increase
the specificity.

---
### Unstructured css code
Often it ends up that new css code is added to the end of the
file or marked as `!important` to the the styles applied.