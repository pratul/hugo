+++
title = "Fixing the irritating Apache 2 warning"
date = 2008-10-10
+++

For all those who have been using Apache 2 on a localhost on a Linux distro, there's this weird (and very irritating) warning that one gets whenever the Apache server is started or stopped. 

`Could not reliably determine the server's fully qualified domain name, using 127.0.1.1 for ServerName`

The address you get here might vary, but the error persists. Here's how to fix it:

- Open `/etc/apache2/apache2.conf` in your favourite text editor.
- Find the line that says `ServerRoot "/etc/apache2"`
- Add another line below it `ServerName "localhost"`
- Restart Apache server.
- Heave a sigh of relief from that darn irritant.

NOTE: This is valid only if you are running Apache on a localhost. If you're running it for a different domain, you'll probably need to replace localhost with your host name.