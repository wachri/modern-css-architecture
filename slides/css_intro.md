## CSS
(a short overview)

---
### Basics
* CSS = Cascading Style Sheets
* Styles from a parent node underlaying the cascading. This means that (most of the styles) cascade down to child nodes
* [Selectors are matched from right to left](http://stackoverflow.com/questions/5797014/why-do-browsers-match-css-selectors-from-right-to-left)
* A selector has a specificity
* Selectors with a greater specificity can override styles with a lower specificity
* The selector `.class1 .class2` has a greater specificity as only `.class`
* If both selectors have the same specificity the position in the stylesheet matters


---
### Selectors are
* ID, e.g. `#header`
* Class, e.g. `.promo`
* Type, e.g. `div`
* Adjacent sibling, e.g. `h2 + p`
* Child, e.g. `li > ul`
* Descendant, e.g. `ul a`
* Universal, i.e. `*`
* Attribute, e.g. `[type="text"]`
* Pseudo-classes/-elements, e.g. `a:hover`

---
### Specificity depends on
(in order of the specificity)

1. Type of the selector (Elements, classes, Ids)
1. If it is inline
1. Is is flaged with `!important`

---
### Specificity calculation
https://css-tricks.com/specifics-on-css-specificity/#article-header-id-0

---
### CSS Specifishity
http://blog4coders.com/wp-content/uploads/2014/07/speciphicity.jpg