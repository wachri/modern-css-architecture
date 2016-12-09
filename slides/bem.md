## BEM
(Block Element Modifier)


---
### What is BEM
It is a naming methodology which helps us to avoid bad practices.

---
### Syntax
```
.block {}
.block__element {}
.block--modifier {}
```


```
.site-search {} /* Block */
.site-search__field {} /* Element */
.site-search--full {} /* Modifier */
```

http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/

---
### Why BEM
* Avoid inheritance
* Reduces the specificity to a minium level
* Transparency in the meaning of the classes
* Helps structuring your code
* Helps writing reusable code

---
### SASS and BEM
```
.block {
  &__element {
    background-color: #ff0;

    &--modifier {
      background-color: #fff;
    }
  }
}
```

get's in css
```
.block__element {
  background-color: #ff0;
}
.block__element--modifier {
  background-color: #fff;
}
```

---
### Bad practices in BEM

```
.block__elem1__elem2
```

* Blocks are the only entities that support nested structure
* A block is a namespace
* Hinders the ability to change the internal structure of a block

