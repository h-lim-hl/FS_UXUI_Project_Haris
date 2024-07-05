BELLS Institute of Higher Learning
UX Design and User Interface Theory Project Assignment
Candidate: Haris Lim Hao Li

Project Brief:
Create a landing page for a business (Cafe)

Assessment Criteria
User Experience and User Interface:
Target user group - protential customers
Apparent problem(s) supposedly to solve - online presence
											out reach
Features that solve problem(s) of protential customer - Menu items preview
														Location information
														contact information.
Deploy portfolio, available publicly - https://h-lim-hl.github.io/FS_UXUI_Project_Haris/
Layout of the website must be aesthetically functional - see above

HTML Proficiency
There must be a inner site navigation that allows the user to view the different pages in the site - site uses scrollspy

There must be no errors when running the web page through a HTML validation - all html and css validated.

There must be at least three other kind of HTML elements besides the follow: <body>, <head>, <html>, <p>, <div> and <a> -
<iframe>
<img>
<br>

CSS Proficiency
There must be at least one instance of changing the font properties, such as font family, font color etc.
- exist classes menu-tab-hlink and menu-tab-hlink:hover

There must be at least one instance of selecting an element by ID
- does not exist however to demonstrate proficiency to select elements with id, in css section select them with "#idname". Eg. <h2 id="hero-header"> Hero Header </h2> ||  #hero-header { color = blue; } 

There must be at least one instance of selecting an element by class - all elements modified by bootstrap and custom css uses class selection

Make use of padding at least once - padding is applied generally with bootstrap p~ classes, eg. "px-1". index.html, line 26.

Make use of margin at least once - margin is applied generally with bootstrap m~ classes, eg. "my-1". index.html, line 52.

Incorporate at least one flexbox layout - Site is mostly created with bootstrap and is inherently flex-based. 

Demonstrate at least one instance of flex basis, flex grow and flex shrink.
Flex basis and shrink is not used in the site. The design did not need them. To demonstrate understanding:
flex-basis sets the initial size of the flex child element along the parent flex-direction, ie. if the parent is in the row direction then child element has flex-basis defined size along the row direction when it is uneffected by screen size and available space in the parent.
flex-shrink allows the flex child element to shrink if more space is need due to screen size or parent available space. The number assigned to flex-shrink attribute is the ratio to the sum off all sibling flex-shrink elements. The larger the raito the smaller then element can shrink.
Note that using flex-shrink (and flex-grow), their ratio relates to the available space in the parent. Thus, they will occupy available unused space.
flew-grow can be see in index.css menu-tab and menu-tab:hover.

Layout should fit at least one mobile device besides desktop browser (width up to 1580 pixel) - Layout is tested on 320px to 1920px width, specifically on 320px and 1920px.

Demonstrate at least one media query affecting the layout of the web site. - The site uses bootstrap wrapped media queries, eg. "col-sm-6". index.html line 52.

CSS Frameworks
Make use of at least three developed components from a chosen CSS framework - 
1. spyscroll - index.html, line 26.
2. listgroup - mains.html, line 17.
3. carousel - index.html, line 197.

Make use of at least one layout tool once from a chosen CSS framework. - Site aligns elements mostly with "col" class from bootstrap.