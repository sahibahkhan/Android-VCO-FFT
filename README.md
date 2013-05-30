Android-VCO-FFT
===============


###Summary

This is Android Code for a Fourier Frequency Reading and Peak Analysis of a Texas Instruments LM331N Voltage Controlled Oscillator.


###Motivation: 
####Low-Cost Data-Logger (<$10), Utilizing Existing Smartphones for Analysis, Web-Connectivity, & Display

Existing data-loggers are extremely expensive and lack both web-connectivity and the ability for students to take them home.

This serves the dual purposes of creating an extremely low-cost solution for voltage levels as well as forging a path for students to continue their scientific education anywhere (as it is literally mobile device). 

Since most of my students have Smartphones, I designed, prototyped, and ironed out a way to use these smartphones* as laboratory instruments (Android proof-of-concept only for now).

*Android POC is available for now, I will create an IPhone version of this app as well (in addition to a donate version which looks a little bit more shiny).


###Uses:

As a simple web-service-connectable solution for analog medical-diagnostic or engineering/scientific data analysis (patient temperature, spectroscopy measurements, soil-resistivity, etc.)


###Licensing

Against my better financial interests, but I am considering (just considering) an MIT License for this code -- maybe.


###Details

This is for now a slow measurement technique (I believe I can get it to around 100 ms refresh rate eventually, from observation of currently published FFT apps on the Google Play Store).


###Future Hardware Enhancements


1) Wire up additional Frequency to Voltage Converter


###Future Software Enhancements

1) Email data in CSV Format

2) Increasing resolution by Quadratic Interpolation: Logging of the nearest neighbors of max measured freq (FFT-Mode) and doing quadratic interpolation to find more precise estimate of max-freq.

3) Create toggle to allow for lower sample-rates

4) Utilize wireless connectivity to periodically push data to a web-server.

5) Optimize to push upper limit on sample-rate

6) Toggle switch between FFT and Zero-Crossing peak freq methods.

.
.
.

?) Implement wavelet analysis while taking larger chunks of data -- this will allow more rapid measurements with the trade off of doing post-processing (lower screen refresh rate -- which is okay if you simply want the device to take samples and come back later).




