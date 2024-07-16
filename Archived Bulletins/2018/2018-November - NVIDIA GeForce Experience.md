# NVIDIA GeForce Experience (Bulletin ID: 4740)



 NVIDIA GeForce Experience - November 2018
============================================================




 Updated 09/29/2021 01:09 PM



NVIDIA has released a software update for GeForce Experience. This update addresses issues that may lead to escalation of privileges or information disclosure. To protect your system, download and install this software update through the [GeForce Experience Downloads](https://www.geforce.com/geforce-experience/download) page.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 



---




### Details


This section summarizes the potential impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors follow [CVSS V3](https://www.first.org/cvss/user-guide) standards.




This section summarizes the potential impact that this security update addresses. Descriptions use CWE™, and base scores and vectors follow CVSS V3 standards.
| \*\*CVE\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2018‑6263 | NVIDIA GeForce Experience contains a vulnerability in which an attacker who has access to a local user account can plant a malicious dynamic link library (DLL) during application installation, which may lead to escalation of privileges. | 8.8 | [AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2018‑6265 | NVIDIA GeForce Experience contains a vulnerability during application installation on Windows 7 in elevated privilege mode, where a local user who initiates a browser session may obtain escalation of privileges on the browser. | 8.2 | [AV:L/AC:L/PR:L/UI:R/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:R/S:C/C:H/I:H/A:H) |
| CVE‑2018‑6266 | NVIDIA GeForce Experience contains a vulnerability where a local user may obtain third party integration parameters which may lead to information disclosure. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N) |


NVIDIA’s risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk of your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


 


### Security Updates


The following table lists the software products and versions affected by these potential vulnerabilities, and the updated versions that address these vulnerabilities.




The following table lists the software products and versions affected by these potential vulnerabilities, and the updated versions that address these vulnerabilities.
| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- |
| GeForce Experience | Windows | All versions prior to 3.16 | 3.16 |


Download the updates from the [NVIDIA GeForce Experience Downloads](http://www.geforce.com/geforce-experience/download) page, or open the client to automatically apply the security update.


**Notes:**


* Affected versions include the versions listed and all earlier branches and releases.
* If you are using an unsupported version or an earlier unsupported branch, upgrade to the latest supported version. To identify products that are no longer supported, contact [NVIDIA Support](http://www.nvidia.com/object/support.html).


### 


### Mitigations


None. See [Security Updates](#security-updates) for the versions to install.


### 


### Acknowledgements


CVE-2018-6263: NVIDIA thanks Pierre-Alexandre Braeken for reporting this issue. 


CVE-2018-6266: NVIDIA thanks Akshay Jain for reporting this issue. 
 


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](http://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential vulnerability in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### 


### Revision History




Revision History





| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | November 19, 2018 | Initial release |


### 


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


* [ NVIDIA GeForce Experience Software Security Updates for Multiple Vulnerabilities When GameStream is Enabled](/app/answers/detail/a_id/4685/related/1)
* [ NVIDIA GeForce Experience - September 2018](/app/answers/detail/a_id/4725/related/1)
* [ NVIDIA Jetson TX1, Jetson TK1, Jetson TX2, and Tegra K1 L4T Security Updates for Multiple Vulnerabilities](/app/answers/detail/a_id/4635/related/1)
* [ NVIDIA GPU Display Driver Security Updates for Multiple Vulnerabilities](/app/answers/detail/a_id/4649/related/1)
* [ NVIDIA SHIELD TV Security Updates for Multiple Vulnerabilities](/app/answers/detail/a_id/4631/related/1)








