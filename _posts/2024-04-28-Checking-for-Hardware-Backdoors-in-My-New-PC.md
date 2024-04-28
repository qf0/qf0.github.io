---
layout: post
title: "Checking for Backdoors in My New PC"
date: 2024-04-28
---
I bought a new PC for a cheaper price from Hong Kong. I was worried about backdoors from the CCP, so here's some steps I've done so far to check for backdoors:
Dumped the BIOS firmware using Chipsec and uploaded it to VirusTotal and Hyrbid-Analysis as well as light research using UFEI viewer etc. The motherboard was custom made in Shenzhen which is in mainland China which is concerning, but honestly a lot of hardware comes from there and there's a pretty cool marketplace in Shenzhen.
The chips on the board look legit. Of course there could be a special chip that I overlooked, but I'm not skilled enough to detect something like that and the companies I reached out that specialize in supply chain security left me on read, so :/.

Of course there could be backdoors in the hard drive they included, but that's really rare and I can just buy a new hard drive for cheap. Overall, I'm pretty confident it doesn't have any backdoors, and I'm just a young random dude in the midwest, so I doubt they would target me.
I'm planning to at least disable Intel ME using the HAP backdoor, and I'm going to try to port Coreboot to my motherboard or use Purism Libre mini "Pureboot" fork for a similar motherboard. 
