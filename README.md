# Week9
Total time spent: **5** hours

For this project, I created three VirtualMachines to create HoneyPots and intercept attacks. I used the Google Cloud Platform to create these instances on the Google Compute Engine running Ubuntu 14.04 Trusty. The three instances created were, ubuntu-trusty-1 which was the admin VM, mhn-honeypot-1 which was the Dionaea honeypot, and mhn-honeypot-2 which was the Snort honeypot.

## Issues Encountered

I did not encounter any issues for this experiment. My TPM sent us alternative links for instructions that were helpful and easy to follow for setting up the google cloud virtual machines.

## Summary of Data

I deployed two honeypots and kept them on for about 4 hours from 2:00PM to 6:00PM EST. Although the second honeypot was deployed for a little less time because it was created about half an hour later. From the AdminVM dashboard, we could see that there were:

__Total number of attacks in the last 24 hours: 604
      - Dionaea honeypot intercepted around 480 attacks
      - Snort honeypot intercepted around 124 attacks
  
__Top 5 attacker IPs were mainly from France and America

__Top 5 attack ports were: 8088 (49 attacks)
                           5060 (24 attacks)
                           445 (18 attacks)
                           81 (15 attacks)
                           23 (14 attacks)


__TOP 5 Attacks Signatures:
ET DROP Dshield Block Listed Source group 1 (89 times)
ET CINS Active Threat Intelligence Poor Reputation IP TCP group 7 (6 times)
ET SCAN Sipvicious User-Agent Detected (friendly-scanner) (4 times)
ET CINS Active Threat Intelligence Poor Reputation IP TCP group 41 (3 times)
ET CINS Active Threat Intelligence Poor Reputation IP TCP group 67 (3 times)

The raw data can be found in the session.json file uploaded 

## Other Notes/Questions

None
