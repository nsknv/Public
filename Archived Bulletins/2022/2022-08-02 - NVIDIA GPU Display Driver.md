# NVIDIA GPU Display Driver (Bulletin ID: 5383)



 NVIDIA GPU Display Driver - August 2022
==========================================================




 Updated 08/16/2022 11:29 AM



NVIDIA has released a software security update for NVIDIA GPU Display Driver. This update addresses issues that may lead to denial of service, information disclosure, escalation of privileges, code execution, or data tampering.


To protect your system, download and install this software update through the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software and NVIDIA Cloud Gaming updates, through the NVIDIA Licensing Portal.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.


#### NVIDIA GPU Display Driver




| \*\*CVE IDs\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑31606 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape, where a failure to properly validate data might allow an attacker with basic user capabilities to cause an out-of-bounds access in kernel mode, which could lead to denial of service, information disclosure, escalation of privileges, or data tampering. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑31607 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer (`nvidia.ko`), where a local user with basic capabilities can cause improper input validation, which may lead to denial of service, escalation of privileges, data tampering, and limited information disclosure. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑31608 | NVIDIA GPU Display Driver for Linux contains a vulnerability in an optional D-Bus configuration file, where a local user with basic capabilities can impact protected D-Bus endpoints, which may lead to code execution, denial of service, escalation of privileges, information disclosure, and data tampering. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑31610 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`), where a local user with basic capabilities can cause an out-of-bounds write, which may lead to code execution, denial of service, escalation of privileges, information disclosure, or data tampering. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑31617 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`), where a local user with basic capabilities can cause an out-of-bounds read, which may lead to code execution, denial of service, escalation of privileges, information disclosure, or data tampering. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑31612 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape, where a local user with basic capabilities can cause an out-of-bounds read, which may lead to a system crash or a leak of internal kernel information. | 7.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:H) |
| CVE‑2022‑31613 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer, where any local user can cause a null-pointer dereference, which may lead to a kernel panic. | 7.1 | [AV:L/AC:L/PR:N/UI:N/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:C/C:N/I:N/A:H) |
| CVE‑2022‑34665 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer, where a local user with basic capabilities can cause a null-pointer dereference, which may lead to denial of service. | 6.5 | [AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H) |
| CVE‑2022‑34666 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer, where a local user with basic capabilities can cause a null-pointer dereference, which may lead to denial of service. | 6.5 | [AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H) |
| CVE‑2022‑31616 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape, where a local user with basic capabilities can cause an out-of-bounds read, which may lead to denial of service, or information disclosure. | 6.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:N/A:H) |
| CVE‑2022‑31615 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer, where a local user with basic capabilities can cause a null-pointer dereference, which may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |


#### NVIDIA vGPU Software




