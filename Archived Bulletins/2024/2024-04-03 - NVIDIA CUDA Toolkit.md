# NVIDIA CUDA Toolkit (Bulletin ID: 5517)



 NVIDIA CUDA Toolkit - April 2024
===================================================




 Updated 04/03/2024 08:33 PM



NVIDIA has released a software update for NVIDIA® CUDA® Toolkit. To protect your system, download and install this software update from the [CUDA Toolkit Downloads](https://developer.nvidia.com/cuda-toolkit) page.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Vector\*\* | \*\*Base Score\*\* | \*\*Severity\*\* | \*\*CWE\*\* | \*\*Impacts\*\* |
| --- | --- | --- | --- | --- | --- | --- |
| CVE‑2024‑0072 | NVIDIA CUDA toolkit for all platforms contains a vulnerability in cuobjdump and nvdisasm where an attacker may cause a crash by tricking a user into reading a malformed ELF file. A successful exploit of this vulnerability may lead to a partial denial of service. | [AV:L/AC:L/PR:N/UI:R/S:U/C:N/I:N/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:R/S:U/C:N/I:N/A:L&version=3.1) | 3.3 | Low | [CWE‑476](https://cwe.mitre.org/data/definitions/476.html) | Denial of service |
| CVE-2024-0076 | NVIDIA CUDA toolkit for all platforms contains a vulnerability in cuobjdump and nvdisasm where an attacker may cause a crash by tricking a user into reading a malformed ELF file. A successful exploit of this vulnerability may lead to a partial denial of service. | [AV:L/AC:L/PR:N/UI:R/S:U/C:N/I:N/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:R/S:U/C:N/I:N/A:L&version=3.1) | 3.3 | Low | [CWE‑125](https://cwe.mitre.org/data/definitions/125.html) | Denial of service |
| CVE-2023-31028 | NVIDIA nvJPEG2000 Library for Windows and Linux contains a vulnerability where improper input validation might enable an attacker to use a specially crafted input file. A successful exploit of this vulnerability might lead to a partial denial of service. | [AV:L/AC:L/PR:L/UI:R/S:U/C:N/I:N/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:R/S:U/C:N/I:N/A:L&version=3.1) | 2.8 | Low | [CWE‑20](https://cwe.mitre.org/data/definitions/20.html) | Denial of service |
| CVE-2024-0080 | NVIDIA nvTIFF Library for Windows and Linux contains a vulnerability where improper input validation might enable an attacker to use a specially crafted input file. A successful exploit of this vulnerability might lead to a partial denial of service. | [AV:L/AC:L/PR:L/UI:R/S:U/C:N/I:N/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:R/S:U/C:N/I:N/A:L&version=3.1) | 2.8 | Low | [CWE‑20](https://cwe.mitre.org/data/definitions/20.html) | Denial of service |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA products affected, versions affected, and the updated version that includes this security update.




| \*\*CVE IDs Addressed\*\* | \*\*Affected Products\*\* | \*\*Platform or OS\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2024-0072 CVE-2024-0076 | NVIDIA CUDA Toolkit | Windows, Linux | All versions prior to CUDA Toolkit v12.4 | CUDA Toolkit v12.4U1 |
| CVE-2023-31028 | nvJPEG2000 Library | Windows, Linux | All versions prior to nvJPEG2000 v0.7.x | nvJPEG2000 v0.7.x |
| CVE-2024-0080 | nvTIFF Library | Windows, Linux | All versions prior to nvTIFF v0.3.0 | nvTIFF v0.3.0 |


### Notes


* Earlier software releases of this product are also affected. If you are using an earlier release, upgrade to the latest release version.


### Acknowledgements


NVIDIA thanks the following finders for reporting these issues:


* CVE-2024‑0072, CVE-2024-0076: Matteo Marini and Daniele Cono D'Elia
* CVE‑2023-31028, CVE-2024-0080: hjy79425575


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | April 3, 2024 | Initial release |


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


* [ NVIDIA GPU Display Driver - October 2023](/app/answers/detail/a_id/5491/related/1)
* [ NVIDIA GeForce NOW for Android - August 2023](/app/answers/detail/a_id/5476/related/1)
* [ NVIDIA GPU Display Driver - March 2023](/app/answers/detail/a_id/5452/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) - June 2023](/app/answers/detail/a_id/5466/related/1)
* [ NVIDIA DGX H100 - August 2023](/app/answers/detail/a_id/5473/related/1)








