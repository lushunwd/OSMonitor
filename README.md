OS Monitor for Android  [![Build Status](https://drone.io/github.com/eolwral/OSMonitor/status.png)](https://drone.io/github.com/eolwral/OSMonitor/latest) [![Coverity Scan Build Status](https://scan.coverity.com/projects/3432/badge.svg)](https://scan.coverity.com/projects/3432)
=======

#### Going to Mainitenance Mode (2016/08/29)
Due to Android 7.0's security enhancement, OS Monitor won't work any more, I decide to move the project into manitenance mode, it won't support Android 7.0 and following version.

#### How to become a Beta Tester
1. [Join this community](https://plus.google.com/communities/104176911627256834500)
2. [Opt-in link](https://play.google.com/apps/testing/com.eolwral.osmonitor)

=======

OS Monitor is a tool for monitoring your Android system.

It offers the following information.

- Processes - monitor all processes.
- Connections - display every network connection.
- Misc - monitor processors, network interfaces and file system.
- Messages - search dmesg or logcat in real-time. 

if you would like to know that how it works, please check Wiki page!

**Support Languages**

- Polish - Thanks to Jarek Mazur
- Hebrew - Thanks to Zamarin Arthur
- Italian - Thanks to Gabriele Zappi
- German - Thanks to Benko111@XDA
- Russian - Thanks to equeim
- Spanish  - Thanks to xphnx
- Hungarian - Thanks to Zsigmond
- Serbian - Thanks to pejakm
- Hindi - Thanks to chaitanya-lakkundi
- English
- Chinese

### Developed By ###

* eolwral@gmail.com

### Wiki & FAQ ###
wiki - https://github.com/eolwral/OSMonitor/wiki

### License ###

    Copyright 2013 Kenney Lu

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


----------

[![Donate using PayPal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=D9NDEKVA8WE3A "Donate using PayPal")

----------

### Change Log ###

**Version 3.5.0.7**
- Merge 'Force Close' feature for process view (Thanks to Venryx)
- Hindi Language (Thanks to chaitanya-lakkundi)
- Fix 2 FC issues
- Use new NDK
- Set "maxSdkVersion" as API 23 (it won't support Android 7.0)

**Version 3.5.0.6**
- Add a option for notification's background color
- Strip image's inforamtion and adjust color

**Version 3.5.0.5**
- Fix notification issue (Thanks to Sigfried)

**Version 3.5.0.1**
- Fix flawd translation 
- Improve compatiable for root mode

**Version 3.5.0.0**
- Spanish Language (Thanks to xphnx)
- Hungarian Language (Thanks to Zsigmond)
- Serbian Language (Thanks to pejakm)
- Notification Icon for Material UI (Thanks to xphnx)
- Fix MAC address (Thanks to walek75 and Roy)
- Add AppInfo for process (Thanks to digi-owl)
- Fix incorrect status for AutoStart

**Version 3.4.1.0**
- Fix SetCPU function (Thanks to Ulrich)

**Version 3.4.0.9**
- Bettr naming for unix domain socket
- Fix command for root mode

**Version 3.4.0.8**
- Fix crash when set cpu
- Fix some issues on root mode

**Version 3.4.0.6**

- Fix incorrect swap value
- Fix incorrect sudo command (Thanks to Stephen)

**Version 3.4.0.2**

- Fix incorrect UDP status (Thanks to haarp)

**Version 3.4.0.1**

- Fix crash when pressing hardware button on LG phone (Thanks to Jimmy) 
- Fix typo for Russia language files (Thanks to Serge)

**Version 3.4.0.0**

- Reduce memory usage about 10% and improve speed. (Thanks to ARoiD)
- Use unix domain socket on filesystem to fix TCP issue. (Thanks to Mateusz)

**Version 3.3.1.0**

- Support Android Lollipop
- Use NDK r10c and support library v21 

**Version 3.3.0.5**

- Fix force close on Android 2.3

**Version 3.3.0.2**

- fix logcat function on Android L Preview
- fix "watch log" function (Thanks to Gerd)
- support 3 new screen density (experiment) 

