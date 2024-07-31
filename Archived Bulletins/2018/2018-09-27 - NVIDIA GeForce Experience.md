# NVIDIA GeForce Experience (Bulletin ID: 4725)



 NVIDIA GeForce Experience - September 2018
=============================================================




 Updated 09/29/2021 01:09 PM



NVIDIA has released a software update to address potential security vulnerabilities in GeForce Experience. When GameStream is enabled and an unauthorized user gains system access, these issues may lead to limited user information disclosure, denial of service, or escalation of privileges. To protect your system, download and install this software update through the [GeForce Experience Downloads](https://www.geforce.com/geforce-experience/download) page.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security](http://www.nvidia.com/product-security/).
-------------------------------------------------------------------------






---




### Vulnerability Details


This section summarizes the potential vulnerabilities. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors follow [CVSS V3](https://www.first.org/cvss/user-guide) standards.




This section summarizes the potential vulnerabilities. Descriptions use CWE™, and base scores and vectors follow CVSS V3 standards.


| \*\*CVE\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*CVSS V3 Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2018‑6261 | NVIDIA GeForce Experience contains a vulnerability when GameStream is enabled which sets incorrect permissions on a file, which may to code execution, denial of service, or escalation of privileges by users with system access. | 8.8 | [AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2018‑6262 | NVIDIA GeForce Experience contains a vulnerability when GameStream is enabled where limited sensitive user information may be available to users with system access, which may lead to information disclosure. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N) |


NVIDIA’s risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk of your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following table lists the software products and versions affected by these potential vulnerabilities, and the updated versions that address these vulnerabilities.




The following table lists the software products and versions affected by these potential vulnerabilities, and the updated versions that address these vulnerabilities.
| \*\*CVE\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Versions\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2018‑6261 CVE‑2018‑6262 | GeForce Experience | Windows | All versions prior to 3.15 | 3.15 or later |


Download the updates from the [NVIDIA GeForce Experience Downloads](http://www.geforce.com/geforce-experience/download) page, or open the client to automatically apply the security update.


**Notes:**


* All branches prior to the versions listed in the Affected Versions column are impacted.
* If you are using an unsupported version or an earlier unsupported branch, upgrade to the latest supported version. To identify products that are no longer supported contact [NVIDIA Support](http://www.nvidia.com/object/support.html).


### Mitigations


None. See [Security Updates](#security-updates) for the versions to install to address these vulnerabilities.


### Acknowledgements


CVE‑2018‑6261: NVIDIA thanks Mark Barnes for reporting this issue.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](http://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential vulnerability in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History




Revision History




| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | September 27, 2018 | Initial release |


### Support


If you have any questions about this security bulletin, contact [NVIDIA Support](http://www.nvidia.com/object/support.html).


##### Disclaimer


ALL NVIDIA INFORMATION, DESIGN SPECIFICATIONS, REFERENCE BOARDS, FILES, DRAWINGS, DIAGNOSTICS, LISTS, AND OTHER DOCUMENTS (TOGETHER AND SEPARATELY, “MATERIALS”) ARE BEING PROVIDED “AS IS.” NVIDIA MAKES NO WARRANTIES, EXPRESS, IMPLIED, STATUTORY, OR OTHERWISE WITH RESPECT TO THE MATERIALS, AND ALL EXPRESS OR IMPLIED CONDITIONS, REPRESENTATIONS AND WARRANTIES, INCLUDING ANY IMPLIED WARRANTY OR CONDITION OF TITLE, MERCHANTABILITY, SATISFACTORY QUALITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT, ARE HEREBY EXCLUDED TO THE MAXIMUM EXTENT PERMITTED BY LAW.


Information is believed to be accurate and reliable at the time it is furnished. However, NVIDIA Corporation assumes no responsibility for the consequences of use of such information or for any infringement of patents or other rights of third parties that may result from its use. No license is granted by implication or otherwise under any patent or patent rights of NVIDIA Corporation. Specifications mentioned in this publication are subject to change without notice. This publication supersedes and replaces all information previously supplied. NVIDIA Corporation products are not authorized for use as critical components in life support devices or systems without express written approval of NVIDIA Corporation.










Is this answer helpful?
-----------------------



Yes
No







Answers others found helpful
----------------------------


* [ NVIDIA GeForce Experience – March 2019](/app/answers/detail/a_id/4784/related/1)
* [ NVIDIA Jetson TX1, Jetson TK1, and Tegra K1 L4T Security Updates for CPU Speculative Side Channel Vulnerabilities](/app/answers/detail/a_id/4616/related/1)
* [ NVIDIA Jetson TX2 L4T Security Updates for CPU Speculative Side Channel Vulnerabilities](/app/answers/detail/a_id/4617/related/1)
* [Security Notice: CPU Speculative Side Channel Vulnerabilities](/app/answers/detail/a_id/4609/related/1)
* [ NVIDIA SHIELD TV Security Updates for CPU Speculative Side Channel Vulnerabilities](/app/answers/detail/a_id/4613/related/1)








