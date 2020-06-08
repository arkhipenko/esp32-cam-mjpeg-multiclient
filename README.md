# ESP32 MJPEG Multiclient Streaming Server

This is a simple MJPEG streaming webserver implemented for AI-Thinker ESP32-CAM or ESP-EYE modules. 

This is tested to work with **VLC** and **Blynk** video widget. 



**This version uses FreeRTOS tasks to enable streaming to up to 10 connected clients**



Inspired by and based on this Instructable: [$9 RTSP Video Streamer Using the ESP32-CAM Board](https://www.instructables.com/id/9-RTSP-Video-Streamer-Using-the-ESP32-CAM-Board/)

Full story: https://www.hackster.io/anatoli-arkhipenko/multi-client-mjpeg-streaming-from-esp32-47768f

------

##### Other repositories that may be of interest

###### ESP32 MJPEG streaming server servicing a single client:

https://github.com/arkhipenko/esp32-cam-mjpeg



###### ESP32 MJPEG streaming server servicing multiple clients (FreeRTOS based):

https://github.com/arkhipenko/esp32-cam-mjpeg-multiclient



###### ESP32 MJPEG streaming server servicing multiple clients (FreeRTOS based) with the latest camera drivers from espressif.

https://github.com/arkhipenko/esp32-mjpeg-multiclient-espcam-drivers



###### Cooperative multitasking library:

https://github.com/arkhipenko/TaskScheduler

