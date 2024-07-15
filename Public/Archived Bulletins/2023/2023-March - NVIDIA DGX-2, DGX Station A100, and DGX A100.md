# NVIDIA DGX-2, DGX Station A100, and DGX A100 (Bulletin ID: 5449)



 NVIDIA DGX-2, DGX Station A100, and DGX A100 - March 2023
============================================================================




 Updated 03/23/2023 09:05 AM



NVIDIA has released a firmware security update for the NVIDIA DGX-2™ server, DGX A100 server, and DGX Station A100. This update addresses issues that may lead to code execution, denial of service, escalation of privileges, loss of data integrity, information disclosure, or data tampering.


To protect your system, download and install this firmware update through the [NVIDIA Enterprise Support Portal](https://nvid.nvidia.com/dashboard/).


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑42274 | NVIDIA BMC contains a vulnerability in the IPMI handler, where an attacker with the required privileges can cause a buffer overflow, which may lead to denial of service or code execution. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42280 | NVIDIA BMC contains a vulnerability in the SPX REST authorization handler, where an unauthorized user can exploit a path traversal, which may lead to escalation of privileges. | 7.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N) |
| CVE‑2022‑42282 | NVIDIA BMC contains a vulnerability in the SPX REST API, where an attacker with the required privileges can access arbitrary files, which may lead to information disclosure. | 6.5 | [AV:N/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N) |
| CVE‑2022‑42283 | NVIDIA BMC contains a vulnerability in the IPMI handler, where an attacker with the required privileges can cause a buffer overflow, which may lead to denial of service or code execution. | 6.4 | [AV:L/AC:H/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42286 | NVIDIA DGX-2 SBIOS contains a vulnerability in Bds, which may lead to code execution, denial of service, or escalation of privileges. | 6.0 | [AV:L/AC:L/PR:H/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:U/C:N/I:H/A:H) |
| CVE‑2022‑42287 | NVIDIA BMC contains a vulnerability in the IPMI handler, where an attacker can upload and download arbitrary files under certain circumstances, which may lead to denial of service, escalation of privileges, information disclosure, or data tampering. | 6.0 | [AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:N) |
| CVE‑2022‑42289 | NVIDIA BMC contains a vulnerability in the SPX REST API, where an attacker with the required privileges can inject arbitrary shell commands, which may lead to code execution, denial of service, information disclosure, or data tampering. | 7.2 | [AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42290 | NVIDIA BMC contains a vulnerability in the SPX REST API, where an attacker with the required privileges can inject arbitrary shell commands, which may lead to code execution, denial of service, information disclosure, or data tampering. | 7.2 | [AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2023‑0200 | NVIDIA DGX-2 contains a vulnerability in OFBD where a user with high privileges and a pre-conditioned heap can cause an access beyond a buffers end, which may lead to code execution, escalation of privileges, denial of service, and information disclosure. | 7.5 | [AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2023‑0201 | NVIDIA DGX-2 SBIOS contains a vulnerability in Bds, where a user with high privileges can cause a write beyond the bounds of an indexable resource, which may lead to code execution, denial of service, compromised integrity, and information disclosure. | 6.7 | [AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2023‑0202 | NVIDIA DGX A100 SBIOS contains a vulnerability where an attacker may modify arbitrary memory of SMRAM by exploiting the `GenericSio` and `LegacySmmSredir` SMM APIs. A successful exploit of this vulnerability may lead to denial of service, escalation of privileges, and information disclosure. | 7.5 | [AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2023‑0206 | NVIDIA DGX A100 SBIOS contains a vulnerability where an attacker may modify arbitrary memory of SMRAM by exploiting the NVME SMM API. A successful exploit of this vulnerability may lead to denial of service, escalation of privileges, and information disclosure. | 7.5 | [AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2023‑0207 | NVIDIA DGX-2 SBIOS contains a vulnerability where an attacker may modify the ServerSetup NVRAM variable at runtime by executing privileged code. A successful exploit of this vulnerability may lead to denial of service. | 7.5 | [AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.


To protect your system, download and install this firmware update through the [NVIDIA Enterprise Support Portal](https://nvid.nvidia.com/dashboard/).




| \*\*CVE IDs Addressed\*\* | \*\*Hardware Platform\*\* | \*\*System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* | \*\*Firmware Container\*\* |
| --- | --- | --- | --- | --- | --- |
| CVE‑2022‑42274 CVE‑2022‑42280 CVE‑2022‑42282 CVE‑2022‑42283 CVE‑2022‑42287 CVE‑2023‑0200 CVE‑2023‑0201 | DGX-2 | DGX-2 | All BMC versions prior to 1.08.00 | 01.08.00 | 23.3.1 |
| CVE‑2022‑42286 CVE‑2022‑42289 CVE‑2022‑42290 CVE‑2023‑0207 | DGX-2 | DGX-2 | All SBIOS versions prior to 0.33 | 0.33 | 23.3.1 |
| CVE‑2023‑0202 CVE‑2023‑0206 | DGX A100 | DGX A100 | All SBIOS versions prior to 1.18 | 1.18 | 22.12.1 |
| \*\*AMI Security Advisory CVEs Addressed\*\* | | | | | |
| CVE‑2022‑40259 CVE‑2022‑40242 CVE‑2022‑2827 | DGX Station A100 | DGX Station A100 | All BMC versions prior to 2.01.00 | 2.01.00 | 23.3.1 |


### Additional Information


#### Security Vulnerabilities Reported by AMI


The following table lists potential security vulnerabilities in some AMI MegaRAC SP-X Baseboard Management Controllers that have been reported by AMI. These vulnerabilities may allow user enumeration, unauthorized access, or arbitrary code execution.




| \*\*CVE ID\*\* | \*\*Severity\*\* | \*\*Summary\*\* |
| --- | --- | --- |
| [CVE‑2022‑40259](https://nvd.nist.gov/vuln/detail/CVE‑2022‑40259) | Critical | AMI MegaRAC Redfish Arbitrary Code Execution |
| [CVE‑2022‑40242](https://nvd.nist.gov/vuln/detail/CVE‑2022‑40242) | High | MegaRAC Default Credentials Vulnerability |
| [CVE‑2022‑2827](https://nvd.nist.gov/vuln/detail/CVE‑2022‑2827) | High | AMI MegaRAC User Enumeration Vulnerability |


The following table lists the status of the NVIDIA response to these vulnerabilities for each NVIDIA DGX system.




| \*\*System\*\* | \*\*Status\*\* |
| --- | --- |
| DGX-1 | Not vulnerable - no response required |
| DGX-2 | Not vulnerable - no response required |
| DGX A100 | To be addressed in May 2023 as stated in [NVIDIA DGX A100 Server and DGX Station A100 - December 2022](https://nvidia.custhelp.com/app/answers/detail/a\_id/5435) |
| DGX Station | Not vulnerable - no response required |
| DGX Station A100 | Addressed in this update |


#### Security Vulnerabilities Reported by Intel


The following table lists potential security vulnerabilities in some Intel Processors that have been reported by Intel. These vulnerabilities may allow escalation of privileges or denial of service. They are addressed in DGX-2 SBIOS release version 0.33.




| \*\*CVE ID\*\* | \*\*Severity\*\* | \*\*Summary\*\* |
| --- | --- | --- |
| [CVE‑2020‑12357](https://nvd.nist.gov/vuln/detail/CVE‑2020‑12357) | High | Intel(R) Processors Privilege Escalation Vulnerability |
| [CVE‑2020‑8670](https://nvd.nist.gov/vuln/detail/CVE‑2020‑8670) | High | Intel(R) Processors Privilege Escalation Vulnerability |
| [CVE‑2020‑8700](https://nvd.nist.gov/vuln/detail/CVE‑2020‑8700) | High | Intel(R) Processors Privilege Escalation Vulnerability |
| [CVE‑2020‑12359](https://nvd.nist.gov/vuln/detail/CVE‑2020‑12359) | High | Intel(R) Processors Privilege Escalation Vulnerability |
| [CVE‑2020‑12358](https://nvd.nist.gov/vuln/detail/CVE‑2020‑12358) | Medium | Intel(R) Processors Denial of Service Vulnerability |
| [CVE‑2021‑0095](https://nvd.nist.gov/vuln/detail/CVE‑2021‑0095) | Medium | Intel(R) Processors Denial of Service Vulnerability |
| [CVE‑2020‑12360](https://nvd.nist.gov/vuln/detail/CVE‑2020‑12360) | Medium | Intel(R) Processors Privilege Escalation Vulnerability |
| [CVE‑2020‑24486](https://nvd.nist.gov/vuln/detail/CVE‑2020‑24486) | Medium | Intel(R) Processors Denial of Service Vulnerability |


### Acknowledgements


CVE‑2022‑42274, CVE‑2022‑42280, CVE‑2022‑42282, CVE‑2022‑42283, CVE‑2022‑42286, CVE‑2022‑42287, CVE‑2022‑42289, CVE‑2022‑42290: The NVIDIA Offensive Security Research (OSR) team reported these issues.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | March 23, 2023 | Initial release |


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


* [Security Notice: NVIDIA Response to OpenSSL Vulnerabilities - November 2022](/app/answers/detail/a_id/5405/related/1)
* [ NVIDIA Omniverse Kit - January 2023](/app/answers/detail/a_id/5418/related/1)
* [ NVIDIA Data Plane Development Kit (MLNX\_DPDK) - August 2022](/app/answers/detail/a_id/5389/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson AGX Orin Series - January 2023](/app/answers/detail/a_id/5442/related/1)
* [ NVIDIA GPU Display Driver - August 2022](/app/answers/detail/a_id/5383/related/1)








