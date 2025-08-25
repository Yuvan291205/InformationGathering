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
<img width="1917" height="1139" alt="image" src="https://github.com/user-attachments/assets/93750f78-abfc-4029-9597-6a04a2fa8549" />

### Finding Hosting Company :
<img width="1914" height="1136" alt="image" src="https://github.com/user-attachments/assets/a30ef00c-8e68-4302-8740-e1568985810c" />

### History of the website :
<img width="1919" height="1141" alt="image" src="https://github.com/user-attachments/assets/9d142d5a-d3f3-48dc-b5b6-7795bdd787a7" />


### ping command :
<img width="1280" height="704" alt="image" src="https://github.com/user-attachments/assets/2632705e-fb14-4874-a2be-806ffe1f6c82" />


### netcat :
<img width="1280" height="704" alt="image" src="https://github.com/user-attachments/assets/f7550c86-ed62-44e7-986d-ed5348719756" />

### nmap :
<img width="1280" height="704" alt="image" src="https://github.com/user-attachments/assets/2e288817-3585-43b3-8ca5-5636a9c4efbc" />

### whatweb :
<img width="1280" height="704" alt="image" src="https://github.com/user-attachments/assets/20436b39-9c6f-4d3e-8c0f-4194a62cc900" />

### httprint :
<img width="1280" height="704" alt="image" src="https://github.com/user-attachments/assets/c506f75d-5b16-4bc7-b171-b84da0837d85" />

### TCP  and UDP traceroute :
<img width="1920" height="1057" alt="image" src="https://github.com/user-attachments/assets/4af6ff17-ed2f-4b99-a3c2-347b0d15369b" />

## RESULT:
The information gathering techniques tools/procedure were identified successfully


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
