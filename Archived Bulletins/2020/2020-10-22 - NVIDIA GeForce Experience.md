# NVIDIA GeForce Experience (Bulletin ID: 5076)



 NVIDIA GeForce Experience - October 2020
===========================================================




 Updated 10/05/2021 11:33 AM



NVIDIA has released a software security update for NVIDIA® GeForce Experience™ software. This update addresses issues that may lead to denial of service, escalation of privileges, code execution, or information disclosure.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


To protect your system, download and install this software update from the [GeForce Experience Downloads](https://www.geforce.com/geforce-experience/download) page or open the client to automatically apply the security update.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


>Go to [NVIDIA Product Security.](https://www.nvidia.com/security/)
-------------------------------------------------------------------






---




### Details


This section provides a summary of potential vulnerabilities and their impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/v3.1/user-guide) standards.




This section provides a summary of potential vulnerabilities and their impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/v3.1/user-guide) standards.
| \*\*CVE IDs\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2020‑5977 | NVIDIA GeForce Experience contains a vulnerability in NVIDIA Web Helper NodeJS Web Server in which an uncontrolled search path is used to load a node module, which may lead to code execution, denial of service, escalation of privileges, and information disclosure. | 8.2 | [AV:L/AC:L/PR:L/UI:R/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:R/S:C/C:H/I:H/A:H) |
| CVE‑2020‑5990 | NVIDIA GeForce Experience contains a vulnerability in the ShadowPlay component which may lead to local privilege escalation, code execution, denial of service or information disclosure. | 7.3 | [AV:L/AC:L/PR:L/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:R/S:U/C:H/I:H/A:H) |
| CVE‑2020‑5978 | NVIDIA GeForce Experience contains a vulnerability in its services in which a folder is created by `nvcontainer.exe` under normal user login with `LOCAL\_SYSTEM` privileges which may lead to a denial of service or escalation of privileges. | 3.2 | [AV:L/AC:L/PR:L/UI:R/S:C/C:N/I:N/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:R/S:C/C:N/I:N/A:L) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.


Download the updates from the [GeForce Experience Downloads](https://www.geforce.com/geforce-experience/download) page or open the client to automatically apply the security update.




The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.
| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2020‑5977 CVE‑2020‑5978 CVE‑2020‑5990 | GeForce Experience | Windows | All versions prior to 3.20.5.70 | 3.20.5.70 |


### Mitigations


See [Security Updates](#security-updates) for the version to install.


### Acknowledgements


NVIDIA thanks following individuals for reporting the issues:


* CVE‑2020‑5977: Xavier DANEST of Decathlon and Boris Ryutin
* CVE‑2020‑5978: Hashim Jawad of ACTIVELabs
* CVE‑2020‑5990: Hashim Jawad of ACTIVELabs


### Get the Most Up to Date Product Security Information


Visit the[NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History




Revision History





| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 2.0 | October 28, 2020 | Updated the acknowledgements for CVE‑2020‑5977 |
| 1.0 | October 22, 2020 | Initial release |


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


* [ NVIDIA GeForce Experience - July 2020](/app/answers/detail/a_id/5038/related/1)
* [ NVIDIA GeForce Experience - December 2019](/app/answers/detail/a_id/4954/related/1)
* [ NVIDIA GeForce Experience - November 2019](/app/answers/detail/a_id/4860/related/1)
* [ NVIDIA GeForce Experience – March 2019](/app/answers/detail/a_id/4784/related/1)
* [ NVIDIA GeForce Experience - November 2018](/app/answers/detail/a_id/4740/related/1)








