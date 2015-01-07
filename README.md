gpssettings
===========

Display the location settings page

Example :

	var gpsDetect = cordova.require('cordova/plugin/gpsDetectionPlugin');
	phonegapReady().then(function () {
		gpsDetect.checkGPS(onSuccess, onError);
	});


Installing the plugin in your project:

cordova plugin add com.dataforpeople.plugins.gpssettings
