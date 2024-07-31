# NVIDIA Omniverse Nucleus and Omniverse Cache (Bulletin ID: 5342)



 NVIDIA Omniverse Nucleus and Omniverse Cache - April 2022
============================================================================




 Updated 04/28/2022 05:23 PM



NVIDIA has released a software update for the Windows versions of Omniverse™ Nucleus and Omniverse Cache to address a security issue that may lead to code execution, impacting confidentiality, integrity, and availability.


To protect your system, open the Omniverse Launcher and apply the appropriate update. If you have Nucleus installed, apply the update in the **Nucleus** tab. If you have Cache installed, apply the Cache update in the **Library** tab.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/v3.1/user-guide) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑28198 | NVIDIA Omniverse Nucleus and Cache contain a vulnerability in its configuration of OpenSSL, where an attacker with physical access to the system can cause arbitrary code execution which can impact confidentiality, integrity, and availability. | 6.6 | [AV:P/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:P/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.


To protect your system, open the Omniverse Launcher and apply the appropriate update.


* If you have Nucleus installed, apply the update in the **Nucleus** tab.
* If you have Cache installed, apply the Cache update in the **Library** tab.




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2022‑28198 | Omniverse Nucleus | Windows | 2021.3.2 | 2022.1.1 |
| Omniverse Cache | Windows | 2021.3.0 | 2022.1.1 |


#### Notes


* Earlier software releases that support this product are also affected. If you are using an earlier release, upgrade to the latest branch release.


### Mitigations


None. See [Security Updates](#security-updates) for the version to install.


### Acknowledgements


CVE‑2022‑28198: NVIDIA thanks Xavier Danest - Decathlon for reporting this issue.


### Get the Most Up to Date Product Security Information


Visit the  [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | April 28, 2022 | Initial release |


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
* [ NVIDIA GeForce Experience - December 2021](/app/answers/detail/a_id/5295/related/1)
* [ NVIDIA License System - February 2022](/app/answers/detail/a_id/5319/related/1)
* [ NVIDIA SHIELD TV - January 2022](/app/answers/detail/a_id/5259/related/1)
* [Security Notice: NVIDIA Response to Security Incident - March 2022](/app/answers/detail/a_id/5333/related/1)








