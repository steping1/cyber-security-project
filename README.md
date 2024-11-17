# cyber-security-project
https://github.com/user-attachments/files/17791922/Midterm-Project.odt

[Midterm-Project.odt](https://github.com/user-attachments/files/17791922/Midterm-Project.odt)

# -----------------

Chapter 1: Dataset Selection
1. Overview of the Dataset
Dataset Name: Edge-IIoTset
Source: Edge-IIoTset dataset
Purpose:
Edge-IIoTset is designed to analyze various cyber threats that arise in IoT and IIoT applications.
Significance for Cybersecurity:
The dataset provides realistic data for investigating vulnerabilities in IoT/IIoT systems and detecting cyberattacks using machine learning techniques. It contributes to cybersecurity research in areas such as attack detection, anomaly analysis, and classification of attacks.

1.2 Features of the Dataset
The Edge-IIoTset dataset includes various network features and sensor data. Some of the prominent features are:
•	Timestamp: Indicates the time when the data was collected, providing date and time information.
•	Source IP and Destination IP: The source IP refers to the IP address of the device initiating the traffic, while the destination IP represents the IP address of the receiving device.
•	Protocol Type: Defines the type of protocol used in the connection (e.g., TCP, UDP).
•	Connection Duration: Shows the duration of the network connection.
•	Byte Count: Specifies the amount of data sent and received.
Each feature plays a critical role in attack detection and data analysis. Examining these features in detail helps to better understand potential anomalies and threats in network traffic.

1.3 Analysis of Each Feature
1.	Timestamp:
The timestamp is critical for analyzing the timing of attacks and identifying specific attack patterns. For example, traffic anomalies occurring during specific time periods can be detected. In DDoS (Distributed Denial of Service) attacks, it is possible to track high traffic targeting the same destination over a certain period through timestamps. Moreover, analyzing the times when attacks are concentrated can help develop strategies to enhance security protocols during these periods.
2.	Source IP and Destination IP:
IP addresses play an important role in identifying the source and target of specific attacks. For instance, analyzing the source IP addresses of requests targeting the same destination from multiple sources can be crucial for detecting botnet or DDoS attacks. Similarly, examining destination IP addresses can help identify attacks targeting sensitive systems in advance, enabling appropriate security measures.
3.	Protocol Type:
The protocol type is significant for detecting certain types of attacks. Different protocols may have different vulnerabilities. For instance, SYN flood attacks are common with the TCP protocol, while UDP is vulnerable to UDP flood attacks as it is a connectionless protocol. By analyzing protocol type information, it is possible to determine the type of attacks and implement security measures at the protocol level.
4.	Connection Duration:
Connection duration is an important factor in identifying attack types. While normal network connections occur within a certain time range, attacks such as DDoS under heavy traffic may have unusually short or long durations. Connections that are abnormally long often aim to conduct persistent attacks on the system. Therefore, very short or long connection durations are considered suspicious and may require further analysis.
5.	Byte Count:
The byte count is particularly useful for analyzing attacks such as data breaches and DDoS. Abnormally high or low amounts of data may indicate a breach or denial-of-service attack. For example, observing an unexpectedly large byte count during a connection could indicate an attack aimed at consuming the target system's bandwidth. Low data transfers may also signal stealthy

