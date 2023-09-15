# Mapty

-Description


Using the Geolocation API, this application gets the user's location when the app is loaded and then render's a map of their current location on the screen.

Users are able to click anywhere on the map and add a workout that they completed and keep track of their past workouts. Click and drag the map to move to different locations. Right now the only workouts available to add are running and cycling. I plan to add more workouts soon to be added. 

When a workout is added, a marker is rendered on the map. When clicked, the map will move its position to where the marker is, using the localStorage API the workouts will stay on the screen even when the app is closed or reloaded.


-Libraries

I used the third-party library, Leaflet, to get the map and render it on the screen. 
If you are unfamiliar with the library, here is the documentation: https://leafletjs.com/reference.html
