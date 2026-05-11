*This project has been created as part of the 42 curriculum by thblack-*

**Description**
NetPractice is a mandatory 42 school core curriculum project that is intended to introduce students to networks, specifically TCP (Transmission Control Protocol), IP addresses and subnet masks.
TCP is the transport layer and is a standard for exchanging messages over a network. It establishes a connection between source and destination, breaks data into packets, and ensures lossless transfer.
IP addresses are the network layer. This project trains studentss with the use of IPv4 IP addresses. Nowadays the newer IPv6 is the standard, but IPv4 is simpler and thus an easier tool for learning some basics.
The subnet mask is a 32 bit (4 bytes) addresses used to define which portion of an IP address is the network adress (shared) and which is the host (user/router/etc.). In binary form 1s *"mask"* the network portion and 0s *"mask"* the host. Subnet masks are commonly written either in decimal e.g. 255.255.255.0 or in CIDR notation /24 (the number of bits for the network address).
Other key concepts:
- A switch connects multiple devices but does not have interfaces of its own.
- A router connects multiple networks together and has an interface for each network it connects to. The range of possible IP addresses on each network must not overlap.
- A routing table is a data table stored on a router that indicates the different routes to destinations. In this project it consists of a destination (either *"default"* or a network address and CIDR mask e.g. 40.40.40.0/24) and a next step i.e. the next interface along the route.

**Instructions**
To run the trainer and evaluator open the folder `netpractice` from `net_practice.1.7.tgz` in terminal the run the command `python3 -m http.server`. Once the server is running, open the address `http://localhost:8000` in your web browser.

**Resources**
https://www.geeksforgeeks.org/computer-networks/tcp-ip-model/
https://www.geeksforgeeks.org/computer-networks/introduction-to-subnetting/
https://www.geeksforgeeks.org/computer-networks/default-gateway-in-networking/
https://www.geeksforgeeks.org/computer-networks/open-systems-interconnection-model-osi/
https://www.geeksforgeeks.org/computer-networks/difference-between-router-and-switch/

**Submission Details**
10 exported configuration files (one per level) must be in the repository root.
