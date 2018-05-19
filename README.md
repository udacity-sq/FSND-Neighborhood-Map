# Neighborhood Map Project - Udacity FSND Project 5
Develop a single page application featuring a map which shows interesting locations. Utilizing the Goole Maps API create map & location
markers which highlight 5 locations the user should visit if they are in the area. The application has the following features:

* List of locations 
* Map with location markers
* Interactive location markers with infowindows which pull location information from wikipedia

# Detailed Features:
This project utilizes Knockout.js. Following the guidelines there is separation between the Model and ViewModel. The Goole Maps
API is used to create the Map and the associated markers. Knockout is not used for handling the Google Map functionality. Maps data
are loaded asynchronously and errors are handled gracefully, notifiying the user of possible issues. Similar to the Google Maps data,
Wikipedia is also used to asynchronously load data related to Location markers. See the infowindow for attribution.

Applications List Features:
* Filterable Location list. Text based filtering - Markers filter automatically as well.
* Selection of a list item pops open the associated markers info window
Map features:
* Clicking on a locations marker will make the marker bounce & open an info window 
* Clicking on the info windows 'x' will close it out

# How to Launch Application :
Download or Clone Repository. Double click the file ```neighborhood_map.html```. The application should launch in the web browser. 
If not, please right click the file and select open with -> chrome or web browser of your choice. Do ensure that internet access is 
available and check firewall settings if the map or infowindows show any errors.

# Resources:
* Udacity course [Intro to Ajax](https://www.udacity.com/course/ud110)
* Udacity course [Javascript Desgin Patterns](https://www.udacity.com/course/javascript-design-patterns--ud989)
* this in Javascript-[bind and this - Object Creation in JavaScript](https://www.youtube.com/watch?v=GhbhD1HR5vk)
* MDN Documentation -[.include](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/includes)
* Knockout Utility Funcitons-[Dealing with Arrays in your ViewModel](http://www.knockmeout.net/2011/04/utility-functions-in-knockoutjs.html)
* Knockout Pro Tips-[Working with observable arrays](https://www.strathweb.com/2012/07/knockout-js-pro-tips-working-with-observable-arrays/)
* Stackoverflow-[filter-maps-markers](https://stackoverflow.com/questions/22323073/how-to-filter-google-maps-markers-in-one-array-with-select)
* Google Maps Documentation- [Map Examples](https://developers.google.com/maps/documentation/javascript/examples/)
* Udacity Forums-[Discussion Forum] (https://discussions.udacity.com/)
* MDN web docs-[Array.prototype.filter()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
* BootStrap documentation-[Navbar](https://getbootstrap.com/docs/3.3/components/#navbar)
* BootStrap documentation-[Collapse Feature](https://getbootstrap.com/docs/4.0/components/collapse/)
* GitHub-[ssicet](https://github.com/ssicet?tab=repositories)
* GitHub-[Christianq010](https://github.com/Christianq010)
* GitHub-[callforsky](https://github.com/callforsky)



# License information:
This Application and it's associated code is free to use. 
