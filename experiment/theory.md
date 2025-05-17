### Theory

Passive attacks are a type of security attack that involve the interception and/or monitoring of data transmissions without modifying the data itself. The goal of a passive attack is usually to eavesdrop on sensitive information or to gather data for future exploitation.

#### Types of Passive Attacks

1. Eavesdropping: This involves an attacker listening in on a conversation or data transmission between two parties. The attacker may use various techniques to intercept and capture data, such as packet sniffing.

2. Traffic analysis: In traffic analysis, an attacker analyzes patterns of network traffic to deduce information about the communication, such as the identity of the parties involved, the content of the communication, or the timing and frequency of the communication.

Passive attacks are typically more difficult to detect than active attacks, as they do not involve any modification or disruption of data. To protect against passive attacks, it is important to implement strong encryption and authentication measures to ensure that data transmissions are secure and can only be accessed by authorized parties. Additionally, network monitoring tools and intrusion detection systems can help detect and prevent passive attacks by monitoring network traffic for suspicious activity.

#### Eavesdropping Attack Process

Eavesdropping is a type of passive attack where an attacker intercepts and listens in on a conversation or data transmission between two parties. The attacker may use various techniques to capture the data being transmitted, such as packet sniffing or wiretapping. The goal of eavesdropping is usually to gather sensitive information or data that can be used for future exploitation.

```
Step 1: Data Transmission Begins
+------------+                             +------------+
|   Sender   | ------------------------->  | Receiver   |
|  (Alice)   |        Data Packets         |   (Bob)    |
+------------+                             +------------+
```

```
Step 2: Attacker Listens Silently
                      |
                      | (Monitors communication)
                      v
               +-----------------+
               |   Eavesdropper  |
               |     (Eve)       |
               +-----------------+
               | Uses tools like |
               | Wireshark or    |
               | packet sniffers |
               +-----------------+
```

```
Step 3: Sensitive Data Intercepted (Read-only)
- Eve captures packets without altering them
- Reads or stores:
   → Emails
   → Credentials
   → Personal data
```

```
Outcome:
✔️ Communication continues uninterrupted
⚠️ Privacy is compromised
```

#### Example of Eavesdropping

Alice is sending a confidential email to Bob from her computer. An attacker, Eve, who is on the same network as Alice and Bob, uses a packet sniffer tool to intercept and capture the data packets that are being transmitted between Alice's and Bob's computers. With the help of the packet sniffer, Eve is able to read the contents of Alice's email, including any sensitive information or personal details.

In this scenario, Eve is eavesdropping on Alice's and Bob's conversation by intercepting their email communication. Because the communication was not encrypted, Eve was able to easily capture the data packets and read the contents of Alice's email. This type of attack can be prevented by using encryption to protect the confidentiality of data transmissions. For example, if Alice had used a secure email service that encrypts email transmissions, Eve would not have been able to intercept and read the email content even if she was able to capture the data packets.
