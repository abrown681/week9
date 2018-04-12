## Which Honeypot(s) you deployed ##
I deployed the Ubuntu - Dionaea honneypot using the MHN VM on Google's Google Cloud Platform (GCP).

## Any issues you encountered ##
Most of the issues I encountered were related to VM installation. The instructions to setup GCP were a bit vague in the sense that I wasn't quite sure how to create a new project or if I even needed to make a new project. I also wasn't sure about the difference between a project and configuration type. 

Aside from initializing the project, I also ran into firewall issues. I could not access the external ip until I went into the VM settings on the GCP console and set the firewall to allow HTTP(S) traffic. For some reason, it is initialized to NOT allow traffic. 

## A summary of the data collected: number of attacks, number of malware samples, etc. ##
At the time of writing this report, the honeypot VM has been running for about 45 minutes. It has already intercepted 70 different attacks from a variety of foreign countries!

## Any unresolved questions raised by the data collected ##
