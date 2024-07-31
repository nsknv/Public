# NVIDIA SHIELD TV (Bulletin ID: 5148)



 NVIDIA SHIELD TV - January 2021
==================================================




 Updated 10/05/2021 01:45 PM



NVIDIA has released a software security update for NVIDIA SHIELD® TV. This update addresses issues that may lead to denial of service, escalation of privileges, or data loss. To protect your system, download and install this software update through the update notification that will appear on the Home Screen or by going to Settings>About>System update.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).
------------------------------------------------------------------






---




### Details


This section summarizes the potential impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS V3.1](https://www.first.org/cvss/user-guide) standards.




This section summarizes the potential impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS V3.1](https://www.first.org/cvss/user-guide) standards.
| \*\*CVE IDs\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2021‑1068 | NVIDIA SHIELD TV contains a vulnerability in the NVDEC component, in which an attacker can read from or write to a memory location that is outside the intended boundary of the buffer, which may lead to denial of service or escalation of privileges. | 7.8 | [AV:L/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1069 | NVIDIA SHIELD TV contains a vulnerability in the `NVHost` function, which may lead to abnormal reboot due to a null pointer reference, causing data loss. | 6.1 | [AV:L/AC:L/PR:N/UI:N/S:U/C:N/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:N/I:L/A:H) |
| CVE‑2021‑1067 | NVIDIA SHIELD TV contains a vulnerability in the implementation of the RPMB command status, in which an attacker can write to the Write Protect Configuration Block, which may lead to denial of service or escalation of privileges. | 5.7 | [AV:P/AC:L/PR:N/UI:N/S:U/C:L/I:H/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:P/AC:L/PR:N/UI:N/S:U/C:L/I:H/A:L) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version available that includes this security update. Download the updates through **Settings**>**About**>**System update**.




The following table lists the NVIDIA software products affected, versions affected, and the updated version available that includes this security update. Download the updates through \*\*Settings\*\*>\*\*About\*\*>\*\*System update\*\*.
| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- |
| SHIELD TV | Android-P | Shield Experience prior to 8.2.2 | Shield Experience Upgrade 8.2.2 |


**Note:**


* SHIELD TV upgrade version 8.2.2 includes the Android™ Security Patch level 2020-12-05. For more information about what is included in Android security patch levels, refer to the [Android Security Bulletins](https://source.android.com/security/bulletin).
* Earlier releases of this product are also affected. If you are using an earlier release, upgrade to the latest release.


### Mitigations


None. See [Security Updates](#security-updates) for the version to install.


### Acknowledgements


NVIDIA thanks following individuals for reporting the issues.


* CVE‑2021‑1067 - Rotem Sela and Brian Mastenbrook of Western Digital
* CVE‑2021‑1068 - NVIDIA Product Security Team
* CVE‑2021‑1069 - Billy Laws


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
| 1.0 | January 19, 2021 | Initial release |


### Support


If you have any questions about this Security Bulletin, contact [NVIDIA Support](https://www.nvidia.com/object/support.html).


##### Disclaimer


ALL NVIDIA INFORMATION, DESIGN SPECIFICATIONS, REFERENCE BOARDS, FILES, DRAWINGS, DIAGNOSTICS, LISTS, AND OTHER DOCUMENTS (TOGETHER AND SEPARATELY, “MATERIALS”) ARE BEING PROVIDED “AS IS.” NVIDIA MAKES NO WARRANTIES, EXPRESS, IMPLIED, STATUTORY, OR OTHERWISE WITH RESPECT TO THE MATERIALS, AND ALL EXPRESS OR IMPLIED CONDITIONS, REPRESENTATIONS AND WARRANTIES, INCLUDING ANY IMPLIED WARRANTY OR CONDITION OF TITLE, MERCHANTABILITY, SATISFACTORY QUALITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT, ARE HEREBY EXCLUDED TO THE MAXIMUM EXTENT PERMITTED BY LAW.


Information is believed to be accurate and reliable at the time it is furnished. However, NVIDIA Corporation assumes no responsibility for the consequences of use of such information or for any infringement of patents or other rights of third parties that may result from its use. No license is granted by implication or otherwise under any patent or patent rights of NVIDIA Corporation. Specifications mentioned in this publication are subject to change without notice. This publication supersedes and replaces all information previously supplied. NVIDIA Corporation products are not authorized for use as critical components in life support devices or systems without express written approval of NVIDIA Corporation.










Is this answer helpful?
-----------------------



Yes
No







Answers others found helpful
----------------------------


* [ NVIDIA GeForce Experience - October 2020](/app/answers/detail/a_id/5076/related/1)
* [ NVIDIA GeForce Experience - July 2020](/app/answers/detail/a_id/5038/related/1)
* [ NVIDIA GeForce Experience - December 2019](/app/answers/detail/a_id/4954/related/1)
* [ NVIDIA GeForce Experience – March 2019](/app/answers/detail/a_id/4784/related/1)
* [ NVIDIA GeForce Experience - November 2018](/app/answers/detail/a_id/4740/related/1)








