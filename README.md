# Networking-Fundamentals

In my role as a network security analyst at RockStar Corporation, I was tasked with conducting a network vulnerability assessment for their newly established office in Hollywood, California. The assignment involved several phases, and I successfully completed the tasks as outlined below:

### Phase 1: "I'd like to Teach the World to ping"
I ran ping commands from my local machine to determine the IPs for the Hollywood office. Using the provided list of network assets, I executed the ping <IP Address> command. I recorded the relevant information, including the ping commands used, a summary of the results, and identified the OSI layer(s) involved.

### Phase 2: "Some SYN for Nothin'"
Building on the findings from Phase 1, I conducted a SYN scan against the IP(s) accepting connections using Nmap. The SYN scan revealed open ports on the RockStar Corp server, and I documented this information in the submission file. The OSI layer(s) associated with SYN scans were also identified.

### Phase 3: "I Feel a DNS Change Comin' On"
Utilizing the information gathered from Phase 2, I attempted to access the servers accepting connections using the default credentials provided by RockStar Corp (Username: jimi, Password: hendrix). Additionally, I investigated an issue with accessing rollingstone.com from the Hollywood office. After successful SSH access, I identified and recorded the modified configuration file affecting the website access. Using nslookup, I determined the real domain associated with the IP address. All relevant findings were documented in the submission file.

### Phase 4: "ShARP Dressed Man"
Within the RockStar server accessed in Phase 3, I located a note left by the hacker indicating the storage location of packet captures. I used Wireshark to analyze the provided PCAP file, identifying and recording suspicious activity such as OSI layers, protocols, IP addresses, and MAC addresses. This information was included in the submission file.

I successfully completed the network vulnerability assessment, providing detailed documentation of each phase, findings, network vulnerabilities, and mitigation strategies as required by RockStar Corp.
