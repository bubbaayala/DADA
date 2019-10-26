## Week 1 Write-Up
Week 1 was a great introduction into malware with lectures provided by the Director of threat intelligence at McAfee Labs whom of which discussed a wide variety of topics while including very relevant information. After viewing all lecture material I was thoroughly intrigued by the material provided covering malware which I would like to discuss in more detail. Some of the topics discussed pertained to malwares existence, Careers dealing with anti-malware, security terminology, Advanced Persistent Threats (APT's), and APT's tactics/strategies.

### Malware's Existence
One of the main questions asked in the lecture was 'why does malware exist?'. During discussion a number of reasons were discussed such as political gain, financial gain, reconnaissance on an individual/group, denial of services, and destroying systems due to having the capability. From the discussion we can see like a number of harmful aspects to industries malware itself exists due to motives from other individuals. I always found motives as proof that no matter what industry you are in if there are tools to build/improve then they can be abused to destroy/harm others which for this class is software being utilized for malware. 

### Careers/Roles in Developing Anti-Malware
Careers in developing Anti-Malware began arising in the early 90's with very few positions being offered at first and mostly pertained to working for a computer anti-virus research organization. Since then the anti-malware scene has significantly increased with a huge rise in career opportunities and research due to software becoming such an integral part in society. Software security and malware research has grown into a massive billion dollar aspect of the computer indsutry. While positions and roles may very in the development/research of anti-malware they have similar goals they wish to obtain. Those goals consist of finding solutions to safe computing, identifying threats, and using best practices to handle threats. Particular tasks discussed by our lecturer were how members of his team had to not only identify threats but also develop countermeasures for each unique threat while using multiple perspectives on the situation to get a good grasp on what they are dealing with as well as how it should be dealt with. 

### Malware/Security Terminology
- White(Clean): A clean file or sample of code that is harmless or unharmed.
- Black(Dirty): A 'dirty' file or sample of code that is harmful or has been harmed by malware.
- Sample: An identified piece or section of code that is malware.
- Goat: A sacrificial machine or system developed to analyze the behaviors of malware. 
- Rootkit: A set of software tools use to gain unauthorized access to a computer system. 
- Honeypot: A computer security mechanism set to detect, deflect, or countermeasure attempts of malware. 
- Bootkit: A malicious infection which targets the master boot record located on the physical motherboard of a computer.
- Spyware: Malware that takes personal identification information from a system without the user or system's knowledge. 
- Ransomeware: Malware that gains access to sensitive files on another host then encrypts them while forcing a ransome value to unencrypt the sensitive files. 
- CVE: Acronym for Common Vulnerabilities and Exposures which is used as a form of reference to vulnerabilities in systems that have been exposed to the public. 

### Malware Naming Scheme
One of the topics I found interesting was how malware is named/identified. Being unaware of the procedure I was impressed by how specific the naming scheme was in order to create a unique name for each threat found (should be mentioned that this is not the only naming scheme developed but is what is used by McAfee). 

The naming scheme is as follows: 
     Type: + Platform/ + Family + .Varient + !Information
     Example Provided: Trojan:Win32/Reveton.T!Ink
     
### Advanced Persistent Threats (APT's) 
In the final lecture for this week the lecturer introduced and discussed advanced persistent threats (term originated from 2006 by the U.S. Air Force). In essence, an APT is a computer network attack from a person/group to gain unauthorized access to a network while remaining undetected for an extensive amount of time. Each word in the term also has its own definition pertaining to the threat and follows as such:

##### APT Acronym Breakdown
- Advanced: Operators behind the threat have a wide range of knowledge on the topic with the intelligence to develop unique attacks to gather necessary information.
- Persistent: Operators of the attack give priority to a specific task/attack rather than taking the opportunity for quick or small gains therefore implying that external entities are possibly at play. 
- Threat: This model is a threat as they have the capability and intetion of performing some type of harm to others. 

APT's also have similar aspects to most malware in terms of attackers/operators, motives, targets, and end goals. Advanced persistent threats, however, do have a model known as the APT-Kill-Chain (structure of APT attack) that operators follow in order to develop an APT attack. The steps of an APT-Kill-Chain are as follows.

##### APT-Kill-Chain Attack Structure/Strategy
1. Reconnaissance: operators run scanners to identify open ports, anti-virus software, machine informaiton, file meta data, and so on.
2. Weaponization: operators begin building a payload based on an attack vector that will be effective on the machine/system. 
3. Delivery: form of implementation for how the payload will be put into the desired/target system. 
4. Exploitation: execution of the payload after it has been delivered to the target system/machine.
5. Installation: following the execution the payload will be installed onto the target system/machine. 
6. Command and Control: The adversary now has the capabilities of executing the desired commands to achieve the end goals set for their attack.
7. Actions and Objectives: phase where the data exfiltration begins over the network and where the operators retrieve the desired information. 

### Week 1 Conclusions
Week 1 was a great introduction to malware with lectures provided by an individual within the industry who provided relevant and intriguing information to the students. The homework was a strong complement to the lecture materials as we were able to utilize malware analysis tools to a known malware attack which we were able to analyze with the tools provided in the dedicated virtual machines. As a result of the homework we were able to thoroughly analyze a form of malware and just how complex an attack can become and how hard they are to identify without the proper knowledge of malware or application of anti-virus software/tools. Overall, week 1 as stated was a smooth, effective introdction into malware and a great opportunity to play with malware analysis tools to increase our knowledge on how to properly dissect an infected system/machine. 


