MAKE A WEBSITE
Amazing Space
Amazing Space is a space adventure company. They heard about your skills with CSS spacing and boundaries, and have asked you to improve the layout of their homepage. Get ready to push the limits with this next project!

Mark the tasks as complete by checking them off
Amazing Space
1.
Amazing Space wants space images in the gallery to look more distinct. In style.css locate the .space-item .thumbnail class selector. Add a border property of 2px solid #ffffff.



2.
In the web browser, you notice that the inner space between the content and border of the company description paragraph is looking cramped.

In style.css, increase the padding for the .company-description selector to 30px or until it looks right to you.

Once you find the .company-description selector in style.css, add the following:

padding: 30px;
You can replace 30px with whatever value you would like.

3.
In index.html, figure elements with the class space-item contain images. In the web browser the figures appear too far apart from each other. In style.css, the margin property for the .space-item selector is currently 40px. Decrease it to 20px, or until it seems correct to you.




4.
Amazing Space is concerned that the "Learn More" link appears too close to the company description paragraph. In style.css, locate the .learn-more selector and increase the margin-top property until there is sufficient room between the paragraph element and the "Learn More" link in the web browser.

Increase the margin-top property for the .learn-more selector to whatever value looks right to you. Here is a suggestion:

margin-top: 20px;
5.
At the bottom of the webpage in the web browser, find "About", "Missions" and "Archive". In index.html, these are represented by list items in an unordered list.

In style.css, give the nav li selector a display property of inline so that the list items share the same line.



6.
Next, notice the "Contact Us" button at the bottom of the webpage in the web browser.

In index.html the button is represented by an a element inside a div with class contact-btn.

In style.css, locate the .contact-btn selector. Add a float property of right so that the "Contact Us" button floats to the right of the navbar items.


7.
To arrange the space images in rows, locate the .space-container selector in style.css. Add a display property of flex. To make the space images wrap, below display: flex; add a flex-wrap property of wrap. Finally, to center the rows on the webpage, add the justify-content property, and give it a value of center.


8.
Amazing Space is pleased with your work thus far. They just have one more request. Since their spaceships are filled with pushable buttons, they would like you to put one on their homepage, too.

Make the "Contact Us" button move down and up when clicked. Locate the .contact-btn a:active selector in style.css. Add a position property of relative. Below it, add a top property of 3px.

Test out the effect by clicking the "Contact Us" button in the web browser.
