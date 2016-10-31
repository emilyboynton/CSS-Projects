#CSS Accordion Menu
This project is a space-saving Accordion Menu with all of the stylings and transitions written in CSS. This project was inspired by a workshop from Treehouse.

##CSS
The labels for each of these menu items has been treated as a radio element. When an input is checked, i.e. a label is clicked, the relevant content is shown and previously shown content disappears.

##Transitions
To get around the problem of not being able to use a height transition for the content, instead I have used a transition for max-height. The max-height "100%" value is equal to slightly larger than the largest .tab-content value. Subtle transitions were also added to the label when clicked, simply for added focus.
