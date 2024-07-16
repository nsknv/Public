# NVIDIA SHIELD TV (Bulletin ID: 5259)



 NVIDIA SHIELD TV - January 2022
==================================================




 Updated 01/12/2022 12:22 PM



NVIDIA has released a software security update for NVIDIA SHIELD® TV. This update addresses issues that may lead to information disclosure, denial of service, code execution, or escalation of privileges. To protect your system, download and install this software update through **Settings**>**About**>**System update**.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section summarizes the potential impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS V3.1](https://www.first.org/cvss/user-guide) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2021‑1106 | NVIDIA Linux kernel distributions contain a vulnerability in `nvmap`, where writes may be allowed to read-only buffers, which may result in escalation of privileges, denial of service, information disclosure, or data tampering. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1107 | NVIDIA Linux kernel distributions contain a vulnerability in `nvmap` `NVMAP\_IOC\_WRITE\*` paths, where improper access controls may lead to code execution, denial of service, or compromised integrity of system components. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑34401 | NVIDIA Linux kernel distributions contain a vulnerability in `nvmap` `NVGPU\_IOCTL\_CHANNEL\_SET\_ERROR\_NOTIFIER`, where improper access control may lead to code execution, compromised integrity, or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1108 | NVIDIA Linux kernel distributions contain a vulnerability in FuSa Capture (VI/ISP), where integer underflow caused by lack of input validation may lead to complete denial of service, partial integrity, and serious confidentiality loss for all processes in the system. | 7.3 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:L/A:H) |
| CVE‑2021‑34402 | NVIDIA Tegra kernel driver contains a vulnerability in NVIDIA NVDEC, where a user with high privileges might be able to read from or write to a memory location that is outside the intended boundary of the buffer, which may lead to denial of service, Information disclosure, loss of Integrity, or possible escalation of privileges. | 6.7 | [AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑34403 | NVIDIA Linux distributions contain a vulnerability in nvmap ioctl, which allows any user with a local account to exploit a use-after-free condition, leading to code privilege escalation, loss of confidentiality and integrity, or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑34404 | Android images for T210 provided by NVIDIA contain a vulnerability in BROM, where failure to limit access to AHB-DMA when BROM fails may allow an unprivileged attacker with physical access to cause denial of service or impact integrity and confidentiality beyond the security scope of BROM. | 7.1 | [AV:P/AC:H/PR:N/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:P/AC:H/PR:N/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2021‑34405 | NVIDIA Linux distributions contain a vulnerability in TrustZone’s `TEE\_Malloc` function, where an unchecked return value causing a null pointer dereference may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2021‑1112 | NVIDIA Linux kernel distributions contain a vulnerability in `nvmap`, where a null pointer dereference may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2021‑34406 | NVIDIA Tegra kernel driver contains a vulnerability in NVHost, where a specific race condition can lead to a null pointer dereference, which may lead to a system reboot. | 4.7 | [AV:L/AC:H/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:N/S:U/C:N/I:N/A:H) |


SHIELD TV update includes Android™ Security Patch level **2021-09-05**. For more information about what is included in Android security patch levels, refer to the [Android Security Bulletins](https://source.android.com/security/bulletin).


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Download the update through Settings>About>System update.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- |
| SHIELD TV | Android-P | Shield Experience prior to SE 9.0 | Shield Experience Upgrade SE 9.0 |


**Note:**


* Earlier releases of this product are also affected. If you are using an earlier release, upgrade to the latest release.


### Mitigations


See [Security Updates](#security-updates) for the version to install.


### Acknowledgements


CVE‑2021‑34406: NVIDIA thanks Billy Laws for reporting this issue.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | January 12, 2022 | Initial release |


### Support


If you have any questions about this Security Bulletin, contact [NVIDIA Support](https://www.nvidia.com/object/support.html).


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
* [ NVIDIA GPU Display Driver - October 2021](/app/answers/detail/a_id/5230/related/1)
* [ NVIDIA GPU Display Drivers - July 2021](/app/answers/detail/a_id/5211/related/1)
* [ NVIDIA GPU Display Driver - April 2021](/app/answers/detail/a_id/5172/related/1)
* [ NVIDIA GPU Display Driver - June 2020](/app/answers/detail/a_id/5031/related/1)








