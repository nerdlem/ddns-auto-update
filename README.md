# ddns-auto-update

This is a very simple shell script I use to keep a suitable DNS entry pointing to hosts with dynamic IP addresses. I wanted a mechanism to do this without having to resort to unnecessarily complex dynamic update schemes or third party services.

Simply place the accompanying script in `/usr/local/bin` and tweak the enclosed crontab file.

This scripts depends on the following commands being available:

* awk
* host
* ip
* jq
* nsupdate
* ping
