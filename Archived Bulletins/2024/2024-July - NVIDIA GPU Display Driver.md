# NVIDIA GPU Display Driver (Bulletin ID: 5557)



 NVIDIA GPU Display Driver - July 2024
========================================================




 Updated 07/09/2024 10:14 AM



NVIDIA has released a software security update for NVIDIA GPU Display Driver to address the issues that are disclosed in this bulletin.


To protect your system, download and install this software update through the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software and Cloud Gaming updates, through the NVIDIA Licensing Portal.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.


#### NVIDIA GPU Display Driver




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Vector\*\* | \*\*Base Score\*\* | \*\*Severity\*\* | \*\*CWE\*\* | \*\*Impacts\*\* |
| --- | --- | --- | --- | --- | --- | --- |
| CVE‑2024‑0107 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the user mode layer, where an unprivileged regular user can cause an out-of-bounds read. A successful exploit of this vulnerability might lead to code execution, denial of service, escalation of privileges, information disclosure, and data tampering. | [AV:L/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H) | 7.8 | High | [CWE‑125](https://cwe.mitre.org/data/definitions/125.html) | Code execution, denial of service, escalation of privileges, information disclosure, data tampering |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and might not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates for NVIDIA GPU Display Driver


The following table lists the NVIDIA software products affected, versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- | --- |
| CVE‑2024‑0107 | GeForce | Windows | R555 | All driver versions prior to 556.12 | 556.12 |
| Windows 10 and 11 | R470 | All driver versions prior to 475.14 for support of [GeForce Kepler desktop](https://nvidia.custhelp.com/app/answers/detail/a\_id/5202/kw/kepler%20desktop) | 475.14 |
| Windows 7 and 8.x | R470 | All driver versions prior to 475.14 | 475.14 |
| NVIDIA RTX/ Quadro, NVS | Windows | R550 | All driver versions prior to 552.74 | 552.74 |
| R535 | All driver versions prior to 538.78 | 538.78 |
| R470 | All driver versions prior to 475.14 | 475.14 |
| Tesla | Windows | R550 | All driver versions prior to 552.74 | 552.74 |
| R535 | All driver versions prior to 538.78 | 538.78 |
| R470 | All driver versions prior to 475.14 | 475.14 |


**Notes:**


* Your computer hardware vendor might provide you with Windows GPU display driver versions including 556.12, 552.74, 538.78, and 475.14, which also contain the security updates.
* The table above might not be a comprehensive list of all affected supported versions or branch releases and might be updated as more information becomes available.
* Earlier software branch releases that support these products might also be affected. If you are using an earlier branch release for which an updated version is not listed, upgrade to the latest branch release.


### Security Updates for NVIDIA vGPU Software


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Log in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal.




| \*\*CVE IDs Addressed\*\* | \*\*vGPU Software Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | \*\*vGPU Software\*\* | \*\*Driver\*\* |
| CVE‑2024‑0107 | Guest driver | Windows | All versions up to and including 17.2 | 552.55 | 17.3 | 552.74 |
| All versions up to and including 16.6 | 538.67 | 16.7 | 538.78 |
| All versions up to and including 13.11 | 475.06 | 13.12 | 475.14 |


**Notes:**


* The table above might not be a comprehensive list of all affected supported versions or branch releases and might be updated as more information becomes available.
* Earlier software branch releases that support these products might also be affected. If you are using an earlier branch release for which an update version is not listed, upgrade to the latest branch release.


### Security Updates for NVIDIA Cloud Gaming


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Download the updates through the NVIDIA Licensing Portal.




| CVE IDs Addressed | Cloud Gaming Component | Operating System | Affected Versions | | Updated Version | |
| --- | --- | --- | --- | --- | --- | --- |
| Cloud Gaming Software | Driver | Cloud Gaming Software | Driver |
| CVE‑2024‑0107 | Guest driver | Windows | All versions up to and including the June 2024 release | 555.99 | June 2024 release | 556.12 |


### Mitigations


Refer to [Security Updates for NVIDIA GPU Display Driver](#security-updates-for-nvidia-gpu-display-driver), [Security Updates for NVIDIA vGPU Software](#security-updates-for-nvidia-vgpu-software), or [Security Updates for NVIDIA Cloud Gaming](#security-updates-for-nvidia-cloud-gaming) for the version to install.


### Acknowledgements


NVIDIA thanks the following people for reporting the issues:


CVE‑2024‑0107: Piotr Bania - Cisco Talos


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | July 9, 2024 | Initial release |


### Support


If you have any questions about this security bulletin, contact [NVIDIA Support](https://www.nvidia.com/object/support.html).


### Frequently Asked Questions (FAQs)


[How do I determine which NVIDIA display driver version is currently installed on my PC?](https://nvidia.custhelp.com/app/answers/detail/a_id/2039)


##### Disclaimer


ALL NVIDIA INFORMATION, DESIGN SPECIFICATIONS, REFERENCE BOARDS, FILES, DRAWINGS, DIAGNOSTICS, LISTS, AND OTHER DOCUMENTS (TOGETHER AND SEPARATELY, “MATERIALS”) ARE BEING PROVIDED “AS IS.” NVIDIA MAKES NO WARRANTIES, EXPRESS, IMPLIED, STATUTORY, OR OTHERWISE WITH RESPECT TO THE MATERIALS, AND ALL EXPRESS OR IMPLIED CONDITIONS, REPRESENTATIONS AND WARRANTIES, INCLUDING ANY IMPLIED WARRANTY OR CONDITION OF TITLE, MERCHANTABILITY, SATISFACTORY QUALITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT, ARE HEREBY EXCLUDED TO THE MAXIMUM EXTENT PERMITTED BY LAW.


Information is believed to be accurate and reliable at the time it is furnished. However, NVIDIA Corporation assumes no responsibility for the consequences of use of such information or for any infringement of patents or other rights of third parties that may result from its use. No license is granted by implication or otherwise under any patent or patent rights of NVIDIA Corporation. Specifications mentioned in this publication are subject to change without notice. This publication supersedes and replaces all information previously supplied. NVIDIA Corporation products are not authorized for use as critical components in life support devices or systems without express written approval of NVIDIA Corporation.










Is this answer helpful?
-----------------------



Yes
No







Answers others found helpful
----------------------------


* [Support Plan for Kepler-series GeForce GPUs for Desktop](/app/answers/detail/a_id/5202/related/1)
* [How do I determine which NVIDIA display driver version is currently installed on my PC?](/app/answers/detail/a_id/2039/related/1)
* [ NVIDIA GPU Display Driver - October 2023](/app/answers/detail/a_id/5491/related/1)
* [ NVIDIA GeForce Experience - January 2023](/app/answers/detail/a_id/5384/related/1)
* [ NVIDIA GPU Display Driver - August 2022](/app/answers/detail/a_id/5383/related/1)








