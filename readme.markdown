PolyPage
========
Polypage was designed to ease the process of showing 
multiple page states in html mock-ups. 
By simply adding class names to a document you can 
imply state and conditional view logic.


BASIC USAGE
-----------
    $(document).ready(function() {
    	$.polypage.init();
    });


SETTINGS
--------
There aren't any!
It just works. 

Having said that feel free to modify the css styling to work 
with your wireframes.

If you want to force a state to be active when the page 
loads then you can pass it in as an Array to the init 
function like so...

    $.polypage.init([ 'logged_in', 'admin' ]);


By default, polypage appends a div containing the page states to the body tag of the html. If you want the polypage states to be added elsewhere, you can call the init function with a css selector for the target element.

    $.polypage.init(null,"#page_controls");
    $.polypage.init([ 'logged_in', 'admin' ],"#page_controls");



MORE INFO
---------
For more help and an example open the index.html file in a web browser.

CONTRIBUTERS
------------
Andy Kent <andy.kent@me.com> (http://adkent.com/)
Natalie Downe <nat@natbat.net> (http://notes.natbat.net/)
