# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="911" height="738" alt="481471391-ece0be13-fcbb-4a9c-898e-a73a596893fe" src="https://github.com/user-attachments/assets/2a578527-fffe-4aad-b818-ecc653a2dd31" />


### Finding Hosting Company :
<img width="1617" height="847" alt="481471400-3419c66f-6e12-4fe7-9677-e5636dd9520c" src="https://github.com/user-attachments/assets/1bd83dcb-a355-4284-a6c4-cdfe148c4e24" />


### History of the website :
<img width="1919" height="922" alt="481471427-87be68bf-ab41-4d29-8661-c529d7ec62ef" src="https://github.com/user-attachments/assets/5573fa11-9518-4135-87fa-5be4c26dd8df" />

### ping command :
<img width="1920" height="1051" alt="kali linux  Running  - Oracle VirtualBox 08-09-2025 08_39_26" src="https://github.com/user-attachments/assets/a49e37e0-8843-48f0-85e3-43d250bf6a33" />


### whois :
<img width="1920" height="1051" alt="kali linux  Running  - Oracle VirtualBox 08-09-2025 08_41_51" src="https://github.com/user-attachments/assets/285bb852-e7b4-4f14-b48a-84f0a8ac411a" />


### netcat :
<img width="1920" height="1051" alt="kali linux  Running  - Oracle VirtualBox 08-09-2025 08_43_43" src="https://github.com/user-attachments/assets/a86b7244-8ec4-4197-a76f-fbbc9e2c9ea3" />

### nmap :
<img width="1920" height="1051" alt="kali linux  Running  - Oracle VirtualBox 08-09-2025 08_44_45" src="https://github.com/user-attachments/assets/d301d99d-de04-4bb1-b517-f198c0ee561f" />


### whatweb :
<img width="1920" height="1051" alt="kali linux  Running  - Oracle VirtualBox 08-09-2025 08_46_20" src="https://github.com/user-attachments/assets/9a99f42e-c199-4668-8e45-337eca28beea" />


### httprint :
<img width="630" height="208" alt="481471617-b671f174-01c3-4154-8801-e1b7f21dae74" src="https://github.com/user-attachments/assets/d604bbc6-f7a4-49bf-be01-5a24160279bf" />


### TCP traceroute :
<img width="1920" height="1051" alt="kali linux  Running  - Oracle VirtualBox 08-09-2025 08_53_35" src="https://github.com/user-attachments/assets/43995f42-cbf0-40a5-94b8-7d23beb4ed3e" />


### UDP traceroute :
<img width="1920" height="1051" alt="kali linux  Running  - Oracle VirtualBox 08-09-2025 08_55_02" src="https://github.com/user-attachments/assets/dbfd711c-e43a-4772-97c2-359c94e68764" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
