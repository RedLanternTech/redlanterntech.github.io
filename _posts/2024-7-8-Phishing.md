---
layout: post
title: Phishing on the 4th of July.
---

Normally on the 4th of July, I would prefer to sit out in a boat or by the lake, trying my hand at fishing.

What do I do instead? Go over a recent attempt to attack a customer of mine via phishing.

It still kind of amazes me that phishing is still the primary way to attack an organization. But the reason (I think) it is so effective is because it just takes one email at the right moment with the right content to get someone to fall for it. Let's go over a recent situation I had.

I had a client waiting for an invoice from a vendor. This was to make payment for some services that were already rendered. It was towards the end of the day, and as they were wrapping up, the email finally came in with the subject "Invoice Number 38340943 - Payment Due". The client, who had been waiting for this email all day, quickly opened the PDF attached to the message, only to be presented with an image of a QR code. At this point, they realized they were under attack.

Fortunately, my client stopped and reached out to ask for assistance. There are others who would scan the QR code and be presented with a login for Microsoft 365, only to have their session taken over and their account compromised. It's relentless. Some attackers just want a jumping-off point to send out spam messages; others are looking for information they can use (Personally Identifiable Information, Passwords, Account Numbers, etc.). The point is, the attacks never end, and they will keep coming.

So what do I do? I treat all phishing attacks like this the same:

1. Isolate the machine.
2. End all Microsoft 365 sessions by locking the user out.
3. Examine the headers and look for any other messages that may have been sent to other users.
4. Block the domain or email server from future connections.
5. Execute the PDF in a sandbox environment.
6. Run a full virus scan on the compromised machine.

Another resource I had in my back pocket was my SOC team, whom I also notified of a possible breach. They immediately began their incident response procedures and also performed a secondary analysis on top of what I had already found. In these situations, you have to work with your team, no matter the timing or how small things may seem.

For those who wish to get more familiar with phishing incident response, TryHackMe has a great course on responding to phishing emails. In fact, their whole SOC 1 Learning Path is well worth it.

Until next time, 73's and take care everyone.

For Additional Information, check out

[TryHackMe's Phishing Module](https://tryhackme.com/module/phishing)

[Phishing IR Playbook](https://github.com/counteractive/incident-response-plan-template/blob/master/playbooks/playbook-phishing.md)

[MX Toolbox-The Literal Swiss Army Knife of Email Troubleshooting](https://mxtoolbox.com/)

[Google's E-Mail Header Analysis](https://toolbox.googleapps.com/apps/messageheader/analyzeheader)
