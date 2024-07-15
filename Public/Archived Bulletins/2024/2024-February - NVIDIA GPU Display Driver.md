# NVIDIA GPU Display Driver (Bulletin ID: 5520)



 NVIDIA GPU Display Driver - February 2024
============================================================




 Updated 02/28/2024 09:01 AM



NVIDIA has released a software security update for NVIDIA GPU Display Driver to address the issues that are disclosed in this bulletin.


To protect your system, download and install this software update through the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software and Cloud Gaming updates, through the NVIDIA Licensing Portal.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.


#### NVIDIA GPU Display Driver




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Vector\*\* | \*\*Base Score\*\* | \*\*Severity\*\* | \*\*CWE\*\* | \*\*Impacts\*\* |
| --- | --- | --- | --- | --- | --- | --- |
| CVE‑2024‑0071 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the user mode layer, where an unprivileged regular user can cause an out-of-bounds write. A successful exploit of this vulnerability may lead to code execution, denial of service, escalation of privileges, information disclosure, and data tampering. | [AV:L/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H) | 7.8 | High | [CWE‑125](https://cwe.mitre.org/data/definitions/125.html) | Code execution, denial of service, escalation of privileges, information disclosure, data tampering |
| CVE‑2024‑0073 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer when the driver is performing an operation at a privilege level that is higher than the minimum level required. A successful exploit of this vulnerability may lead to code execution, denial of service, escalation of privileges, information disclosure, and data tampering. | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) | 7.8 | High | [CWE‑250](https://cwe.mitre.org/data/definitions/250.html) | Code execution, denial of service, escalation of privileges, information disclosure, data tampering |
| CVE‑2024‑0074 | NVIDIA GPU Display Driver for Linux contains a vulnerability where an attacker may access a memory location after the end of the buffer. A successful exploit of this vulnerability may lead to denial of service and data tampering. | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H) | 7.1 | High | [CWE‑788](https://cwe.mitre.org/data/definitions/788.html) | Denial of service, data tampering |
| CVE‑2024‑0078 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer, where a user in a guest can cause a NULL-pointer dereference in the host, which may lead to denial of service. | [AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H) | 6.5 | Medium | [CWE‑476](https://cwe.mitre.org/data/definitions/476.html) | Denial of service |
| CVE‑2024‑0075 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability where a user may cause a NULL-pointer dereference by accessing passed parameters the validity of which has not been checked. A successful exploit of this vulnerability may lead to denial of service and limited information disclosure. | [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:N/A:H) | 6.1 | Medium | [CWE-476](https://cwe.mitre.org/data/definitions/476.html) | Denial of service, limited information disclosure |
| CVE‑2022‑42265 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer handler, where an unprivileged regular user can cause integer overflow, which may lead to denial of service, information disclosure, and data tampering. | [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L)[L](https://cwe.mitre.org/data/definitions/190.html) | 5.3 | Medium | [CWE‑190](https://cwe.mitre.org/data/definitions/190.html) | Denial of service, information disclosure, and data tampering |


#### NVIDIA vGPU Software




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Vector\*\* | \*\*Base Score\*\* | \*\*Severity\*\* | \*\*CWE\*\* | \*\*Impacts\*\* |
| --- | --- | --- | --- | --- | --- | --- |
| CVE‑2024‑0077 | NVIDIA Virtual GPU Manager contains a vulnerability in the vGPU plugin, where it allows a guest OS to allocate resources for which the guest OS is not authorized. A successful exploit of this vulnerability may lead to code execution, denial of service, escalation of privileges, information disclosure, and data tampering. | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) | 7.8 | High | [CWE‑285](https://cwe.mitre.org/data/definitions/285.html) | Code execution, denial of service, escalation of privileges, information disclosure, data tampering |
| CVE‑024‑0079 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer, where a user in a guest VM can cause a NULL-pointer dereference in the host. A successful exploit of this vulnerability may lead to denial of service. | [AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H) | 6.5 | Medium | [CWE‑476](https://cwe.mitre.org/data/definitions/476.html) | Denial of service |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates for NVIDIA GPU Display Driver


#### CVE IDs Addressed in Each Windows Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows driver branch.




| \*\*Windows Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R550, R545, R535 | CVE‑2024‑0071, CVE‑2024‑0073, CVE‑2024‑0078, CVE‑2024‑0075, |
| R470 | CVE‑2024‑0071, CVE‑2024‑0073, CVE‑2024‑0078, CVE‑2022‑42265 |


#### Security Updates for NVIDIA GPU Windows Display Driver


The following table lists the NVIDIA software products affected, Windows driver versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Windows | R550 | All driver versions prior to 551.61 | 551.61 |
| Windows 10 and 11 | R470 | All driver versions prior to 474.82 for support of [GeForce Kepler desktop](https://nvidia.custhelp.com/app/answers/detail/a\_id/5202/kw/kepler%20desktop) | 474.82 |
| Windows 7 and 8.x | R470 | All driver versions prior to 474.89 | 474.89 |
| Studio | Windows | R550 | All driver versions prior to 551.61 | 551.61 |
| NVIDIA RTX, Quadro, NVS | Windows | R550 | All driver versions prior to 551.61 | 551.61 |
| R535 | All driver versions prior to 538.33 | 538.33 |
| R470 | All driver versions prior to 474.82 | 474.82 |
| Tesla | Windows | R550 | All driver versions prior to 551.61 | 551.61 |
| R535 | All driver versions prior to 538.33 | 538.33 |
| R470 | All driver versions prior to 474.82 | 474.82 |


#### CVE IDs Addressed in Each Linux Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux driver branch.




| \*\*Linux Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R550, R545, R535 | CVE‑2024‑0074, CVE‑2024‑0075 |
| R470 | CVE‑2024‑0074, CVE-2022-42265 |


#### Security Updates for NVIDIA GPU Linux Display Driver


The following table lists the NVIDIA software products affected, Linux driver versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Linux | R550 | All driver versions prior to 550.54.14 | 550.54.14 |
| R535 | All driver versions prior to 535.161.07 | 535.161.07 |
| R470 | All driver versions prior to 470.239.06 | 470.239.06 |
| NVIDIA RTX, Quadro, NVS | Linux | R550 | All driver versions prior to 550.54.14 | 550.54.14 |
| R535 | All driver versions prior to 535.161.07 | 535.161.07 |
| R470 | All driver versions prior to 470.239.06 | 470.239.06 |
| Tesla | Linux | R550 | All driver versions prior to 550.54.14 | 550.54.14 |
| R535 | All driver versions prior to 535.161.07 | 535.161.07 |
| R470 | All driver versions prior to 470.239.06 | 470.239.06 |


#### Notes


* Your computer hardware vendor may provide you with Windows GPU display driver versions including 552.34, 546.59, 538.18 and 474.80, which also contain the security updates.
* The tables above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, upgrade to the latest branch release.


### Security Updates for NVIDIA vGPU Software


#### CVE IDs Addressed in Each Windows vGPU Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows vGPU driver branch.




| \*\*Windows Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R535 | CVE‑2024‑0071, CVE‑2024‑0073, CVE‑2024‑0074, CVE‑2024‑0075, CVE‑2024‑0078 |
| R470 | CVE‑2024‑0071, CVE‑2024‑0073, CVE‑2024‑0074, CVE‑2024‑0078, CVE‑2022‑42265 |


#### CVE IDs Addressed in Each Linux vGPU Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux vGPU driver branch.




| \*\*Linux Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R535 | CVE‑2024‑0074, CVE‑2024‑0075, CVE‑2024‑0078 |
| R470 | CVE‑2024‑0074, CVE‑2024‑0078, CVE‑2022‑42265 |


#### CVE IDs Addressed in Each vGPU Manager Driver Branch


The following table lists the CVE IDs addressed by the update in each vGPU Manager driver branch.




| \*\*vGPU Manager Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R535 | CVE‑2024‑0073, CVE‑2024‑0074, CVE‑2024‑0075, CVE‑2024‑0077, CVE‑2024‑0078, CVE‑2024‑0079 |
| R470 | CVE‑2024‑0073, CVE‑2024‑0074, CVE‑2024‑0077, CVE‑2024‑0078, CVE‑2022‑4226 |


#### Affected Components, Affected Versions, and Updated Versions


The following table lists NVIDIA vGPU software components affected, versions affected, and the updated version that includes this security update.




| \*\*CVE IDs Addressed\*\* | \*\*vGPU Software Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | \*\*vGPU Software\*\* | \*\*Driver\*\* |
| CVE‑2024‑0071 CVE‑2024‑0073 CVE‑2024‑0074 CVE‑2024‑0075 CVE‑2024‑0078 CVE‑2022‑42265 | Guest driver | Windows | All versions up to and including 16.3 | 538.15 | 16.4 | 538.33 |
| All versions up to and including 13.9 | 474.64 | 13.10 | 474.82 |
| CVE‑2024‑0074 CVE‑2024‑0075 CVE‑2024‑0078 CVE-2022-42265 | Guest driver | Linux | All versions up to and including 16.3 | 535.154.05 | 16.4 | 535.161.07 |
| All versions up to and including 13.9 | 470.223.02 | 13.10 | 470.239.06 |
| CVE‑2024‑0074 CVE‑2024‑0075 CVE‑2024‑0077 CVE‑2024‑0078 CVE‑2024‑0079 CVE‑2022‑42265 | Virtual GPU Manager | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM, Ubuntu | All versions up to and including 16.3 | 535.154.02 | 16.4 | 535.161.05 |
| All versions up to and including 13.9 | 470.223.02 | 13.10 | 470.239.01 |
| CVE‑2024‑0073 CVE‑2024‑0074 CVE‑2024‑0075 CVE‑2024‑0077 CVE‑2024‑0078 CVE‑2024‑0079 CVE‑2022‑42265 | Virtual GPU Manager | Azure Stack HCI | All versions up to and including 16.3 | 538.15 | 16.4 | 538.33 |


**Notes:**


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, upgrade to the latest branch release.


### Security Updates for NVIDIA Cloud Gaming


#### CVE IDs Addressed in Each Windows Cloud Gaming Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows Cloud Gaming driver branch.




| \*\*Windows Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R545 | CVE‑2024‑0071, CVE‑2024‑0074, CVE‑2024‑0075, CVE‑2024‑0078 |


#### CVE IDs Addressed in Each Linux Cloud Gaming Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux Cloud Gaming driver branch.




| \*\*Linux Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R545 | CVE‑2024‑0074, CVE‑2024‑0075, CVE‑2024‑0078 |


#### CVE IDs Addressed in Each Cloud Gaming Manager Driver Branch


The following table lists the CVE IDs addressed by the update in each Cloud Gaming Manager driver branch.




| Gaming Manager Driver Branch | CVE IDs Addressed |
| --- | --- |
| R545 | CVE‑2024‑0073, CVE‑2024‑0074, CVE‑2024‑0075, CVE‑2024‑0077, CVE‑2024‑0078, CVE‑2024‑0079 |


#### Affected Components, Affected Versions, and Updated Versions


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.




| \*\*CVE IDs Addressed\*\* | \*\*Cloud Gaming Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | Updated Version | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* | Cloud Gaming Software | Driver |
| CVE‑2024‑0071 CVE‑2024‑0073 CVE‑2024‑0074 CVE‑2024‑0075 CVE‑2024‑0078 CVE‑2022‑422657 | Guest driver | Windows | All versions up to and including the January 2024 release | 546.65 | February 2024 release | 551.61 |
| CVE‑2024‑0074 CVE‑2024‑0075 CVE‑2024‑0078 CVE‑2022‑42265 | Guest driver | Linux | All versions up to and including the January 2024 release | 545.37.02 | February 2024 release | 550.54.14 |
| CVE‑2024‑0074 CVE‑2024‑0075 CVE‑2024‑0077 CVE‑2024‑0078 CVE‑2024‑0079 CVE‑2022‑42265 | Virtual GPU Manager | Red Hat Enterprise Linux KVM, VMware vSphere | All versions prior to and including the January 2024 release | 545.37.02 | February 2024 release | 550.54.10 |


### Acknowledgements


NVIDIA thanks the following people for reporting the issues:


CVE‑2024‑0071: Piotr Bania - Cisco Talos


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | February 28, 2024 | Initial release |


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


* [ NVIDIA GPU Display Driver - October 2023](/app/answers/detail/a_id/5491/related/1)
* [ NVIDIA GeForce NOW for Android - August 2023](/app/answers/detail/a_id/5476/related/1)
* [ NVIDIA DGX H100 - August 2023](/app/answers/detail/a_id/5473/related/1)
* [ NVIDIA DGX A100 and DGX A800 - June 2023](/app/answers/detail/a_id/5461/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) - June 2023](/app/answers/detail/a_id/5466/related/1)








