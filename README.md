# Active-Directory-Home-Lab
Active Directory Home Lab

Overview

I’ve been working on my first Active Directory home lab to get more hands-on experience with IT and cybersecurity.

I set up Windows Server 2025 in VirtualBox, created my own domain, and started practicing user management and security log investigations.

My goal with this project is to better understand how Active Directory works and how SOC Analysts investigate account activity.

Lab Setup

* Oracle VirtualBox
* Windows Server 2025
* Domain: adlab.test
* Domain Controller: DC01
* Active Directory Users and Computers
* Windows Event Viewer

What I’ve Done So Far

* Installed Windows Server and configured Active Directory Domain Services.
* Created a domain controller and user accounts.
* Created security groups and practiced changing user memberships.
* Practiced disabling accounts and reviewing account activity.
* Used Event Viewer to investigate account creation, group membership changes, and authentication attempts.
* Troubleshot a user’s login issues and confirmed a successful network authentication.

Security Events I’ve Practiced With

Event ID	Description
4720	User account created
4728	User added to a security-enabled global group
4625	Failed logon
4624	Successful logon

What I Learned

One thing I’ve learned is that finding a security event doesn’t automatically tell you the full story.

For example, I initially had trouble authenticating with one of my test accounts. After checking the account settings and reviewing the security logs, I was able to confirm a successful network logon using Event ID 4624.

I’m still learning, but working through these issues has helped me understand Active Directory and Windows security logs better.

Next Steps

* Practice investigating file access permissions.
* Learn more Windows Security Event IDs.
* Set up a domain-joined Windows workstation.
* Continue building hands-on SOC investigation skills.
