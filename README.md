# CTI_Assignment_Harsh_Vyas
## Diamond Model Extraction — Rhysida Ransomware

| Diamond Vertex | Extracted Information | Evidence from Report |
|----------------|------------------------|------------------------|
| **Adversary** | Rhysida ransomware group | CISA report states Rhysida is responsible for recent attacks |
| **Infrastructure** | TOR leak site, C2 servers, VPN | Report notes use of TOR for leaking victim data |
| **Capability** | Ransomware, data encryption, lateral movement | Report describes encryption and exfiltration techniques |
| **Victim** | Education, healthcare, government, manufacturing | Report lists targeted organizations across sectors |

**Threat Actor Profile Summary — Rhysida Ransomware**
**1. Threat Actor Name**

**Rhysida ransomware group**

**2. Targeted Sectors or Regions**

**Rhysida is a ransomware organization that hacks schools, hospitals, government institutions, and technology firms.**
They are like a service, as they engage the other criminals who carry out the actual attacks. Most of their attacks are money-oriented. They normally threaten to leak information that is stolen in case the victim declines to make payment.

**3. Attack Vector and Initial Access Method**

**The group normally begins by gaining access to systems by compromising open remote services like VPN or RDP with stolen or weak passwords.**
They also sometimes enter the network with the help of malware. Once they get inside, they employ Windows native tools to hide their activities among the normal activities of the system. **They execute PowerShell and command-line utilities and access the network through a remote desktop** to navigate through the network, gather information and install before installing the ransomware.

**4. Summary of Diamond Model Analysis**

**The attacker with the help of the Diamond Model is the Rhysida ransomware group and its networks.**
Tools that they use are usually **compromised VPN accounts, remote desktops, and even malware loaders.**
They will be able to **encrypt files, rob data, rob logins, and silently navigate within a network.**
Their primary market is for individuals in **schools, hospitals, government employment, and IT companies.**

**5. Mitigation Strategies**

**To reduce the likelihood of Rhysida attacks, CISA says to put MFA on all remote access systems, keep internet-facing devices patched, minimize RDP exposure, and look for weird PowerShell or admin tool use.**
Network zoning and well-constructed password policies also enable damage to remain small in case an attacker breaks in.
