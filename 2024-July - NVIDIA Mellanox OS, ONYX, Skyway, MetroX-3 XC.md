# NVIDIA Mellanox OS, ONYX, Skyway, MetroX-3 XC (Bulletin ID: 5559)



 NVIDIA Mellanox OS, ONYX, Skyway, MetroX-3 XC - July 2024
============================================================================




 Updated 07/23/2024 10:13 AM



NVIDIA has released a firmware update for NVIDIA Mellanox OS, ONYX, Skyway, and MetroX-3 XC. To protect your system, download and install this firmware update from the [NVIDIA Enterprise Support Portal](https://enterprise-support.nvidia.com/s/).


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards. 





| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Vector\*\* | \*\*Base Score\*\* | \*\*Severity\*\* | \*\*CWE\*\* | \*\*Impacts\*\* |
| --- | --- | --- | --- | --- | --- | --- |
| CVE-2024-0101 | NVIDIA Mellanox OS, ONYX, Skyway, MetroX-2 and MetroX-3 XC contain a vulnerability in ipfilter, where improper ipfilter definitions could enable an attacker to cause a failure by attacking the switch. A successful exploit of this vulnerability might lead to denial of service. | [AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H&version=3.1) | 7.5 | High | [CWE‑693](https://cwe.mitre.org/data/definitions/693.html) | Denial of service |
| CVE-2024-0104 | NVIDIA Mellanox OS, ONYX, Skyway, MetroX-2 and MetroX-3 XC contain a vulnerability in the LDAP AAA component, where a user can cause improper access. A successful exploit of this vulnerability might lead to information disclosure, data tampering, and escalation of privileges. | [AV:N/AC:H/PR:L/UI:N/S:U/C:L/I:L/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:H/PR:L/UI:N/S:U/C:L/I:L/A:N&version=3.1) | 4.2 | Medium | [CWE‑284](https://cwe.mitre.org/data/definitions/284.html) | Information disclosure, data tampering, escalation of privileges |



The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA products affected, versions affected, and the updated version that includes this security update.











| \*\*CVE IDs Addressed\*\* | \*\*Affected Products\*\* | \*\*Platform or OS\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2024-0101 | Mellanox OS | Mellanox OS | All versions prior to and including 3.11.1000 | 3.11.2002 |
| ONYX | ONYX LTS | All versions prior to and including 3.10.4300 | 3.10.4402 |
| Skyway | Skyway | All versions prior to and including 8.2.1000 | 8.2.2000 |
| Skyway LTS | All versions prior to and including 8.1.4300 | 8.1.4400 |
| MetroX-3 XC | MetroX | All versions prior to and including 18.2.1000 | 18.2.2000 |
| MetroX-2 | MetroX | All versions prior to and including 3.11.1000 | 3.11.2002 |
| CVE‑2024-0104 | Mellanox OS | Mellanox OS LTS | All versions prior to and including 3.11.2100 | 3.11.2202 |
| ONYX | ONYX LTS | All versions prior to and including 3.10.4302 | 3.10.4402 |
| Skyway | Skyway | All versions prior to and including 8.2.2100 | 8.2.2202 |
| MetroX-3 XC | MetroX | All versions prior to and including 18.2.2100 | 18.2.2200 |
| MetroX-2 | MetroX | All versions prior to and including 3.11.1000 | 3.11.2002 |



### Notes


* Earlier software releases of this product are also affected. If you are using an earlier release, upgrade to the latest release version.


### Get the Most Up-to-Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History









| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | July 23 2024 | Initial release |



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


* [ NVIDIA GeForce NOW for Android - August 2023](/app/answers/detail/a_id/5476/related/1)
* [ NVIDIA License System - February 2022](/app/answers/detail/a_id/5319/related/1)
* [ NVIDIA GPU Display Driver - October 2021](/app/answers/detail/a_id/5230/related/1)
* [ NVIDIA SHIELD TV - January 2021](/app/answers/detail/a_id/5148/related/1)
* [ NVIDIA DGX-1 and NVIDIA DGX-2 Systems - July 2021](/app/answers/detail/a_id/5213/related/1)








