# NVIDIA GPU Display Driver (Bulletin ID: 5468)



 NVIDIA GPU Display Driver - June 2023
========================================================




 Updated 06/27/2023 08:03 AM



NVIDIA has released a software security update for NVIDIA GPU Display Driver. This update addresses issues that may lead to code execution, denial of service, escalation of privileges, data tampering, or information disclosure. 


To protect your system, download and install this software update through the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software update, through the NVIDIA Licensing Portal.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.


#### NVIDIA GPU Display Driver




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE-2022-34671 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the user-mode layer, where an unprivileged user can cause an out-of-bounds write, which may lead to code execution, information disclosure, and denial of service. | 8.5 | [CWE: 787](https://cwe.mitre.org/data/definitions/787.html) [AV:N/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2023‑25515 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability where unexpected untrusted data is parsed, which may lead to code execution, denial of service, escalation of privileges, data tampering, or information disclosure. | 7.8 | [CWE: 822](https://cwe.mitre.org/data/definitions/822.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2023‑25516 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer, where an unprivileged user can cause an integer overflow, which may lead to information disclosure and denial of service. | 7.1 | [CWE: 190](https://cwe.mitre.org/data/definitions/190.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:H) |


#### NVIDIA vGPU Software




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2023‑25517 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where a guest OS may be able to control resources for which it is not authorized, which may lead to information disclosure and data tampering. | 7.1 | [CWE: 285](https://cwe.mitre.org/data/definitions/285.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates for NVIDIA GPU Display Driver


#### CVE IDs Addressed in Each Windows Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows driver branch.




| \*\*Windows Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R535, R525, R470, R450 | CVE-2022-34671, CVE‑2023‑25515 |


#### Security Updates for NVIDIA GPU Windows Display Driver


The following table lists the NVIDIA software products affected, Windows driver versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Windows | R535 | All driver versions prior to 536.23 | 536.23 |
| Windows 10 and 11 | R470 | All drivers versions prior to 474.44 for support of [GeForce Kepler desktop](https://nvidia.custhelp.com/app/answers/detail/a\_id/5202/kw/kepler%20desktop) | 474.44 |
| Windows 7 and 8.\*x\* | R470 | All driver versions prior to 474.44 | 474.44 |
| Studio | Windows | R535 | All driver versions | Available the week of June 29, 2023 |
| NVIDIA RTX, Quadro, NVS | Windows | R535 | All driver versions prior to 536.25 | 536.25 |
| R525 | All driver versions prior to 529.11 | 529.11 |
| R470 | All driver versions prior to 474.44 | 474.44 |
| Tesla | Windows | R535 | All driver versions prior to 536.25 | 536.25 |
| R525 | All driver versions prior to 529.11 | 529.11 |
| R470 | All driver versions prior to 474.44 | 474.44 |
| R450 | All driver versions prior to 454.23 | 454.23 |


#### CVE IDs Addressed in Each Linux Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux driver branch.




| \*\*Linux Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R535, R525, R470, R450 | CVE‑2023‑25515, CVE‑2023‑25516 |


#### Security Updates for NVIDIA GPU Linux Display Driver


The following table lists the NVIDIA software products affected, Linux driver versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Linux | R535 | All driver versions prior to 535.54.03 | 535.54.03 |
| R525 | All driver versions prior to 525.125.06 | 525.125.06 |
| R470 | All driver versions prior to 470.199.02 | 470.199.02 |
| NVIDIA RTX, Quadro, NVS | Linux | R535 | All driver versions prior to 535.54.03 | 535.54.03 |
| R525 | All driver versions prior to 525.125.06 | 525.125.06 |
| R470 | All driver versions prior to 470.199.02 | 470.199.02 |
| Tesla | Linux | R535 | All driver versions prior to 535.54.03 | 535.54.03 |
| R525 | All driver versions prior to 525.125.06 | 525.125.06 |
| R470 | All driver versions prior to 470.199.02 | 470.199.02 |
| R450 | All driver versions prior to 450.248.02 | 450.248.02 |


**Notes**


* Your computer hardware vendor may provide you with Windows GPU display driver versions including 536.19,531.87, 529.08, 574.44, and 454.23, which also contain the security updates.
* The tables above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, upgrade to the latest branch release.


### Security Updates for NVIDIA vGPU Software


#### CVE IDs Addressed in Each Windows vGPU Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows driver branch.




| \*\*Windows Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R535, R525, R470, R450 | CVE-2022-34671, CVE‑2023‑25515 |


#### CVE IDs Addressed in Each Linux vGPU Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux vGPU driver branch




| \*\*Linux Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R535, R525, R470, R450 | CVE‑2023‑25516 |


#### CVE IDs Addressed in Each vGPU Manager Driver Branch


The following table lists the CVE IDs addressed by the update in each vGPU Manager driver branch




| \*\*vGPU Manager Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R535, R525 | CVE‑2023‑25516, CVE‑2023‑25517 |
| R470, R450 | CVE‑2023‑25516 |


#### Affected Products, Affected Versions, and Updated Versions


The following table lists NVIDIA software products affected, versions affected, and the updated version that includes this security update.




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | Updated Version | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | vGPU Software | Driver |
| CVE-2022-34671 CVE‑2023‑25515 | vGPU software (guest driver) | Windows | All versions prior to and including 15.2 | 528.89 | 15.3 | 529.11 |
| All versions prior to and including 13.7 | 474.30 | 13.8 | 474.44 |
| All versions prior to and including 11.12 | 454.14 | 11.13 | 454.23 |
| CVE‑2023‑25516 | vGPU software (guest driver) | Linux | All versions prior to and including 15.2 | 525.105.17 | 15.3 | 525.125.06 |
| All versions prior to and including 13.7 | 470.182.03 | 13.8 | 470.199.02 |
| All versions prior to and including 11.12 | 450.236.01 | 11.13 | 450.248.02 |
| CVE‑2023‑25516 CVE‑2023‑25517 | vGPU software (Virtual GPU Manager) | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM | All versions prior to and including 15.2 | 525.105.14 | 15.3 | 525.125.03 |
| All versions prior to and including 13.7 | 470.182.02 | 13.8 | 470.199.03 |
| All versions prior to and including 11.12 | 450.236.03 | 11.13 | 450.248.03 |


**Notes**


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, upgrade to the latest branch release.


### Security Updates for NVIDIA Cloud Gaming


#### CVE IDs Addressed in Each Windows Cloud Gaming Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows driver branch.




| \*\*Windows Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R535, R525, R470, R450 | CVE-2022-34671, CVE‑2023‑25515 |


#### CVE IDs Addressed in Each Linux Cloud Gaming Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux Cloud Gaming driver branch




| \*\*Linux Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R535, R525, R470, R450 | CVE-2022-34671, CVE‑2023‑25515 |


#### CVE IDs Addressed in Each Cloud Gaming Manager Driver Branch


The following table lists the CVE IDs addressed by the update in each Cloud Gaming Manager driver branch




| \*\*vGPU Manager Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R535, R525 | CVE‑2023‑25516, CVE‑2023‑25517 |
| R470, R450 | CVE‑2023‑25516 |


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* | \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* |
| CVE-2022-34671 CVE‑2023‑25515 | NVIDIA Cloud Gaming (guest driver) | Windows | All versions prior to and including May 2023 release | All versions prior to 531.79 | June 2023 release | 536.25 |
| CVE‑2023‑25516 | NVIDIA Cloud Gaming (guest driver) | Linux | All versions prior to and including May 2023 release | All versions prior to 530.51 | June 2023 release | 535.54.03 |
| CVE‑2023‑25516 CVE‑2023‑25517 | NVIDIA Cloud Gaming (Virtual GPU Manager) | Red Hat Enterprise Linux KVM | All versions prior to and including May 2023 release | All versions prior to 530.51 | June 2023 release | 535.54.06 |


### Acknowledgements


NVIDIA thanks the following people for reporting these issues:


CVE-2022-34671: Piotr Bania - Cisco Talos


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | June 26, 2023 | Initial release |


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


* [ NVIDIA GPU Display Driver - March 2023](/app/answers/detail/a_id/5452/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson AGX Orin Series - January 2023](/app/answers/detail/a_id/5442/related/1)
* [ NVIDIA CUDA Toolkit - March 2023](/app/answers/detail/a_id/5446/related/1)
* [ NVIDIA GeForce Experience - January 2023](/app/answers/detail/a_id/5384/related/1)
* [ NVIDIA Omniverse Kit - January 2023](/app/answers/detail/a_id/5418/related/1)








