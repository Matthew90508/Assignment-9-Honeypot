# Assignment 9-Honeypot
Codepath week 9

Create a repository on Github with a README.md that includes a brief writeup about your experiment. Include the following details:

Which Honeypot(s) you deployed? 
-Dionaea - mhn-honeypot-1

Any issues you encountered?
-Initially I was recieving an error during the first firewall step along the lines of "precondition not met, billing not enabled." I eventually figured out the problem and created a billing account and linked it to the appropriate project. Later on when you first had to ssh into the external ip, it kept failing to connect. Awhile later, I learned http wasn't enabled and after enabling the protocol it worked just fine.

A summary of the data collected?
-A total of 1185 attacks were collected with no malware samples. Several different protocols such as pcap and smbd can be seen in use among a variety of ports. Info can be seen in the session.json.

Any unresolved questions raised by the data collected?
-I expected to see lots of countries that could be considered our enemy such as Russia, but saw a suprisingly large amount of USA attacks.
