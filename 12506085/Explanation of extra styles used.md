Explanation of extra styles used : 


**Layout and sizing**



box-sizing: border-box: padding and border stay inside the width you set, so elements don’t grow wider than expected.

flex-wrap: wrap: flex items move to a new line when they run out of space.

gap: 10px: adds even space between flex items.

overflow-x: auto: adds a sideways scrollbar when content, like the table, is too wide for the screen.

height: auto: the image keeps its proportions when its width changes.

display: block: makes an element take its own line, so the image can be centered with margin: auto.



**Borders and shapes**



border-radius: rounds the corners. 50% on the picture makes it a circle.

border-collapse: collapse: merges the table’s double borders into single lines.



**Text and lists**



text-align: centers or left-aligns text.

text-decoration: none: removes the underline from links.

list-style: none: removes the bullets from a list.



**Selectors and states**



:nth-child(odd) and :nth-child(even): pick every other item, which is how the table rows get alternating colors.

:last-child: picks the last item in a group, used to remove the extra space under the final list item.

:valid: styles a form field when what’s typed is accepted. Yours gets a green border.

:active: styles a button at the moment it’s being clicked.

.profile-pic, #about img: the comma styles both selectors with the same rule.



**Forms and small details**



outline: none: removes the browser’s default outline around a focused field. I replaced it with a plum border so users can still see where they’re typing.

cursor: pointer: shows the hand cursor over buttons.

font-family: inherit: makes form fields use the page’s font instead of the browser default.

width: 100% on inputs: makes the fields stretch to fill the form.

