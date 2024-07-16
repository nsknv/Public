# NVIDIA CUDA Toolkit (Bulletin ID: 5094)



 NVIDIA CUDA Toolkit - October 2020
=====================================================




 Updated 10/05/2021 11:37 AM



NVIDIA has released a software update for NVIDIA® CUDA® Toolkit software. This update addresses security issues that may lead to code execution, denial of service, or information disclosure.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


To protect your system, download and install this software update from the [CUDA Toolkit Downloads page](https://developer.nvidia.com/cuda-toolkit)
---------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security.](https://www.nvidia.com/security/)
------------------------------------------------------------------






---




### Details


This section provides a summary of potential vulnerabilities and their impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/v3.1/user-guide) standards.




This section provides a summary of potential vulnerabilities and their impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/v3.1/user-guide) standards.
| \*\*CVE IDs\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2020‑5991 | NVIDIA CUDA Toolkit contains a vulnerability in the NVJPEG library in which an out-of-bounds read or write operation may lead to code execution, denial of service, or information disclosure. | 6.6 | [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.


Download the updates from the [CUDA Toolkit Downloads](https://developer.nvidia.com/cuda-toolkit) page to apply the security update.




The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.
| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2020‑5991 | CUDA Toolkit | Windows | All versions prior to CUDA Toolkit 11.1.1 | CUDA Toolkit 11.1.1 |


### Mitigations


See [Security Updates](#security-updates) for the version to install.


### Acknowledgements


NVIDIA thanks the following individuals for reporting the issue:


* CVE‑2020‑5991: Weidang Peng of Qihoo 360 AIVUL Team


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
| 1.0 | October 29, 2020 | Initial release |


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


* [ NVIDIA GPU Display Driver - June 2020](/app/answers/detail/a_id/5031/related/1)
* [ NVIDIA GPU Display Driver - February 2020](/app/answers/detail/a_id/4996/related/1)
* [ NVIDIA Jetson AGX Xavier, TX1, TX2, and Nano L4T - July 2020](/app/answers/detail/a_id/5039/related/1)
* [ NVIDIA GeForce Experience - July 2020](/app/answers/detail/a_id/5038/related/1)
* [Security Notice: NVIDIA Response to Ripple20 - June 2020](/app/answers/detail/a_id/5033/related/1)








