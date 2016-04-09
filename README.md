toridasu
========

Toridasu is a single-page Javascript app to select and reformat NHK Easy News articles
for offline reading and study. The output page is formatted for readability;
on OS X, it's easy to print to PDF.

Scott Oglesby, http://www.kurumi.com/

Browser compatibility:
* OS X: tested on Firefox 45, Chrome 48 - OK
* OS X Safari: no good; Safari doesn't understand "for (x of y)" notation
* Win 7 Firefox: OK
* Win 7 Chrome: no good; new tab doesn't open
* Win 7 IE 11: unspecified problem, doesn't load :-/

Notes:
* Save toridasu.html as a local file and open it. If you host it somewhere,
  Javascript's same origin policy will prevent it from accessing the NHK site.