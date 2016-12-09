## Browser Rendering
(or how our code get's displayed on the screen)

---
### Main flow
1. Bytes → characters → tokens → nodes → object model.
1. Render Tree
1. Layout
1. Painting
1. Display


---
### Object Models
* HTML markup get's transformed into the Document Object Model (DOM)
* CSS markup is transformed into the CSS Object Model (CSSOM)


---
### The render tree
![building the render tree](./slides/img/render-tree-construction.png)
[Image Source](https://apps.developers.google.com/web/fundamentals/performance/critical-rendering-path/render-tree-construction?hl=de)


---
### Layout
Each node get's its exact coordinates where it should appear on the screen


---
### Painting
Traversal over the tree and painting



