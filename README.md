Remailer-Server-Monitor
=======================

A server statistics monitor for remailer sysops.

This project consist of bash scripts that create a webpage consisting of information pertaining to the server as well as a sysop's remailer.

The web page is divided into sections:

Machine
Linux distribution number
Distributor ID: <distribution name>
Description: <distribution description>
Release: <number>
Codename: <name>
OpenSSL: <distribution number / date>
Up days, Users, Load average: 5min 15min 30min
Last login: <date, time, length>

Rogue Processes
<unrecognized running processes>

Free

Netstats

Mixmaster<br>
TOP data
MD5
Key+/-dates / days to expdt

Misc Stats
<mailq count>
<size of /var/log>

Mixmaster
<pool count>
<pool records processed today>
<mbox message count>

Remailer Statistics
<stats for your remailer from each pinger>

