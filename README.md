# hbbts
TimeShift for CableTV based by HbbTV


1. apt-get install apache2 php5 libapache2-mod-php5 screen sudo
2. unpacked files HBBTS-project in www-directory
3. php.ini: enable short_tags option
4. apache2.conf: enable mod_rewrite
5. add `www-data ALL=(ALL) NOPASSWD: /usr/bin/screen` in the file `/etc/sudoers` and reboot service `sudo`
6. edit file `/src/channels.db` and put your milticast addresses
7. add on the broadcasted TV channels in the Astra_5.62 the addresses of the Hbbtv resources

