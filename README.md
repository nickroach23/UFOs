# UFOs

### Background 
The webpage and dynamic table we have built throughout the module are working as intended, but Dana (our customer) has decided she would like the table to be filtered even further. While it currently filters by the date, she would like to include the ability to filter by more column headers. The ability to pinpoint a search by date and country, for example, would go a long way in providing more in-depth analysis of UFO sightings.

### Objectives 
The goal for this analysis are to:
* Create, update, and deploy JavaScript functions to provide additional table filters.
* Update and deploy forEach (for loop) to loop through the filters and update them with user input
* Update and populate the dynamic filters and table using JavaScript and HTML.


### Resources 
* JavaScript 
* HTML
* CSS


### Analysis 

I added the list items for the filters that were required (city, state, country and shape). Once this was completed, I built the JavaScript code to grab the users input from these items and added a JS object named(filters). I found a code on Stack Overflow that helped me remove the keys and values from the object if the user did not enter the data into the field (empty values). Once we have this clean object, we are now able to loop through it by converting the object on a array to build the filtered data. Then we return to the buildTable() function where we passed the filteredData as the parameter. I reccommend that we could improve the accuracy of the data by making a dropdown list where the user can choose from. 
