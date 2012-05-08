SVG Input Elements
==================

Currently this project implements text areas, similar to HTML `<textarea>`s. 
You can try it out with ./demo.html (just add jQuery and jQuery SVG and 
adjust the href values). 

The goal is to implement input elements that feel and behave naturally (i.e. 
as corresponding HTML input elements etc). 

Features 
--------
* Line wrapping
* Word wrapping of long words
* Copy/cut/paste
* Text selection with mouse and keyboard
* Change cursor position with left/right/up/down/home/end etc
* Handles both paragraphs (`enter`) and manual line breaks (`shift+enter`)
* Undo/redo
* ...

Requirements
------------
This project requires [jQuery](http://docs.jquery.com/Downloading_jQuery) 
(we're using 1.7.2) and the 
[jQuery SVG plugin](http://keith-wood.name/svg.html)

Development
-----------
Next in line to be implemented are select boxes and variations of the text 
area (like a list box, for example). 

Feel free to join in and develop, if you want to contact us please e-mail 
Tim at [info@sypreme.se](mailto:info@sypreme.se) or Josef at 
[josef.ottosson@josf.se](mailto:josef.ottosson@josf.se). 

In a future version, we would build it both for JQuery SVG and Raphael, or 
rid of both dependencies completely. We would love some help implementing 
this! About choosing which to build for, we refer to this thread (for now):
http://stackoverflow.com/questions/588718/jquery-svg-vs-raphael