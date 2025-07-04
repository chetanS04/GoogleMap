🗺️ React Native Google Map Polygon Tracker
This is a simple React Native component that uses Google Maps (react-native-maps) to display a polygon shape (geofence or boundary) on a map.

📸 Preview
A polygonal region is shown on a map centered around New Delhi (India).

📦 Tech Stack
React Native
react-native-maps
Google Maps Provider


🚀 Features
Renders a Google Map
Draws a polygon using a set of coordinates
Configurable polygon color and boundary
Initial map region focus


📱 Android Setup Notes
Make sure to add the Google Maps API key in your android/app/src/main/AndroidManifest.xml:

<meta-data
  android:name="com.google.android.geo.API_KEY"
  android:value="YOUR_API_KEY_HERE"/>
