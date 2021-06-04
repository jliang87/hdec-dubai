---
layout: post
title:  "Door Security Issues and Resolutions"
date:   2021-06-03 
categories: Door Security
---

First, download the operating software for the door security by going to [https://www.hikvision.com/en/support/download/software/ivms4200-series/](https://www.hikvision.com/en/support/download/software/ivms4200-series/). After installation, open the program and create a super user for local login to control the door security devices as directed. 


The following are the main functionalities needed for most uses cases inside our office.
>![]({{site.baseurl}}/assets/door1.PNG){:style="width:800px"}

To add the 15th floor and 27th floor devices, go to Device Management and perform the following. Note the IP's for the two locations. Both devices use an 'admin' account with the same password. Ask our office administrator for password.
>![]({{site.baseurl}}/assets/door2.PNG){:style="width:800px"}


After the devices are added, go to Persons and "Get From Devices" to import the existing personel records. After import, one can view and modify personel information `locally`. To change card number, a card reader is needed. Finger print and facial recognition can be done on the devices themselves. 
>![]({{site.baseurl}}/assets/door3.PNG){:style="width:800px"}
>![]({{site.baseurl}}/assets/door4.PNG){:style="width:800px"}

For the changes made to be effective on the actual devices or `remotely`, go to Access Control -> Authorization -> Access Group and add new rule, selecting all personel and devices then save. Finally, Apply Changes to Device, which should apply changes to both 15th and 27th floor.  
>![]({{site.baseurl}}/assets/door5.PNG){:style="width:800px"}

Click on the clog icon to change the remote configurations of devices. In System -> System Maintenance, one can roboot the device. In System -> User, one can change the device's admin user password. 
>![]({{site.baseurl}}/assets/door6.PNG){:style="width:800px"}
>![]({{site.baseurl}}/assets/door7.PNG){:style="width:800px"}
>![]({{site.baseurl}}/assets/door8.PNG){:style="width:800px"}

And finally in Time and Attendance -> Attendance Statistics -> Attendance Record, one can retrieve the namesake.
>![]({{site.baseurl}}/assets/door9.PNG){:style="width:800px"}
