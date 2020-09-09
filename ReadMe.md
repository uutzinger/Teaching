# Audio and Video Setup for PodCast Teaching
The following lists low cost options for Zoom teaching with improved Audio and Video hardware.

![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png).

## Hardware

### Simple
To improve audio and video quality for online teaching I use the following equipment.
Most is inspired by youtube generation (e.g Mark Rober and Destin from Smater Every Day)  

1) **Microphone**  
USB Podcast microphone such as fifine K678 ($80 on Amazon)  
2) **Wide Angle Camera**  
1080P camera such as Bietrun 145deg ($35 on Amazon)  
3) **Tripod**  
Such as UBeesize 60-inch Camera Tripod ($36 on Amazon)  
4) **USB Extension Cord**  
Such as 6ft USB3.0 extension cable (9.50 on Amazon)  
5) **USB Expansion Hub**   
Such as AUkey USB3.0 ($13 on Amazon)  
6) **External Speaker**  
Such as TaoTronics Computer Speaker ($50 on Amazon)  
and to connect audio output from computer to speaker Amazon Basics 3.5mm male to male ($6.50 on Amazon)

### Multiple Microphones
Some setups might require multiple audio input channels such as Lavalier Microphone and streaming of arbitrary video sources.  

7) **Lavalier Microphone**  
Such as Hotec Wireless Headset Lavalier Lapel Microphone ($50 on Amazon)  
8) **Additional Audio Input/Output**  
Such as UGREEN USB Audioadapter ($16 on Amazon)  
9) **Earbuds**  
Such as Vogek Earbuds ($11 on Amazon)

## Software
Usually there is **no additional** software needed for simple setups, however when using external microphones one needs to select proper audio input source in Zoom, Discord etc.  

When one wants to stream from arbitrary video source, Open Source **OBS studio** provides virtual camera which can be used as input to Zoom / Discord and OBS can grab any parts of the computer screen.

When one wants to provide multiple audio input sources an Audiomixer such as **VoiceMeter Banana** is recommended. Its free software. Setup is not trivial. It provides two virtial audio in/out devices. One is for Zoom / Discord, the other to connect to Windows audio. The trick is not to connect the microphone to to speaker directly as that creates feedback. Similar Zoom/Discord input should not be connected to Zoom output otherwise echo is generated.