| \*\*CVE IDs\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑31609 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where it allows the guest VM to allocate resources for which the guest is not authorized. This vulnerability may lead to loss of data integrity and confidentiality, denial of service, or information disclosure. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑31614 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin) where it may double-free some resources. An attacker may exploit this vulnerability with other vulnerabilities to cause denial of service, code execution, and information disclosure. | 7.0 | [AV:L/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑31618 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where it can dereference a null pointer, which may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates for NVIDIA GPU Display Driver


#### CVE IDs Addressed in Each Windows Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows driver branch.




| \*\*Windows Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R515, R510, R470, R450 | CVE‑2022‑31606, CVE‑2022‑31610, CVE‑2022‑31612, CVE‑2022‑31613, CVE‑2022‑31616, CVE‑2022‑31617, CVE‑2022‑34665, CVE‑2022‑34666 |


#### Security Updates for NVIDIA GPU Windows Display Driver


The following table lists the NVIDIA software products affected, Windows driver versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Windows | R515 | All driver versions prior to 516.94 | 516.94 |
| Windows 10 and 11 | R470 | All driver versions prior to 473.81 | 473.81 |
| Windows 7 and 8.\*x\* | R470 | All driver versions prior to 473.81 for [support of desktop Kepler-series GPUs](https://nvidia.custhelp.com/app/answers/detail/a\_id/5202/kw/kepler%20desktop) | 473.81 |
| Studio | Windows | R515 | All driver versions prior to 516.94 | 516.94 |
| NVIDIA RTX/Quadro, NVS | Windows | R515 | All driver versions prior to 516.94 | 516.94 |
| R510 | All driver versions prior to 513.46 | 513.46 |
| R470 | All driver versions prior to 473.81 | 473.81 |
| Tesla | Windows | R515 | All driver versions prior to 516.94 | 516.94 |
| R510 | All driver versions prior to 513.46 | 513.46 |
| R470 | All driver versions prior to 472.81 | 473.81 |
| R450 | All driver versions prior to 453.64 | 453.64 |


#### CVE IDs Addressed in Each Linux Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux driver branch.







| \*\*Linux Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R515, R510, R470, R450, R390 | CVE‑2022‑31607, CVE‑2022‑31608, CVE‑2022‑31615 |


#### Security Updates for NVIDIA GPU Linux Display Driver


The following table lists the NVIDIA software products affected, Linux driver versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Linux | R515 | All driver versions prior to 515.65.01 | 515.65.01 |
| R510 | All driver versions prior to 510.85.02 | 510.85.02 |
| R470 | All driver versions prior to 470.141.03 | 470.141.03 |
| R390 | All driver versions prior to 390.154 | 390.154 |
| NVIDIA RTX, Quadro, NVS | Linux | R515 | All driver versions prior to 515.65.01 | 515.65.01 |
| R510 | All driver versions prior to 510.85.02 | 510.85.02 |
| R470 | All driver versions prior to 470.141.03 | 470.141.03 |
| R390 | All driver versions prior to 390.154 | 390.154 |
| Tesla | Linux | R515 | All driver versions prior to 515.65.01 | 515.65.01 |
| R510 | All driver versions prior to 510.85.02 | 510.85.02 |
| R470 | All driver versions prior to 470.141.03 | 470.141.03 |
| R450 | All driver versions prior to 450.203.03 | 450.203.03 |


**Notes:**
* Your computer hardware vendor may provide you with Windows GPU display driver versions including 516.54, 513.39, 473.70 and 453.64 which also contain the security updates.
* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, NVIDIA recommends upgrading to the latest branch release.


### Security Updates for NVIDIA vGPU Software


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Log in to the  [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal.












| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | \*\*vGPU Software\*\* | \*\*Driver\*\* |
| CVE‑2022‑31606 CVE‑2022‑31610 CVE‑2022‑31612 CVE‑2022‑31613 CVE‑2022‑31616 CVE‑2022‑31617 CVE‑2022‑34665 CVE‑2022‑34666 | vGPU software (guest driver) | Windows | All versions prior to and including 14.1 | 512.78 | 14.2 | 513.46 |
| All versions prior to and including 13.3 | 473.47 | 13.4 | 473.81 |
| All versions prior to and including 11.8 | 453.51 | 11.9 | 453.64 |
| CVE‑2022‑34665 CVE‑2022‑34666 CVE‑2022‑31613 | vGPU software (guest driver) | Linux | All versions prior to and including 14.1 | 510.73.08 | 14.2 | 510.85.02 |
| All versions prior to and including 13.3 | 470.129.06 | 13.4 | 470.141.03 |
| All versions prior to and including 11.8 | 450.191.01 | 11.9 | 450.203.02 |
| CVE‑2022‑31609 CVE‑2022‑31613 CVE‑2022‑31614 CVE‑2022‑34665 CVE‑2022‑34666 CVE‑2022‑31618 | vGPU software (Virtual GPU Manager) | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM | All versions prior to and including 14.1 | 510.73.06 | 14.2 | 510.85.03 |
| All versions prior to and including 13.3 | 470.129.04 | 13.4 | 470.141.05 |
| All versions prior to and including 11.8 | 450.191 | 11.9 | 450.203 |


**Notes:**


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, NVIDIA recommends upgrading to the latest branch release.


### Security Updates for NVIDIA Cloud Gaming


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. 












| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* | \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* |
| CVE‑2022‑31606 CVE‑2022‑31610 CVE‑2022‑31612 CVE‑2022‑31613 CVE‑2022‑31616 CVE‑2022‑31617 CVE‑2022‑34665 CVE‑2022‑34666 | NVIDIA Cloud Gaming (guest driver) | Windows | All versions prior to the August 2022 release | All versions prior to 516.94 | August 2022 release | 516.94 |
| CVE‑2022‑31607 CVE‑2022‑31613 CVE‑2022‑34665 CVE‑2022‑34666 | NVIDIA Cloud Gaming (guest driver) | Linux | All versions prior to the August 2022 release | All versions prior to 515.65.01 | August 2022 release | 515.65.01 |
| CVE‑2022‑31607 CVE‑2022‑31609 CVE‑2022‑31613 CVE‑2022‑31614 CVE‑2022‑34665 CVE‑2022‑34666 | NVIDIA Cloud Gaming(Virtual GPU Manager) | Citrix Hypervisor, Red Hat Enterprise Linux KVM | All versions prior to the August 2022 release | All versions prior to 515.65.01 | August 2022 release | 515.65.01 |


### Acknowledgements


NVIDIA thanks the following people for reporting the issues to us:


* CVE‑2022‑31606, CVE‑2022‑31612, CVE‑2022‑31616, and CVE‑2022‑31617 - Thierry Doré of Quarkslab
* CVE‑2022‑31607 - Le Wu of Baidu Security
* CVE‑2022‑31608 - Artem S. Tashkinov
* CVE‑2022‑31615 - Tal Lossos


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 2.0 | August 16, 2022 | Updated the availability of updated drivers for GeForce and Studio on Windows and for all NVIDIA Cloud Gaming drivers |
| 1.0 | August 2, 2022 | Initial release |


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


* [ NVIDIA GPU Display Driver - May 2022](/app/answers/detail/a_id/5353/related/1)
* [ NVIDIA GPU Display Drivers - July 2021](/app/answers/detail/a_id/5211/related/1)
* [ NVIDIA GPU Display Driver - April 2021](/app/answers/detail/a_id/5172/related/1)
* [ NVIDIA GPU Display Driver - January 2021](/app/answers/detail/a_id/5142/related/1)
* [ NVIDIA GPU Display Driver - October 2021](/app/answers/detail/a_id/5230/related/1)








