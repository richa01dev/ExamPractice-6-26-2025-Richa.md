# ExamPractice-6-26-2025-Richa.md
Two diffrent methods of creating bootable USB are:
Method 1-Using the Windows Media Creation Tool
Download the Media Creation Tool:
Go to the official Microsoft Windows download page(https://www.microsoft.com/software-download/windows10 or windows11 depending on version).
Click on "Download tool now" 
Run the tool:Open the downloaded file and accept the license agreement.
Choose “Create installation media”:Select language, edition, and architecture 
Insert your USB drive:
Select USB flash drive:Choose your USB from the list and proceed.
Let it create the bootable drive:
The tool will download Windows and set up the USB. 

Method 2-Using Rufus 
Download Rufus:Go to rufus.ie and download the latest version.
Download Windows ISO:Get the official ISO from Microsoft’s site 
Open Rufus:Plug in your USB, open Rufus (no install needed).
Select the USB and ISO:Under Device, pick your USB.
Under Boot selection, choose Disk or ISO image and load your ISO.
Use default settings for most users (Partition scheme: GPT, Target system: UEFI).
Click “Start”:Rufus will warn that the drive will be erased. Click OK to continue.
It creates the bootable USB in a few minutes.
A video which can help a little better to understand:
https://www.youtube.com/watch?v=C8zeiiZS1Yg

Software tools which are in need to create bootable USB:
For Method 1 Windows Media Creation Tool: Windows Media Creation Tool (This is the official Microsoft program that downloads Windows and creates the bootable USB for you).
For Method 2 Using Rufus:Rufus — A free third-party program that writes the Windows ISO image onto the USB to make it bootable.
Windows ISO file — The actual Windows installation file in ISO format which you can download officially from Microsoft’s website.

For creating a bootable Windows USB, the USB drive should be at least 8 GB in size.

Can you do multiple boots from on key?
yes, with special tools we can create a multi-boot USB that lets you choose between different operating systems or installers at boot time.





























