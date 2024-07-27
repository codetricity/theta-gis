# Sensor Data in Image Metadata

![sensor metadata](images/sensor_image/sensor_metadata.png)

For still images, sensor data is stored in the metadata of the image

Cameras have the following internal sensors:

* accelerometer
* gyroscope
* electronic compass

In addition, the THETA X has internal GPS
The data is written into the image metadata and can be read and written with a number of free tools, including [exiftool](https://exiftool.org/).

This is an example of the GPS data from the RICOH THETA X
stored in Exif IFD format.

![image GPS metadata](images/sensor_image/image_gps_metadata.png)

The example below shows shooting at 6 second intervals using
the THETA X interval mode. The camera mounted on a monopod
and held overhead.  A selfie-stick with a 1/4" mount on top will
also work.

![interval sequence](images/sensor_image/interval_sequence.jpeg)

As a quick test of GPS accuracy, I used exiftool to extract
the coordinates from the metadata and then plotted the image
locations on Google Maps.

![google maps](images/sensor_image/google_maps.png)

I also repeated the test with a Z1 using my mobile phone's GPS
to embed the location into the image metadata.

![Z1 maps](images/sensor_image/interval_maps_z1.jpeg)