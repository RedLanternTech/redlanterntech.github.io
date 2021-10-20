---
layout: post
title: Fresh Installs And Checklists
---

At the begining of the year, I had decided to try out Linux Mint on my laptop (A Lenovo Yoga 730).  I have used Linux in the past, especially on Raspberry Pi's
but running it as a daily driver had been hit or miss.  The program I was last holding out on I no longer need to use, so I was free to switch.  
Since January I have swapped over all my major systems to Linux Mint.  I did spend some time over the summer playing with other distributions (Kubuntu, Manjaro, and KDE Neon) but Linux Mint was the the one that stuck. I'll do another post later on my reasons for switching to Linux at home.  

Over the last week, I had to perform a few upgrades on a few personal systems.  First was my trusty old Dell Latitude D630.  Its hard drive and battery 
went to my Grandma to get her system running better and faster.  It is also a D630 that was running Lubuntu but it needed some TLC.  Swapping to Linux Mint XFCE and a 
solid state hard drive really did the trick.  Key advice for anyone **Always Make Grandma Happy**.  That swap also showed me a really nice thing about Linux.  You can carry your Home directory over to other systems and it (mostly) brings all your settings over.  

Because I had borrowed the parts from my D630, I had to do a replacement.  While looking for a SSD that would work, I also found a NVMe that would fit in my 
main desktop in my Radio Room (yes, I have a radio room).  That system was running Kubuntu off a USB 3.0 disk because I had one lying around and wanted to keep
the dual-boot with Windows 10.  

The first thing to do was create a list of all the major items I need to do.  I do this for any reinstall or install I do of a computer.  This keeps me in check
so I don't miss any crucial files or settings.  So what does my list look like for the D630?

## D630 Software and Setup Checklist
- Run `sudo apt update && sudo apt upgrade -y` first 
- Run `sudo apt remove libreoffice-*`
- Verify Neofetch is working
- Run `sudo apt install rofi neovim`
- Install the Brave Browser
- Install Libreoffice from [FlatHub](https://flathub.org/home)
- Setup my password keeper and 2FA 
- Setup VS Code
  - Install Markdown for All, VIM, and Code Spell Checker
- Install Cloud Sync Script
- Copy over my custom .bashrc file
- Setup SuperKey+R to bring up `rofi -show run` and then set the theme
- Sync Bookmarks in Brave

My main machine will be the same list with some exceptions for the monitors.  Its also going to get Amateur Radio Software when I decide to migrate all of that from
Windows to Linux (Second Reason it Dual-Boots, first is Work).  

Now the reason I keep this D630 going and not trashing it is because, I can.  Its still a viable laptop that can at least do basic Web Browsing, Remote into devices,
work on Azure if needed, and even run VS Code to write this blog.  My Grandma uses her for just web browsing.  She doesn't do anything crazy and it's a great laptop.
They are also really easy to work on.  Parts for them are still available.  Really the only problem with mine is the Tab key.  Why spend money on something I can
keep working with a great operating system?  Shoot I was looking at replacements and I could get another laptop from the [MSU Resell](https://msusurplusstore.com/collections/laptops) or [Newegg](https://www.newegg.com/p/pl?Submit=ENE&N=100017489%204016&IsNodeId=1&SpeTabStoreType=97&name=Laptops%20/%20Notebooks).  I however have
a few projects I would rather fund.  I have a super expensive test coming up (hopefully soon, still rewriting my notes).  

Until then, 73's and take care.