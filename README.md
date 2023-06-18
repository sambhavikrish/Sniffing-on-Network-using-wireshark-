Sniffing on Network using wireshark 
Sanjay Kumar Choudhary1, Nitin Kumar2
1Department of Cyber Forensic and information Technology, GITAM, Jhajjar, Haryana India
2Department of Computer Science and Engineering, GITAM, Jhajjar, Haryana India

1. Abstract:   Network traffic sniffing using tools like Wireshark has become a crucial aspect of network analysis and security investigations. This thesis explores the concept of network sniffing, focusing on the use of Wireshark as a powerful tool for capturing and analyzing network packets in real time. The research investigates the methodology, implications, and potential applications of sniffing network traffic using Wireshark.The thesis begins by providing an overview of network sniffing techniques, including their purpose, benefits, and ethical considerations. It emphasizes the importance of obtaining proper authorization and following legal and ethical guidelines when performing network sniffing activities.Next, the thesis delves into the detailed functionality of Wireshark and its capabilities as a network protocol analyzer. It explores the different features and functionalities of Wireshark that enable capturing, filtering, and analyzing network packets. The thesis also discusses the supported protocols and the versatility of Wireshark in handling various network scenarios.
The research then presents a comprehensive methodology for conducting network sniffing using Wireshark. It covers topics such as configuring network interfaces for packet capture, setting up filters to capture specific traffic, and analyzing captured packets for network troubleshooting, security analysis, and performance optimization purposes.
Furthermore, the thesis examines the implications of network sniffing in terms of network security and privacy. It discusses the potential risks associated with unauthorized packet capture, including data leakage, privacy breaches, and vulnerability exposure. The thesis highlights the importance of utilizing network sniffing responsibly and maintaining the integrity and confidentiality of captured data.
Lastly, the thesis explores practical applications of network sniffing using Wireshark across different domains, including network administration, security auditing, forensic investigations, and educational purposes. It provides real-world examples and case studies to demonstrate the effectiveness of Wireshark in various scenarios.
By the end of this thesis, readers will gain a comprehensive understanding of network sniffing using Wireshark, including its methodology, implications, and practical applications. The research aims to contribute to the knowledge base in the field of network analysis and security and provide insights for individuals and organizations seeking to utilize Wireshark effectively for network monitoring and analysis.
Keywords:  Network Sniffing,  Packet Capture,  Network Analysis,  Protocol Analyzer, Packet Inspection,  Network Troubleshooting,  Protocol Decoding,  Network Security,  Packet Filtering,  Network Monitoring,  Traffic Analysis,  Performance Optimization
2. Concept:   The concept of network sniffing involves the capture and analysis of network traffic to gain insights into the communication occurring within a computer network. It is commonly used for network troubleshooting, security analysis, and performance optimization. Network sniffing allows administrators and security professionals to examine the packets of data flowing through a network in order to understand network behavior, identify issues, and detect potential security threats. Network sniffing, when used responsibly and within legal and ethical boundaries, provides valuable insights into network behavior, security vulnerabilities, and performance optimization opportunities. It is an essential technique for network administrators, security professionals, and researchers to gain a deeper understanding of network operations and ensure the integrity and efficiency of computer networks
Here are the key aspects of network sniffing:
•	Packet Capture: Network sniffing tools, such as Wireshark, capture packets of data that traverse a network. These packets contain information about the source and destination addresses, protocols being used, payload data, and other relevant details.
•	Promiscuous Mode: Sniffing tools operate in promiscuous mode, allowing them to capture all network traffic on the network segment they are connected to. This includes not only the traffic intended for the device running the sniffing tool but also traffic destined for other devices on the network.
•	Protocol Analysis: Sniffing tools can analyze captured packets to decode and interpret the underlying network protocols. This enables the identification of different types of traffic, such as HTTP, DNS, FTP, and more, and helps in understanding how data is exchanged between devices.
•	Traffic Filtering: Network sniffing tools often provide filtering mechanisms to selectively capture specific types of traffic or traffic between specific devices. This allows focusing on relevant data and reducing the amount of captured traffic for analysis.
•	Network Troubleshooting: Network administrators use sniffing to troubleshoot network issues. By analyzing captured packets, they can identify errors, misconfigurations, or performance bottlenecks, helping in diagnosing and resolving network problems.
•	Security Analysis: Sniffing tools are valuable for security professionals in detecting and investigating network security incidents. By inspecting packet-level details, they can identify suspicious patterns, unauthorized access attempts, or network attacks. Sniffing can also be used for penetration testing and vulnerability assessments.
•	Performance Optimization: Network sniffing assists in optimizing network performance by analyzing traffic patterns. It helps identify bandwidth-intensive applications, inefficient network configurations, or bottlenecks, allowing administrators to make informed decisions to improve network performance.
3. Pre-Approval and Authorization:- Before engaging in network sniffing activities, it is crucial to obtain proper authorization. Network sniffing involves monitoring and analyzing network traffic, which can potentially intrude on users' privacy and violate legal and ethical boundaries if performed without consent. Unauthorized network sniffing can have serious legal and ethical consequences. Always prioritize obtaining proper authorization and ensure that you comply with all relevant laws and regulations. Respecting privacy and maintaining the security of captured data should be paramount throughout the network sniffing process.
Here are the steps to follow for pre-authorization:
•	Understand Applicable Laws and Regulations: Familiarize yourself with the laws and regulations relevant to network monitoring and data privacy in your jurisdiction. Different countries may have specific legal requirements and restrictions regarding network sniffing activities. Ensure that you comply with all applicable laws to avoid any legal repercussions.
•	Obtain Consent from Relevant Parties: Obtain written consent from the owners or administrators of the network you intend to monitor. This is particularly important if the network belongs to an organization or involves multiple users. Clearly communicate the purpose, scope, and duration of the sniffing activity and ensure that all parties involved understand and agree to it.
•	Define the Scope and Purpose: Clearly define the scope and purpose of the network sniffing activity. Determine what specific traffic you will monitor, the duration of monitoring, and the goals you aim to achieve. This will help establish a clear understanding with the network owners and ensure that your activities align with their expectations.
•	Document Authorization: Document the authorization you receive in writing. Include details such as the authorized duration, scope of monitoring, parties involved, and any specific conditions or restrictions imposed. This documentation serves as evidence of consent and can protect you in case of any future disputes.
•	Communicate Privacy and Security Measures: Clearly communicate the measures you will take to ensure privacy and security during network sniffing. Assure the network owners that you will handle the captured data responsibly, maintain confidentiality, and implement appropriate security measures to prevent unauthorized access or misuse of sensitive information.
•	Consult Legal and Ethical Guidelines: Consult professional advice, such as legal counsel or ethical guidelines from relevant professional associations, to ensure that your network sniffing activities adhere to established standards and ethical principles.
4.  Network protocol analyser :-A network protocol analyzer, also known as a network packet analyzer or network sniffer, is a tool or software application used to capture, analyze, and interpret network traffic at the packet level. It allows network administrators, security professionals, and developers to examine the contents and behavior of network packets, helping them understand, troubleshoot, and optimize network communication. The key features and capabilities of a network protocol analyzer:
•	Packet Capture: The analyzer captures network packets flowing through a network interface or a specific network segment. It can capture packets in real time or from packet capture files.
•	Protocol Decoding: The captured packets are decoded to interpret the network protocols being used, such as TCP/IP, UDP, HTTP, DNS, FTP, and more. The analyzer understands the structure of different protocols and can extract relevant information from the packet headers and payloads.
•	Packet Filtering: The analyzer provides the ability to filter and select specific packets based on various criteria, such as source or destination IP addresses, port numbers, protocol types, and specific data patterns. Filtering helps focus the analysis on relevant packets, reducing the amount of data to be processed.
•	Packet Analysis: The analyzer provides detailed analysis of captured packets, allowing users to examine various aspects of network communication. It can display packet headers, payloads, timing information, and protocol-specific details. This analysis helps in understanding network behavior, identifying errors, diagnosing performance issues, and detecting security threats.
•	Statistics and Performance Metrics: The analyzer collects and presents statistics and performance metrics related to network traffic. This includes information like packet counts, packet sizes, bandwidth usage, round-trip times, retransmission rates, and other performance indicators. These metrics aid in network troubleshooting and optimization.
•	Protocol-Specific Analysis: A protocol analyzer is often capable of performing in-depth analysis of specific protocols. It can detect protocol-specific issues, anomalies, or non-compliant behaviors. For example, it may analyze HTTP responses for potential security vulnerabilities or analyze DNS queries for misconfigurations.
•	Advanced Features: Some protocol analyzers offer advanced features such as session reconstruction, flow analysis, graphical visualization of network traffic, support for encrypted protocols, integration with other security tools, and scripting capabilities for customized analysis and automation.
Popular network protocol analyzers include Wireshark, tcpdump, Microsoft Network Monitor, and Colasoft Capsa. These tools are widely used in network administration, network security, software development, and academic research to gain insights into network behavior, troubleshoot issues, optimize performance, and enhance security.
By leveraging a network protocol analyzer, professionals can gain a deeper understanding of network communication, detect anomalies or vulnerabilities, and make informed decisions to improve the overall functionality, security, and performance of computer networks.
5. Capabilities and important features of Wireshark
Wireshark is a powerful network protocol analyzer that provides detailed insights into network traffic. It offers numerous features and capabilities that make it an essential tool for network administrators, security analysts, and developers. Overall, Wireshark's feature-rich and comprehensive capabilities make it an invaluable tool for network troubleshooting, security analysis, protocol development, and network performance optimization. Some of the important features and capabilities of Wireshark include:
•	Packet Capture and Analysis: Wireshark can capture network packets from various interfaces and protocols. It allows you to analyze the captured packets in real-time or from saved packet capture files.
•	Support for Multiple Protocols: Wireshark supports a wide range of network protocols, including Ethernet, Wi-Fi, TCP/IP, HTTP, DNS, FTP, SSH, and many more. This versatility enables it to analyze and decode packets from different layers of the network stack.
•	Deep Packet Inspection: It provides detailed inspection and analysis of network packets, allowing you to examine the contents of each packet. You can view packet headers, payloads, and other relevant information to understand the network behavior and troubleshoot issues.
•	Filter and Search Capabilities: Wireshark offers powerful filtering options that allow you to focus on specific network traffic based on criteria such as IP addresses, ports, protocols, packet lengths, and more. This helps you isolate and analyze specific packets or specific types of network traffic.
•	Protocol Decoding: Wireshark can decode and interpret various network protocols, providing meaningful information about the network communication. It can dissect protocol-specific fields and display them in a human-readable format, making it easier to understand the network traffic.
•	Statistics and Performance Analysis: Wireshark provides various statistics and performance metrics to help analyze network behavior. It can generate graphs and charts to visualize packet rates, throughput, round-trip times, and other performance parameters.
•	VoIP Analysis: Wireshark has extensive capabilities for analyzing Voice over IP (VoIP) protocols such as SIP (Session Initiation Protocol) and RTP (Real-time Transport Protocol). It can analyze call flows, detect audio quality issues, and provide insights into VoIP communication.
•	Network Security Analysis: Wireshark is widely used for network security analysis and troubleshooting. It can help detect and analyze network attacks, such as packet sniffing, port scanning, and DoS (Denial-of-Service) attacks. Additionally, it can be used to analyze encrypted traffic when provided with the encryption keys.
•	Extensibility and Customization: Wireshark offers a rich set of APIs and protocols that allow you to extend its functionality or integrate it into other applications. You can develop custom dissectors, plugins, and scripts to analyze proprietary or specialized protocols.
•	Cross-Platform Availability: Wireshark is available for multiple operating systems, including Windows, macOS, Linux, and various Unix-based systems. This ensures that network administrators and analysts can use it across different platforms.
6. Methodology :- Remember to always conduct network sniffing in compliance with legal and ethical guidelines. It's important to have proper authorization and ensure privacy protection while capturing and analyzing network traffic.
Conducting network sniffing using Wireshark involves the following methodology:
•	Prepare Your Environment:
o	Install Wireshark: Download and install the latest version of Wireshark from the official website (https://www.wireshark.org/).
o	Connect to the Network: Ensure that your computer is connected to the network you want to sniff. This can be a wired Ethernet network or a Wi-Fi network.
•	Choose the Capture Interface:
o	Launch Wireshark: Open Wireshark on your computer.
o	Select Capture Interface: Choose the appropriate network interface to capture packets. If you are connected via Ethernet, select the Ethernet interface. For Wi-Fi, choose the Wi-Fi adapter.
•	Start the Packet Capture:
o	Start Capturing: Click on the "Start" or "Capture" button in Wireshark to begin capturing packets.
o	Specify Capture Filters (optional): You can apply capture filters to limit the captured packets based on specific criteria like IP addresses, protocols, or ports.
•	Capture Network Traffic:
o	Perform Network Activities: Perform the network activities that you want to capture. This could include visiting websites, sending/receiving emails, running specific applications, or any other network communication.
•	Stop the Packet Capture:
o	Stop Capturing: Once you have captured the desired network traffic or completed the network activities, click on the "Stop" or "Capture" button in Wireshark to stop capturing packets.
•	Analyze Captured Packets:
o	Explore Packet List: Wireshark will display a list of captured packets in its main window. Each row represents a captured packet, and you can sort and filter the packets based on various criteria.
o	Inspect Packet Details: Select a packet from the list to view its details. Wireshark will provide a detailed breakdown of the packet, including protocol headers, payload, and other relevant information.
o	Use Filters and Search: Utilize Wireshark's powerful filtering and search capabilities to focus on specific packets or types of network traffic for analysis.
•	Interpret and Analyze:
o	Analyze Protocol Behavior: Wireshark enables you to interpret and analyze the behavior of different protocols involved in the captured packets. You can dissect protocol-specific fields, observe timings, and identify anomalies or errors.
o	Identify Network Issues: Look for network issues such as latency, packet loss, misconfigurations, security threats, or other abnormalities that may impact network performance or security.
o	Generate Statistics and Visualizations: Utilize Wireshark's statistical tools and graphs to generate performance metrics, round-trip times, throughput, or any other relevant network statistics.
•	Troubleshoot and Take Action:
o	Troubleshoot Network Problems: Use the information gathered from Wireshark to troubleshoot and resolve network issues. This may involve identifying misbehaving devices, diagnosing protocol errors, or optimizing network performance.
o	Implement Network Improvements: Based on your analysis, you can make necessary adjustments to network configurations, security measures, or application settings to improve network performance, reliability, or security.
7. Network sniffing using Wireshark has numerous practical applications in various domains. These are just a few examples of the practical applications of network sniffing using Wireshark. Its versatility and comprehensive analysis capabilities make it a valuable tool in network administration, security analysis, protocol development, and performance optimization.
•	Some of the common practical applications of network sniffing using Wireshark include:
•	Network Troubleshooting: Wireshark helps diagnose and troubleshoot network-related issues by capturing and analyzing network packets. It allows you to identify network bottlenecks, packet loss, latency problems, misconfigurations, and other network anomalies that could be affecting performance or connectivity.
•	Protocol Analysis and Development: Wireshark is commonly used for analyzing and developing network protocols. It helps developers understand the behavior of protocols by dissecting packet headers and payloads. Wireshark can be used to test the implementation of protocols, verify compliance with standards, and identify any issues or deviations.
•	Network Security Analysis: Wireshark is a valuable tool for network security analysts. It allows them to monitor and analyze network traffic for detecting and investigating security threats, such as malware infections, unauthorized access attempts, DoS attacks, or suspicious network behavior. Wireshark can assist in identifying vulnerabilities, analyzing attack patterns, and implementing appropriate security measures.
•	Performance Optimization: By capturing and analyzing network traffic, Wireshark can provide insights into network performance issues. It helps identify sources of latency, bandwidth utilization, application performance bottlenecks, and other factors affecting network efficiency. With this information, administrators can optimize network configurations, prioritize critical traffic, and improve overall network performance.
•	VoIP and Unified Communications Analysis: Wireshark is widely used for analyzing Voice over IP (VoIP) and unified communications protocols. It helps monitor and troubleshoot call quality issues, detect network-related voice problems, identify packet loss, delay, or jitter affecting voice communication, and analyze signaling protocols like SIP or H.323.
•	Network Monitoring and Capacity Planning: Wireshark can be used for ongoing network monitoring and capacity planning. By capturing and analyzing network traffic over time, it helps administrators understand usage patterns, identify peak traffic periods, monitor resource utilization, and make informed decisions regarding network infrastructure upgrades or capacity expansions.
•	Intrusion Detection and Forensics: Wireshark can assist in intrusion detection and forensic analysis. By capturing packets during or after a security incident, it allows analysts to reconstruct the attack timeline, understand the attack vectors, and gather evidence for forensic investigations. Wireshark helps in identifying suspicious or malicious network activities, unauthorized access attempts, and data breaches.
•	Network Baseline Establishment: Wireshark can help establish network baselines by capturing and analyzing normal network traffic patterns. By establishing a baseline, administrators can identify deviations from normal behavior, detect anomalies, and promptly respond to potential security threats or performance issues.









8. Case Study: Troubleshooting Slow Network Performance Using Wireshark
Scenario: A company's network is experiencing slow performance, affecting employee productivity and causing frustration. The IT team decides to use Wireshark to analyze the network traffic and identify the cause of the slowdown.
Objective: Identify the network issue causing slow performance and propose appropriate solutions to optimize network performance.
Steps Taken:
1.	Capturing Network Traffic:
o	The IT team installs Wireshark on a dedicated workstation connected to a network switch port mirroring the traffic.
o	They configure Wireshark to capture packets on the relevant interface.
2.	Analyzing the Captured Packets:
o	The team starts the packet capture and performs various tasks on the network, such as browsing the internet, accessing internal servers, and transferring files.
o	They stop the packet capture and open the captured file in Wireshark for analysis.
3.	Identifying Network Bottlenecks:
o	The team begins by examining the overall network statistics in Wireshark, such as packet rates, average packet size, and utilization levels.
o	They use Wireshark's graphs and statistics to identify any abnormal patterns or significant delays in packet transmission.
4.	Analyzing Protocol Behavior:
o	The team filters the captured packets based on protocols of interest, such as HTTP, DNS, or TCP, to focus their analysis.
o	They observe the protocol conversations and analyze response times, server delays, and packet retransmissions.
o	Through protocol decoding, they identify any errors, timeouts, or misconfigurations that could contribute to slow performance.
5.	Investigating Latency Issues:
o	The team looks for latency-related problems by examining round-trip times (RTT) between client requests and server responses.
o	They identify instances of high RTT, packet loss, or excessive retransmissions, which indicate network congestion or performance bottlenecks.
6.	Troubleshooting Application Performance:
o	The team filters packets related to the specific applications experiencing slowness.
o	They examine the payload of these packets, focusing on the request-response patterns and analyzing any delays or errors within the application layer.
7.	Finding Network Misconfigurations:
o	The team looks for misconfigurations, such as duplicate IP addresses, incorrect subnet masks, or routing issues.
8.	They analyze the captured packets to identify any abnormal network behavior caused by misconfigured devices or incorrect network settings.

9.	Analyzing Bandwidth Utilization:
o	The team uses Wireshark's statistics and graphs to examine bandwidth utilization patterns during peak usage periods.
o	They identify bandwidth-hungry applications or devices that might be causing congestion and affecting overall network performance.
10.	Proposing Solutions and Optimizations:
o	Based on their analysis, the team proposes solutions to address the identified network issues, such as optimizing routing configurations, upgrading network equipment, or implementing Quality of Service (QoS) policies.
o	They prioritize their recommendations based on the severity of the issues and potential impact on network performance.
11.	Implementing Network Improvements:
o	The team collaborates with network administrators and stakeholders to implement the proposed solutions.
o	They monitor the network after implementing the improvements to ensure that the performance issues have been resolved.
Results and Benefits:
•	The IT team identified a misconfigured router that was causing excessive packet drops and retransmissions, resulting in slow network performance.
•	By resolving the misconfiguration and implementing appropriate routing optimizations, the team improved network responsiveness and reduced latency.
•	Employee productivity increased, and the frustration caused by slow network performance was alleviated.
Wireshark proved instrumental in diagnosing the network performance issues, allowing the team to pinpoint the root cause and implement targeted solutions.












Bibliography:
1.	Title: "Network Traffic Analysis and Intrusion Detection System Using Wireshark and Snort" Authors: Ali, D., & Abualkishik, A. Publication Year: 2018 Source: 2018 International Conference on Computer and Applications (ICCA)
2.	Title: "Performance Evaluation of VoIP Protocols Using Wireshark" Authors: Singh, P., & Batra, S. Publication Year: 2020 Source: 2020 International Conference on Inventive Computation Technologies (ICICT)
3.	Title: "Wireshark for Network Forensics: Analysis of Captured Network Traffic for Investigative Purposes" Authors: Raj, A., & Gupta, A. Publication Year: 2020 Source: 2020 11th International Conference on Computing, Communication and Networking Technologies (ICCCNT)
4.	Title: "Application of Wireshark for Network Security Monitoring and Incident Response" Authors: Singh, N., & Singh, R. Publication Year: 2020 Source: 2020 11th International Conference on Computing, Communication and Networking Technologies (ICCCNT)
5.	Title: "Analysis of Network Traffic Using Wireshark and tshark" Authors: Kotsiantis, S. B., & Pintelas, P. E. Publication Year: 2021 Source: Data Analysis and Applications 2: International Conference, ICDDAA 2021, St. Petersburg, Russia, June 23–25, 2021, Proceedings


