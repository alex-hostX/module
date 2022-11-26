# module

What is an HTML Module?
HTML Modules are the new proposal for importing HTML files into a document.

HTML import supported a similar feature and permitted to import an HTML file (eventually containing itself JS and CSS) but it has been deprecated and JS module import has partially substituted that feature.

The point of HTML imports are to complete that part and make possible to import HTML files again instead of JavaScript files only. Today you just can't import files that contain HTML (again, you could do that when meta rel=import href=myfile.html> which is not supported anymore). If you want to do that, you have to write HTML in JavaScript string prior to process it.
