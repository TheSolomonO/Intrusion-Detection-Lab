# Intrusion-Detection-Lab

## Objective

The Snort project aimed to monitor and detect any suspicious network traffic on a home network. The primary focus was to analyze network data for potential threats and generate alerts in response to abnormal patterns. This hands-on experience was designed to deepen understanding of intrusion detection, network security, and threat analysis.

### Skills Learned

- Advanced understanding of Snort as an Intrusion Detection System (IDS) and its practical application in network monitoring.
- Proficiency in analyzing and interpreting network traffic for suspicious activity.
- Ability to configure Snort rules and recognize malicious signatures and patterns.
- Enhanced knowledge of network protocols, packet analysis, and security threats.
- Development of critical thinking and problem-solving skills in detecting and mitigating network vulnerabilities.

### Tools Used

- Snort Intrusion Detection System (IDS) for monitoring and detecting suspicious network traffic.
- Nmap for network scanning and generating traffic to test Snort detection capabilities.
- Custom Snort rule configuration for identifying and responding to specific network behaviors and threats.

## Steps

-  Here I installed SNORT onto my Ubuntu machine. 
![1](https://github.com/user-attachments/assets/15a8ab67-4354-4a12-a7d1-413ec08b53d8)

- I then specified my Local Area Network Address and used the /32 CDIR notation.
![2](https://github.com/user-attachments/assets/8a45134e-5908-4f6e-a01b-92f34a64de3b)

- Next, I opened the snort configuration file to specify my home net. 
![3](https://github.com/user-attachments/assets/cb8d78f4-ec24-4c01-b6b4-a1c567b7c74c)

- Here I launched the snort.alert.fast command to view the traffic on my network.
![4](https://github.com/user-attachments/assets/e898adee-a988-4062-8097-5b9403962d73)

-Finally I ran an Nmap scan on a different machine and Snort ended up detecting the scan. Here are the results. 
![5](https://github.com/user-attachments/assets/1e8255b1-71fc-44c6-9496-9480d86a4652)

*Ref 1: Network Diagram*
