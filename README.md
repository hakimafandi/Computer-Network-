This project involves the design and implementation of a network infrastructure for a fictional hospital chain named "Kani," with branches in India and Malaysia. The headquarters is located in Bangalore, India, and additional branches are situated in Puchong and Klang in Malaysia, and New Delhi, Goa, and Coimbatore in India. The network design aims to connect all branches efficiently, ensuring secure and reliable communication across the entire organization.
Features

1.Branch Network Design:

-The headquarters and branches have specific departments including Administration, Research & Development, Outpatient, Emergency, Pharmacy, Radiology, and specialized departments like Cardiology, Gynaecology, Neurology, and Orthopaedics.
-Each department's network requirements are analyzed, and appropriate subnetting is applied to ensure optimal allocation of IP addresses.

2.IP Address Allocation:

-The major network is assigned the IP block 70.90.64.0/20, providing 4094 available IP addresses.
-Subnets are created for each department and branch to cater to 350 hosts, with room for future expansion.

3. Network Components:

-Each branch is equipped with its own DHCP server, ensuring dynamic IP allocation within the branch.
-Centralized servers for DNS, web services, email, and other applications are used to provide essential services to all branches.

4. Routing and Performance:

-RIP (Routing Information Protocol) is implemented to ensure efficient routing between branches, minimizing routing loops by using hop count as the metric.
-Static routing is employed for predictable and straightforward network traffic management.
-Fast Ethernet is used to ensure high-speed data transfer and improved error detection and correction.

5. Security Measures:

-Each branch's router is configured with secure passwords to prevent unauthorized access.
-The logical diagram includes security measures to safeguard network integrity and data privacy.

6. Cost Efficiency:

-Copper cables are chosen for network connections due to their cost-effectiveness and ease of installation, reducing maintenance and installation costs.

Network Design Justification.

-A switch is allocated for each department in every branch to ensure better network performance and ease of expansion.
-The logical diagram and IP address allocation are designed to accommodate current needs and future growth.
-Each branch is connected via a router with a dedicated password, enhancing security and preventing unauthorized access.
