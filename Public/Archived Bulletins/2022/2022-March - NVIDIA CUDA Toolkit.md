# NVIDIA CUDA Toolkit (Bulletin ID: 5334)



 NVIDIA CUDA Toolkit - March 2022
===================================================




 Updated 04/07/2022 04:01 PM



NVIDIA has released a software update for NVIDIA® CUDA® Toolkit software. This update addresses security issues that may lead to code execution, denial of service, or information disclosure.


To protect your system, download and install this software update from the [CUDA Toolkit Downloads](https://developer.nvidia.com/cuda-toolkit) page.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑21821 | NVIDIA CUDA Toolkit SDK contains an integer overflow vulnerability in `cuobjdump`.To exploit this vulnerability, a remote attacker would require a local user to download a specially crafted, corrupted file and locally execute `cuobjdump` against the file. Such an attack may lead to remote code execution that causes complete denial of service and an impact on data confidentiality and integrity. | 7.8 | [AV:L/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.


Download the update from the [CUDA Toolkit Downloads](https://developer.nvidia.com/cuda-toolkit) page to apply the security update.




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2022‑21821 | CUDA Toolkit | Windows and Linux | All versions prior to CUDA Toolkit 11.6 Update 2 | 11.6 Update 2 |


#### Notes


* Earlier software releases that support this product are also affected. If you are using an earlier release, upgrade to the latest release version.


### Mitigations


If you address this vulnerability by installing the CUDA Toolkit version listed in [Security Updates](#security-updates), it is recommended, but not required, that you also update the CUDA driver at the same time. If you prefer to remain on an older CUDA driver, refer to [CUDA Compatibility](https://docs.nvidia.com/deploy/cuda-compatibility/index.html) for more information.


This issue exists in the standalone developer utility `cuobjdump`, which is shipped with CUDA Toolkit. It does not affect normal runtime execution of CUDA. It is encountered only when developer tools are run against specifically malformed binaries.


Applications that are built with or distributed with the CUDA runtime components listed in [Attachment A of the CUDA EULA](https://docs.nvidia.com/cuda/eula/index.html#attachment-a) are not affected by this vulnerability. The base and runtime variants of NGC CUDA containers are also unaffected because they do not contain the `cuobjdump` utility.


### Acknowledgements


NVIDIA thanks Leonardo Galli for reporting this issue.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 2.0 | April 7, 2022 | Added information about how to mitigate this issue for affected CUDA Toolkit versions |
| 1.0 | March 28, 2022 | Initial release |


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


* [ NVIDIA SHIELD TV - January 2022](/app/answers/detail/a_id/5259/related/1)
* [ NVIDIA Omniverse Launcher - January 2022](/app/answers/detail/a_id/5318/related/1)
* [ NVIDIA License System - February 2022](/app/answers/detail/a_id/5319/related/1)
* [ NVIDIA GeForce Experience - December 2021](/app/answers/detail/a_id/5295/related/1)
* [Security Notice: NVIDIA Response to Log4j Vulnerabilities - December 2021](/app/answers/detail/a_id/5294/related/1)








