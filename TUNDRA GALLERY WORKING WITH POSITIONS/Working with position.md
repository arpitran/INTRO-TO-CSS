BOUNDARIES AND SPACE
Working with Position
The CSS position property enables you to position HTML elements in exact locations on a webpage. One useful value for this property is relative. This value positions page elements on a webpage relative to where they would normally appear.

By first setting position: relative;, you can then use the CSS properties top, left, bottom, and right to shift an element away from where it would have normally appeared on the page.

The code snippet below moves a div with the class container 10px away from the up and 20px away from the left side of the page.

.container {
  position: relative; 
  top: 10px; 
  left: 20px;
}
Ever click a button on a webpage that seemed to move down and then back up like a real-life button? We can implement this trick using the position property.

1.
In main.css, locate .contact-btn a, which is the selector for anchor elements that have a parent with the "contact-btn" class.

Beneath the properties already listed for the .contact-btn a selector, add:

.contact-btn a { 
  position: relative;
}
Click Run.

2.
Next, locate the .contact-btn a:active selector. :active is a psuedo-class selector, which we use to style an element only while it's being clicked.

Add the following CSS to the .contact-btn a:active selector:

  top: 2px;
This will cause the Contact button to move down slightly while being clicked, simulating a real-life button being pushed.

Click Run then try clicking the Contact button in the web browser!
