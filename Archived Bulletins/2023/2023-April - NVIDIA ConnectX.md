# NVIDIA ConnectX (Bulletin ID: 5459)



 NVIDIA ConnectX - April 2023
===============================================




 Updated 04/18/2023 09:10 AM



NVIDIA has released a security update for NVIDIA ConnectX® firmware. This update addresses issues that may lead to denial of service.


To protect your system, download and install this firmware update from the [NVIDIA Networking Support](https://network.nvidia.com/support/firmware/firmware-downloads/) page.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2023‑0204 | NVIDIA ConnectX-5, ConnectX-6, and ConnectX6-DX contain a vulnerability in the NIC firmware, where an unprivileged user can cause improper handling of exceptional conditions, which may lead to denial of service. | 6.5 | [CWE-703](https://cwe.mitre.org/data/definitions/703.html) [AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H) |
| CVE‑2023‑0203 | NVIDIA ConnectX-5, ConnectX-6, and ConnectX6-DX contain a vulnerability in the NIC firmware, where an unprivileged user can exploit insufficient granularity of access control, which may lead to denial of service. | 5.0 | [CWE-1220](https://cwe.mitre.org/data/definitions/1220.html) [AV:N/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:L) |
| CVE‑2023‑0205 | NVIDIA ConnectX-5, ConnectX-6, and ConnectX6-DX contain a vulnerability in the NIC firmware, where an unprivileged user can exploit insufficient granularity of access control, which may lead to denial of service. | 5.0 | [CWE-1220](https://cwe.mitre.org/data/definitions/1220.html) [AV:N/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:L) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA products affected, versions affected, and the updated version that includes this security update.




| \*\*CVE IDs Addressed\*\* | \*\*Product\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- |
| CVE‑2023‑0203 CVE‑2023‑0204 CVE‑2023‑0205 | NVIDIA ConnectX Firmware | All versions prior to 35.1012 | 35.1012 |


#### Notes


* Earlier firmware releases that support this product are also affected. If you are using an earlier release, upgrade to the latest release version.


### Acknowledgements


NVIDIA thanks Xinhao Kong, Jingrong Chen, Wei Bai, Yechen Xu, Mahmoud Elhaddad, Shachar Raindel, Jitendra Padhye, Alvin R. Lebeck, and Danyang Zhuo for reporting these issues.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | April 18, 2023 | Initial release |


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


* [ NVIDIA GeForce Experience - January 2023](/app/answers/detail/a_id/5384/related/1)
* [ NVIDIA CUDA Toolkit - March 2023](/app/answers/detail/a_id/5446/related/1)
* [ NVIDIA Omniverse Kit - January 2023](/app/answers/detail/a_id/5418/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson AGX Orin Series - January 2023](/app/answers/detail/a_id/5442/related/1)
* [ NVIDIA GPU Display Driver - March 2023](/app/answers/detail/a_id/5452/related/1)








