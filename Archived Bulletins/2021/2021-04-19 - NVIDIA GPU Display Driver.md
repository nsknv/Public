# NVIDIA GPU Display Driver (Bulletin ID: 5172)



 NVIDIA GPU Display Driver - April 2021
=========================================================




 Updated 10/05/2021 01:54 PM



NVIDIA has released a software security update for NVIDIA GPU Display Driver. This update addresses issues that may lead to code execution, denial of service, escalation of privileges, and information disclosure.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


To protect your system, download and install this software update through the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software update, through the NVIDIA Licensing Portal.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).
------------------------------------------------------------------






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.


#### NVIDIA GPU Display Driver





This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.


| \*\*CVE IDs\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2021‑1074 | NVIDIA Windows GPU Display Driver installer contains a vulnerability where an attacker with local unprivileged system access may be able to replace an application resource with malicious files. This attack requires a user with system administration rights to execute the installer and requires the attacker to replace the files in a very short time window between file integrity validation and execution. Such an attack may lead to code execution, escalation of privileges, denial of service, and information disclosure. | 7.3 | [AV:L/AC:L/PR:L/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:R/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1075 | NVIDIA Windows GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape where the program dereferences a pointer that contains a location for memory that is no longer valid, which may lead to code execution, denial of service, or escalation of privileges. An attacker does not have any control over the information and may conduct only limited data modification. | 7.3 | [AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:L/A:H) |
| CVE‑2021‑1076 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer (`nvlddmkm.sys` or `nvidia.ko`) where improper access control may lead to denial of service, information disclosure, or data corruption. | 6.6 | [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:H) |
| CVE‑2021‑1077 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability where the software uses a reference count to manage a resource that is incorrectly updated, which may lead to denial of service. | 6.6 | [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:H) |
| CVE‑2021‑1078 | NVIDIA Windows GPU Display Driver for Windows contains a vulnerability in the kernel driver (`nvlddmkm.sys`) where a NULL pointer dereference may lead to system crash. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


#### NVIDIA vGPU Software




The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.
| \*\*CVE IDs\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2021‑1080 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), in which certain input data is not validated, which may lead to information disclosure, tampering of data, or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1081 | NVIDIA vGPU software contains a vulnerability in the guest kernel mode driver and Virtual GPU manager (vGPU plugin), in which an input length is not validated, which may lead to information disclosure, tampering of data, or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1082 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), in which an input length is not validated, which may lead to information disclosure, tampering of data, or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1083 | NVIDIA vGPU software contains a vulnerability in the guest kernel mode driver and Virtual GPU Manager (vGPU plugin), in which an input length is not validated, which may lead to information disclosure, tampering of data, or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1084 | NVIDIA vGPU driver contains a vulnerability in the guest kernel mode driver and Virtual GPU Manager (vGPU plugin), in which an input length is not validated, which may lead to information disclosure, tampering of data, or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1085 | NVIDIA vGPU driver contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where there is the potential to write to a shared memory location and manipulate the data after the data has been validated, which may lead to denial of service, escalation of privileges, and information disclosure but attacker doesn't have control over what information is obtained. | 7.3 | [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:H/A:H) |
| CVE‑2021‑1086 | NVIDIA vGPU driver contains a vulnerability in the Virtual GPU Manager (vGPU plugin) where it allows guests to control unauthorized resources, which may lead to integrity and confidentiality loss or information disclosure. | 7.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N) |
| CVE‑2021‑1087 | NVIDIA vGPU driver contains a vulnerability in the Virtual GPU Manager (vGPU plugin), which could allow an attacker to retrieve information that could lead to a Address Space Layout Randomization (ASLR) bypass. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N) |


### Security Updates for NVIDIA GPU Display Driver


This section provides details of the security update for each affected operating system. Download the update for your operating system from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.


#### Windows


##### CVE IDs Addressed in Each Windows Driver Branch


The following table lists the CVE IDs addressed by the update in each driver branch.




The following table lists the CVE IDs addressed by the update in each driver branch.




| \*\*Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R465, R418 | CVE‑2021‑1075, CVE‑2021‑1076, CVE‑2021‑1078 |
| R460, R450 | CVE‑2021‑1075, CVE‑2021‑1076, CVE‑2021‑1077, CVE‑2021‑1078 |
| R390 | CVE‑2021‑1074, CVE‑2021‑1075, CVE‑2021‑1076, CVE‑2021‑1078 |


