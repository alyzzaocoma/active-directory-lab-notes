# Active Directory Domain Services — Lab Documentation
Windows Server Active Directory and Domain Controller setup — self-study lab notes

## Overview
This is my personal lab documentation for setting up and managing
Windows Server infrastructure. I made this as a hands-on guide while
learning Active Directory, DNS, DHCP, File Server, and basic
RedHat Linux administration using Oracle VirtualBox.

Note: Everything here was done in a virtual lab environment (no real
networks or production systems were involved.)
<br><br>

## A few things to note before reading
+ The examples inside are **not in strict sequence**. Some sections
  use different IP addresses, subnet configurations, or domain names
  because I was exploring specific concepts separately. For example,
  I might use one subnet setup to explain DHCP and a completely
  different one when demonstrating DNS (this is intentional, not
  an error.)

+ I used **celebrities/ made-up names** as sample
  user accounts (for Active Directory user creation, group policies,
  etc.). These are just placeholder names I used to make the lab
  scenarios feel more realistic and easier to follow.

+ The passwords shown (like P@ssw0rd1) are **default lab passwords**
  used only inside the virtual environment for practice.
<br><br>

## Topics covered
**Windows Server**
- Installing Windows Server 2016 Data Center on VirtualBox
- Hardware configuration (hard disk, CPU, memory allocation)
- IP address and network configuration
- Remote Desktop Connection setup
- VM snapshots

**Active Directory Domain Services**
- Promoting a server to Domain Controller
- Creating organizational units, users, and groups
- Group Policy configuration (password policies, access control)
- Joining client machines to the domain
- Password resets and account troubleshooting

**DNS**
- Forward and reverse lookup zones
- Host record creation
- DNS resolution testing

**DHCP**
- DHCP server and scope setup
- Automatic IP assignment for clients

**File Server**
- Setting up shared folders with permissions

**RedHat Linux**
- Basic commands (file management, permissions, users)
- Ownership, group management, and process handling

## Tools used
- Oracle VirtualBox
- Windows Server 2016 Data Center
- Active Directory Domain Services (AD DS)
- Group Policy Management Console
- DNS Server / DHCP Server
- RedHat Linux
<br><br>

## Here is the link to the full notes
The complete step-by-step documentation with screenshots:
[Notes-Active Directory Domain Services.pdf](Notes-Active-Directory-Domain-Services.pdf)
