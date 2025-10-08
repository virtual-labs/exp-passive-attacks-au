

Passive attacks are security attacks that involve intercepting or monitoring data transmissions without modifying them. The goal is to eavesdrop on sensitive information or gather data for future exploitation.

#### Types of Passive Attacks

1.  **Eavesdropping**: This is the act of secretly listening to a private conversation or data transmission between two parties. An attacker can use techniques like packet sniffing to intercept and capture data. The goal is to gather sensitive information, such as login credentials or personal data, that can be used for malicious purposes. Since eavesdropping does not alter the data, it can continue undetected while compromising privacy.

2.  **Traffic Analysis**: In traffic analysis, an attacker monitors patterns in network traffic to deduce information. This can reveal who is communicating, how often, and at what times, even if the content of the communication is encrypted.

Passive attacks are difficult to detect because they don't disrupt data exchange. Strong encryption and authentication are the primary defenses, ensuring that even intercepted data remains confidential. Network monitoring tools can also help detect suspicious activity.

#### Example of Eavesdropping

An eavesdropping attack typically follows these steps:
1.  **Data Transmission**: A sender (e.g., Alice) sends data packets to a receiver (e.g., Bob) over a network.
2.  **Silent Interception**: An attacker (e.g., Eve) on the same network uses a tool like a packet sniffer to silently monitor and capture these packets without altering them.
3.  **Information Exposure**: Because the communication is unencrypted, Eve can read the contents of the captured packets, exposing sensitive information.

For instance, if Alice sends an unencrypted email to Bob, Eve can intercept it and read its contents. Had the email been encrypted, Eve would only see scrambled data, rendering the interception useless. This highlights the importance of encryption in protecting data confidentiality.
