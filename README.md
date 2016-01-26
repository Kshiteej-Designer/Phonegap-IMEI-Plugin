# org.hygieiasoft.cordova.uid
Here is Cordova plugin to get unique identifiers: UUID, IMEI, IMSI, ICCID and MAC.

This plugin defines a `cordova.plugins.uid` object.
The object is not available until after the `deviceready` event.

		document.addEventListener('deviceready', onDeviceReady, false);
		function onDeviceReady() {
			console.log(cordova.plugins.uid.IMEI); (choose your function)
		}

### Hot to use from Command line
		cordova plugin add org.hygieiasoft.cordova.uid

### Plugin Properties in deviceready event
- uid.UUID - var string = cordova.plugins.uid.UUID;
- uid.IMEI - var string = cordova.plugins.uid.IMEI;
- uid.IMSI - var string = cordova.plugins.uid.IMSI;
- uid.ICCID - var string = cordova.plugins.uid.ICCID;

