# css-for-omni

CSS demo

The oCSS object does all the heavy lifting. All you need to do is create the object inside the $construct of any object where you want use "CSS".

The only required parameter is to pass in a reference to the container where you want the CSS to be in effect.

In this example, I've chosen extreme colors to demonstrate differences, not because any of these look good together.

To make this work throughout the program, place the object in the primary window superclass and it will work throughout the whole application.

In the current example, I've made decorators for Group Box, Headed Listbox, Entry Field, Multiline Entry Field, Tab Pane, Push Button, and a background wash component to put a wash on the background.

The current theme could be read from a preferences row in the database and applied to each type of object in the window. In this way, you could allow users to set the colors and style for any type of object from a preferences pane.