##### Affected Products, Affected Versions, and Updated Version for Windows


The following table lists the NVIDIA software products affected, versions affected, and the updated driver versions available from nvidia.com that address the CVE IDs listed above.




The following table lists the NVIDIA software products affected, versions affected, and the updated driver versions available from nvidia.com that address the CVE IDs listed above.
| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Windows | R465 | All versions prior to 466.11 | 466.11 |
| R460 | All versions prior to 462.31 | 462.31 |
| NVIDIA RTX/Quadro, NVS | Windows | R465 | All versions prior to 466.11 | 466.11 |
| R460 | All versions prior to 462.31 | 462.31 |
| R450 | All versions prior to 452.96 | 452.96 |
| R390 | All versions prior to 392.65 | 392.65 |
| Tesla | Windows | R460 | All versions prior to 462.31 | 462.31 |
| R450 | All versions prior to 452.96 | 452.96 |
| R418 | All versions prior to 427.33 | 427.33 |


#### Linux


##### CVE IDs Addressed in Each Linux Driver Branch


The following table lists the CVE IDs addressed by the update in each driver branch.




The following table lists the CVE IDs addressed by the update in each driver branch.




| \*\*Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R465, R418, R390 | CVE‑2021‑1076 |
| R460, R450 | CVE‑2021‑1076, CVE‑2021‑1077 |


##### Affected Products, Affected Versions, and Updated Version for Linux


The following table lists the NVIDIA software products affected, versions affected, and the updated driver versions available from nvidia.com that address the CVE IDs listed above.




The following table lists the NVIDIA software products affected, versions affected, and the updated driver versions available from nvidia.com that address the CVE IDs listed above.
| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce NVIDIA RTX/Quadro, NVS | Linux | R465 | All versions prior to 465.24.02 | 465.24.02 |
| R460 | All versions prior to 460.73.01 | 460.73.01 |
| R450 | All versions prior to 450.119.03 | 450.119.03 |
| R390 | All versions prior to 390.143 | 390.143 |
| Tesla | Linux | R460 | All versions prior to 460.73.01 | 460.73.01 |
| R450 | All versions prior to 450.119.03 | 450.119.03 |
| R418 | All versions prior to 418.197.02 | 418.197.02 |


#### Notes


* Your computer hardware vendor may provide you with Windows GPU display driver versions, including 465.99 and 462.30, which also contain the security updates.
* The tables above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products are also affected. If you are using an earlier branch release, upgrade to the latest branch release.


### Security Updates for NVIDIA vGPU Software


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Log in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal.




The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Log in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal.
| \*\*CVE IDs Addressed\*\* | \*\*vGPU Software Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | \*\*vGPU Software\*\* | \*\*Driver\*\* |
| CVE‑2021‑1075 CVE‑2021‑1076 CVE‑2021‑1077 CVE‑2021‑1078 CVE‑2021‑1081 CVE‑2021‑1083 CVE‑2021‑1084 | vGPU software (guest driver) | Windows | All versions prior to 12.2 | All versions prior to 462.31 | 12.2 | 462.31 |
| All versions prior to 11.4 | All versions prior to 452.96 | 11.4 | 452.96 |
| CVE‑2021‑1076 CVE‑2021‑1077 CVE‑2021‑1081 CVE‑2021‑1083 CVE‑2021‑1084 | vGPU software (guest driver) | Linux | All versions prior to 12.2 | All versions prior to 460.73.01 | 12.2 | 460.73.01 |
| All versions prior to 11.4 | All versions prior to 450.119.03 | 11.4 | 450.119.03 |
| CVE‑2021‑1080 CVE‑2021‑1081 CVE‑2021‑1082 CVE‑2021‑1083 CVE‑2021‑1084 CVE‑2021‑1085 CVE‑2021‑1086 CVE‑2021‑1087 | vGPU software (Virtual GPU Manager) | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM | All versions prior to 12.2 | All versions prior to 460.73.02 | 12.2 | 460.73.02 |
| All versions prior to 11.4 | All versions prior to 450.124 | 11.4 | 450.124 |
| CVE‑2021‑1075 CVE‑2021‑1076 CVE‑2021‑1078 CVE‑2021‑1081 | vGPU software (guest driver) | Windows | All versions prior to 8.7 | All versions prior to 427.33 | 8.7 | 427.33 |
| CVE‑2021‑1076 CVE‑2021‑1081 | vGPU software (guest driver) | Linux | All versions prior to 8.7 | All versions prior to 418.197.02 | 8.7 | 418.197.02 |
| CVE‑2021‑1080 CVE‑2021‑1081 CVE‑2021‑1082 CVE‑2021‑1085 CVE‑2021‑1086 CVE‑2021‑1087 | vGPU software (Virtual GPU Manager) | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM, Nutanix AHV | All versions prior to 8.7 | All versions prior to 418.196 | 8.7 | 418.196 |


