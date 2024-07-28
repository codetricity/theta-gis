# THETA X Internal GPS

Refer to this [blog post](https://blog.ricoh360.com/en/12219). A summary of
the main points is provided below.

## System Support

* GPS
* GLONASS
* QZSS
* SBAS(WAAS, EGNOS, MSAS, GAGAN)
* A-GPS

## Utilizing A-GPS

A-GPS (Assisted GPS) is a function that obtains auxiliary data for acquiring location information from the Internet. It allows for faster positioning speed, positioning in locations that could not be geolocated with traditional GPS, and improved positional accuracy immediately after positioning.

To enable A-GPS, _Client Mode_ must first be enabled in THETA X control menu and a direct connection must be made between THETA X and a wireless LAN router.

The time required for initial positioning has been one of the major issues with digital cameras in the past. The A-GPS technology RICOH has adopted can dramatically shorten positioning speeds, and we hope that everyone will take advantage of it. Some devices require a PC to download A-GPS, but THETA X can enable it just by turning on Client Mode before using THETA X.

THETA X A-GPS downloads two types of data: positioning speed priority data and time period priority data. The positioning speed priority data is valid for a short period of time (2 to 4 hours), but can provide positioning in less than 5 seconds. Duration priority data takes 5 to 20 seconds, but once downloaded, it is valid for about one month.

## Location Information in Videos

THETA X can use high-resolution and low-frame-rate video modes such as 8K/10fps via the API. In this video mode, continuous location information is recorded not only at the start of shooting, but also during video recording at a maximum rate of 1 Hz (once per second) in accordance with the Camera Motion Metadata standard defined by Google Street View.

## Caution

* Depending on the geographical or weather conditions, the position information may not be acquired, or the acquisition of the position information may take time. When acquiring the position information, avoid places where radio waves are blocked or reflected, such as indoors, underground, near tall buildings, or under large trees.
* Since the position of GPS satellites changes constantly, the position information may not be acquired, or the acquisition of the position information may take time.
* If there is an object that generates radio waves in the same frequency band, such as a mobile phone, or a magnetic object such as a high-tension wire near the camera, the position information may not be acquired.
* If you do not use the position information addition function for a long time or move a large distance from the place where the position information was last acquired, the acquisition of the position information may take time.
* Be sure to turn off the position information addition function in places where the use of electronic devices is prohibited, such as in hospitals and during takeoff and landing of airplanes.
* The collection of position information is regulated in some countries and regions. Use this function only in the country or region where you purchased the camera.
* The position information addition function of this camera was developed as a function for personal-use digital cameras. It cannot be used for navigation equipment for aircraft, vehicles, and people, and for surveying equipment. Ricoh is not liable for any damages caused by using it for these purposes.
