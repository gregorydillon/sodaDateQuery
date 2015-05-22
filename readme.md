There should be an attribution for the basic setup

I think it was either Chris W Hong, or Chris Metcalf.  not sure?

answer - 
Push to https://github.com/chriswhong/sodaDateQuery.git denied. Verify that you have push access to the repository.

Novelity - Learning point of this file is 
1) Date Slider
2) dynatable

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

