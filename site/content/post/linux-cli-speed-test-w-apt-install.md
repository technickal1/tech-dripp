---
title: Linux CLI speed test w/apt install
date: 2018-12-17T17:26:28.630Z
description: >-
  Sometimes when you need a quick speed test, using command line can be the
  fastest.
---
It will take the overhead of anything like HTML, CSS, or Javascript out of the equation. Follow these simple steps to install the speedtest.net command line tool into your version of Linux.

```
sudo apt install speedtest-cli

Need to get 19.1 kB of archives.
After this operation, 85.0 kB of additional disk space will be used.
Get:1 http://deb.debian.org/debian stretch/main amd64 speedtest-cli all 1.0.0-1 [19.1 kB]
Fetched 19.1 kB in 1s (11.5 kB/s)  
Selecting previously unselected package speedtest-cli.
(Reading database ... 106147 files and directories currently installed.)
Preparing to unpack .../speedtest-cli_1.0.0-1_all.deb ...
Unpacking speedtest-cli (1.0.0-1) ...
Processing triggers for man-db (2.7.6.1-2) ...
Setting up speedtest-cli (1.0.0-1) ...

speedtest-cli

nickhenryhousehold@penguin:~$ speedtest-cli
Retrieving speedtest.net configuration...
Retrieving speedtest.net server list...
Selecting best server based on ping...
Hosted by BridgeMAXX (Indianapolis, IN) [56.60 km]: 9.227 ms
Testing download speed................................................................................
Download: 64.38 Mbit/s
Testing upload speed....................................................................................................
Upload: 34.53 Mbit/s
nickhenryhousehold@penguin:~$ 
```

I've tested this on Debian Stretch and it worked flawlessly!
