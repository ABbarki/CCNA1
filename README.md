# CCNA 1 – Module 1: Networking Today

## Topic 1: Networks and Their Purpose

### 1. What is a Network?

A **computer network** is a group of interconnected devices that communicate and share information or resources.

**Example: University Network**

- Students use computers.
- Computers connect to switches.
- Switches connect to routers.
- Routers provide access to the Internet.
- Printers are shared across the network.

### 2. Why Do We Need Networks?

| Purpose | Example |
|---|---|
| Communication | Email, messaging |
| Resource sharing | Shared printers |
| File sharing | Sharing documents |
| Internet access | Browsing websites |
| Centralized management | Managing users and servers |

### 3. Important Networking Terms

- **Host:** Any device that communicates over a network.
- **Client:** A device or application requesting a service.
- **Server:** A device or application providing a service.
- **Peer-to-peer:** Devices share resources directly without requiring a dedicated server.
- **Network infrastructure:** The devices and connections that make networking possible.

### 4. Client-Server vs. Peer-to-Peer

#### Client-Server

Clients request services from a centralized server.

Example:
- A computer requests a website.
- The web server processes the request.
- The server sends the webpage back to the computer.

#### Peer-to-Peer (P2P)

Devices can share resources directly without requiring a dedicated central server.

Example:
- Two computers share files directly.
- Each computer can act as both a client and a server.

### 5. Comparison

| Client-Server | Peer-to-Peer |
|---|---|
| Centralized management | Decentralized management |
| Dedicated servers | No dedicated server required |
| Easier centralized security | Security managed by individual devices |
| Suitable for larger networks | Often suitable for smaller networks |

### 6. Knowledge Check

1. What is a computer network?
2. In a client-server network, who provides services?
3. Which model allows devices to share resources directly?

### Key Takeaways

- Networks connect devices to communicate and share resources.
- Hosts are devices that communicate over a network.
- Clients request services.
- Servers provide services.
- Client-server networks use centralized servers.
- Peer-to-peer networkect resource sharing.
# CCNA 1 – Module 1: Networking Today

## Topic 2 – Network Components

### 1. The Three Main Network Components

1. End devices.
2. Intermediary devices.
3. Network media.

## 2. End Devices

An end device is a device that acts as the source or destination of network communication.

Examples:
- Desktop computers
- Laptops
- Smartphones
- Servers
- Network printers
- IP phones
- Smart TVs
- Security cameras

### Network Interface Card (NIC)

A NIC is hardware that allows a device to connect to a network.

Types:
- Ethernet NIC: Wired connection.
- Wireless NIC: Wi-Fi connection.

### Source and Destination

- Source: Device sending information.
- Destination: Device receiving information.

Example: When your laptop requests a webpage:
- Laptop = Source.
- Web server = Destination.

## 3. Intermediary Devices

Intermediary devices connect end devices and help move data through a network.

| Device | Main function |
|---|---|
| Switch | Connects devices within a LAN |
| Router | Connects different networks |
| Wireless Access Point | Connects wireless devices to a network |
| Firewall | Filters network traffic according to security rules |
| Modem | Modulates and demodulates signals for certain access technologies |

### Switch

- Connects multiple devices inside a LAN.
- Uses MAC addresses to forward Ethernet frames.
- Traditionally operates at OSI Layer 2.

### Router

- Connects different networks.
- Uses IP addresses to forward packets.
- Operates at OSI Layer 3.

### Wireless Access Point

- Allows wireless devices to connect to a network.
- Uses Wi-Fi technology.
- Bridges wireless clients to the wired network.

## 4. Network Media

Network media are the channels through which data travels between network devices.

### A. Copper Cables
- Transmit data using electrical signals.
- Commonly used in Ethernet networks.
- Example: UTP Ethernet cable.

### B. Fiber-Optic Cables
- Transmit data using light.
- Support high bandwidth and long distances.
- Resistant to electromagnetic interference.

### C. Wireless
- Transmits data using electromagnetic waves.
- No physical cable is required between wireless communicating devices.
- Examples: Wi-Fi and Bluetooth.

### Comparison

| Feature | Copper | Fiber | Wireless |
|---|---|---|---|
| Signal | Electrical | Light | Radio waves |
| Physical cable | Yes | Yes | No |
| EMI interference | Susceptible | Resistant | Can experience interference |
| Typical use | LAN | High-speed links | Wi-Fi |

EMI = Electromagnetic Interference.

## 5. How Network Components Work Together

Example: Sending a file from your laptop to another computer.

1. Your laptop creates the data.
2. Its NIC sends the data through Ethernet or Wi-Fi.
3. A switch receives and forwards the data.
4. A router forwards it to another network if necessary.
5. The destination computer receives the data.

Remember:
- End devices create or receive data.
- Intermediary devices move data.
- Network media carry data.

## 6. Important CCNA Exam Differences

| Description | Component |
|---|---|
| Creates or receives data | End device |
| Connects multiple LAN devices | Switch |
| Connects different networks | Router |
| Forwards frames using MAC addresses | Switch |
| Forwards packets using IP addresses | Router |
| Provides wireless connectivity | Access Point |
| Transmits using electrical signals | Copper |
| Transmits using light | Fiber |
| Transmits using radio waves | Wireless |
| Filters traffic using security rules | Firewall |

## 7. Packet Tracer Practical Challenge

Build a simple network:

1. Add one switch.
2. Add two PCs.
3. Connect both PCs to the switch using Copper Straight-Through cables.
4. Configure:

PC0:
- IP address: 192.168.1.1
- Subnet mask: 255.255.255.0

PC1:
- IP address: 192.168.1.2
- Subnet mask: 255.255.255.0

5. Open PC0's Command Prompt and execute:

```bash
ping 192.168.1.2
```

You should receive replies.

## 8. Key Takeaways

- End devices are sources and destinations of communication.
- Intermediary devices forward and manage network traffic.
- Network media carry data.
- Switches use MAC addresses to forward Ethernet frames.
- Routers use IP addresses to forward packets between networks.
- Copper uses electrical signals.
- Fiber uses light.
- Wireless uses radio waves.

## 9. Self-Test

1. What are the three categories of network components?
2. What is the purpose of a NIC?
3. Which device connects different networks?
4. Which device forwards Ethernet frames using MAC addresses?
5. What is the difference between a switch and a router?
6. Which medium transmits data using light?
7. What is the purpose of a wireless access point?
8. What are the main functions of end devices and intermediary devices?