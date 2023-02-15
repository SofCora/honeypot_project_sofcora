# honeypot_project_sofcora
codepath intermediate cyber security fall 2022
Honeypot Assignment
Time spent: 8 hours spent in total

Objective: Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

MHN-Admin Deployment (Required)
Summary: How did you deploy it? Did you use GCP, AWS, Azure, Vagrant, VirtualBox, etc.? Using gcloud I did an mhn-admin virtual machine and downloaded the admin application from pwnlandia on github i then configurred the superadmin email and password

Dionaea Honeypot Deployment (Required)
Summary: Briefly in your own words, what does dionaea do? its the honeypot application software script that is connected to the mhn admin terminal. it allows for the honeypot to be attacked using a rasberry pi.

Database Backup (Required)
Summary: What is the RDBMS that MHN-Admin uses? What information does the exported JSON file record?

Session.json file exports the id, protocol, ipfeed, timestamp, source ip, honeypot type, source port, destination port Be sure to upload session.json directly to this GitHub repo/branch in order to get full credit.

Notes
Describe any challenges encountered while doing the assignment. the codepath course portal writeup is different from the hackmd and both are different than the baruch video walkthrough. There were also some challenges with my nmap scan running but nothing showing up on the map itself even though the attacks were showing on the attack page on my browser.
