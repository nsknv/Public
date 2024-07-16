# NVIDIA CUDA Toolkit (Bulletin ID: 5446)



 NVIDIA CUDA Toolkit - March 2023
===================================================




 Updated 03/01/2023 04:53 PM



NVIDIA has released a software update for NVIDIA® CUDA® Toolkit software. This update addresses security issues that may lead to denial of service or information disclosure.


To protect your system, download and install this software update from the [CUDA Toolkit Downloads](https://developer.nvidia.com/cuda-toolkit) page.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).

 



---




### Details


This section summarizes the potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors follow [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector/CWE\*\* |
| --- | --- | --- | --- |
| CVE‑2023‑0193 | NVIDIA CUDA Toolkit SDK contains a vulnerability in `cuobjdump`, where a local user running the tool against a malicious binary may cause an out-of-bounds read, which may result in a limited denial of service and limited information disclosure. | 4.4 | [AV:L/AC:L/PR:N/UI:R/S:U/C:L/I:N/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:R/S:U/C:L/I:N/A:L) [CWE-125](https://cwe.mitre.org/data/definitions/125.html) |
| CVE‑2023‑0196 | NVIDIA CUDA Toolkit SDK contains a bug in `cuobjdump`, where a local user running the tool against an ill-formed binary may cause a null- pointer dereference, which may result in a limited denial of service. | 3.3 | [AV:L/AC:L/PR:N/UI:R/S:U/C:N/I:N/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:R/S:U/C:N/I:N/A:L) [CWE-476](https://cwe.mitre.org/data/definitions/476.html) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the software products and versions affected, and the updated version available from nvidia.com that includes this security update.


Download the update from the [CUDA Toolkit Downloads](https://developer.nvidia.com/cuda-toolkit) page to apply the security update.




| \*\*CVEs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2023‑0193 CVE‑2023‑0196 | NVIDIA CUDA Toolkit | Linux | All versions prior to 12.1 | 12.1 |
| Windows | All versions prior to 12.1 | 12.1 |


#### Notes


* Earlier software releases of this product are also affected. If you are using an earlier release, upgrade to the latest release version.


### Acknowledgements


CVE‑2023‑0193: NVIDIA thanks r3pwnx (@r3pwnx) of 360AIVul for reporting this issue.


CVE‑2023‑0196: NVIDIA thanks hjy79425575 for reporting this issue.


### Get the Most Up to Date Product Security Information


Visit the  [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | March 1, 2023 | Initial release |


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
* [ NVIDIA DCGM - August 2021](/app/answers/detail/a_id/5219/related/1)
* [ NVIDIA GeForce Experience - April 2021](/app/answers/detail/a_id/5184/related/1)
* [ NVIDIA GeForce Experience - February 2021](/app/answers/detail/a_id/5155/related/1)








