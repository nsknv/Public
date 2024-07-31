# NVIDIA BlueField 2 and 3 BMC (Bulletin ID: 5511)



 NVIDIA BlueField 2 and 3 BMC - January 2024
==============================================================




 Updated 01/22/2024 08:11 PM



NVIDIA has released a firmware update for NVIDIA BlueField DPU Baseboard Management Controller (BMC).


To protect your system, download and install this firmware update from the [NVIDIA DOCA Software Framework](https://developer.nvidia.com/networking/doca) page.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Vector\*\* | \*\*Base Score\*\* | \*\*Severity\*\* | CWE | Impacts |
| --- | --- | --- | --- | --- | --- | --- |
| CVE‑2023‑31037 | NVIDIA Bluefield 2 and Bluefield 3 DPU BMC contains a vulnerability in `ipmitool`, where a root user may cause code injection by a network call. A successful exploit of this vulnerability may lead to code execution on the OS. | [AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H) | 7.2 | High | [CWE‑94](https://cwe.mitre.org/data/definitions/94.html) | Code execution |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA products affected, versions affected, and the updated version that includes this security update.




| \*\*CVE IDs Addressed\*\* | \*\*Affected Product(s)\*\* | \*\*Platform/OS\*\* | \*\*Affected Version(s)\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2023‑31037 | Bluefield 2 DPU BMC, BlueField 3 DPU BMC | BMC software | LTS:2.8.2-46 23.04 23.07 23.09 | LTS: 2.8.2-51 23.10 |


### Acknowledgements


NVIDIA thanks HaoKun Yang for reporting issue CVE‑2023‑31037.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | January 23, 2024 | Initial release |


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
* [ NVIDIA GeForce NOW for Android - August 2023](/app/answers/detail/a_id/5476/related/1)
* [ NVIDIA DGX A100 and DGX A800 - June 2023](/app/answers/detail/a_id/5461/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) - June 2023](/app/answers/detail/a_id/5466/related/1)
* [ NVIDIA GPU Display Driver - March 2023](/app/answers/detail/a_id/5452/related/1)








