##### How did you determine which rules should be placed in each new CSS file?

The way I determined which rules should go in which files was by following these simple rules from SMACSS
- Base rules are applied to elements using an element selector, a descendent selector, or a child selector, along with any pseudo- classes. It doesn’t include any class or ID selectors. So I moved all element only selectors or ones with descendantes to the base.css
- Layout rules generally have a single selector: a single ID or class name. I moved all styles with singe id's or classes to layout.css. I realize that some times two selectors might be needed (ie. .l-flipped #article).
- Module components usually don't use IDs or element selectors, sticking only to class names. A module will likely contain a number of elements and there is likely to be a desire to use descendent or child selectors to target those elements.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I didn't refactor the code. I looked at the files but I did not catch anything that needed refactoring.