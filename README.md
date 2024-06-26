# Optimized-Network-Architecture-for-Power-Generation-System-Test-Sites.
![image](https://github.com/Leisure-Codes/Optimized-Network-Architecture-for-Power-Generation-System-Test-Sites./assets/83419227/06e9c5b3-6958-4ee3-9ba7-684dfe0b6d7e)

During my bachelor's program, I had the opportunity to work with a startup company as part of an assignment to study and optimize their current network infrastructure. With extensive research and assistance from the company's chief Network Engineer, I was able to enhance the network's security and performance.

The company's network architecture is designed to optimize the transmission, security, and analysis of data generated by power generation systems across three distinct locations. The primary components of this architecture include the Product Testing Site (Plant 19), the Research Team Site, and the Analytics Team Site, each located within different campus area networks (CANs).

### 1. Product Testing Site (Plant 19)
Location: Plant 19

Function: This site hosts the power generator machines where extensive testing is conducted.

Data Transmission: Data generated from the tests is transmitted to the on-site server.

Security: A firewall is deployed to monitor and filter the data packets, ensuring that only legitimate traffic passes through and preventing any malicious packets from entering the network.

### 2. Research Team Site
Location: Separate campus from Plant 19

Function: Researchers at this location access the test data to conduct detailed analysis.

Connectivity: A dedicated, high-speed data link connects the Research Team Site to the Plant 19 site. This link is secured with end-to-end encryption to protect the data during transit.

Data Integrity: Given the significant distance between the locations, repeaters are employed along the transmission path to boost signal strength and maintain data integrity, ensuring that the data arrives without degradation or loss.

### 3. Analytics Team Site (24/7 IT Park Office)
Location: 24/7 IT Park

Function: The analytics team processes and interprets the data to extract actionable insights.

Data Access: The on-site server at Plant 19 is configured to securely transmit data to the main server located at the Analytics Team Site.
Security Measures: Multiple layers of security are implemented:

Firewall: A robust firewall monitors all incoming and outgoing traffic, blocking unauthorized access and ensuring that only authenticated users can access the data.

Authentication Protocols: Strong authentication mechanisms, such as multi-factor authentication (MFA) and secure socket layer (SSL) certificates, are employed to verify user identities and encrypt communications.

### 4. Network Infrastructure
Transmission Channels: Data channels between Plant 19 and the Analytics Team Site are fortified with advanced encryption standards (AES) to prevent data breaches.

Repeaters: Strategically placed repeaters help 99amplify the signal over long distances, maintaining high data quality and preventing signal attenuation.

Main Server: The centralized main server at the Analytics Team Site acts as the primary repository for all analytical data. This server is secured with an additional firewall to provide an extra layer of protection against cyber threats.

### 5. Operational Protocols
Data Monitoring: Continuous monitoring of network traffic using intrusion detection systems (IDS) and intrusion prevention systems (IPS) to detect and mitigate potential threats in real-time.

Data Integrity Checks: Regular integrity checks and hashing algorithms (e.g., SHA-256) are used to ensure that the data has not been tampered with during transmission.

Access Control: Role-based access control (RBAC) policies are implemented to restrict data access to authorized personnel only, based on their roles and responsibilities within the organization

## --Update 1--
###Description : As an update, I missed an integral part of the network, the employees also needs to communicate with other offices which are located in different countries and for that there has to be a wireless connection which connects the Regional server to the global one.
So, here is the updated network which represents the overall network architecture along with labelling for regional locations.
![image](https://github.com/Leisure-Codes/Optimized-Network-Architecture-for-Power-Generation-System-Test-Sites./assets/83419227/ec897b13-79fa-4ec7-a433-32a2c4f2a56b)
