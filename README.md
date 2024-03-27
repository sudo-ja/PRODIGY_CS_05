# PRODIGY_CS_05

Prodigy Cyber Security Internship - Task 5 - Network Packet Analyzer

Develop a packet sniffer GUI tool that captures and analyzes network packets. Display relevant information such as source and destination IP addresses, protocols, and payload data. Ensure the ethical use of the tool for educational purposes.

Please take a moment to review the included PacketSnifferGUI.py file.

This Python code creates a simple graphical user interface (GUI) for a packet sniffer application using the Tkinter library. The GUI consists of a single button labeled "Start Capture" and a text area where captured packet information will be displayed. When the "Start Capture" button is clicked, the start_capture method is invoked. Inside this method, the pyshark library is used to initiate a live packet capture on the Ethernet interface. For every packet captured (up to 10 packets in this example), information such as the packet itself, source and destination IP addresses, protocol, and payload are extracted and appended to the text area within the GUI. The GUI remains responsive during the capture process, allowing users to interact with other components or close the application if needed. This code provides a basic foundation for building more advanced network monitoring tools or studying network protocols in a visual manner.
