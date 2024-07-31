# NVIDIA DCGM (Bulletin ID: 5219)



 NVIDIA DCGM - August 2021
============================================




 Updated 10/05/2021 02:18 PM



NVIDIA has released a software update for NVIDIA® Data Center GPU Manager (DCGM). The update addresses security issues that may lead to privilege escalation, total loss of confidentiality and integrity, and complete denial of service. To protect your system, [download and install the latest DCGM release from the CUDA repositories](https://developer.nvidia.com/dcgm#Downloads).
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).
------------------------------------------------------------------






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/v3.1/user-guide) standards.




This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/v3.1/user-guide) standards.
| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2021‑34398 | NVIDIA DCGM contains a vulnerability in the DIAG module where any user can inject shared libraries into the DCGM server, which is usually running as root, which may lead to privilege escalation, total loss of confidentiality and integrity, and complete denial of service | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=(AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H)) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration. 


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. 





The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. 
| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2021‑34398 | DCGM | Linux | DCGM versions up to and including 2.2.8 | DCGM 2.2.9 |



#### Notes


* Earlier software branch releases that support this product are also affected. If you are using an earlier branch release, upgrade to the latest branch release.


### Mitigations


See [Security Updates](#security-updates) for the version to install.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History




Revision History





| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | August 6, 2021 | Initial release |


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


* [ NVIDIA GeForce Experience - June 2021](/app/answers/detail/a_id/5199/related/1)
* [ NVIDIA GeForce Experience - April 2021](/app/answers/detail/a_id/5184/related/1)
* [ NVIDIA GeForce Experience - February 2021](/app/answers/detail/a_id/5155/related/1)
* [ NVIDIA GeForce NOW - November 2020](/app/answers/detail/a_id/5096/related/1)
* [ NVIDIA GeForce Experience - July 2020](/app/answers/detail/a_id/5038/related/1)








