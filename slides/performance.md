## Performance
(Short introduction what matters to improve render performance)

---
### Render blocking resources
There are several sources which are renderblocking by default. This means the browser won't render any thin until the source is
completely loaded or e.g. in case of CSS not until the CSSOM is constructed. 

---
### Render blocking resources are

* CSS
* JavaScript
* Fonts

---
### Repaint
A repaint is triggered when the visibility of an element is changed (e.g. visibility or background color)


---
### Reflow
A reflow is more critical for performance because the layout of some nodes (or the hole page) have to be rerendered
[![IMAGE ALT TEXT](http://img.youtube.com/vi/dndeRnzkJDU/0.jpg)](https://www.youtube.com/watch?v=dndeRnzkJDU "Gecko Reflow Visualization - Wikipedia")

--- 
### What foreces layout / reflow?
https://gist.github.com/paulirish/5d52fb081b3570c81e3a


---
### Example that it matters
[![IMAGE ALT TEXT](http://img.youtube.com/vi/2vFrZXWiwIc/0.jpg)](https://www.youtube.com/watch?v=2vFrZXWiwIc "Troubleshooting rendering performance issues")