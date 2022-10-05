# Wyze Cam Outdoor Firmware
## 4.17.4.278 (September 12, 2022)
* Fixed a bug that caused microSD card recording to fail when allowing time zones offset by half an hour
## 4.17.4.140 (June 29, 2022)
* Added support for time zones offset by half an hour
* Fixed a night vision issue
Note: This firmware is halted because the support for offset time zones caused microSD card recording failure. We apologize for the issue and are working to resolve it.
## 4.17.4.124 (March 23, 2022)
* Fixed an issue that caused delays when loading live stream video
## 4.17.3.93 (February 16, 2022)
* Fixed a bug that caused Events with night vision turned on to speed up
* Fixed a bug that caused faster battery drain when using Cam Plus
* Security improvements
## 4.17.2.40 (December 20, 2021)
* Added support for Wyze Solar Panel
## 4.17.1.290 (November 17, 2021)
* Fixed a bug that prevented Cam Plus Events from being triggered or tagged correctly
## 4.17.1.287 (October 11, 2021)
* Fixed an issue that caused Wyze Cam Outdoor to not record Motion Events when Cam Plus is enabled
* Fixed an issue that caused battery drain for Wyze Cam Outdoor
## 4.17.1.247 (September 8, 2021)
* Fixed a bug that caused the Base Station to keep flashing blue after changing the connection method
Note: This firmware is paused while we look into reports of a solid, yellow light on the Base Station after updating. If you have experienced this, please reach out to Wyze Customer Support.
## 4.17.1.185 (August 9, 2021)
* Fixed a Base Station bug that prevented Event videos from being received properly if sent from multiple cameras at the same time
## 4.17.1.170 (July 14, 2021)
* Fixed a bug that caused an incorrect battery usage status
## 4.17.1.123 (June 14, 2021)
*  Added Siren support
* Added a Battery Usage Summary in Device Info
* Adjusted the image sensitivity so that it’s easier to trigger motion when the sensitivity is set to low (around 10)
* Removed the push notification when the camera is fully charged to support future products
* Disabled the DHCP server while the Base Station is not pairing or in Travel Mode
## 4.17.1.52 (April 19, 2021)
* Added support for Wyze Home Monitoring
* Bug Fixes
## 4.17.1.35 (March 9, 2021)
* Added support for recording Cam Plus Events while viewing the Wyze Cam Outdoor live stream
## 4.17.1.027 (February 10, 2021)
* Fixed a bug that caused Cam Plus Events to not detect people properly
* Fixed a bug that caused accelerated battery drain with weak WiFi signal
## 4.17.1.019 (January 26, 2021)
* Added support for a software motion detection zone
* Added a Record Sound toggle
* Fixed a bug causing error code 06 and 07
Note: Firmware file removed due to critical bugs. We are working on resolving them and will send out new versions when they're ready. Sorry for the trouble!
## 4.17.1.001 (January 5, 2021)
* Added support for the Base Station to connect over WiFi
* Hid the Base Station SSID
* Added support for motion-only scheduled local recordings
## 4.17.0.186 (December 2, 2020)
* Fixed a bug that showed the wrong duration for Cam Plus videos
* Added support for syncing time
* Bug fixes
## 4.17.0.183 (November 3, 2020)
* Added support for Cam Plus
* Fixed a connectivity bug caused by incompatible firmware
* Fixed an bug that occasionally caused the firmware update to fail
* Fixed a bug that caused the Wyze Cam Outdoor to stay connected when disconnected from WiFi
* Fixed a bug that the prevented the status light from turning solid red when the camera was turned off and fully charged
* Known Issues:
* Missing Event thumbnails when Person Detection is turned off (this is a cloud issue and will be resolved later)
## 4.17.0.160 (October 29, 2020)
* Fixed a bug preventing live stream connection for newer Wyze Cam Outdoor cameras
Note: This firmware version was pushed to devices that were affected. It was not available to all Wyze Cam Outdoor devices.
## 4.17.0.159 (September 9, 2020)
* Added push notifications when the Wyze Cam Outdoor is full charged
* Added push notifications when local microSD card recordings are complete
* Fixed bugs that prevented Event videos from triggering properly
* Fixed a delayed push notification issue
* Added limited logs when the camera doesn't have a microSD card
* Fixed a Travel Mode voice prompt bug
## 4.17.0.146 (July 29, 2020)
* Added motion detection logic besides PIR when motion Events are triggered
* Fixed an issue that caused night vision to turn on and off repeatedly in some low-light situations
* Changed file directory names for microSD card recordings
* Fixed a scheduled recording download bug
* Fixed a bug that prevented retrieval of local recording information
* Bug fixes
