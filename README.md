
HTML Geolocation API

# HTML-5-JS-Geolocation

Geolocation
The example below returns the latitude and longitude of the user's position:
Demo: https://kenny254.github.io/HTML-5-JS-Geolocation-/

The HTML Geolocation API is used to locate a user's position.

Locate the User's Position
The HTML Geolocation API is used to get the geographical position of a user.

Since this can compromise privacy, the position is not available unless the user approves it.

Note: Geolocation is most accurate for devices with GPS, like smartphones.

Browser Support
The numbers in the table specify the first browser version that fully supports Geolocation.

API					
Geolocation	5.0 - 49.0 (http)
50.0 (https)	9.0	3.5	5.0	16.0
Note: As of Chrome 50, the Geolocation API will only work on secure contexts such as HTTPS. If your site is hosted on an non-secure origin (such as HTTP) the requests to get the users location will no longer function.

Using HTML Geolocation
The getCurrentPosition() method is used to return the user's position.

