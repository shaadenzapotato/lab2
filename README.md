# lab2

Requirements:

-Map: When a user visit the site, they should be taken to a page where they can see a map of the City of Calgary.

-Search: Users should be able to search for the building permits that their issued dates are within certain date range. Users should be able to use a date range picker widget to select the date range for the search. 

    widget used: https://daterangepicker.com/
    
-Identify: Users should be able to click on a marker on the map, a pop-up box should appear, and showing the following details about the building permit: issueddate, workclassgroup, contractorname, communityname and originaladdress.

-Sometimes there will be overlapping markers, i.e., multiple building permits located at the same location. You need to develop an intuitive way allowing users to find the information about the building permit. 

    Leaflet Plug-in used: https://github.com/jawj/OverlappingMarkerSpiderfier-Leaflet. 
    
-Sometimes at certain zoom levels the Markers can get very close to each other, and the map are not visually appealing. You need to use a clustering plug-in to solve the issue. 
    
    plug-in used: https://github.com/Leaflet/Leaflet.markercluster. 
    
-When a user search for a new date range, the map should be refreshed and display the new matching result.
