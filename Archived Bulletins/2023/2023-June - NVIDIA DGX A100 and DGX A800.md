# NVIDIA DGX A100 and DGX A800 (Bulletin ID: 5461)



 NVIDIA DGX A100 and DGX A800 - June 2023
===========================================================




 Updated 07/14/2023 11:34 AM



NVIDIA has released a firmware security update for the NVIDIA DGX™ A100 system and the NVIDIA DGX A800 system. This update addresses issues that may lead to code execution, denial of service, data tampering, escalation of privileges, and information disclosure.


To protect your system, download and install this firmware update through the [NVIDIA Enterprise Support Portal](https://nvid.nvidia.com/dashboard/).


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2023‑25521 | The NVIDIA DGX A100 and A800 systems contain a vulnerability in SBIOS, where improper validation of an input parameter may lead to code execution, escalation of privileges, denial of service, information disclosure, and data tampering. | 7.5 | [CWE-250](https://cwe.mitre.org/data/definitions/250.html) [AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H&version=3.1) |
| CVE‑2023‑25522 | The NVIDIA DGX A100 and A800 systems contain a vulnerability in SBIOS, where information that is provided in an unexpected format may cause improper validation of an input parameter, which may lead to denial of service, information disclosure, and data tampering. | 7.5 | [CWE-20](https://cwe.mitre.org/data/definitions/20.html) [AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H&version=3.1) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following tables list the NVIDIA systems affected, firmware versions affected, and the updated version that includes this security update.


To protect your system, download and install this firmware update through the [NVIDIA Enterprise Support Portal](https://nvid.nvidia.com/dashboard/).


**Note:** To get the updated BMC and SBIOS versions listed in the tables, upgrade to the NVIDIA DGX A100 Firmware Update Container Version 23.06.3. Firmware updates are available through the NVIDIA Enterprise Support Portal.


#### Security Advisory CVE IDs Addressed by NVIDIA




| \*\*CVE IDs Addressed\*\* | \*\*Hardware Platform\*\* | \*\*System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2023‑25521 | NVIDIA DGX | NVIDIA DGX A100 NVIDIA DGX A800 | All SBIOS versions prior to 1.21 | 1.21 |
| CVE‑2023‑25522 | NVIDIA DGX | NVIDIA DGX A100 NVIDIA DGX A800 | All SBIOS versions prior to 1.21 | 1.21 |


#### Security Advisory CVE IDs Addressed by AMI




| \*\*CVE IDs Addressed\*\* | \*\*Hardware Platform\*\* | \*\*System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2022‑26872 CVE‑2022‑40259 CVE‑2022‑2827 CVE‑2022‑40242 | NVIDIA DGX | NVIDIA DGX A100 NVIDIA DGX A800 | All BMC versions prior to 00.20.04 | 00.20.04 |
| CVE‑2021‑26316 CVE‑2021‑39298 CVE‑2021‑26402 CVE‑2022‑23813 CVE‑2022‑23814 CVE‑2021‑26328 | NVIDIA DGX | NVIDIA DGX A100 NVIDIA DGX A800 | All SBIOS versions prior to 1.21 | 1.21 |


### Security Vulnerabilities Reported by AMI


The following table lists potential security vulnerabilities in some AMI MegaRAC SP-X baseboard management controllers that have been reported by AMI. These vulnerabilities may allow user enumeration, unauthorized access, or arbitrary code execution. The NVIDIA DGX-1, NVIDIA DGX-2, NVIDIA DGX Station, and NVIDIA DGX Station A100 systems are not vulnerable to these issues.




| \*\*CVE ID\*\* | \*\*Severity\*\* | \*\*Vendor\*\* |
| --- | --- | --- |
| [CVE‑2022‑40259](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-40259) | Critical | AMI |
| [CVE‑2022‑26872](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-26872) | High | AMI |
| [CVE‑2022‑2827](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-2827) | High | AMI |
| [CVE‑2021‑26316](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-26316) | High | AMI |
| [CVE‑2021‑39298](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-39298) | High | AMI |
| [CVE‑2021‑26402](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-26402) | High | AMI |
| [CVE‑2022‑40242](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-40242) | Medium | AMI |
| [CVE‑2022‑23813](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-23813) | Medium | AMI |
| [CVE‑2022‑23814](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-23814) | Medium | AMI |
| [CVE‑2021‑26328](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-26328) | Medium | AMI |


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.1 | July 14, 2023 | Updated broken CVE hyperlinks to the security vulnerabilties reported by AMI. |
| 1.0 | June 30, 2023 | Initial release |


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


* [ NVIDIA DGX-1 and NVIDIA DGX-2 Systems - July 2021](/app/answers/detail/a_id/5213/related/1)
* [ NVIDIA GeForce Experience - January 2023](/app/answers/detail/a_id/5384/related/1)
* [ NVIDIA CUDA Toolkit - March 2023](/app/answers/detail/a_id/5446/related/1)
* [ NVIDIA GeForce Experience - February 2021](/app/answers/detail/a_id/5155/related/1)
* [ NVIDIA GeForce Experience - June 2021](/app/answers/detail/a_id/5199/related/1)








