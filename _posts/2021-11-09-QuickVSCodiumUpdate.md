---
type: post
title:  Quick update on using VSCodium
---

So I ran into an interesting issue using VSCodium.  Since the start I have had some odd issue with Code Spell Checker from Street Side Software.
It's great for when I write these blog posts and my CISSP notes.  The problem I was having was it would load an older version of it in
VSCodium.  This wasn't a problem as you only lost the ability to right-click on the work to open the suggestions.

Last week (for the 100th) time, I redid the operating system on my Dell D630 (which went from Mint XFCE, to Manjaro Mate, and back to Linux Mint (with Mate this time)) and
I realized, the spell checker was now on the latest build.  Fortunately when I do builds for customers and my personal projects I keep notes. 

What I had done differently was how I installed VSCodium.  For my desktop and other laptop, I had used the Snap store.  For this build, I had pulled the .deb from
VSCodium's web site.  Turns out the snap store is a few versions behind.  Swapping out to the latest build of VSCodium resolved my issue with 
Code Spell Checker.

This goes into something else I have been doing for the last week, I have been reviewing applications on the Snap Store and FlatHub.  Both are great if you can't
get a native install for your Linux distribution (like Arch if you don't trust the AUR). But some software is hit or miss on how updated it is.  Brave Browser has this issue.  They recommend using the 
native installer instead of their Snap version.  The inverse of this issue I have found is Emacs.  If you want the latest build, the Snap version is the way to go.  LibreOffice is the same way.  

So what I have learned from all this is:
1. Glad I am on a Debian based version of Linux because everyone supports it
2. AppImages might be better than Flatpak or Snap.  Those seem to support their own update mechanism
3. Always go for what is native to your Linux Distribution if you can
4. Always read the web site for the software you want to download and go by what they recommend.

I could probably solve some of this by going to a distribution of Linux that is more current with software packages.  But that would be at the cost of stability.  If given the choice between stability and being on the bleeding-edge, I'll take stability.  It is what my clients and users expect and it is what I like at home.

Either way, those are just my quick thoughts.  I like how I have VSCodium setup with the VIM and Code Spell Checker.  I have emulated the setup
on my work computer and it is just nice to not have to move your hands away from the keyboard to work on a file.  

Until then, take care and 73's.