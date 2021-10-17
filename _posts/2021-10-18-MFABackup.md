---
layout: post
title: Always have a backup for your Password Keepers and 2FA
---

So here is a fun scenario.  It's 6:30am, you want to get to work quickly as you have a meeting at 7:30. 
You have your coffee in your big green Stanley cup, you load up the car and drive 30 minutes into work.
Of course there is never-ending construction and you are a little late getting in. 
Sitting down at your desk you take out your work phone and use the 2fa code to get logged in.  Then you reach for your
personal phone to play some [light tunes](https://youtu.be/_ITiwPMUzho) and find it is not in your pocket like you thought.

The phone that has your own personal 2FA. 

The phone that has your link to your password database.

The phone that you pray is not in the driveway.

On a rainy day.

Crap.

Now I did exaggerate a little on that story as it happened to me last Wednesday.  I wasn't in a total panic as I knew the laptop I had with me
was authorized to get into my 2FA and Password Keeper to the device. Also, I know I have my backup codes locked safe away in case something happened. As enterprise-level security becomes more prevalent in our personal lives,
we need to make sure we take precautions to not lock ourselves out of our accounts.  

Think about everything that now requires or can accept Two-Factor Authentication.  Online Password keepers, Email Accounts, Web Hosting, GitHub, the 
list goes on and on.  Sure some of those are easy (relatively speaking) to get into if you lose the one device that had your 2FA token but
what about the stuff that isn't.  Encrypted Email accounts like Tutanota and ProtonMail, if you lose your 2FA (or even your password) thats it, 
you are not getting into your data or your email.  Also think of the time it would take to recover other accounts.  A Web Domain will probably require
you to fax over a notarized letter with a photo ID before they would even talk to you. 

This echo's one of the many mantra's of IT "Always have a backup". 

When setting up new security practices like 2FA and Password Databases,
always, always have at least some backup method to access your data.  So what should someone do?

# What to do?

1. Backup your data to offline storage.  Portable hard drive in a safe/fireproof box/somewhere with your important data.  Encrypt it with a password you can remember or look up.  If you have a password database, back it up there as well.  If you can get it offsite and multiple copies, even better.  
2. Backup your 2FA Tokens.  Aegis or Authy both allow you to backup your 2FA keys.  Authy gives you the ability sync tokens across devices.  Aegis lets you back them up.  Both are good options
3. Make sure you have a way to get to your password database.  KeepassXC is a great project.  The database can be synced with OneDrive or Dropbox.  If you are concerned about it being stolen, multiple thumb drives work.  For the online options, make sure you have a 2FA token on it (that you backed up) and authorize a few devices so you can at least get into it with your master password. Dashlane and Bitwarden are the two I see as being popular and secure. Given a choice, I'd take Bitwarden.  
4. Print off the recovery codes for your 2FA.  Seriously, print them off and put them in a fireproof safe.  Offsite and secure.  
5. Check everything periodically.  Once a quarter is the standard.  Make sure all your backups work.  Run an exercise on if you lose your phone/tablet/the place you keep your 2FA and Passwords. 

Hopefully some of those tips above save someone some grief in their personal lives.   