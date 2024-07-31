# NVIDIA CUDA Toolkit (Bulletin ID: 5548)



 NVIDIA CUDA Toolkit - July 2024
==================================================




 Updated 07/11/2024 07:32 AM



NVIDIA has released a software update for NVIDIA® CUDA® Toolkit. To protect your system, download and install this software update from the [CUDA Toolkit Downloads](https://developer.nvidia.com/cuda-toolkit) page.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.





| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Vector\*\* | \*\*Base Score\*\* | \*\*Severity\*\* | \*\*CWE\*\* | \*\*Impacts\*\* |
| --- | --- | --- | --- | --- | --- | --- |
| CVE-2024-0102 | NVIDIA CUDA Toolkit for all platforms contains a vulnerability in nvdisasm, where an attacker can cause an out-of-bounds read issue by deceiving a user into reading a malformed ELF file. A successful exploit of this vulnerability might lead to denial of service. | [AV:L/AC:L/PR:N/UI:R/S:U/C:N/I:N/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:R/S:U/C:N/I:N/A:L&version=3.1) | 3.3 | Low | [CWE‑125](https://cwe.mitre.org/data/definitions/125.html) | Denial of service |



The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA products affected, versions affected, and the updated version that includes this security update.











| \*\*CVE IDs Addressed\*\* | \*\*Affected Products\*\* | \*\*Platform or OS\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2024-0102 | NVIDIA CUDA Toolkit | Windows, Linux | All versions up to and including CUDA Toolkit 12.5U1 | CUDA Toolkit 12.6 |



### Notes


* Earlier software releases of this product are also affected. If you are using an earlier release, upgrade to the latest release version.


### Acknowledgements


NVIDIA thanks Matteo Marini and Daniele Cono D'Elia for reporting issue CVE-2024-0102.


### Get the Most Up-to-Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History









| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | July 11, 2024 | Initial release |



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


* [ NVIDIA CUDA Toolkit - March 2023](/app/answers/detail/a_id/5446/related/1)
* [ NVIDIA DGX A100 and DGX A800 - June 2023](/app/answers/detail/a_id/5461/related/1)
* [ NVIDIA SHIELD TV - January 2021](/app/answers/detail/a_id/5148/related/1)
* [ NVIDIA GeForce Experience - January 2023](/app/answers/detail/a_id/5384/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) - June 2021](/app/answers/detail/a_id/5205/related/1)








