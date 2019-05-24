---
id: 2137
title: Building the Rig
date: 2017-12-05T17:15:31+00:00
author: Joe Rodgers
layout: post
guid: https://explainer.tech/sidenotes/?p=2137
permalink: /building-the-rig/
categories:
  - Mining
---
I finally built a rig. It’s a personal goal that’s been lingering since last fall. I learned quite a lot in this process. Multi GPU setups and mining software can be challenging. Cryptocurrency is tough, this Ethereum wallet is hard to wrap your head around. But it’s been fun. I will probably pick up some more GPU’s from Microcenter over the next couple months just to fill this bad boy up.

Here’s the unofficial order of operations for this whole thing:

Parts List:

  * ASUS 19 GPU motherboard
  * Pentium processor
  * (2) XFX RX 580 GTS Black Edition
  * 8GB DDR4 Memory
  * 120GB SSD
  * 1000 Platinum Power Supply
  * WiFi Adapter
  * USB Boot Drive
  * Thermal Compund

  1. Went to Microcenter and purchased all components for mining rig.
  2. Got home put parts together and no boot. I googled the mobo and apparently this thing was rushed to market and there have been many complaints of the drivers. I couldn’t get this thing to boot. Here is my first big goof up, I didn’t purchase a power switch. I had an old case sitting in the corner wo I attached the power switch connectors from the case to the ASUS mobo and it still wouldn’t boot. After a couple hours I gave up, repackaged the mobo and moved on.
  3. Now that I couldn’t build my rig I was sitting here starting at my shiny new RX 580 graphics cards… so I slapped one in my desktop PC and I was off to the races. Once the HW was installed, pulling the drivers down from AMD’s website was a breeze. I setup the cryptocurrency mining software and let it do it’s thing. After tweaking the settings in the GPU management SW, I was able to mine an average of $45 USD per month in ETH. Pretty damn cool.
  4. I returned the ASUS mobo to Microcenter with no trouble and ordered an alternate mobo off Amazon. This time I opted for a more stable mining board, the ASRock H110 Pro BTC+. Definitely the best mobo name I’ve ever heard. I picked up a power switch and a DVI to VGA display adapter too.
  5. That same day, I stopped by ACE hardware to gather supplies to build a chassis. This called for 1&#215;1 wood for the frame and a bunch of angle frame supports. I used a handsaw for the wooden pieces and let’s just say that cutting a right angle is not my strong suit. The frame got built.
  6. I began installing the components and eventually had a PC mounted in the frame. It looks like shit. I powered it up with a single GPU and guess what, it booted right into the Windows installation screen. I plugged in my key and began installation. Then it asked me where to install windows. Oops again, I forgot to install the SSD.
  7. Reboot
  8. Now I am getting black screen. Nothing is showing up. I try using the GPU for display, nope. I go back to mobo display out, nope.
  9. Power down
 10. Uninstall GPU
 11. Reboot, nothing.
 12. Reboot again. Finally Windows installer comes back and I enter key and make sure SSD is installed.
 13. Now I am in Windows. There is no wifi.
 14. Go back to desktop PC and download drivers for TPlink WiFi adapter and install them on rig.
 15. BOOM, now I have WiFi.
 16. Reboot for safe measure and now install Windows critical updates.
 17. Back to the GPU. Get a single RX 580 installed but the drivers are giving me serious heartburn. It’s not showing up in device manger. I search for a solution and can only find articles saying to pull down a legacy AMD software called Catalyst that manages old HW. It works. Now Device Manager sees the GPU.
 18. Reboot.
 19. Install Claymore mining software and fire it up.
 20. It works. I am getting 15 MH/s. I was getting 18.5 MH/s on my desktop. WTF is going on here.
 21. Go to sleep.
 22. Wake up and try to install GPU 2. It won’t show up in device manager. I am so frustrated. This is the GPU that was in my desktop so I know it works. I have Catalyst installed too and it is recognizing the other GPU. Nothing is working.
 23. Download AMD Uninstall program that wipes all AMD SW and Drivers.
 24. Start from scratch. Install AMD Relive and it works. I am prompted to update the AMD SW and do it but get errors. I try this 3 times but the update will not take. So I am stuck on the old version.
 25. Change GPU bios from Graphics mode to Compute mode, and then overclock memory and cpu.
 26. Reboot.
 27. Launch Claymore.
 28. Now I’m getting 40+ MH/s on the rig.

&nbsp;

It’s ugly, cable management is nonexistent, but damnit, it’s mine and it’s running and for now, it’s generating money. So weird. Here’s a final pic too.

