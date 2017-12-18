Android-Image-Filters
=====================
## Introduction

### Image Filter allows you to add various effect on image.

There are main two purpose of Image Processing 

1. Image Understanding: It is used to identify content of image, weather image contents human faces, objects (bus, train, etc.), measure dimension of objects,etc, OpenCV (Open Source Computer Vision Library) is mainly used for Image Understanding. 
2. Image Beautify : It is used to beautify image by adding different filters, adjust colour, adjust contrast, etc..

Android provides two options for Image Filters/Processing

1. Using SDK with Java Code,Android SDK has "android.graphics" package contains Classes related to Image Processing. 
2. Using NDK with C/C++ Code

### Application

I developed simple application which demonstrated 30 different image filters. Application has on button to select image from gallery, bottom strip contain visual representation of effect, simply click on effect to apply in your selected photo. Application will apply selected effect and store image in your SDCard with effect name.
Entire logic of Image filter/processing is written in pure java (without NDK/C++). 

### ScreenShots

![alt text](http://2.bp.blogspot.com/-UCEaLaFmkNA/UigUdxxSIoI/AAAAAAAAETc/L4yAbF2HJyk/s320/device-2013-08-30-104059.png "Screenshot 1")   ![alt text](http://3.bp.blogspot.com/-bBRtY1g0ivs/UigUduB-cLI/AAAAAAAAETY/a7KEJ7PcET4/s320/device-2013-08-30-104130.png "Screenshot 2")

I give full credit about Android Image Filters to **Pete Houston  (<http://petehouston.com/>).**

Original Source Code:  <http://xjaphx.wordpress.com/learning/tutorials/>

### References

1. <http://www.jhlabs.com/ip/filters/>
2. <http://developer.android.com/reference/android/media/effect/EffectFactory.html>
3. <https://code.google.com/p/android-image-filtering/>
4. <http://xjaphx.wordpress.com/learning/tutorials/>
5. <https://code.google.com/p/android-image-filtering/>
6. <https://github.com/ragnraok/android-image-filter>
