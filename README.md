
XCL: Extensible CSS Libraries
=================
Pre-built extensible CSS plugins for isolated use in any context to solve common CSS problems

PURPOSE
=================
These CSS libraries are intended to consolidate CSS code that is
commonly replicated all over the web into several modular plugins.
They are intended to be generic in order to be used for any purpose,
while also being extensible so that any functionality can be
overridden using CSS's 'cascading' functionality.
It has been modelled using some principles of Classes and Inheritance
from Object Oriented Programming, with CSS classes being available
for use as-is, or to be inherited and some properties to be overridden
as required.

INSTRUCTIONS FOR USE
=================
The libraries should be included as @import instructions at the top of
your CSS file. These should be seen as the libraries available in many OOP
languages - they can be used as-is, or inherited and then extended
by adding sub-classes. But they should be treated as read-only.

If you require a change in functionality set the class of the rule
and set the properties you would like to override. See the
Demo/Custom Theme/CSSLibraries.css for examples.
If you want to add an extension, such as a new type of button, add a new
class and add the styles for the button. Then add the class to the button
in the HTML
See Buttons/button-plugins.css for examples

MORE INFORMATION & FEEDBACK
=================
Feedback and code contributions are actively encouraged
If you've created any extensions that you think would be helpful in the main library
files please submit them for consideration
