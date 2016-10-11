Steps followed:

1) I decided to pick University of Washington, Bothell(this is different from University of Washington, Seattle). It is hard to find schools where courses are in html format! 
2) I created a raw.txt and then used a curl command as shown in curl.txt.
3) I created a no_whitespace.html using html minified.
4) I scrubbed the data using the commands in additional_cleaning.txt
5) Finally I have a clean file - saved as data.js
6) course.html has all the functions written to create data visualization. This file calls for other files such courses_graph, d3.tip.js, styles_examples.js. 
	- this file also included some steps take to clean the data - I am removing articals, repeated word such as courses, department, converting everything to lowercase.