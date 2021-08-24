# Install cordova 

Install Cordova and follow the [installation instructions](https://cordova.apache.org/#getstarted).

For an Android Phone you have to activate the Developer Mode first - depending on the model specific but mostly quite similar to the [following description](https://www.howtogeek.com/129728/how-to-access-the-developer-options-menu-and-enable-usb-debugging-on-android-4.2/). 

Once you have installed Cordova and are able to open the terminal you can type following:

~~~bash
npm install -g cordova
cordova create MyApp
cd MyApp
cordova platform add browser
cordova run browser
~~~

This should create a cordova project and add the web browser as plattform. You can also add Android or iOS as platform. Make sure you have the right SDK installed. [Installation instructions](https://cordova.apache.org/docs/en/10.x/guide/platforms/android/) can be found [here](https://cordova.apache.org/docs/en/10.x/guide/platforms/android/)
 
By adding the plattform and connecting an Android phone that has developer mode enabled you can start the application right away on the phone
~~~bash
cordova platform add android
cordova run android --device
~~~