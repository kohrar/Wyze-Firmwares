# Wyze Cam v1 Firmware
## 3.9.4.35 (August 17, 2022)
* Fixed a bug that could prevent the camera from reconnecting
* This firmware is difficult for the camera to apply due to its size. If your device has a solid yellow light or cannot connect after the update, please try flashing the firmware using a microSD card to recover it
* Note: While this product isn't officially supported and we aren't able to fit more features and bug fixes onto the hardware, we’ve created firmware update 3.9.4.35 to fix this cloud connection problem.
## 3.9.4.32 (January 21, 2020)
* Improvements for syncing video and audio
* Other bug fixes 
## 3.9.4.16 (April 23, 2019)
* Integrated the latest firmware for Wyze Sense
* Added thumbnails for Event videos
* Improved the security of time lapse downloading
* Applied the detection zone and sensitivity settings for local recording
* Fixed an issue that may cause cameras with microSD cards to reboot
* Security updates
## 3.9.3.96 (Feb 20, 2019)
* Fixed an issue where devices rebooted due to poor network connections
* Fixed an issue leading to device reboot when the Wyze Cam does not have microSD card read/write permission
* Fixed an issue causing devices to not recognize microSD cards
* Fixed an issue where devices sent extra heartbeat signals to AWS
* Additional security updates
## 3.9.3.88 (Dec 13, 2018)
* Updated solution for the 'incorrect offline status' issue
* Added more guard check before firmware upgrade to make upgrade safer
* Added logs for firmware upgrade to catch upgrade issues
* Fixed an issue that cameras may not execute on/off/restart commands correctly
* Fixed an issue that camera keeps some large size videos on SD card
## 3.9.3.72 (Sept 25, 2018)
* Added automation and shortcuts, double tap zoom, and arrows in Playback
* Fixed a bug that with the camera turned off, night vision still switches on or off and IR's stay on
* Fixed a bug when the alert schedule jumps to a random time schedule after switching to all day
## 3.9.3.62 (Apr 26, 2018)
* Motion detection zone (only works with app v1.3 to be released later)
* Allowed turning on/off sound for recording (only works with app v1.3 to be released later)
* Changed motion/sound alert sensitivity to 1-100 scale (only works with app v1.3 to be released later)
* Updated connection libraries with better connection results
## 3.9.2.30 (Feb 15, 2018)
* Simplified alert logic for better alert and notification stability
* Enable recording and pause/resume in playback
* Enable microSD card format
* Provide option to turn on/off timestamp watermark in video frame
* Bug fixes
## 3.9.1.102
* Improved connectivity focusing on reducing intermittent disconnections
* Improved troubleshooting during setup
* Fixed an issue that assigned different MAC addresses for a device
* Bug fixes
## 3.9.1.84
* Alert schedule support (v1.1.42 app or above required)
* Allowed camera to sync time with the app (fixed DST time change issue, V1.1.42 app or above required)
* Added troubleshooting during setup for wrong network name and WEP network
* Tuned down motion alert sensitivity
* More accurate playback availability display (v1.1.42 app or above required)
* Updated time verification mechanism
* Bug fixes
## 3.9.1.52
* Improved connection stability
* Improved live stream stability
* Fixed an issue with no alerts being received when the alert setting is on
* Fixed an issue with local recording under ‘Record only mode’
* Fixed an issue with occasional mismatch between MAC address and device ID
