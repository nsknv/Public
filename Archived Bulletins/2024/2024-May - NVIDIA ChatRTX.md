# NVIDIA ChatRTX (Bulletin ID: 5533)



 NVIDIA ChatRTX - May 2024
============================================




 Updated 05/09/2024 03:15 PM



NVIDIA has released a software update for NVIDIA® ChatRTX. To protect your system, download and install this software update from the [ChatRTX Download](https://www.nvidia.com/en-us/ai-on-rtx/chatrtx/) page.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Vector\*\* | \*\*Base Score\*\* | \*\*Severity\*\* | \*\*CWE\*\* | \*\*Impacts\*\* |
| --- | --- | --- | --- | --- | --- | --- |
| CVE-2024-0096 | NVIDIA ChatRTX for Windows contains a vulnerability in Chat RTX UI, where a user can cause an improper privilege management issue by sending user inputs to change execution flow. A successful exploit of this vulnerability might lead to information disclosure, escalation of privileges, and data tampering. | [AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:N&version=3.1) | 7.5 | High | [CWE-269](https://cwe.mitre.org/data/definitions/269.html) | Information disclosure, escalation of privileges, data tampering |
| CVE-2024-0097 | NVIDIA ChatRTX for Windows contains a vulnerability in ChatRTX UI, where a user can cause an improper privilege management issue by exploiting interprocess communication between different processes. A successful exploit of this vulnerability might lead to information disclosure, escalation of privileges, and data tampering. | [AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:N&version=3.1) | 7.5 | High | [CWE-269](https://cwe.mitre.org/data/definitions/269.html) | Information disclosure, escalation of privileges, data tampering |
| CVE-2024-0098 | NVIDIA ChatRTX for Windows contains a vulnerability in the ChatRTX UI and backend, where a user can cause a clear-text transmission of sensitive information issue by data sniffing. A successful exploit of this vulnerability might lead to information disclosure. | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N&version=3.1) | 5.5 | Medium | [CWE-319](https://cwe.mitre.org/data/definitions/319.html) | Information disclosure |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA products affected, versions affected, and the updated version that includes this security update.


Download the update from the [ChatRTX Download](https://www.nvidia.com/en-us/ai-on-rtx/chatrtx/) page to apply the security update.




| \*\*CVE IDs Addressed\*\* | \*\*Affected Products\*\* | \*\*Platform or OS\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE-2024-0096 CVE-2024-0097 CVE-2024-0098 | ChatRTX | Windows | All versions prior to and including 0.2.1 | NVIDIA ChatRTX 0.3 |


### Notes


* Earlier software releases of this product are also affected. If you are using an earlier release, upgrade to the latest release version.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | May 1, 2024 | Initial release |


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


* [ NVIDIA GPU Display Driver - October 2023](/app/answers/detail/a_id/5491/related/1)
* [ NVIDIA GeForce NOW - September 2020](/app/answers/detail/a_id/5052/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) - June 2023](/app/answers/detail/a_id/5466/related/1)
* [ NVIDIA GeForce Experience - December 2021](/app/answers/detail/a_id/5295/related/1)
* [ NVIDIA GPU Display Driver - September 2020](/app/answers/detail/a_id/5075/related/1)








