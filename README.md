# codepath-week9

Instructions
Create a repository on Github with a README.md that includes a brief writeup about your experiment. Include the following details:

    Which Honeypot(s) you deployed

I deployed three honeypots total, Dionaea, Wordpot, and Suricata.

![](https://github.com/ayushg97/codepath-week9/blob/master/sensors.PNG)

    Any issues you encountered

The main issue I has was during the setup of the mhn-admin. One of the install scripts linked to an expired github repo, so it had to be changed to another one which had the proper files. Once that was done, the rest of the setup was simple.

    A summary of the data collected: number of attacks, number of malware samples, etc.

Total of 243 attacks. 227 for dionaea, 0 for wordpot, and 14 for suricata. It makes sense that wordpot didnt get any attacks since it is not as likely a target for generic attacks that happen more frequently. There were not malware samples collected over the time period. 

    Any unresolved questions raised by the data collected

There were no unresolved questions raised by the data. The only anomaly was wordpot.