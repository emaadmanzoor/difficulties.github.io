---
layout: post
title: 'Runaway Skype'
categories: [technology]
tags: [skype]
---
I've noticed that my copy of Skype for Mac has had runaway CPU usage recently. After a little bit of digging, I ran across [this thread][1] on the Skype support forum that provided a temporary workaround.

   [1]: http://community.skype.com/t5/Mac/Skype-takes-100-CPU-mac-osx-Lion/td-p/39994/page/2

Apparently, Skype breaks when it shows a large number of Contacts. 

To keep the app from eating your CPU, you can create an empty contact list and select it. My CPU usage went from 89% (with Skype at idle, not on a call) to less than 1% immediately after clicking the empty list.

Unfortunately, the Skype for Mac interface is highly non-intuitive when it comes to creating new lists. To help, here's a brief walkthrough:

{% include image.html title="Online List" file="skype-1.jpg" %}

First select your "Online" list if possible. This should cut the number of visible users down and give your CPU and fan a little breathing room. If none of your friends are online you can do this from any user page that shows your contacts.

In the Skype user table, the far right column should be "Lists".

> **NOTE:** If your Skype window isn't wide enough, you'll never see the lists column. 

{% include image.html title="Add to List..." file="skype-2.jpg" %}

Right click the "--" in the List column for one of your contacts. Select "Add to List…"

{% include image.html title="Create List" file="skype-3.jpg" %}

A new tab will appear with a link that says "Create List". Click on the link and give your soon-to-be-empty list a name. Mine is called "Nobody" (sorry Mark).

You're almost done. In your toolbar you should now have a new list with only one user. Click it.

In my testing a single user list was enough to keep the CPU from freaking out. You can stop here, but I wanted a truly empty list, since I don't really trust the Skype app at idle anymore. 

The only way I've found to remove someone from a list is to (counter-intuitively) right-click and select "Add to List…" again. 

{% include image.html title="Nobody" file="skype-4.jpg" %}

Uncheck the box (See, Mark? It was all for science.) and you're left with a truly empty list. 

Your CPU, fans, and possibly friends will thank you.
