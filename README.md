# map-app
building a mapping prototype

README

mapquest API was used. https://www.mapquest.com/

Leaflet.js, a javasript library, is used too. https://leafletjs.com/reference-1.5.0.html

this was built with simple API code from MDN tutorial:
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Third_party_APIs

buttons and fields were taken as code from:
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Silly_story_generator
https://github.com/mdn/learning-area/blob/master/javascript/introduction-to-js-1/assessment-start/index.html



*****-----Pre-MVP WORK-----*****
PHASED APPROACH TO MVP & BETA TESTING
	*****-----*****

Phase 1: Map i/o, General setup requirements.
DONE(11/10/19) - get my own API key from mapquest.com
DONE(11/10/19) - add fields for event date/time
DONE(11/12/19)- when a user inputs coordinates into the field and clicks submit, it should add the coordinate to an array 
DONE(11/12/19)- create an array of markers
DONE(11/14/19)- when a user inputs coordinates into the field and clicks submit, it should add that as a marker on the map.
DONE(11/14/19)- build the input / output functionality for the popups, to show up as a popup of the marker.
DONE(11/14/19)- connect it to git / github, or a solid IDE.
- connect it to an Integrated Development environment for easier development
- make it save all markers& popups into a database.
- add more input fields that add to the map with marker.
- understand layers within leaflet/javascript

Phase 2
- format the page to be more pleasing to the eye
- separate javascript, HTML, and CSS files.
- connect to the Map API that connects coordinates to actual Locations.
- display a list of coordinates next to the map, a list of all the different locations of the markers.
Phase 2B:
	- add category fields
	- build coordinates / input data into a JSON file.

Phase 3:
- add filter capabilities via checkbox on the list of marker location coordinates. Filter/search by popup text.
- make this a live website, attached to a domain name. such that people can actually go to a webpage and try it out.
	- add filter capabilities by category (drop down)

Phase 4: User Feedback & Responses
- ability to create markers/popups that are stored server-side, such that you can see whatever evnts people have added.
- customer development, user feedback
DONE(11/10/19)- find first 5 beta testers.
- begin feedback from beta-testers.

- re-build this in node.js on a different computer.

*****-----POST-MVP WORK-----*****
PHASED APPROACH TO PRODUCT LAUNCH
	*****-----*****

Phase 5:
- add the clustering capability to the map
- allow creation of user accounts:
- change map marker icon to be colored and smaller/ less bulky.
- ensure interactions work.
- facebook/google API
- convert the code I've written into more "Idiomatic Code", meaning more simple, elegant code.

Phase 6:
- add user profile specifics, such as bio / profile picture
- allow users to save markers
- Migrate to Google Maps?
