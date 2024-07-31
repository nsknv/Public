# NVIDIA NVFlash, GPUModeSwitch Tool (Bulletin ID: 4928)



 NVIDIA NVFlash, GPUModeSwitch Tool - November 2019
=====================================================================




 Updated 09/29/2021 02:48 PM



NVIDIA has released a software security update for NVIDIA NVFlash Tool. This update addresses issues that may lead to escalation of privileges, information disclosure, or denial of service. This update is available only to NVIDIA OEMs and partners.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security](https://www.nvidia.com/product-security/).
--------------------------------------------------------------------------






---




### Details


This section summarizes the potential impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS V3](https://www.first.org/cvss/user-guide) standards.




This section summarizes the potential impact that this security update addresses. Descriptions use CWE™, and base scores and vectors use CVSS V3 standards.
| \*\*CVE\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2019‑5688 | NVIDIA kernel mode driver (`nvflash.sys`, `nvflsh32.sys`, and `nvflsh64.sys`) contains a vulnerability in which authenticated users with administrative privileges can gain access to device memory and registers of other devices not managed by NVIDIA, which may lead to escalation of privileges, information disclosure, or denial of service. | 6.7 | [AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk of your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected and the updated versions that include this security update.




The following table lists the NVIDIA software products affected and the updated versions that include this security update.
| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Updated Version\*\* |
| --- | --- | --- |
| NVFlash NVUFlash | Windows | 5.588.0 |
| GPUModeSwitch | Windows | 2019-11 |


**Notes:**


* NVFlash and NVUFlash
	+ This product update is available only to NVIDIA OEMs and partners.
	+ There is no action for end-users.
* GPUModeSwitch product update is available by logging in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Center.


### Mitigations


None. See [Security Updates](#security-updates) for the version to install.


### Acknowledgements


CVE‑2019‑5688: NVIDIA thanks Jesse Michael and Mickey Shkatov of Eclypsium for reporting this issue.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential vulnerability in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History




Revision History





| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 2.0 | November 14, 2019 | Added GPUModeSwitch to affected products |
| 1.0 | November 6, 2019 | Initial release |


### Support


If you have any questions about this security bulletin, contact [NVIDIA Support](https://www.nvidia.com/object/support.html).


##### Disclaimer


Information is believed to be accurate and reliable at the time it is furnished. However, NVIDIA Corporation assumes no responsibility for the consequences of use of such information or for any infringement of patents or other rights of third parties that may result from its use. No license is granted by implication or otherwise under any patent or patent rights of NVIDIA Corporation. Specifications mentioned in this publication are subject to change without notice. This publication supersedes and replaces all information previously supplied. NVIDIA Corporation products are not authorized for use as critical components in life support devices or systems without express written approval of NVIDIA Corporation.


ALL NVIDIA INFORMATION, DESIGN SPECIFICATIONS, REFERENCE BOARDS, FILES, DRAWINGS, DIAGNOSTICS, LISTS, AND OTHER DOCUMENTS (TOGETHER AND SEPARATELY, “MATERIALS”) ARE BEING PROVIDED “AS IS.” NVIDIA MAKES NO WARRANTIES, EXPRESS, IMPLIED, STATUTORY, OR OTHERWISE WITH RESPECT TO THE MATERIALS, AND ALL EXPRESS OR IMPLIED CONDITIONS, REPRESENTATIONS AND WARRANTIES, INCLUDING ANY IMPLIED WARRANTY OR CONDITION OF TITLE, MERCHANTABILITY, SATISFACTORY QUALITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT, ARE HEREBY EXCLUDED TO THE MAXIMUM EXTENT PERMITTED BY LAW.










Is this answer helpful?
-----------------------



Yes
No







Answers others found helpful
----------------------------


* [ NVIDIA GeForce Experience – March 2019](/app/answers/detail/a_id/4784/related/1)
* [ NVIDIA GeForce Experience - November 2018](/app/answers/detail/a_id/4740/related/1)
* [ NVIDIA Jetson TX1 and TX2 L4T - April 2019](/app/answers/detail/a_id/4787/related/1)
* [ NVIDIA GeForce Experience Software Security Updates for Multiple Vulnerabilities When GameStream is Enabled](/app/answers/detail/a_id/4685/related/1)
* [ NVIDIA GPU Display Driver - February 2019](/app/answers/detail/a_id/4772/related/1)








