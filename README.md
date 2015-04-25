# Summary

This data visualization charts more than 300 different U.S. airports performance from 2008. It shows each connections between all airports and some useful information about each airport.

# Design

I decided to use pure d3.js.

Visualization shows all US airports. Each circle is airport. Bigger circle's radius means bigger amount of flights in current airport. On circle mouseover shows useful information about this airport and connections with others airports. Yellow arcs mean inbound flights, blue arcs mean outbound flights.

# Feedback

I interviewed 3 individuals in person, and asked for their feedback on the data visualization after prompting them with the background information and a small set of questions. Highlighted comments from them are listed below:

+   Add more useful information in title. (at current review visualization didn't have any title)
+   Add more information in tip. Like exact number of inbound/outbound flights.
+   Show arcs with lower opacity, before any mouseover. I'm interesting to see exact messy visualization of paths between airports and cities.

# Resources

+   d3.js Documentation http://d3js.org
+   Data Visualization and D3.js (Udacity) https://www.udacity.com/course/viewer#!/c-ud507-nd
+   Various Stack Overflow posts http://stackoverflow.com/search?q=d3.js