# UFO Sightings using JavaScript!

![Banner 1](https://github.com/mpournaras/UFOs/blob/main/static/images/banner.png)

## Purpose
1. Explain the strengths and weaknesses of JavaScript "standard" and JavaScript version ES6+.
2. Describe JavaScript syntax and ideal use cases.
3. Build and deploy JavaScript functions, including built-in functions.
4. Convert JavaScript functions to arrow functions.
5. Build and deploy JavaScript for loop.
6. Create, populate, and actively filter a table using JavaScript and HTML

## Overview 
A client requested that we provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, the client requested we add table filters for the city, state, country, and shape.  The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website. 

## Results:
### Welcome to UFO Sightings! 

![Pic 1](https://github.com/mpournaras/UFOs/blob/main/static/images/top.PNG)

### How the filters appear when first landing on the page:
![Pic 2](https://github.com/mpournaras/UFOs/blob/main/static/images/bottom.PNG)

### How the filters appear after being used: 
By typing in the suggested placeholder elements as the filters, the result returns 2 matches.  Make sure to type everything in lower case letters and do not have spaces at the end of the text.  Click off the input box or press enter to initiate the filter.  To reset the filter criteria, click the UFO Sightings at the top left of the website. 

![Pic 3](https://github.com/mpournaras/UFOs/blob/main/static/images/working_filters.PNG)


## Summary: 

### Drawback:
The user must know specific dates, cities, or other entries in fields to search. The filters require correct lower-case spellings and cannot include spaces at the end.  The city Grants Pass that was used, for example, could not be typed as "grantspass", “grants pass_”, or "Grants Pass".  The only correct input would be "grants pass".

The scaling on my browser (Google Chrome) was not ideal either. It was a full page of information but the font was small on my very standard monitor. Zooming helped but I would like to not have to do that. Perhaps have it auto scale to the monitor.

### Recommendations: 
1. The next addition to the filters should be to add a trim function. This would allow it to catch spaces at the end of words and allow for various character cases at the beginning or end of words. San Diego for example had 3 sighings in January 2010
2. 
![Pic 4](https://github.com/mpournaras/UFOs/blob/main/static/images/trim.PNG)

2. A date range could be preferable than a singular date.  It would be understandable to not know the single date you would be looking for.  Perhaps, the UFO Sightings occur more frequently in a specific month instead of a specific day within the month.  I would recommend to add a filter function to include a date range as the filter to aid in the investigation of UFO Sightings. San Diego for example had 3 sighings in January 2010

![Pic 5](https://github.com/mpournaras/UFOs/blob/main/static/images/date.PNG)
