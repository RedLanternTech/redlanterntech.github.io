---
layout: post
title: Small, Big, and Future Projects 
---
## Introduction
In my continuous pursuit of knowledge and professional growth, I have been actively engaged in various cybersecurity endeavors over the past few weeks. In this article, I will provide a brief overview of my experiences and highlight the key aspects of each undertaking.

## Azure AZ-305
Since April, I have been diligently preparing for the Azure AZ-305 exam. While it is less technical than the AZ-104, a solid understanding of the appropriate products and their application is still crucial. Notably, there are three effective methods for migrating MS-SQL to Azure: deploying it on a VM, utilizing an Azure SQL Instance, or leveraging an Azure Elastic SQL Instance. To enhance my memory retention, I have shifted from typing notes to writing them by hand, a technique that has proven to be more effective for me. My goal is to complete the exam by the end of Quarter 2. To achieve this, I have been utilizing MeasureUP, along with Microsoft Learn and Udemy courses, to thoroughly prepare.

## Farewell to OpenSUSE Tumbleweed
Having used OpenSUSE Tumbleweed on my laptop since January, I must admit that it is undoubtedly one of the finest rolling distributions available. It offers a superior out-of-the-box experience and remarkable stability, surpassing even Arch Linux. However, due to the significant number of updates that accumulated while my laptop remained idle for extended periods, I decided to transition away from OpenSUSE. Although Zypper, the package manager, is reliable, its update process proved to be slow in comparison. In early April, a complete recompilation of the install base resulted in the reinstallation of every single package. Consequently, I made the switch back to an Arch-based distribution and am currently utilizing EndeavourOS. While I also explored other options such as NixOS, Fedora, BlendOS, and VanillaOS, I have yet to find an immutable distribution that perfectly suits my needs for a desktop environment.

## Penetration Testing Lab
Approximately six months ago, I acquired a Dell PowerEdge Rackmount Server, which has remained idle in my basement due to the lack of hard drives. Instead of deploying Nextcloud, as initially intended, I have decided to repurpose the server as a Penetration Testing lab. This will provide me with an ideal playground to refine my skills in network assessments and acquire new ones (perhaps even pursuing PenTestPlus in the future). Consequently, I plan to install NixOS with KVM on the server to fulfill this purpose effectively.

## Nextcloud
In my previous article, I mentioned my migration to Nextcloud AIO. To ensure a smooth transition, I created a comprehensive checklist to guide me throughout the process, mitigating the risk of overlooking critical elements (checklist available in the link below). Personally, I find checklists invaluable for projects of all sizes, as they help me maintain focus and minimize the chances of missing crucial steps. Configuring Nextcloud AIO within a closed environment posed a unique challenge, particularly concerning SSL implementation without internet access. Fortunately, I was able to leverage Tailscale's SSL Proxy feature to overcome this obstacle successfully. Nextcloud AIO has proven to be an exceptional product, surpassing its predecessor, NextCloudPi, in various aspects. With features such as online editing, improved performance, robust backup solutions, and seamless self-updates, it has significantly enhanced my user experience. The integration with KDE is seamless, mobile apps function more effectively, and interruptions have been greatly reduced.

## OpenSense
Now, let's delve into an exciting project: the construction of my OpenSense box. While I had contemplated using PFSense for some time, my brother-in-law persuaded me to explore OpenSense instead. The availability of robust hardware plays a significant role when dealing with a network that supports numerous devices. What sets OpenSense apart is its exceptional visibility into network traffic at the gateway from a security standpoint. While PiHole provided some visibility, OpenSense takes it to another level. Moreover, OpenSense incorporates built-in IDS/IPS capabilities, and by adding ZenArmor (even on the free tier), I have transformed it into an impressive security apparatus. Throughout the summer, I plan to further expand my network's security posture, and I look forward to sharing my experiences and insights with you here.

With that, I extend my warmest wishes for a fruitful June. Take care, and 73's.