#### Notes


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products are also affected. If you are using an earlier branch release, upgrade to the latest branch release.


### Mitigations


See [Security Updates for NVIDIA GPU Display Driver](#security-updates-display-driver) or [Security Updates for NVIDIA vGPU Software](#security-updates-vgpu-software) for the version to install.


### Acknowledgements


NVIDIA thanks Wenxiang Qian of Tencent Blade Team for reporting CVE‑2021‑1082, CVE‑2021‑1084, and CVE‑2021‑1087.


Issues CVE‑2021‑1081 and CVE‑2021‑1083 were discovered by the NVIDIA Product Security Team.


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
| 7.0 | June 29, 2021 | Updated the description for CVE‑2021‑1075 |
| 6.0 | May 27, 2021 | Updated the description and score for CVE-2021-1074 |
| 5.0 | May 5, 2021 | Clarified affected driver versions for vGPU software |
| 4.0 | April 30, 2021 | Updated information about security updates for vGPU software 12.2 |
| 3.0 | April 23, 2021 | Added information about CVEs and security updates for vGPU software |
| 2.0 | April 21, 2021 | Added information about the R450, R418, and R390 driver updates for Windows |
| 1.0 | April 19, 2021 | Initial release |


### Support


If you have any questions about this security bulletin, contact [NVIDIA Support](https://www.nvidia.com/object/support.html).


### Frequently Asked Questions (FAQs)


[How do I determine which NVIDIA display driver version is currently installed on my PC?](https://nvidia.custhelp.com/app/answers/detail/a_id/2039)


##### Disclaimer


ALL NVIDIA INFORMATION, DESIGN SPECIFICATIONS, REFERENCE BOARDS, FILES, DRAWINGS, DIAGNOSTICS, LISTS, AND OTHER DOCUMENTS (TOGETHER AND SEPARATELY, "MATERIALS") ARE BEING PROVIDED "AS IS." NVIDIA MAKES NO WARRANTIES, EXPRESS, IMPLIED, STATUTORY, OR OTHERWISE WITH RESPECT TO THE MATERIALS, AND ALL EXPRESS OR IMPLIED CONDITIONS, REPRESENTATIONS AND WARRANTIES, INCLUDING ANY IMPLIED WARRANTY OR CONDITION OF TITLE, MERCHANTABILITY, SATISFACTORY QUALITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT, ARE HEREBY EXCLUDED TO THE MAXIMUM EXTENT PERMITTED BY LAW.


Information is believed to be accurate and reliable at the time it is furnished. However, NVIDIA Corporation assumes no responsibility for the consequences of use of such information or for any infringement of patents or other rights of third parties that may result from its use. No license is granted by implication or otherwise under any patent or patent rights of NVIDIA Corporation. Specifications mentioned in this publication are subject to change without notice. This publication supersedes and replaces all information previously supplied. NVIDIA Corporation products are not authorized for use as critical components in life support devices or systems without express written approval of NVIDIA Corporation.










Is this answer helpful?
-----------------------



Yes
No







Answers others found helpful
----------------------------


* [ NVIDIA GPU Display Driver - January 2021](/app/answers/detail/a_id/5142/related/1)
* [ NVIDIA GPU Display Driver - June 2020](/app/answers/detail/a_id/5031/related/1)
* [ NVIDIA GPU Display Driver - September 2020](/app/answers/detail/a_id/5075/related/1)
* [ NVIDIA GPU Display Driver - November 2019](/app/answers/detail/a_id/4907/related/1)
* [ NVIDIA GPU Display Driver - February 2020](/app/answers/detail/a_id/4996/related/1)








