---
layout: post
title:  "Run multiple Dropbox instances on Linux"
date:   2015-07-08 14:35
categories: meta
---

# Run multiple Dropbox instances on Linux

Create two custom folders, one for file syncing (``~/dropbox-xc``), and one for the configuration files (``~/.dropbox-xc``).

Run the following in a terminal:

{% highlight bash %}

HOME=$HOME/.dropbox-xc /usr/bin/dropbox start -i

{% endhighlight %}

The setup window will appear and guide you through the configuration process. When it asks you for the Dropbox location, check the option “I want to choose where to put my Dropbox folder” and select the other folder that you have created.

## Run multiple dropbox accounts on startup

Open a text editor (gEdit for Ubuntu). Paste the following:

{% highlight bash %}

#!/bin/bash
HOME=$HOME/.dropbox-xc /usr/bin/dropbox start

{% endhighlight %}

Save the file as DropboxAltStarter.sh in your Home folder.

Make it executable:

{% highlight bash %}

chmod 755 ~/DropboxAltStarter.sh

{% endhighlight %}

Go to System -> Preferences -> Startup Applications. Click Add and include the following:

**Name:** 2nd instance of Dropbox
**Command:** /home/Username/DropboxAltStarter.sh

Click Ok.

[Source](http://maketecheasier.com/run-multiple-dropbox-accounts-in-mac-and-linux/2010/05/24)
