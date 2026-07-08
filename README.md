# Design and Implementation of a Secure IoT Edge Network Utilizing Zero Trust Architecture

![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

## Project Description
Full design and implementation of a Zero Trust security model for IoT edge networks. Includes project report, source code, datasets, screenshots, and installation guidelines.

## 📋 Project-Overview

This project presents a comprehensive design and implementation of a secure IoT Edge Network infrastructure utilizing **Zero Trust Architecture** principles. The network topology is designed using **Cisco Packet Tracer** and demonstrates advanced security concepts including access control lists (ACLs), routing protocols, and device authentication.

## 🎯 Key Features

- **Zero Trust Architecture**: Implements the principle of "never trust, always verify" for all network communications
- **IoT Edge Network**: Demonstrates edge computing concepts with IoT devices, servers, and gateways
- **Advanced Routing**: OSPF-based dynamic routing with security policies
- **Security Policies**: ACL-based access control and device-level security configurations
- **Protocol Testing**: Comprehensive testing of ARP, ICMP, and OSPF protocols
- **Performance Analysis**: Quantitative measurements and performance metrics

## 📁 Project Structure

```
├── 1_Final_Project_Report/
│   └── Design_and_Implementation_of_a_Secure_IoT_Edge_Network_...docx
│       (Detailed project documentation and architecture)
│
├── 2_Source_Code/
│   └── mehdi_project.pkt
│       (Cisco Packet Tracer network simulation file)
│
├── 3_Presentation_Slides/
│   └── (PowerPoint presentation slides)
│
├── 4_Dataset_Database_Files/
│   ├── Performance Analysis and Quantitative measurement.csv
│   └── (Additional data files)
│
├── 5_Installation_Guidelines/
│   └── Installation_and_Execution_Guidelines.txt
│       (Detailed setup and execution instructions)
│
├── 6_Screenshots_Output_Results/
│   └── (Output screenshots and test results)
│
└── README.md
    (This file)
```

## 🚀 Getting Started

### Prerequisites

- **Cisco Packet Tracer** v8.2 or later
  - Free download: https://www.netacad.com/courses/packet-tracer
  - Requires free Cisco NetAcad account registration
- **Microsoft Word** or compatible viewer (for project report)
- **Microsoft PowerPoint** or compatible viewer (for presentation)
- **Spreadsheet application** (Excel, Google Sheets, etc. for CSV data)

### Installation & Setup

1. **Install Cisco Packet Tracer**
   - Visit https://www.netacad.com
   - Register for a free NetAcad account
   - Download Packet Tracer for your operating system
   - Install and launch the application

2. **Open the Project**
   - Launch Cisco Packet Tracer
   - Go to **File → Open**
   - Navigate to `2_Source_Code/mehdi_project.pkt`
   - The network topology will load automatically

3. **Review Documentation**
   - Open `1_Final_Project_Report/` for detailed architecture documentation
   - View `3_Presentation_Slides/` for overview slides
   - Read `5_Installation_Guidelines/Installation_and_Execution_Guidelines.txt` for detailed execution steps

## 🔧 Running the Simulation

### Basic Simulation Steps

1. Open `mehdi_project.pkt` in Cisco Packet Tracer
2. Switch to **Simulation** mode (Alt + Shift + S or click "Simulation" tab)
3. Click **Play** to start the simulation
4. Use **Add Simple PDU** to send test packets between devices

### Testing Protocols

**ICMP (Ping Tests)**
- Send ping requests between devices to test connectivity
- Observe packet flow in the network
- Results documented in: `6_Screenshots_Output_Results/icmp*.jpeg`

**ARP (Address Resolution)**
- Observe ARP resolution in event list
- Verify MAC address learning
- Results documented in: `6_Screenshots_Output_Results/arp*.jpeg`

**OSPF (Routing Protocol)**
- Verify dynamic routing table convergence
- Check OSPF neighbor relationships
- Results documented in: `6_Screenshots_Output_Results/ospf*.jpeg`

### Verifying Zero Trust Policies

1. Click on any network device (router, switch, or IoT device)
2. Navigate to **Config** or **CLI** tab
3. Review applied:
   - Access Control Lists (ACLs)
   - Security policies
   - Device authentication rules

## 📊 Performance Analysis

The project includes comprehensive performance metrics:

- **Dataset Files**: `4_Dataset_Database_Files/`
  - Performance Analysis and Quantitative measurement.csv
  - Contains metrics on network latency, throughput, and security overhead

## 📸 Test Results & Screenshots

All output screenshots are located in `6_Screenshots_Output_Results/`:

| Test Type | Files | Description |
|-----------|-------|-------------|
| ARP Protocol | arp.jpeg, arp1.jpeg, arp2.jpeg | ARP protocol testing results |
| ICMP Ping | icmp1.jpeg, icmp2.jpeg, icmppath.jpeg | ICMP connectivity tests |
| OSPF Routing | ospf.jpeg, ospf2.jpeg | OSPF routing verification |
| Device Config | pc0.png, pc1.png, pc2.png | PC configurations |
| Server Config | server0.png, server1.png, server3.png | Server configurations |
| IoT Devices | tablet0.png, tablet2.png | IoT device configurations |

## 🏗️ Network Architecture Highlights

### Zero Trust Implementation
- **Principle of Least Privilege**: Each device only accesses what it needs
- **Continuous Verification**: All network communications are authenticated and verified
- **Micro-segmentation**: Network divided into isolated security zones
- **Access Control Lists**: Granular ACLs at every network boundary

### IoT Edge Network Design
- **Edge Computing**: Processing at network edge to reduce latency
- **Device Isolation**: IoT devices segregated in dedicated VLAN/security zones
- **Gateway Security**: Secure gateways controlling IoT device communications
- **Data Protection**: Encrypted communications between edge devices and central systems

## 📖 Documentation

- **Project Report**: Comprehensive documentation of design decisions and implementation details
- **Installation Guide**: Step-by-step setup and execution instructions
- **Presentation Slides**: Visual overview of project objectives and results
- **Performance Data**: CSV files with quantitative analysis

## 🔒 Security Considerations

This project demonstrates:
- Access Control Lists (ACLs) for traffic filtering
- VLANs for network segmentation
- Authentication mechanisms for device verification
- Encrypted communication protocols
- Zero Trust Architecture best practices

## 👨‍💻 Author

Project developed as part of network security and IoT infrastructure studies.

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

This is an academic project. For improvements or suggestions, please create an issue or pull request.

## 📞 Support

For questions or issues:
1. Refer to the detailed installation guide in `5_Installation_Guidelines/`
2. Check the project report for architecture details
3. Review test results in `6_Screenshots_Output_Results/`

## 🔗 Resources

- [Cisco Packet Tracer Documentation](https://www.netacad.com/courses/packet-tracer)
- [Zero Trust Architecture Guidelines](https://www.nist.gov/publications/zero-trust-architecture)
- [IoT Security Best Practices](https://www.iot.org/security)

---

**Last Updated**: May 2026

**Project Status**: ✅ Complete and Tested
