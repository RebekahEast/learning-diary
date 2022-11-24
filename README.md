# Learning Diary
A daily journal of my learnings in CSS

<hr>
<h2> 24.11.2022 - CSS </h2>

- Specificity - EXAMPLE 

![Screenshot 2022-11-24 at 16 46 16](https://user-images.githubusercontent.com/109970293/203834039-0d9aeb9b-c471-4a10-9df0-5d9bac7f94cc.png)

In the example code above, the color of the heading would be set to firebrick, as the class selector is more specific than the type selector. If an ID attribute (and selector) were added to the code above, the styles within the ID selector’s body would override all other styles for the heading.

Over time, as files grow with code, many elements may have IDs, which can make CSS difficult to edit since a new, more specific style must be created to change the style of an element.

To make styles easy to edit, it’s best to style with a type selector, if possible. If not, add a class selector. If that is not specific enough, then consider using an ID selector.

- Chaining - EXAMPLE

![Screenshot 2022-11-24 at 16 47 22](https://user-images.githubusercontent.com/109970293/203834246-d803d2a2-1609-4a91-8f0d-9e27cc268c98.png)

The code above would select only the h1 elements with a class of special. If a p element also had a class of special, the rule in the example would not style the paragraph.
<hr>

