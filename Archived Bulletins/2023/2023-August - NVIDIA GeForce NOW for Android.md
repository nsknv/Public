# NVIDIA GeForce NOW for Android (Bulletin ID: 5476)



 NVIDIA GeForce NOW for Android - August 2023
===============================================================




 Updated 08/28/2023 10:18 AM




NVIDIA has released a firmware security update for the NVIDIA GeForce NOW Android mobile and TV app. This update addresses issues that may lead to code execution, denial of service, and information disclosure. To protect customer systems, the NVIDIA GeForce NOW for Android app will prompt customers to download and install the latest version upon opening the application.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).







---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector and CWE\*\* |
| --- | --- | --- | --- |
| CVE‑2023‑31014 | NVIDIA GeForce Now for Android contains a vulnerability in the game launcher component, where a malicious application on the same device can process the implicit intent meant for the streamer component. A successful exploit of this vulnerability may lead to limited information disclosure, denial of service, and code execution. | 4.2 | [AV:L/AC:H/PR:L/UI:R/S:U/C:L/I:L/A:](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:A/AC:L/PR:H/UI:N/S:U/C:L/I:H/A:N)[L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:R/S:U/C:L/I:L/A:L) [CWE-927](https://cwe.mitre.org/data/definitions/927.html) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following tables list the NVIDIA systems affected, firmware versions affected, and the updated version that includes this security update.


To protect your system, download and install this firmware update through the [NVIDIA Enterprise Support Portal](https://nvid.nvidia.com/dashboard/).




| \*\*CVE IDs Addressed\*\* | Affected Product | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2023‑31014 | GeForce NOW for Android mobile and TV app | Android OS | 6.00.32705137 to 6.04.33108832 | 6.05.33200069 |


### Acknowledgements


NVIDIA thanks Oversecured for reporting issue CVE-2023-31014.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | August 28, 2023 | Initial release |


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


* [ NVIDIA DCGM - August 2021](/app/answers/detail/a_id/5219/related/1)
* [ NVIDIA GeForce Experience - April 2021](/app/answers/detail/a_id/5184/related/1)
* [ NVIDIA GeForce Experience - February 2021](/app/answers/detail/a_id/5155/related/1)
* [ NVIDIA GeForce Experience - July 2020](/app/answers/detail/a_id/5038/related/1)
* [ NVIDIA GeForce NOW - November 2020](/app/answers/detail/a_id/5096/related/1)








