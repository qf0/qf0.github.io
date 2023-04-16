---
layout: post
title: "Virus Scanners and Anti Virus Misconceptions"
date: 2023-04-16
---

On various forums, I've seen what appears to be a notion that simply scanning an unknown portable executable(PE) through VirusTotal, anti-virus, or Hybird-Analysis would detect all malcious programs. 
However, this is incorrect and I'll explain why in this blog post. VirusTotal scans a PE through various Anti-Virus software. This will show if a PE matches a fingerprint related to know malware. This is called signature based detection. 
Signature based detection can be bypassed though. Methods such as packing, using a polymorphic engine, adding junk code, renaming variables, functiong, and/or encrypting/obfuscating can result in a new PE signature resulting in no detection.

Tailored malware made or modified for a target would also usually bypass signature based detection, and some advanced malware could it's being ran through VirusTotal, and/or Hybird-Analysis and not run the malware's payload.
Such can be acomplished through fingerprinting VirusTotal system things like a Google IP, or OS license or such foruth. Or simply by adding an if statement delay to not run if the host OS's clock is not matching a certian date. 
Behaviour based detection can be bypassed by also preventing execution of detection of analysis and by changing the malware payload's options/methods. Anti-virus vendors usually grab the PE's uploaded to VirusTotal and such for manaual or advance analysis for discovery of complex/new malware. 

Running unknown/sus PE/files in a virtual machine (network off. Unless someone is willing to risk wasteing a VM escape 0day on you. Which can go for a bit of money based on Zerodium's 0day price chart) is usually a save bet. Manually doing reverse engineering is the only way to truely know if a PE/file is malware or not. Reverse Engineering requires a lot of skill, and time however. Especially for black box (no source code) advance malware.
Don't always trust positive reviews of software online. There's services to buy botted reviews/ratings and download points can be replaced with malware if someone hijacks a privileged account. 
Conclusion: Anti-virus, and online scanners such as VirusTotal can be fooled. Manual reverse engineering is the only way to know for sure if a PE/file is safe. 
