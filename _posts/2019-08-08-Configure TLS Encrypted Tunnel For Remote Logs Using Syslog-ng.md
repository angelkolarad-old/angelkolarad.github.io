---
layout: post
title: Configure TLS Encrypted Tunnel For Remote Logs Using Syslog-ng
subtitle: Remote Logging over TLS 
bigimg: /img/configure-tls-encrypted-tunnel-for-remote-logs-using-syslog-ng.png
image: img/configure-tls-encrypted-tunnel-for-remote-logs-using-syslog-ng.png
tags: [Configure TLS Encrypted Tunnel,syslog-ng,syslog-ng tlstls,logging]
show-avatar: false
---

You might be a Sysadmin, developer, DBA or whatever, logs are like treasure boxes for anyone working in IT. And the best practice to keep logs in a central location together with local copy. Most of the logging programs have the ability to send logs to a remote logging server (as well as receive logs from remote machines); eg rsyslog, syslog-ng etc.

But, still there is a concern for sending server/application/database logs sending over tcp as plain text; yes indeed. But no need to worry as most of the logging programs will have simple mechanisms to implement TLS Tunnels for sending and receiving logs. In below demo, we will implement TLS tunnel to send logs from one machine (using syslog-ng) and receive the logs on another logging server (syslog-ng).

[See Full Article](https://www.techbeatly.com/2019/08/configure-tls-encrypted-tunnel-for-remote-logs-using-syslog-ng.html/)
