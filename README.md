# SNORT-IDS-Project

## Intrusion Detection System using open-source SNORT

## Description

Configured an intrusion detection system (IDS) using SNORT to monitor network traffic and detect malicious events/policy violations.

## Software used

SNORT, SNORPY, Wireshark

### Resources used for this project:

- Blue Team Hacking | Intrusion Detection with Snort
- Immersive Labs – SNORT Lab

## Steps

Step 1:
Used virtual box to run a Linux ubuntu VM to install SNORT

![image](https://github.com/brayden031/SNORT-IDS-Project/assets/99925439/31b843bd-1904-48fd-857a-eeab901ea6cb)
<br>
<br>
<br>
Step 2:
Configured snort config file to check traffic was actively passing through, after that turned off all preinstalled snort default/community rules.
<br>
<br>
<br>
Step 3:
Navigated to the “snort.rules” file and created the first rule.
This rule is used to create an alert based on any ICMP packets received from any source ip/port to the destination IP through any port. 

![image](https://github.com/brayden031/SNORT-IDS-Project/assets/99925439/154b08c6-7088-43d0-9778-243a76aed147)
<br>
<br>
<br>
Step 4:
Running snort to test that the config and first rule added runs successfully

![image](https://github.com/brayden031/SNORT-IDS-Project/assets/99925439/6a67d307-76f0-4d96-b4f2-efc5a6aa09fe)
<br>
<br>
<br>
Step 5:
Pinged the VM from another device to test the Snort alert detected the ICMP packets and successfully displayed the alert

![image](https://github.com/brayden031/SNORT-IDS-Project/assets/99925439/0e8c7962-20df-4ce4-8475-9ecb5af0496a)
![image](https://github.com/brayden031/SNORT-IDS-Project/assets/99925439/260aa823-b03e-4a56-ba2d-6d9084ba202b)
<br>
<br>
<br>
Step 6: 
Added another new rule. Alerts when TCP from a source ip/port comes to the destination ip on port 22 with the triggered message “SSH authentication attempt”
![image](https://github.com/brayden031/SNORT-IDS-Project/assets/99925439/1f3c019b-5ffe-4ab1-9714-d7c58df3e0f1)
![image](https://github.com/brayden031/SNORT-IDS-Project/assets/99925439/0e266e1c-4f07-477c-86dc-aa7ad0b8bc94)
![image](https://github.com/brayden031/SNORT-IDS-Project/assets/99925439/796667ef-36c3-42fb-a875-f9c0ed99f894)
<br>
<br>
<br>
Step 7:
Examined community created rules to gain a greater understanding of SNORTS capabilities.
<br>
<br>
<br>
Step 8: 
Investigated the log files produce from the SNORT alerts using wireshark to ensure the packets had been accurately captured.
![image](https://github.com/brayden031/SNORT-IDS-Project/assets/99925439/5e598246-35d6-40e8-abe0-086632db76ac)
![image](https://github.com/brayden031/SNORT-IDS-Project/assets/99925439/82b31bf8-a23c-4da2-925b-583bba4faa36)
<br>
<br>
<br>
Step 9:
Worked through the snort pathway on immersive labs to gain a greater hands-on experience with different rules and scenario-based labs.
<br>
<br>
<br>
Step 10:
Successfully completed all SNORT labs and earned the immersive labs badge.
![image](https://github.com/brayden031/SNORT-IDS-Project/assets/99925439/96f4a8c0-aa28-49d6-906f-8a43b03d58b2)