<img class="posthaven-gallery-image" src="https://i2.wp.com/phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/medium_IMG_20171205_1303518.jpg?resize=800%2C533&#038;ssl=1" data-posthaven-state="processed" data-medium-src="https://i2.wp.com/phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/medium_IMG_20171205_1303518.jpg?resize=800%2C533&#038;ssl=1" data-medium-width="800" data-medium-height="533" data-large-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/large_IMG_20171205_1303518.jpg" data-large-width="1200" data-large-height="800" data-thumb-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/thumb_IMG_20171205_1303518.jpg" data-thumb-width="200" data-thumb-height="200" data-xlarge-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/xlarge_IMG_20171205_1303518.jpg" data-xlarge-width="2400" data-xlarge-height="1600" data-orig-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/IMG_20171205_1303518.jpg" data-orig-width="4056" data-orig-height="2704" data-posthaven-id="1973667" data-recalc-dims="1" /><img class="posthaven-gallery-image" src="https://i0.wp.com/phaven-prod.s3.amazonaws.com/files/image_part/asset/1973668/sNyPwRKR4oo80z_s_O4ybVU9H0w/medium_IMG_20171205_1303255.jpg?resize=800%2C533&#038;ssl=1" data-posthaven-state="processed" data-medium-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/medium_IMG_20171205_1303518.jpg" data-medium-width="800" data-medium-height="533" data-large-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/large_IMG_20171205_1303518.jpg" data-large-width="1200" data-large-height="800" data-thumb-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/thumb_IMG_20171205_1303518.jpg" data-thumb-width="200" data-thumb-height="200" data-xlarge-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/xlarge_IMG_20171205_1303518.jpg" data-xlarge-width="2400" data-xlarge-height="1600" data-orig-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/IMG_20171205_1303518.jpg" data-orig-width="4056" data-orig-height="2704" data-posthaven-id="1973667" data-recalc-dims="1" /><img class="posthaven-gallery-image" src="https://i1.wp.com/phaven-prod.s3.amazonaws.com/files/image_part/asset/1973672/xPJ6ISn07LRky6RZDkEwuV_g6UI/medium_Screenshot_120517_115214_AM.jpg?resize=800%2C533&#038;ssl=1" data-posthaven-state="processed" data-medium-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/medium_IMG_20171205_1303518.jpg" data-medium-width="800" data-medium-height="533" data-large-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/large_IMG_20171205_1303518.jpg" data-large-width="1200" data-large-height="800" data-thumb-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/thumb_IMG_20171205_1303518.jpg" data-thumb-width="200" data-thumb-height="200" data-xlarge-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/xlarge_IMG_20171205_1303518.jpg" data-xlarge-width="2400" data-xlarge-height="1600" data-orig-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/IMG_20171205_1303518.jpg" data-orig-width="4056" data-orig-height="2704" data-posthaven-id="1973667" data-recalc-dims="1" /><img class="posthaven-gallery-image" src="https://i0.wp.com/phaven-prod.s3.amazonaws.com/files/image_part/asset/1973671/bHGbt0kfDWIJWC-qOnU6pDLepz4/medium_IMG_20171205_1302533.jpg?resize=800%2C533&#038;ssl=1" data-posthaven-state="processed" data-medium-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/medium_IMG_20171205_1303518.jpg" data-medium-width="800" data-medium-height="533" data-large-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/large_IMG_20171205_1303518.jpg" data-large-width="1200" data-large-height="800" data-thumb-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/thumb_IMG_20171205_1303518.jpg" data-thumb-width="200" data-thumb-height="200" data-xlarge-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/xlarge_IMG_20171205_1303518.jpg" data-xlarge-width="2400" data-xlarge-height="1600" data-orig-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/IMG_20171205_1303518.jpg" data-orig-width="4056" data-orig-height="2704" data-posthaven-id="1973667" data-recalc-dims="1" /><img class="posthaven-gallery-image" src="https://i1.wp.com/phaven-prod.s3.amazonaws.com/files/image_part/asset/1973670/L7e5DbIyYH5pFrvF-hlg6xAU1yw/medium_IMG_20171205_1303082.jpg?resize=800%2C533&#038;ssl=1" data-posthaven-state="processed" data-medium-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/medium_IMG_20171205_1303518.jpg" data-medium-width="800" data-medium-height="533" data-large-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/large_IMG_20171205_1303518.jpg" data-large-width="1200" data-large-height="800" data-thumb-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/thumb_IMG_20171205_1303518.jpg" data-thumb-width="200" data-thumb-height="200" data-xlarge-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/xlarge_IMG_20171205_1303518.jpg" data-xlarge-width="2400" data-xlarge-height="1600" data-orig-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/IMG_20171205_1303518.jpg" data-orig-width="4056" data-orig-height="2704" data-posthaven-id="1973667" data-recalc-dims="1" /><img class="posthaven-gallery-image" src="https://i2.wp.com/phaven-prod.s3.amazonaws.com/files/image_part/asset/1973669/f9OGrveP8bsax5z-oQKtvfZOV8c/medium_IMG_20171205_1303165.jpg?resize=800%2C533&#038;ssl=1" data-posthaven-state="processed" data-medium-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/medium_IMG_20171205_1303518.jpg" data-medium-width="800" data-medium-height="533" data-large-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/large_IMG_20171205_1303518.jpg" data-large-width="1200" data-large-height="800" data-thumb-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/thumb_IMG_20171205_1303518.jpg" data-thumb-width="200" data-thumb-height="200" data-xlarge-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/xlarge_IMG_20171205_1303518.jpg" data-xlarge-width="2400" data-xlarge-height="1600" data-orig-src="https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1973667/PGeP_WEs10qtKfLZMkLq1juGKFo/IMG_20171205_1303518.jpg" data-orig-width="4056" data-orig-height="2704" data-posthaven-id="1973667" data-recalc-dims="1" /> 

&nbsp;