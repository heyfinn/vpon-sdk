---
layout:         "ios"
title:          "iOS - AdMob"
lead:           "iOS メディエーション"
description:    "The description for this page in the meta data in header."
keywords:       "Keywords for this page, in the meta data"
permalink:       jp/ios/advanced/admob/
lang:            "jp"
---
# Google AdMob mediation
--------
Google Admob Mediation document, please refer to [here].

# Google Ad Network Mediation
-----

1. Log in Google AdMob.
 Please log in to your [AdMob account][0]
![1]  

2. `Monetise` -> `+ Monetise new app`  
![][2]  

3. Select an app: <br>
  (1) Put your app name.<br>
  (2) Select `platform`. <br>
  (3) Click `Add app`. <br>
![][3]  

4. Select ad format and name ad unit: <br>
(1) Choose "banner" or "interstitial" ad type. <br>
(2) Setting. <br>
(3) Ad unit name (ex. Vpon_Banner).  <br>
(4) Save it. <br>
![][4]  

5. Get an Ad unit ID, then click Done.
![][5]  

6. Edit mediation
![][6]  

7. New ad network
![][7]  

8. Set Vpon into mediation list：    <br>
(1) Find the VPON Network tag in Available ad netwroks <br>
(2) Vpon Ad ID: put the Vpon’s Banner ID that you get from vpon’s back office.  <br>
(3) Zone: Choose the region, which you want to request ads from Vpon Platform.  <br>

(If the user of your app is from China, you need to fill with `cn` in this column; otherwise, you need to fill with `tw`.)

![][8]  


# Download Sample Code
--------------------
[Download Sample Code]

  [here]: https://developers.google.com/mobile-ads-sdk/docs/admob/mediation#android
  [0]: http://www.google.com.tw/ads/admob/
  [1]:  {{site.baseurl}}/assets/img/AdMobScreenshotEnglishAndroid1.jpg
  [2]:  {{site.baseurl}}/assets/img/Admob2_eng.png
  [3]:  {{site.baseurl}}/assets/img/Admob3_eng.png
  [4]:  {{site.baseurl}}/assets/img/Admob4-Android_eng.png
  [5]:  {{site.baseurl}}/assets/img/Admob5-Android_eng.png
  [6]:  {{site.baseurl}}/assets/img/AdMobScreenshotEnglishAndroid6.jpg
  [7]:  {{site.baseurl}}/assets/img/Admob7-Android_eng.png
  [8]:  {{site.baseurl}}/assets/img/AdMobDefaultAdNetWork.jpg
  [Download Sample Code]: {{site.baseurl}}/ios/download/#admob