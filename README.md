# Interfaces-Configuration
Cisco Packet Tracer lab focused on configuring and verifying router and switch interfaces, IPv4 addressing, interface status, and basic network connectivity.


# Interfaces Configuration

## 📖 Overview

This lab focused on configuring and verifying network interfaces on Cisco routers and switches using the Cisco IOS command-line interface.

The lab provided hands-on experience assigning IPv4 addresses, enabling interfaces, configuring interface descriptions, and verifying interface status and connectivity.

## 🎯 Objectives

The lab was designed to:

* Access and configure Cisco device interfaces.
* Assign IPv4 addresses and subnet masks to router interfaces.
* Enable interfaces using the appropriate commands.
* Configure interface descriptions.
* Configure switch interfaces where required.
* Verify interface status and addressing.
* Test connectivity between network devices.
* Troubleshoot basic interface and connectivity problems.

## 🧠 Concepts Practiced

* Cisco IOS CLI
* Router interfaces
* Switch interfaces
* IPv4 addressing
* Subnet masks
* Interface descriptions
* Interface status
* `shutdown` and `no shutdown`
* Basic connectivity testing
* Network troubleshooting

## 🛠️ Tools Used

* Cisco Packet Tracer
* Cisco IOS CLI

## ⚙️ Configuration

The required router and switch interfaces were configured through the Cisco IOS CLI.

Router interfaces were assigned the appropriate IPv4 addresses and subnet masks before being enabled.

Interface descriptions were also configured where appropriate to make the network topology easier to understand and maintain.

Example interface configuration:

```text
interface gigabitEthernet 0/0
ip address <ip-address> <subnet-mask>
description <interface-description>
no shutdown
```

## 🧪 Verification & Testing

Interface configurations were verified using commands such as:

```text
show ip interface brief
show interfaces
show running-config
```

The `show ip interface brief` command was particularly useful for quickly checking:

* Interface IP addresses
* Interface status
* Line protocol status

Connectivity was tested using:

```text
ping <destination-ip>
```

Successful ping tests confirmed that the configured interfaces and addressing were functioning correctly.

## 🔍 Troubleshooting

Common interface-related issues investigated during the lab included:

* Incorrect IP addresses.
* Incorrect subnet masks.
* Interfaces being administratively down.
* Incorrect interface selection.
* Missing `no shutdown` commands.
* Incorrect cable connections.
* Devices being placed in different IP networks.
* Incorrect end-device addressing.

Troubleshooting involved checking interface status, reviewing the running configuration, verifying IP addressing, and performing connectivity tests.

## 🔐 Why Interface Configuration Matters

Network interfaces provide the physical or logical connection between devices.

Correct interface configuration is essential for routers and switches to communicate with neighboring devices and for traffic to move between different networks.

Understanding interface configuration is also a foundation for more advanced CCNA topics such as VLANs, routing protocols, ACLs, and IPv6.

## ✅ Outcome

Successfully configured and verified Cisco network interfaces, assigned IPv4 addressing, enabled interfaces, and tested connectivity between network devices.

## 📚 Skills Demonstrated

* Cisco IOS CLI
* Interface configuration
* IPv4 addressing
* Subnet masks
* Interface verification
* Router configuration
* Switch configuration
* Connectivity testing
* Basic network troubleshooting
