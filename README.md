# Auditng for A11y
## Accessibility Issue 1:
Heading elements are not in a sequentially-descending order
## Failing Element: 
About Me h3 in the content class
## Fix: 
Changed h3 to h2 to fit the sequentially-descending order

## Accessibility Issue 2: 
Background and foreground colors do not have a sufficient contrast ratio
## Failing Elements: 
1. <a href="#"> in <div class="nav">
2. <h3> in <div class="form-section">
3. <div class="footer">
## Fix:
1. Changed the color to #eee in "nav a" class to have the links show clearer against the dark color background.
2. Changed the color to #333 in form-section h3 to appear darker against light background.
3. Changed the color to #eee in footer to show clearer against the dark color background.

## Outcome:
![Picture](Accessbility_Issues.png)