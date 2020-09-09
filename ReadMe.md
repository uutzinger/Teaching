# Audio and Video Setup for PodCast Teaching
The following lists low cost options for Zoom teaching with improved Audio and Video hardware. Also it helps to run two zoom sessions with one on a second monitor so you can see what the students see. 

![Urs' setup](https://github.com/uutzinger/TeachingPodCast/blob/master/Setup.jpg).

## Hardware

### Simple
To improve audio and video quality for online teaching I use the equipment listed below.
Most is inspired by Youtube generation.

1) **Microphone**  
USB Podcast microphone such as fifine K678 ($80 on Amazon).  
2) **Wide Angle Camera**  
1080P camera such as Bietrun 145deg ($35 on Amazon).  
3) **Tripod**  
Such as UBeesize 60-inch Camera Tripod ($36 on Amazon).  
4) **USB Extension Cord**  
Such as 6ft USB3.0 extension cable (9.50 on Amazon) for camera.  
5) **USB Expansion Hub**   
Such as AUkey USB3.0 ($13 on Amazon).  
6) **External Speaker**  
Such as TaoTronics Computer Speaker ($50 on Amazon)  
and to connect audio output from computer to speaker with Amazon Basics 3.5mm male to male ($6.50 on Amazon). This is my "stage monitor" as sometimes its hard to hear the students.

The lavalier microphone below together with additional USB audio input can also be used if one wants to walk around in front of whiteboard.

### Multiple Microphones
Some setups might require multiple audio input channels such as Lavalier Microphone and streaming of arbitrary video sources. Most teaching does not need that.  

7) **Lavalier Microphone**  
Such as Hotec Wireless Headset Lavalier Lapel Microphone ($50 on Amazon)  
8) **Additional Audio Input/Output**  
Such as UGREEN USB Audioadapter ($16 on Amazon)  
9) **Earbuds**  
Such as Vogek Earbuds ($11 on Amazon)

## Software
Usually there is **no additional** software needed for simple setups, however when using external microphones one needs to select proper audio input source in Zoom by clicking on uparrow on microphone or video symbol to select an other camera.  

When one wants to stream from arbitrary video source, Open Source **OBS studio** provides virtual camera which can be used as input to Zoom and OBS can grab any parts of the computer screen. Usually that is not needed as one can already share the screen.

When one wants to provide multiple audio input sources an audio mixer such as **VoiceMeter Banana** is recommended. It is free software. Setup is not trivial. It provides two virtial audio in/out devices. One is for Zoom, the other to connect to Windows audio. The trick is not to connect the microphone to to speaker directly as that creates feedback. Similar Zoom input should not be connected to Zoom output otherwise echo is generated.
