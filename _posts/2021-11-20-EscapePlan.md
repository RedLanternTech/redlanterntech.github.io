---
type:  post
title:  What is your escape plan
---

Something my mentors drilled into me (as they have a background in programming and software sales) is to make sure you have a way to get out of a bad situation when doing an implementation.  My goal when doing implementations is to make sure they are efficient, as non-disruptive to major operations as possible, and do not cause extended downtime.  

Downtime cost money.  Downtime causes headaches. 

I bring this up because I had an interesting situation this week.  I had a third party vendor put in a new fiber switch that was fully tested by them and us, confirmed to be working with no issues.  Everyone signed off and said it was good to go.  Scheduled the actual cut-over to this switch. I arrived onsite and went though my checklist to get everything configured and cut-over.  I was able to make the cut-over with no issues.  I start going though my testing, everything is working the way it should. 5 minutes later the device dies.  Vendor will take a few hours to get out onsite and work on the issue.  

In this situation, I couldn't leave the client down for 3+ hours while we wait for a vendor.  

So what did I do.

First was planning.  The new piece of hardware was a new fiber switch.  The old one wasn't going away until we confirmed everything was working correctly.  So I had the old one to fall back on in case of a problem.

Second was configuration.  I had a spare port in my Firewall that I setup with the new static IP addresses.  The old one could stay in place and give me a quick way back.  I also didn't make major changes to my configuration so even if I did have to cut back, it would be a few mouse clicks.

Third was having a backup.  My firewalls were backed up well before I started working.  That way if my few mouse clicks didn't work, I could just go back to being fresh.

Fourth was having proper documentation. I had a network layout and knew every point between the fiber switch and the firewalls.  Having the proper documentation is invaluable in getting out of situations that could cause downtime.   

If I had to summarize my main point, it is know where you are going and know how to get back in case everything fails.  

Until then, 73's.