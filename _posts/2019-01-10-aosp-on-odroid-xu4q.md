---
layout: post
title: AOSP on ODROID-XU4Q
tag: [AOSP, Android, ORDOID]
---

## AOSP
***
![AOSP](/assets/images/2019-01-10-aosp-on-odroid-xu4q-aosp-icon.png){: width="40%" height="40%"}  
[AOSP(Android Open Source Project)](https://source.android.com "AOSP"){: target="_blank" }  
Google 에서 제공하는 Mobile Device 를 위한 open source operationg system.  
  
## ODROID
***
![HardKernel](/assets/images/2019-01-10-aosp-on-odroid-xu4q-hardkernel-icon.png){: width="60%" height="60%"}  
[HardKernel](https://www.hardkernel.com/ko/ "하드커널"){: target="_blank" }  
ODROID = Open + Droid  
It is a development platform with hardware as well as software.  
대한민국 제조사 HardKernel 에서 제작.  
  
## ODROID-XU4Q
***
![ODROID-XU4Q](/assets/images/2019-01-10-aosp-on-odroid-xu4q-board-icon.png){: width="60%" height="60%"}  
[ODROID-XU4Q](https://www.hardkernel.com/ko/shop/odroid-xu4q-special-price/ "ODROID-XU4Q"){: target="_blank" }  
HardKernel 에서 Exynos5422 를 사용하여 제작한 보드.  
  
## What I want to do
***
- AOSP 환경을 빌드하여 ODROID-XU4Q 보드에 안드로이드 환경을 구성.
- ODROID-XU4Q 보드에서 Android TV 환경으로 동작.
- ~~Youtube, Netflix 등 동영상 어플리케이션 동작 확인.(Device 인증관련 문제로 동작하지 않을 수도 있음.)~~
- USB Cable Tuner 를 장착하여, DVB-C 방송을 볼 수 있도록, [TV Input Framework](https://source.android.com/devices/tv "TV Input Framework") porting.