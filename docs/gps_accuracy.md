# GPS Accuracy

![GPS Data](images/home/sensor_image/sensor_metadata.png)

The location accuracy of GIS chips of most mobile phones and also the THETA X chip vary based on satellite location and other factors.  The [US government official site on GPS](https://www.gps.gov/systems/gps/performance/accuracy/) indicates that mobile phones can provide 5m accuracy under an open sky. As a rough guide, the THETA X can be grouped with the accuracy of mobile phone.
There are two strategies to store higher accuracy:

1. use an external GPS with higher accuracy and store it in a separate log file.  Match the GPS timestamp with the timestamp of the THETA images or video frames (in CaMM data in certain formats).
2. store GPS information in the image metadata of each image.
