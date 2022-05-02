# Computer based 12 lead ECG using STM32F401 Microcontroller
STM32F401 based 12-Lead ECG with USB 2.0 Connectivity

## Overview
This is my final year project to achieve my Bachelor's Degree in Physics, University of Lampung. My inspiration to create this project was my first work from mandatory intership program at RSUD Dr. H. Abdul Moeloek Provinsi Lampung: Interfacing Fukuda Denshi FCP-7101 ECG to PC using Ethernet/LAN (because the ECG doesn't have any external connectivity but Ethernet 10Base-T port). I was thinking, is it great to create device like that but using more common connectivity i.e. USB? And then I start designing the project on paper.

My reference for this design is from [Ivan Dotsinsky's work](http://dx.doi.org/10.1109/51.664031). This work is a great example how a high performance multichannel ECG can be built using op-amp. Although the design is just using 12-bit ADC (recent new designs has been used 24-bit ADC), but it can amplify and record ECG signals with great quality.

## Specifications
1. Simultaneous 12 lead ECG acquisition
2. 12-bit ADC resolution
3. High performance ECG amplifier built using TL074 and AD823
4. USB 2.0 connectivity, no need for external power supply
5. Easy to use GUI program made with Visual C#
6. STM32F401 for digital signal processing (ST filter, HPF, LPF, and 50 Hz noise reduction)

My research article currently still in review, but if you need more detail about this project you can contact me (reyhan_issatyadi@yahoo.co.id) and I will give you the draft of my project report (skripsi, in Indonesian).

## Preview
1. The device

![gambar](https://user-images.githubusercontent.com/57849203/166177218-2b55078a-ece2-4628-bb2a-0d1773bc052f.png)
![gambar](https://user-images.githubusercontent.com/57849203/166177302-725fda99-37e4-4ef7-b75f-2e6f06ed1bd7.png)

2. Recording progress

![gambar](https://user-images.githubusercontent.com/57849203/166177339-8c101966-e788-4429-8644-dab7d6d76dde.png)
![gambar](https://user-images.githubusercontent.com/57849203/166177497-66c3482e-95d8-4024-8e3a-b7066b92867a.png)

3. The GUI program

![gambar](https://user-images.githubusercontent.com/57849203/166177416-ecef123f-195d-4855-95c6-3bce4bbb7c26.png)

4. Sample recording from my lecturer

![00003a_DKA](https://user-images.githubusercontent.com/57849203/166177441-f1575fb3-7c1f-42ed-8e4f-6090c274f7b0.png)

