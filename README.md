# Codeless Tools
Add components to your proyect without write any code:

#####· Video from URL
#####· Video from local path
#####· Image from URL
#####· WebView from URL
#####· MapView from Latitude and Longitude
#####· More components soon...

##Installation
1- Add "Tools" folder to your proyect.<br>
2- Follow the instructions below, to add each element.

##Video from URL
1- Drag and drop a ImageView to your Storyboard.<br>
2- Asign VideoFromURL.swift as ImageView class in "Identity inspector" tag.<br>
3- Set Url, and video settings in "Attributes Inspector" tag.<br>
4- In the same tag, you optionally can add a image as Thumb. In "Image View" section.<br>
5- Build!<br><br>

![Alt text](ReadmeImages/Screen1.png?raw=true "Video URL")

##Video from local
1- Drag and drop a ImageView to your Storyboard.<br>
2- Asign VideoFromLocal.swift as ImageView class in "Identity inspector" tag.<br>
3- Set Video's name, extension and settings in "Attributes Inspector" tag.<br>
4- In the same tag, you optionally can add a image as Thumb. In "Image View" section.<br>
5- Select your <strong>Project root > your Target > Build Phases > Copy Bundle Resources</strong>. If your video is not listed in this list you should add it using the plus button.
6- Build!<br><br>

![Alt text](ReadmeImages/Screen2.png?raw=true "Video Local")

##Image from URL
1- Drag and drop a ImageView to your Storyboard.<br>
2- Asign ImageFromURL.swift as ImageView class in "Identity inspector" tag.<br>
3- Set Url in "Attributes Inspector" tag.<br>
4- Build!<br><br>

![Alt text](ReadmeImages/Screen3.png?raw=true "Image URL")

##WebView from URL
1- Drag and drop a WebView to your Storyboard.<br>
2- Asign WebViewFromURL.swift as UIWebView class in "Identity inspector" tag.<br>
3- Set Url in "Attributes Inspector" tag.<br>
4- Build!<br><br>

![Alt text](ReadmeImages/Screen4.png?raw=true "WebView URL")

##MapView from Latitude and Longitude
1- Drag and drop a MapView to your Storyboard.<br>
2- Asign MapViewFromLatLong.swift as MKMapView class in "Identity inspector" tag.<br>
3- Set Latitude, longitude and the radius of the region in Km, in "Attributes Inspector" tag.<br>
4- Build!<br><br>

![Alt text](ReadmeImages/Screen5.png?raw=true "MapView Lat Long")



