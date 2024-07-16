# NVIDIA Data Center GPU Manager (DCGM) (Bulletin ID: 5328)



 NVIDIA Data Center GPU Manager (DCGM) - March 2022
=====================================================================




 Updated 03/23/2022 10:44 AM



NVIDIA has released a software update for NVIDIA® Data Center GPU Manager (DCGM). The update addresses security issues that may lead to code execution, denial of service, and escalation of privileges. To protect your system, [download and install the latest DCGM release from the CUDA repositories](https://developer.nvidia.com/dcgm#Downloads).


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/v3.1/user-guide) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑21820 | NVIDIA DCGM contains a vulnerability in `nvhostengine`, where a network user can cause detection of error conditions without action, which may lead to limited code execution, some denial of service, escalation of privileges, and limited impacts to both data confidentiality and integrity. | 6.3 | [AV:N/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Versions\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2022‑21820 | DCGM | Linux | All versions prior to 2.3.4 | 2.3.4 and 2.3.5 (latest) |


#### Notes


* Earlier software releases that support this product are also affected. If you are using an earlier release, upgrade to the latest release.


### Mitigations


None. See [Security Updates](#security-updates) for the version to install.


### Acknowledgements


NVIDIA thanks Jeremy Brown for reporting this issue.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 2.0 | March 23, 2022 | Updated the CVSS score, vector, and Security Updates table |
| 1.0 | March 17, 2022 | Initial release |


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


* [ NVIDIA Omniverse Launcher - January 2022](/app/answers/detail/a_id/5318/related/1)
* [ NVIDIA SHIELD TV - January 2022](/app/answers/detail/a_id/5259/related/1)
* [ NVIDIA GeForce Experience - December 2021](/app/answers/detail/a_id/5295/related/1)
* [ NVIDIA License System - February 2022](/app/answers/detail/a_id/5319/related/1)
* [Security Notice: NVIDIA Response to Log4j Vulnerabilities - December 2021](/app/answers/detail/a_id/5294/related/1)








