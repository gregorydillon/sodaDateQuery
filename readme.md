Creates a table from Socrata type endpoint
And demonstrates a date slider
----

The code is now within script '' on  the index.html page



There should be an attribution for the basic setup

https://github.com/chriswhong/sodaDateQuery.git 

I didn't extend the code in anyway, that not me.   Yet
so there is no intention to request a pull
Rather my purpose is to learn how read his code, understand it enough to know how to ake changes to it,
to civic involvement,
serve my purpose.   That is mostly accompled 
1)
I changed the URL from a Socrata Ft Worth Texas endpoint, to one here in San Francisco

2)
I learned how to make dynatable work, and in doing learned that it is a simple powerful tablemaker.


Novelity - Learning point of this file is 
1) Date Slider   *****
2) dynatable

In particular I could see reusing the date slider portion of the code in the app I'm trying for

1)
The date slider implemented very easily.
Just adjusted the url to the socrata endpoint
and changed the name of the date field.
it also looked better by changing the mimimum date

2)
jquery.dynatable.js
I believe this is what is called a jQuery plugin
it creates tables that respond quickly
--
the issues that I had in implementing were,
- learning that dynatable is a thing.   now I know.
- it doesn't warn when if the column getting back within the json object differs from the number of table columsns
- one has named.
- it doesn't unpack the nesting when a json object contains another object, instead it just says object.
- 

