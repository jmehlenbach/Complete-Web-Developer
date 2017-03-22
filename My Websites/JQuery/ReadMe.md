This is the *JQuery* Section
=====

March 22, 2017

Embedding JQuery:
-----
In this section, download the JQuery file, and can be embedded with javascript in the HTML file
The file will need to be either downloaded from the JQuery website or linked to the most recent

	 <script type="text/javascript" src="jquery.min.js"></script>

DetectingAClick.html
-----
Added the ability to use JQuery as a way to interact with the elements on screen. 
Created two squares and circles using css and HTML and then when clicked, an alert was shown. 
Instead of using the specific class or id (square or #circle) we can use just div to affect all div clicks

ChangingWebsiteContent.html
-----
Using Jquery, we are able to change the image or website it the page.
In this case, the iframe was embedded into the webpage, then, using jQuery, and hovering over an element the source of this iframe was updated to a new one

ChangingStyles.html
----
Using some JQuery commands we can change it so that when say the circle is clicked, the square will fade out. 
This section changes CSS properties. 
- Updates the width of the circle
- Fades out the squares

Useful to change the element to either remove it or fade out then remove it. 
	$(this).hide();
	$(this).fadeOut();
	
FadingContent
----
fadeOut() function can have attributed like 2000 for 2 seconds, fast or slow

AnimatingContent
----
*Quite Useful*

Use animate with parameters being a dimension, and the second parameter being a time for it to complete. 
	
		$(this).animate({
		width:"600px",
		height:"600px",
		borderRadius:"100px",
		marginLeft:"100px",
		marginTop:"100px"
		},3000);