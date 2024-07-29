# NVIDIA GeForce Experience (Bulletin ID: 5384)



 NVIDIA GeForce Experience - January 2023
===========================================================




 Updated 01/30/2023 11:44 AM



NVIDIA has released a software security update for NVIDIA® GeForce Experience™ software. This update addresses issues that may lead to code execution, information disclosure, data tampering, and denial of service.


To protect your system, download and install this software update through the [GeForce Experience Downloads](https://www.geforce.com/geforce-experience/download) page, or open the client to automatically apply the security update.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑42291 | NVIDIA GeForce Experience contains a vulnerability in the installer, where a user installing the NVIDIA GeForce Experience software may inadvertently delete data from a linked location, which may lead to data tampering. An attacker does not have explicit control over the exploitation of this vulnerability, which requires the user to explicitly launch the installer from the compromised directory. | 8.2 | [AV:L/AC:L/PR:N/UI:R/S:C/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:R/S:C/C:N/I:H/A:H) |
| CVE‑2022‑31611 | NVIDIA GeForce Experience contains an uncontrolled search path vulnerability in all its client installers, where an attacker with user level privileges may cause the installer to load an arbitrary DLL when the installer is launched. A successful exploit of this vulnerability could lead to escalation of privileges and code execution. | 6.8 | [AV:L/AC:L/PR:L/UI:R/S:U/C:L/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:R/S:U/C:L/I:H/A:H) |
| CVE‑2022‑42292 | NVIDIA GeForce Experience contains a vulnerability in the NVContainer component, where a user without administrator privileges can create a symbolic link to a file that requires elevated privileges to write to or modify, which may lead to denial of service, escalation of privilege or limited data tampering. | 5.0 | [AV:L/AC:H/PR:L/UI:R/S:U/C:N/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:R/S:U/C:N/I:L/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.


Download the updates through the [GeForce Experience Downloads](https://www.geforce.com/geforce-experience/download) page, or open the client to automatically apply the security update.




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2022‑42291 CVE‑2022‑31611 CVE‑2022‑42292 | GeForce Experience | Windows | All versions prior to 3.27.0.112 | 3.27.0.112 |


#### Notes:


* Earlier software releases that support this product are also affected. If you are using an earlier release, upgrade to the latest release.


### Acknowledgements


CVE‑2022‑42291 and CVE‑2022‑31611: NVIDIA thanks Minse Kim of DNSLab, Korea University for reporting these issues.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.1 | January 30, 2023 | Updated the affected and updated versions in the Security Updates table |
| 1.0 | January 30, 2023 | Initial release |


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


* [ NVIDIA GeForce Experience - December 2021](/app/answers/detail/a_id/5295/related/1)
* [ NVIDIA GeForce Experience - June 2021](/app/answers/detail/a_id/5199/related/1)
* [ NVIDIA GeForce Experience - April 2021](/app/answers/detail/a_id/5184/related/1)
* [ NVIDIA GeForce Experience - October 2020](/app/answers/detail/a_id/5076/related/1)
* [ NVIDIA GeForce Experience - February 2021](/app/answers/detail/a_id/5155/related/1)








