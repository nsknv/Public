# NVIDIA GPU Display Drivers (Bulletin ID: 5211)



 NVIDIA GPU Display Drivers - July 2021
=========================================================




 Updated 10/05/2021 02:14 PM



NVIDIA has released a software security update for NVIDIA GPU Display Drivers. This update addresses issues that may lead to information disclosure, data tampering, and denial of service.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


To protect your system, download and install this software update through the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software update, through the NVIDIA Licensing Portal.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).
------------------------------------------------------------------






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.


#### NVIDIA GPU Display Driver




This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.
| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2021‑1089 | NVIDIA GPU Display Driver for Windows contains a vulnerability in `nvidia-smi` where an uncontrolled DLL loading path may lead to arbitrary code execution, denial of service, information disclosure, and data tampering. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1090 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for control calls where the software reads or writes to a buffer by using an index or pointer that references a memory location after the end of the buffer, which may lead to data tampering or denial of service. | 7.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H) |
| CVE‑2021‑1091 | NVIDIA GPU Display driver for Windows contains a vulnerability where an unprivileged user can create a file hard link that causes the driver to overwrite a file that requires elevated privilege to modify, which could lead to data loss or denial of service. | 7.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H) |
| CVE‑2021‑1092 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the NVIDIA Control Panel application where it is susceptible to a Windows file system symbolic link attack where an unprivileged attacker can cause the applications to overwrite privileged files, resulting in potential denial of service or data loss. | 7.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H) |
| CVE‑2021‑1093 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in firmware where the driver contains an `assert()` or similar statement that can be triggered by an attacker, which leads to an application exit or other behavior that is more severe than necessary, and may lead to denial of service or system crash. | 6.2 | [AV:L/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2021‑1094 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for `DxgkDdiEscape` where an out of bounds array access may lead to denial of service or information disclosure. | 6.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:N/A:H) |
| CVE‑2021‑1095 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handlers for all control calls with embedded parameters where dereferencing an untrusted pointer may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2021‑1096 | NVIDIA Windows GPU Display Driver for Windows contains a vulnerability in the NVIDIA kernel mode layer (`nvlddmkm.sys`) handler for `DxgkDdiEscape` where dereferencing a NULL pointer may lead to a system crash. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |


#### NVIDIA vGPU Software




NVIDIA vGPU Softwar
| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2021‑1097 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where it improperly validates the length field in a request from a guest. This flaw allows a malicious guest to send a length field that is inconsistent with the actual length of the input, which may lead to information disclosure, data tampering, or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1098 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where it doesn't release some resources during driver unload requests from guests. This flaw allows a malicious guest to perform operations by reusing those resources, which may lead to information disclosure, data tampering, or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1099 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin) that could allow an attacker to cause stack-based buffer overflow and put a customized ROP gadget on the stack. Such an attack may lead to information disclosure, data tampering, or denial of service. | 7.0 | [AV:L/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1100 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager kernel mode driver (`nvidia.ko`), in which a pointer to a user-space buffer is not validated before it is dereferenced, which may lead to denial of service. | 6.2 | [AV:L/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2021‑1101 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where it can dereference a NULL pointer, which may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2021‑1102 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where it can lead to floating point exceptions, which may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2021‑1103 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where it can dereference a NULL pointer, which may lead to denial of service. | 4.4 | [AV:L/AC:L/PR:H/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:U/C:N/I:N/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates for NVIDIA GPU Display Driver


The following table lists the NVIDIA software products affected, versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for vGPU software, through the NVIDIA Licensing Portal. 


#### Windows


##### CVE IDs Addressed in Each Windows Driver Branch


The following table lists the CVE IDs addressed by the update in each driver branch.




The following table lists the CVE IDs addressed by the update in each driver branch.
| \*\*Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R470, R465, R460 | CVE‑2021‑1089, CVE‑2021‑1090, CVE‑2021‑1091, CVE‑2021‑1092, CVE‑2021‑1093, CVE‑2021‑1094, CVE‑2021‑1095, CVE‑2021‑1096 |
| R450, R418, R390 | CVE‑2021‑1089, CVE‑2021‑1090, CVE‑2021‑1092, CVE‑2021‑1093, CVE‑2021‑1094, CVE‑2021‑1095, CVE‑2021‑1096 |


##### Affected Products, Affected Versions, and Updated Version for Windows


The following table lists the NVIDIA software products affected, versions affected, and the updated driver versions available from nvidia.com that address the CVE IDs listed in the previous table.




The following table lists the NVIDIA software products affected, versions affected, and the updated driver versions available from nvidia.com that address the CVE IDs listed in the previous table.
| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce, Studio | Windows | R470 | All versions prior to 471.41 | 471.41 |
| NVIDIA RTX/Quadro, NVS | Windows | R470 | All versions prior to 471.41 | 471.41 |
| R460 | All versions prior to 462.96 | 462.96 |
| R450 | All versions prior to 453.10 | 453.10 |
| R390 | All versions prior to 392.67 | 392.67 |
| Tesla | Windows | R470 | All versions prior to 471.41 | 471.41 |
| R460 | All versions prior to 462.96 | 462.96 |
| R450 | All versions prior to 453.10 | 453.10 |
| R418 | All versions prior to 427.48 | 427.48 |


