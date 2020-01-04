Notes about sections in start.html

1st Container:
This was designed with page header or page intro section in mind.
We basically used a container, instead of a container fluid to stand out.
Used bg-secondary and text-white (for header text) classes, a classic gray and white combination.
We tried bg-warning -> yellow color text against gray background, a experiment.
We also embedded 2 buttons to see the look and feel.
We used m-2 on button to give it a space between main text and button itself.
p-2 class as well on both to make the button look a bit large.
We used btn-primary and danger variants on it and overall look was ok.

2nd Container:
Again a page intro try out,
A bg-warning and text-dark ( for header).
What stands out is use of display-1 or display-4 classes for header.
And text-success, lead classes for main text also look ok.
lead class as a stand alone does magic when used on main text of the container / section.
We also used py-2 classes on main text to make it standout.
We tried btn-dark, btn-success and btn-secondary on 3 buttons against this background and all look ok.

3rd main content after page intro:
Now its time for main content after page into is designed.
Basically we placed a container inside a section.
We used a cool bg-dark on section, so basically covers the container as well.
One cool trick to make this main content appear as main content reall, we set the container height to
screen height of the client.
This can be acheived by height: 100vh, that is 1005 of viewport height.
We can also set it more than 100%, but that would be a waste of space.
We can also set the height in a more clever way, by setting the property min-height: 100 vh ;).
Now after setting the container height, coming to the content of this container,
And it is common in all above containers is that, we have a row div, creating a row in the container,
and a col div inside that row div, to create a column, since its just 1 it occupies the whole
width of the row.
The height of the container was actually set on row class and we also used, text center and
align-items-center, to keep the text at the center of the whole container.
For heading of this container text, we used h1 with text-white class.
A beautiful black and white combination.
Then a stylish text-warning and display-4 subheading text below that heading also brought a style
of its own.
We then used left and right combinations of text on main text. it was divied into 2 points and
one is given text-left and other is given text-right with text-info class.
The container is looking, now time to apply some buttons, the variation used here is cool again and
beautifully consitent with the style used above.
First button used btn-light same as header, second button used btn-warning same as sub-header and
third one used btn-info same as main content. The overall aura was cool.
White, yello and Dark really make a great combination, inclusion of aqua in it is also not bad.

4th variation of main content after page intro:
For this same as above a container inside a section.
This time section used bg-light for near white background, and just like above style,
row inside container and a col-9 inside container occupying the 9 parts of 12parts of the row,
 which occupies whole width opf the container.
For text inside it, the row was applied classes align-items-center and justify-content-center.
Now just like for align-items-center to work, the items or children inside it should have height
less then the height of the container, in which else case the effect cannot be seen, for justify-
content-center to work as well, the children width should have less width than that of the occupying
container. Hence the use of class col-9.
Now the text are centered at the middle of the container, not exactly center as text-center,
but the text will start at the col-9 start position but col-9 will be at the middle of the container
with equal spacing along sides of it in cross-axis direction.

This is the differene between the text-center and use of justify-items-center.

Coming to header part, we used a cool bg-danger against bg-light, display-2 and text-uppercase class
as well, which makes it really standout in a classy red and white outlook.

Now the main text has classed text-muted (gray) against bg-light and lead and my-4 as well to stand out and
maintain distance between the heading and main content.

Now 2 buttons are introduced, but they are anchor tags with btn classes applied to them, and the color
variants of them are interesting, btn-dark and btn-secondary (gray) against bg-light.
WE also used text-uppercase for button text and p-3 and mt-3 to size up the buttons and to increase
the distance between the buttons and the main content.
Overall look is cool.

5th: Now a ribbon header design with use of font-awesome icons, one thing about this font-awesome icons,
is that theri CDN doesnt work, so download their font-awesome and extract it.
Provide references in you index.html to all.js and all.css present in that font-awesome extracted folder.

A section with a container fluid - container and py-5 padding to extend the ribbon height.
A bg-success is used giving an ok look.
Inside the row, 4 col's with text-center class are used, each containing a font-awesome icon and h3 text below it with class
text-dark.
Font-awesome icon background can be changed by changing the respective col's background.
For each 4 font-awesome icons, bg-danger, bg-info, bg-warning and bg-success are used respectively.

6th: For a sub main content section, we though of placing 3 card like structures.
a bg-light section and inside it a container-fluid container.
A row and 3 col-4 columns, for each of the card.
Each of the col contains, a fa-3x icon, maing icon 3 times larger than normally one. text-info
background for font-awesome icon. A header h2 under it with text-capitalize, text-dark and py-5
to describe the font-awesome icon.
A p tag with text-muted class for description of the card.
Overall a decent card design.





