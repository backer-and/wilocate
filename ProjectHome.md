### Wilocate is a wireless detector tool capable to geolocalize your current position and the wifi networks around. ###

The program can be used for
  * Showing the geographical location of wireless router on Google Map.
  * Geolocating your current position with a pretty good accuracy, like a (sometime inexact) GPS.
  * Showing detailed technical [informations](http://code.google.com/p/wilocate/wiki/Marker_Info) about wireless networks installed around.
  * [Wardriving](http://code.google.com/p/wilocate/#Wardrive_mode_(offline_scanning)) with geographic map support.

The program supports Linux and is currently under heavy development, help us to improve it and fix some bugs. Soon we'll publish Debian/Ubuntu packages. The georeferenced WiFi data used to geocode your request was collected when Google was driving around taking pictures for StreetView.





### Download Wilocate ###

From a linux console get the last version of the program running:
```
svn checkout http://wilocate.googlecode.com/svn/trunk/ wilocate 
```

Execute

```
cd wilocate
./wilocate.py 
```

To open the menu and web browser interface.