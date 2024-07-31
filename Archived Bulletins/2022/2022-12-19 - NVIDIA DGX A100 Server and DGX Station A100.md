# NVIDIA DGX A100 Server and DGX Station A100 (Bulletin ID: 5435)



NVIDIA DGX A100 Server and DGX Station A100 - December 2022
===========================================================




 Updated 01/10/2023 12:39 PM



NVIDIA has released a firmware security update for NVIDIA DGX A100 server and NVIDIA DGX Station A100. This update addresses issues that may lead to code execution, denial of service, escalation of privileges, loss of data integrity, information disclosure, or data tampering.


To protect your system, download and install this firmware update through the [NVIDIA Enterprise Support Portal](https://nvid.nvidia.com/dashboard/).


Go to [NVIDIA Product Security](https://www.nvidia.com/security/)






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑42271 | NVIDIA baseboard management controller (BMC) contains a vulnerability in the Intelligent Platform Management Interface (IPMI) handler, where an attacker with the required privileges can cause a buffer overflow, which may lead to denial of service or code execution. | 8.4 | [AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42272 | NVIDIA BMC contains a vulnerability in the IPMI handler, where an attacker with the required privileges can cause a buffer overflow, which may lead to code execution, denial of service, or escalation of privileges. | 8.1 | [AV:N/AC:H/PR:N/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:H/PR:N/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42273 | NVIDIA BMC contains a vulnerability in `libwebsocket`, where an attacker with the required privileges can cause a buffer overflow, which may lead to denial of service or code execution. | 8.1 | [AV:N/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N) |
| CVE‑2022‑42274 | NVIDIA BMC contains a vulnerability in the IPMI handler, where an attacker with the required privileges can cause a buffer overflow, which may lead to denial of service or code execution. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42275 | NVIDIA BMC contains a vulnerability in the IPMI handler, where an unauthenticated host is allowed to write to a host SPI flash, bypassing secure boot protections. An exploit of this vulnerability may lead to a loss of integrity or denial of service. | 7.7 | [AV:L/AC:L/PR:N/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:N/I:H/A:H) |
| CVE‑2022‑42276 | NVIDIA DGX A100 server contains a vulnerability in SBIOS in the SmiFlash, where a local user with elevated privileges can read, write, and erase the flash, which may lead to code execution, escalation of privileges, denial of service, or information disclosure. The scope of the impact can extend to other components. | 7.5 | [AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2022‑42277 | NVIDIA DGX Station contains a vulnerability in SBIOS in the SmiFlash, where a local user with elevated privileges can read, write, and erase the flash, which may lead to code execution, escalation of privileges, denial of service, or information disclosure. The scope of the impact can extend to other components. | 7.5 | [AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2022‑42278 | NVIDIA BMC contains a vulnerability in the SPX REST API, where an attacker with the required privileges can read and write to arbitrary locations within the memory context of the IPMI server process, which may lead to code execution, denial of service, information disclosure, or data tampering. | 7.2 | [AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42279 | NVIDIA BMC contains a vulnerability in the SPX REST API, where an attacker with the required privileges can inject arbitrary shell commands, which may lead to code execution, denial of service, information disclosure, or data tampering. | 7.2 | [AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42289 | NVIDIA BMC contains a vulnerability in the SPX REST API, where an attacker with the required privileges can inject arbitrary shell commands, which may lead to code execution, denial of service, information disclosure, or data tampering. | 7.2 | [AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42290 | NVIDIA BMC contains a vulnerability in the SPX REST API, where an attacker with the required privileges can inject arbitrary shell commands, which may lead to code execution, denial of service, information disclosure, or data tampering. | 7.2 | [AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42280 | NVIDIA BMC contains a vulnerability in the SPX REST authorization handler, where an unauthorized attacker can exploit a path traversal, which may lead to escalation of privileges. | 7.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N) |
| CVE‑2022‑42281 | NVIDIA DGX A100 contains a vulnerability in SBIOS in the FsRecovery, which may allow a highly privileged local attacker to cause an out-of-bounds write, which may lead to code execution, denial of service, loss of data integrity, or information disclosure. | 6.7 | [AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42282 | NVIDIA BMC contains a vulnerability in the SPX REST API, where an attacker with the required privileges can access arbitrary files, which may lead to information disclosure. | 6.5 | [AV:N/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N) |
| CVE‑2022‑42283 | NVIDIA BMC contains a vulnerability in the IPMI handler, where an attacker with the required privileges can cause a buffer overflow, which may lead to denial of service or code execution. | 6.4 | [AV:L/AC:H/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42284 | NVIDIA BMC stores user passwords in an obfuscated form in a database accessible by the host, which may lead to exposure of user credentials. | 6.2 | [AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N) |
| CVE‑2022‑42285 | DGX A100 SBIOS contains a vulnerability in the Pre-EFI Initialization (PEI) phase, where a privileged user can disable SPI flash protection, which may lead to denial of service, escalation of privileges, or data tampering. | 6.0 | [AV:L/AC:L/PR:H/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:U/C:N/I:H/A:H) |
| CVE‑2022‑42286 | DGX A100 SBIOS contains a vulnerability in Bds, which may lead to code execution, denial of service, or escalation of privileges. | 6.0 | [AV:L/AC:L/PR:H/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:U/C:N/I:H/A:H) |
| CVE‑2022‑42287 | NVIDIA BMC contains a vulnerability in the IPMI handler, where an attacker can upload and download arbitrary files under certain circumstances, which may lead to denial of service, escalation of privileges, information disclosure, or data tampering. | 6.0 | [AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:N) |
| CVE‑2022‑42288 | NVIDIA BMC contains a vulnerability in the IPMI handler, where an unauthorized attacker can use certain oracles to guess a valid BMC username, which may lead to information disclosure. | 5.3 | [AV:N/AC:L/PR:N/UI:N/S:U/C:L/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:N/UI:N/S:U/C:L/I:N/A:N) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA systems affected, firmware versions affected, and the updated version that includes this security update. To protect your system, download and install this firmware update through the [NVIDIA Enterprise Support Portal](https://nvid.nvidia.com/dashboard/).




| \*\*CVE IDs Addressed\*\* | \*\*Hardware Platform\*\* | \*\*System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2022‑42276 CVE‑2022‑42281 CVE‑2022‑42285 CVE‑2022‑42286 | NVIDIA DGX servers | DGX A100 | All SBIOS firmware versions prior to 1.18 | SBIOS Firmware 1.18 |
| CVE‑2022‑42271 CVE‑2022‑42272 CVE‑2022‑42273 CVE‑2022‑42274 CVE‑2022‑42275 CVE‑2022‑42278 CVE‑2022‑42279 CVE‑2022‑42280 CVE‑2022‑42282 CVE‑2022‑42283 CVE‑2022‑42284 CVE‑2022‑42287 CVE‑2022‑42288 CVE‑2022‑42289 CVE‑2022‑42290 | NVIDIA DGX servers | DGX A100 | All BMC firmware versions prior to 00.19.07 | BMC Firmware 00.19.07 |
| CVE‑2022‑42277 | NVIDIA DGX servers | DGX Station A100 | All SBIOS firmware versions prior to 10.16 | SBIOS Firmware 10.16 |


#### Notes:


* To get the updated firmware and SBIOS version listed in the table above, upgrade to the NVIDIA DGX A100 firmware container 22.12.1, or NVIDIA DGX Station A100 firmware container 22.2.1. Firmware updates are available through the NVIDIA Enterprise Support Portal.
* See [Security Updates](#security-updates) for the version to install.
* NVIDIA recommends that all BMC ports be restricted to a dedicated management network with firewall protection. If remote access to the BMC is required, such as for a system hosted at a co-location provider, the BMC should be accessed through a secure method that provides isolation from the Internet, such as through a VPN server.


### Acknowledgements


All the vulnerabilities addressed in this bulletin were discovered by the NVIDIA Offensive Security Research (OSR) team.


### Additional Information


AMI has reported potential security vulnerabilities in some AMI MegaRAC SP-X Baseboard Management Controllers that may allow user enumeration, unauthorized access, or arbitrary code execution. The NVIDIA DGX A100 BMC is affected by the following AMI vulnerabilities and plans to release an update to address them in May 2023.


* [CVE‑2022‑40259](https://nvd.nist.gov/vuln/detail/CVE‑2022‑40259): AMI MegaRAC Redfish Arbitrary Code Execution
* [CVE‑2022‑40242](https://nvd.nist.gov/vuln/detail/CVE‑2022‑40242): MegaRAC Default Credentials Vulnerability
* [CVE‑2022‑2827](https://nvd.nist.gov/vuln/detail/CVE‑2022‑2827): AMI MegaRAC User Enumeration Vulnerability


The NVIDIA DGX-1, DGX-2, DGX Station A100 and DGX Station systems are not vulnerable to these CVEs.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 2.0 | January 10, 2023 | Added CVE IDs omitted from the Security Updates table |
| 1.0 | December 19, 2022 | Initial release |


### Support


If you have any questions about this security bulletin, contact [NVIDIA Support](https://www.nvidia.com/object/support.html).


##### Disclaimer


ALL NVIDIA INFORMATION, DESIGN SPECIFICATIONS, REFERENCE BOARDS, FILES, DRAWINGS, DIAGNOSTICS, LISTS, AND OTHER DOCUMENTS (TOGETHER AND SEPARATELY, “MATERIALS”) ARE BEING PROVIDED “AS IS.” NVIDIA MAKES NO WARRANTIES, EXPRESS, IMPLIED, STATUTORY, OR OTHERWISE WITH RESPECT TO THE MATERIALS, AND ALL EXPRESS OR IMPLIED CONDITIONS, REPRESENTATIONS AND WARRANTIES, INCLUDING ANY IMPLIED WARRANTY OR CONDITION OF TITLE, MERCHANTABILITY, SATISFACTORY QUALITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT, ARE HEREBY EXCLUDED TO THE MAXIMUM EXTENT PERMITTED BY LAW.


Information is believed to be accurate and reliable at the time it is furnished. However, NVIDIA Corporation assumes no responsibility for the consequences of use of such information or for any infringement of patents or other rights of third parties that may result from its use. No license is granted by implication or otherwise under any patent or patent rights of NVIDIA Corporation. Specifications mentioned in this publication are subject to change without notice. This publication supersedes and replaces all information previously supplied. NVIDIA Corporation products are not authorized for use as critical components in life support devices or systems without express written approval of NVIDIA Corporation.










Is this answer helpful?
-----------------------



Yes
No







Answers others found helpful
----------------------------


* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX) - April 2022](/app/answers/detail/a_id/5343/related/1)
* [ NVIDIA Data Plane Development Kit (MLNX\_DPDK) - August 2022](/app/answers/detail/a_id/5389/related/1)
* [Security Notice: NVIDIA Response to OpenSSL Vulnerabilities - November 2022](/app/answers/detail/a_id/5405/related/1)
* [ NVIDIA GPU Display Driver - May 2022](/app/answers/detail/a_id/5353/related/1)
* [ NVIDIA GPU Display Driver - August 2022](/app/answers/detail/a_id/5383/related/1)








