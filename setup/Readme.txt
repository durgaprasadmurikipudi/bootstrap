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
Each of the col contains, a fa-3x icon, making icon 3 times larger than normally one. text-info
background for font-awesome icon. A header h2 under it with text-capitalize, text-dark and py-5
to describe the font-awesome icon.
A p tag with text-muted class for description of the card.
Overall a decent card design.

Notes about sections in index.html:

Navbar section:
As always lets start with navigation section,
We open with a nav tag, we use navbar, navbar-light classes along with navbar-expand-sm and bg-primary.
Background you know it, navbar basically to inkvoke navbar section then navbar-light works funnily. You say navbar-light class, then text is dark. You say navbar-dark text is light.
navbar-expand-sm to make it in expanded view only after screen has touched sm-breakpoint.

Inside the navbar, for the brand there is a class navbar-brand and you apply it to an anchor tag ofcourse with whatever is the name of the website. Here text-uppercase and font-italic is used as well.

Now bootstrap magic, a button to toggle the navbar, with a class navbar-toggle and data-toggle action mentioned as "collapse". you also mention the target with data-target which is navbar-links. Bootstrap is kind enough to provide the icon togglebutton, you just need to apply navbar-toggler-icon class to span tag to get it.
Now coming to navbarlinks# div, just below it which hosts actual navbar links, has classes collapse and navbar-collapse to aid the collapsing probably. 
Inside it, anchor links which are inside the li tag under ul
ul is decoareted with navbar-nav clsss. Each li is been gifted nav-item class to aid navigation.
Anchor links href to unique id to navigate.

Header section:
Who doesn't love a great header section.? 
So a header tag with id #header having bg-dark to enter in dark stoic mode.
a container class under it a row class, with user defined screen height. Also row class also shares align-items-center class for obvious reasons.

inside the row there is a col class, meaning occupying whole width of row.
Now the content begins inside the col, a header h1 for a bang! Header decorated with text-danger, text-uppercase, font-weight-bold and font-italic to beautify it opposite bg-dark of header section.
There is also a small html tag to make the text small, it was adorned with text-light for bg-dark background.

Once this beatiful h1 tag is complete, a p tag with text-muted.lead.w-75.py-2 class gives the description.
There are 2 buttons, each having the same class excepth that define the color.
The classes are btn.btn-outline-primary/success.btn-lg.m-2.text-capitalize.

btn-lg to make the button larger irrespective of screen size. With this header is done.

Skills section:

Ofcourse section tag from now on for the main content, as navbar and header are complete.

A #skills section with class py-5 and bg-white for background.
Then a .container>.row>.col.text-center

Inside the col, we go big, with display-4 header! This is applied to h1 and also text-uppercase, text-danger and mb-0 class as well.

Also string is kept insdie this h1 tag. Below this h1 tag, an underline is cleverly created by applying height as 5px and setting bg as bg-danger for a div tag. Width is manually set in px's to suit the heading above.

Below the underline, a p tag with calsses mt-2.text-capitalize.text-muted with 4 words for description or as a tagline for the title.

Now each skills are designed as a simple card using col sections rather than bootstrap provided card classes.
Each col is adorned with col-md-6/col-lg-3 width text-center and my-4.
Inside each col, we opne the card with fa-icon for each skill like fab.fa-html5 with 5x large size by fa-5x. bg is set to bg-danger against white background.

Under this font awesome icon, a h3.text-uppercase with text skill name.
Below it skill description of about 10 wrods with text-muted class.

Now each skill card is given beautiful footer by a.btn.btn-outline-danger.btn-block.text-uppercase.

Keep as many cards to account for all the skills you have.

About section:
Basically bg-info section, with 2 cols inside a row inside a container fluid section.

each col is given height-80-of-screen-size.
First col ofcourse img, and probably urs ?
second col with d-flex.align-items-center.justify-content-center, to keep text as center of attraction.

Check out the checkbox design, which is lovely and simple..

About projects section:
 #projects section with .py-5.bg-secondary

 and the usual structure, .container>.row>.col and col with .text-center

Now there are 3 rows, first row is section title, usual section title just text colros change to suit their respective bg.
Here bg-danger header opposite bg-secondary.

Second row with py-3 class has 3 columns. Each column has col-sm-6, col-md-4, my-3 and mx-auto for a perfect card structure to hold the image.
image has img-fluid and custom image classes to customise the height of the image.

3rd row is same as of second row completing 6 card structures for 6 projects.

We also used a special class in 3rd row o demosntrate how to remove boostrap induced padding margin between each column. The class is no-gutters.

and the projects is done!.

Team section:
So far we designed our own customr cards, lets have a look at structure and beauty provided by the bootstrap.

A routine section tag, #team.py-5.bg-light

a routne .container and a row for title just like any other title above.

Now a row, to hold the cards.
card design is initiated by div.card.
If you want to have an image at the top if the card, provide an image, and give it class card-img-top, also customise the image size for sure to adjust it inside the card.

now below the card image, card body starts with div.card-body.
Inside the card body, you can have html header tags with card-title class. also p tags with card-text class to describe the card.
additionally below the p tag, you can put a button.

Bootstrap also provides the options for card-footer with the class under the same name.
font awesome icons are provided for social media links for each team member.
To neatly arrange this inside card-footer we are adding along with card-footer bg-secondary.d-flx.justify-content-around.

And that is how a crd is designed and with few of these is how you introduce them to the world!















