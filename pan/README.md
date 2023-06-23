# Wyze Cam Pan Firmware
## Webcam
* The webcam video, speaker, and mic all function properly.
* Mic audio may be low. We suggest you set your audio level to medium, or use your own microphone and speaker.
## 4.29.4.41
* RTSP beta

## 4.10.9.1851 (February 2, 2023)
* Improved the Event Video upload success rate
* Fixed a bug that affected camera connection recovery after a cloud outage

Note: Possible issues with firmware bricking the Cam Pan v1: https://forums.wyze.com/t/wyze-cam-pan-won-t-factory-reset/253005/28

## 4.10.9.1574 (December 7, 2022)
* Fixed a bug that affected camera connection on Wi-Fi with a long password
* Fixed a bug that prevented AI detection settings from syncing
## 4.10.9.1472 (November 2, 2022)
* Fixed a bug that affected camera IoT connection after a cloud outage
* Fixed a bug that caused incorrect membership status after switching between statuses
* Fixed a bug that caused Error 3001 when viewing motion and sound Events
## 4.10.9.1433 (September 27, 2022)
* Improved Internet connection code
* Improved live stream connectivity
* Improved IoT connectivity
* Improved microSD card playback stability
* Bug fixes
* Security improvements
* Due to the security improvement on this firmware, you will need to go through the setup process for your camera if you go back to firmware 4.9.8.1002 or below. Because of this, we are removing those firmware files from this page.
Note: We are doing a gradual release for this firmware over several weeks. If you do not have this firmware version yet, don't worry! You'll receive it later.
## 4.10.8.1002 (March 17, 2022)
* Security improvements
* AI Event bug fixes
## 4.10.8.860 (January 26, 2022)
* Bug fixes
Note: This firmware is paused because some of the devices with this firmware lose AI detection. We are working on a new firmware version to resolve this issue.
## 4.10.8.746 (December 20, 2021)
* Added support for microSD cards larger than 32GB
* Improved the Cam Plus Event replay success rate
* Improved camera stability
* Fixed a constant reboot bug
* Fixed a bug that prevented sound notifications when using Cam Plus
* Fixed a bug that caused missing Events when using Cam Plus
* Other bug fixes
Note: This release is paused while we investigate an AI bug and live streaming issue. We apologize for the inconvenience.
## 4.10.8.501 (November 10, 2021)
* Bug fixes
## 4.10.7.1068 (September 8, 2021)
* Bug fixes
## 4.10.7.798 (July 21, 2021)
* Improved an issue that caused Cam Plus Events to skip or lose frames
* Changed the MP4 audio format
* Reduced the time for receiving push notifications
* Improved sound detection sensitivity
* Fixed a bug that caused a loud sound in Playback if sound was already enabled in the live stream
* Added WPA3 WiFi network support
* Improved camera stability
* Security improvements
## 4.10.6.241 (March 9, 2021)
* Increased 2-way audio volume for Wyze Cam v2 and Pan
* Adjusted the motion detection sensitivity per users’ feedback
* Improved Cam Plus Event push notification time (less strong networks may not see much change)
* Improved the stability of time stamp syncing with the NTP server
* Improved stability for motion detection
* Fixed a bug that caused Event videos to lose a couple of seconds at the beginning
* Fixed a bug causing unnecessary camera reboot
* Other bug fixes and improvements
Note: This firmware update has been paused while we investigate the cause of an issue that may be related to this update. If we find that the update is not the cause, we will resume the rollout.
## 4.10.6.218 (November 18, 2020)
* Added support for a custom motion detection zone (2.15 app required)
* Fixed a bug that caused turned off cameras to start recording after being power cycled
* Changed the algorithm for motion detection when a detection zone is enabled.
* Changed the motion tracking logic when a detection zone is enabled.
Note: This firmware update is paused as we look into increased motion detection sensitivity. If you still want this update, you can flash the firmware using the file linked here.
## 4.10.6.199 (October 21, 2020)
* Fixed a bug that would impact the DST time change
* Fixed a bug that prevented syncing with GMT+13 and GMT+14 time zones
## 4.10.6.193 (October 5, 2020)
* Fixed a bug that caused Wyze Cam Pans to go offline if the camera time zone is outside of GMT-8 to GMT+8
## 4.10.6.191 (September 30, 2020)
* Improved the logs for error analysis
* Fixed a bug that may increase the 'no fragment' error for Event videos
* Fixed a bug which may cause Cam Plus devices to not record motion
* Fixed an bug that could cause a log submission to fail
* Fixed a reboot issue during microSD card playback
* Fixed a reboot issue related to detection zone settings
* Fixed a Wyze Cam Pan bug that caused over-sensitive motion detection when a Detection Zone was enabled
* Fixed a Wyze Cam Pan bug that could trigger Events due to motor movement
* Fixed a bug that could erase microSD card files when not using the FAT32 format
* Other bug fixes
Note: This update was stopped and we will not be uploading the file for download due to a time zone bug fixed in 4.10.6.193.
## 4.10.6.156 (July 28, 2020)
* Added support for Person Detection on CMC videos (2.12 app update required)
* Improved CMC camera stability
* Improved Wyze Cam performance
* Fixed an issue which could cause Wyze Cams using CMC to reboot
* Other bug fixes
## 4.10.5.111 (March 18, 2020)
* Optimized the SD card ejection logic
* Improved Google Nest Hub streaming
## 4.10.5.98 (January 27, 2020)
* Removed XNOR person detection
* Added support for ejecting microSD cards
* Improvements for syncing video and audio
* Fixed event videos making noise when camera has disabled sound recording and CMC service is being used
* Fixed live stream disconnect issues for camera groups
* Other bug fixes
## 4.10.5.94 (January 21, 2020)
* Removed XNOR person detection
* Added support for ejecting microSD cards
* Improvements for syncing video and audio
* Fixed event videos making noise when camera has disabled sound recording and CMC service is being used
* Other bug fixes
## 4.10.5.34 (November 15th, 2019)
* Added support for Complete Motion Capture, an add-on service that will record to the cloud whenever there is motion. Free trial available after the upcoming 2.6 app update.
* Bug fixes
## 4.10.3.169 (September 24th, 2019)
* Added New AI model improving person detection
* Added Security Updates
*  4.10.3.108 (July 8, 2019)
* Added person detection support
* Added support for Wyze Sense status light toggle
* Fixed an issue that may cause time lapse file download failure
* Fixed an issue that may cause Wyze Sense Bridges to stop working when rebooting or upgrading the camera
* Fixed an issue that may cause Wyze Sense Bridges to remain solid yellow if the Wyze Cam Pan loses power
## 4.10.3.60 (May 9, 2019)
* Fixed an issue that prevented motion from being properly detected
## 4.10.3.50 (April 23, 2019)
* Integrated the latest firmware for Wyze Sense
* Improved the security of time lapse downloading
* Fixed the issue with no internet connection causing reboot
* Improved the compatibility with mesh networks
* Applied the detection zone and sensitivity settings for local recording
* Security updates
## 4.10.3.40 (March 4, 2019)
* Fixed an issue where devices rebooted due to poor network connections.
* Fixed an issue leading to device reboot when the Wyze Cam does not have microSD card read/write permission.
* Fixed an issue causing devices to not recognize microSD cards.
* Fixed an issue where devices sent extra heartbeat signals to AWS.
* Added logic to adjust the camera clock automatically for Daylight Savings Time.
* Security updates
## 4.10.2.31 (January 15, 2019)
* Minor IQ (image quality) update, which fixed some devices having yellow tint images
## 4.10.2.27 (December 17, 2018)
* Added more guard check before firmware upgrade to make upgrade safer
* Added logs for firmware upgrade to catch upgrade issues
* Fixed an issue that cameras may not execute on/off/restart commands correctly
* Updated solution for the ‘incorrect offline status’ issue
* Fixed an issue that can cause cameras to upload event videos multiple times
## 4.10.1.40 (October 22, 2018)
* Fixed a bug that caused Playback to play faster during the minute transition
* Added that photos are saved on microSD card as well as the device Album
* Fixed the yellow tint issue on Wyze Pan images
* Other bug fixes
## 4.10.1.27 (September 18, 2018)
* Added V1.5 feature support
* Fixed a bug when the camera is off, night vision switches on/off and IR lights stay on
* Fixed a bug when the camera is off, it still sends alerts
* Other bug fixes
## 4.10.1.8 (July 11, 2018)
* Added Alexa integration support
* Added v1.4 App IoT feature support
* Fixed a bug that night vision LED’s stayed on when the camera is turned off.
* Fixed an issue when IoT status is not updated correctly
* Bug fixes
## 4.10.0.223 (June 15, 2018)
* Fixed an issue for firmware upgrade
* No functionality change
## 4.10.2.222 (May 30, 2018)
* Support all existing features for Wyze Cam v1/v2
* New pan/tilt control support
* New motion tracking feature
* New Pan Scan feature
* Enhanced 2-way audio
