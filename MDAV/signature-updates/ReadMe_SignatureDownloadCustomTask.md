# Windows Defender - Signature Download Custom Task

It is crucial to keep antimalware definitions up-to-date to maintain optimal protection. 
Configuring VMs and VM hosts to stay up-to-date with antimalware definitions correctly can help
avoid increased network bandwidth consumption and out of date AM definitions. Misconfigurations can result in decreased usability of the VM and/or decreased protection from malware.
Windows Defender keeps itself updated when configured with default settings, but how do you keep machines without internet or Windows Update connectivity updated?

This script simplifies deployment of antimalware definitions for VMs and VM hosts. It enables VMs that don't have Internet connectivity or Windows Update (WU) connectivity to have up-to-date definitions by pulling from a UNC share updated by the VM host.

Download the script from PowershellGallery here:

[https://www.powershellgallery.com/packages/SignatureDownloadCustomTask](https://www.powershellgallery.com/packages/SignatureDownloadCustomTask)
