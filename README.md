# sinksmtp 0.2.0

* Repo: github.com/pepa65/sinksmtp
* License: GPLv3
* After: github.com/Siebenmann/sinksmtp
* More extensive documentation: DOC.md

Sinksmtp is a SMTP server that talks SMTP and potentially captures incoming
email, but doesn't do anything with any email it captures except log it to
disk and perhaps save it, where it's up to you to monitor it and pull it out.
It supports TLS if configured and a number of ways to filter and select a
response in the interactions, logging and saving.

Sinksmtp uses the github.com/pepa65/smtpd Go package to handle the low level
details of SMTP serving (it used to be part of it as an example).
