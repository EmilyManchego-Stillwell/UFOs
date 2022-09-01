# UFOs Project

## Overview of Project: <br>
The purpose of this project was to help create a website for a client to share an article on UFOs<br> 
and data on UFO sightings. The client wanted her website to be interactive for users by creating a<br>
table of the UFO sighting data that users could filter by certain criteria, to make it easier for users<br>
to sift through the data or choose what items they are specifically interested in seeing. In order <br>
to achieve what was requested by the client, we used data provided in a javascript file, code that<br>
was written in javascript to create the table and the search function, and an html file to create <br>
the website that called the javascript code to show the UFO Sightings table and make it interactive.<br>
We also used Bootstrap for the CSS framework.

## Results:<br>
A user can interact with client's website by entering different criteria in one or multiple search<br>
boxes found on the lower left-hand side of her website. The different search options are "Date", <br>
"City", "State", "Country", and "Shape." In each search box an example of what can be entered is <br>
found within the box, for example, in the box under "Enter Date" a user can enter a date in the<br>
following format, M/DD/YYYY. A user will start by choosing which search box they want to filter<br>
the data by. Once the website detects a change in the search box, after the data is entered and <br> 
either a button or mouse click occurs, it will automatically filter the table to only show the <br>
specific criteria that was entered into the box. Once one box is filled in, another one can be<br>
selected and have information entered in, and once again, with a button or mouse click, will<br>
update the table to show the new filter along with the old one. Then if a user wants to start all<br>
over, all they have to do is hit the refresh button and then all the criteria entered will be<br>
cleared and the table will default to showing all the data in the starting table. Below are examples<br>
showing the search boxes in action. (Note:the search boxes are sensitive and need to have data entered<br>
specifically as shown in the examples)

**Website with No Search Criteria Entered**
![Initial Website Visit Img](static/images/WebsiteBeforeFilters.png)

**Website with One Search Criteria Entered Under "State"**
![Filtered for State:ca](static/images/WebsiteFilteredStateCA.png)

**Website with Two Search Criteria Entered: "State" and "Shape"**
![Filtered for State:ca & Shape:triangle](static/images/FilterStateCAShapeTri.png)

**Website with Three Search Criteria Entered: "State", "Shape", and "City"**
![Filtered for State:ca, Shape:triangle, & City:san diego](static/images/FilterStateCAShapeTriCitySD.png)

**Website Cleared with New Search Criteria for Different State**
![Filtered for State:co](static/images/WebsiteFilterStateCO.png)

## Summary:<br>
One drawback for this new design is that the data entered into the search boxes needs to be entered exactly<br>
as the examples found in the boxes. If the date is entered as MM/DD/YYYY instead of M/DD/YYYY or any of the<br>
other boxes are entered with capital letters instead of strictly lowercase, the search will render no results<br>
even if results do exist for the criteria entered. Two recommendations for further development are: add a pop-up<br>
dialog box that informs users they entered the criteria incorrectly and to inform them how to enter search criteria <br>
in the search boxes, and to adjust where needed in the source code to make it so the search boxes aren't so<br> 
particular to specific formatting.