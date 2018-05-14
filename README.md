# Neighborhood Map Project - Udacity FSND Project 5
Develop a single page application featuring a map which shows interesting locations. Utilizing the Goole Maps API create map & location
markers which highlight 5 locations the user should visit if they are in the area. The application has the following features:

* List of locations 
* Map with location markers
* Interactive location markers with infowindows which pull location information from wikipedia

# Detailed Features:
This project utilizes Knockout.js. Following the guidelines there is separation between the Model and ViewModel. The Goole Maps
API is used to create the Map and the associated markers. Knockout is not used for handling the Google Map functionality. Maps data
is loaded asynchronously and errors are handled gracefully, notifiying the user of possible issues. Similar to the Google Maps data,
Wikipedia is also used to asynchronously load data related to Location markers. See the infowindow for attribution.

Applications List Features:
* Filterable Location list. Text based filtering - Markers filter automatically as well.
* Selection of a list item pops open the associated markers info window
Map features:
* Clicking on a locations marker will make the marker bounce & open an info window 
* Clicking on the info windows 'x' will close it out

## How to Launch Application :
Download or Clone Repository. Double click the file ```neighborhood_map.html```. The application should launch in the web browser. 
If not, please right click the file and select open with -> chrome or web browser of your choice. Do ensure that internet access is 
available and check firewall settings if the map or infowindows show any errors.

# Resources:
Need to add Google, Course and https://stackoverflow.com/questions/22323073/how-to-filter-google-maps-markers-in-one-array-with-select
* Digital Oceans - [How to Deploy A Flask Application on an Ubuntu VPS](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
* Udacity Forums - [Discussion Forum] (https://discussions.udacity.com/)


# License information:
This Application and it's associated code is free to use. 