#### Linux


##### CVE IDs Addressed in Each Linux Driver Branch


The following table lists the CVE IDs addressed by the update in each driver branch.




The following table lists the CVE IDs addressed by the update in each driver branch.
| \*\*Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R470, R460, R450, R418, R390 | CVE‑2021‑1093, CVE‑2021‑1094, CVE‑2021‑1095 |


##### Affected Products, Affected Versions, and Updated Version for Linux


The following table lists the NVIDIA software products affected, versions affected, and the updated driver versions available from nvidia.com that address the CVE IDs listed in the previous table.




The following table lists the NVIDIA software products affected, versions affected, and the updated driver versions available from nvidia.com that address the CVE IDs listed in the previous table.
| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Linux | R470 | All versions | 470.57.02 |
| R460 | All versions prior to 460.91.03 | 460.91.03 |
| NVIDIA RTX/Quadro, NVS | Linux | R470 | All versions | 470.57.02 |
| R460 | All versions prior to 460.91.03 | 460.91.03 |
| R390 | All versions prior to 390.144 | 390.144 |
| Tesla | Linux | R470 | All versions | 470.57.02 |
| R460 | All versions prior to 460.91.03 | 460.91.03 |
| R450 | All versions prior to 450.142.00 | 450.142.00 |
| R418 | All versions prior to 418.211.00 | 418.211.00 |


#### Notes


* Your computer hardware vendor may provide you with Windows GPU display driver versions including 462.86, 466.83, 471.35 and 471.36, which also contain the security updates.
* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products are also affected. If you are using an earlier branch release, upgrade to the latest branch release.


### Security Updates for NVIDIA vGPU Software


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Log in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal.




The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Log in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal.
| \*\*CVE IDs Addressed\*\* | \*\*vGPU Software Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | \*\*vGPU Software\*\* | \*\*Driver\*\* |
| CVE‑2021‑1089 CVE‑2021‑1090 CVE‑2021‑1091 CVE‑2021‑1092 CVE‑2021‑1093 CVE‑2021‑1094 CVE‑2021‑1095 CVE‑2021‑1096 | vGPU software (guest driver) | Windows | All versions prior to 12.3 | 462.31 | 12.3 | 462.96 |
| All versions prior to 11.5 | 452.96 | 11.5 | 453.10 |
| All versions prior 8.8 | 427.33 | 8.8 | 427.48 |
| CVE‑2021‑1093 CVE‑2021‑1094 CVE‑2021‑1095 | vGPU software (guest driver) | Linux | All versions prior to 12.3 | 460.73.01 | 12.3 | 460.91.03 |
| All versions prior to 11.5 | 450.119.03 | 11.5 | 450.142.00 |
| All versions prior to 8.8 | 418.197.02 | 8.8 | 418.211.00 |
| CVE‑2021‑1097 CVE‑2021‑1098 CVE‑2021‑1099 CVE‑2021‑1100 CVE‑2021‑1101 CVE‑2021‑1102 CVE‑2021‑1103 | vGPU software (Virtual GPU Manager) | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM, Nutanix AHV | All versions prior to 12.3 | 460.73.02 | 12.3 | 460.91.03 |
| All versions prior to 11.5 | 450.124 | 11.5 | 450.142 |
| All versions prior to 8.8 | 418.196 | 8.8 | 418.213 |


#### Notes


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products are also affected. If you are using an earlier branch release, upgrade to the latest branch release.


### Mitigations


See [Security Updates for NVIDIA GPU Display Driver](#security-updates-display-driver) or [Security Updates for NVIDIA vGPU Software](#security-updates-vgpu-software) for the version to install.


### Acknowledgements


NVIDIA thanks the following individuals for reporting issues to us:


* Fabian Toepfer - CVE‑2021‑1090, CVE‑2021‑1095, CVE‑2021‑1096
* Wenxiang Qian of Tencent Blade Team - CVE‑2021‑1099, CVE‑2021‑1100


CVE‑2021‑1103 was discovered by the NVIDIA Product Security Team.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History




Revision History





| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | July 20, 2021 | Initial release |


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


* [ NVIDIA GPU Display Driver - April 2021](/app/answers/detail/a_id/5172/related/1)
* [ NVIDIA GPU Display Driver - January 2021](/app/answers/detail/a_id/5142/related/1)
* [ NVIDIA GPU Display Driver - June 2020](/app/answers/detail/a_id/5031/related/1)
* [ NVIDIA GPU Display Driver - September 2020](/app/answers/detail/a_id/5075/related/1)
* [ NVIDIA GPU Display Driver - November 2019](/app/answers/detail/a_id/4907/related/1)








