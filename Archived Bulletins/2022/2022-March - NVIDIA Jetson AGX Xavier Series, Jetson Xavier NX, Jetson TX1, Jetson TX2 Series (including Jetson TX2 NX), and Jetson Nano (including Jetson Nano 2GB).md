# NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) (Bulletin ID: 5321)



 NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) - March 2022
=======================================================================================================================================================================================




 Updated 03/08/2022 03:08 PM



NVIDIA has released a software update for NVIDIA® Jetson AGX Xavier™ series, Jetson Xavier™ NX, Jetson TX1, Jetson TX2 series (including Jetson TX2 NX), and Jetson Nano™ devices (including Jetson Nano 2GB) in the NVIDIA JetPack™ software development kit (SDK). The update addresses security issues that may lead to denial of service, escalation of privileges, and impact to data integrity and confidentiality.


To protect your system, download and install the latest NVIDIA JetPack SDK from [Jetson Download Center](https://developer.nvidia.com/embedded/downloads).


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).

 



---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/v3.1/user-guide) standards.


 



| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2021‑34401 | NVIDIA Linux kernel distributions contain a vulnerability in `nvmap` `NVGPU\_IOCTL\_CHANNEL\_SET\_ERROR\_NOTIFIER`, where improper access control may lead to code execution, compromised integrity, or denial of service. The scope impact may extend to other components. | 8.8 | [AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2021‑4034 | NVIDIA Jetson sample file system contains a vulnerability related in polkit's `pkexec` utility which can lead to local privilege escalation, causing impact to data confidentiality, data integrity, and service availability. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑21819 | NVIDIA distributions of Jetson Linux contain a vulnerability where an error in the IOMMU configuration may allow an unprivileged attacker with physical access to the board direct read/write access to the entire system address space through the PCI bus. Such an attack could result in denial of service, code execution, escalation of privileges, and impact to data integrity and confidentiality. The scope impact may extend to other components. | 7.6 | [AV:P/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:P/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. To protect your system, download and install the latest NVIDIA JetPack SDK from [Jetson Download Center](https://developer.nvidia.com/embedded/downloads).




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2021‑4034 CVE‑2021‑34401 | Jetson AGX Xavier series, Jetson Xavier NX,  Jetson TX1, Jetson TX2 series, Jetson TX2 NX | Jetson Linux | All 32.\*x\* versions prior to 32.7.1 | 32.7.1 |
| CVE‑2021‑4034 CVE‑2021‑34401 CVE‑2022‑21819 | Jetson Nano, Jetson Nano 2GB | Jetson Linux | All 32.\*x\* versions prior to 32.7.1 | 32.7.1 |


#### Notes:


* Earlier software releases that support this product are also affected. If you are using an earlier release, upgrade to the latest branch release.


### Mitigations


None. See [Security Updates](#security-updates) for the version to install.


### Acknowledgements


CVE‑2022‑21819 - NVIDIA thanks Bennie Affleck of The Good Penguin Ltd for reporting this issue.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | March 8, 2022 | Initial release |


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


* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB)- August 2021](/app/answers/detail/a_id/5216/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) - June 2021](/app/answers/detail/a_id/5205/related/1)
* [ NVIDIA SHIELD TV - January 2022](/app/answers/detail/a_id/5259/related/1)
* [ NVIDIA GeForce Experience - December 2021](/app/answers/detail/a_id/5295/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) - June 2023](/app/answers/detail/a_id/5466/related/1)








