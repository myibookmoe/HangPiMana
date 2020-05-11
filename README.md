# HangPiMana
Simple test app to provide useful information during a pandemic. Keeps a log on where you've been for the past 21 days. Since Malaysia now has the MyTrace app I probably won't be working on this any more, but perhaps the code will be useful to novice developers.

Thanks to:
MapKit - User Current Location tutorial by Muneeb Ali
https://www.codementor.io/@muneebali/mapkit-user-current-location-10xdbyy1v3

Reverse Geocoding with CLGeocoder by Bart Jacobs
https://cocoacasts.com/reverse-geocoding-with-clgeocoder

Core Location Tutorial for iOS: Tracking Visited Locations by Andrew Kharchyshyn
https://www.raywenderlich.com/5247-core-location-tutorial-for-ios-tracking-visited-locations

Various different posts on StackExchange (apologies, I forgot to keep track).

v 0.2
Note field added to LocationDetail screen so you can add short notes for each location. Locations are now saved to the Documents directory. Tapping the Share button on the Locations screen will export the location list as a JSON file. Commented the source code.

v 0.1
Displays a table view. You can add locations manually using the Add button, or automatically using visit tracking. Tapping a row will display more information.

To do list:
- Automatically removing rows which are over 21 days.
- Perhaps display a map on the Location Detail screen?

