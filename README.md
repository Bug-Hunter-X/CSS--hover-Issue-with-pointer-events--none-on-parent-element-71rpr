# CSS :hover Issue with pointer-events: none on parent element

This repository demonstrates a subtle issue with the CSS `:hover` pseudo-class when used in conjunction with `pointer-events: none` on a parent element.  The bug and its solution are explained in the corresponding CSS files (bug.css and bugSolution.css).

**Problem:** The `:hover` pseudo-class may not work as expected on child elements when their parent element has `pointer-events: none` set. This can lead to unexpected behavior in interactive elements. 

**Solution:**  The solution involves adjusting the CSS to handle this situation, possibly by removing `pointer-events: none` if possible or applying a different approach to achieve the desired effect.