# NVIDIA GPU Display Driver (Bulletin ID: 5142)



 NVIDIA GPU Display Driver - January 2021
===========================================================




 Updated 10/05/2021 01:43 PM



NVIDIA has released a software security update for NVIDIA® GPU Display Driver. This update addresses issues that may lead to denial of service, escalation of privileges, data tampering, or information disclosure.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


To protect your system, download and install this software update from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software update, from the NVIDIA Licensing Portal.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security.](https://www.nvidia.com/security/)
------------------------------------------------------------------

 



---




### Details


This section provides a summary of potential vulnerabilities and their impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS](https://www.first.org/cvss/user-guide) v3.1 standards.


#### NVIDIA GPU Display Driver




This section provides a summary of potential vulnerabilities and their impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS](https://www.first.org/cvss/user-guide) v3.1 standards
| \*\*CVE IDs\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2021‑1051 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape in which a local user can get elevated privileges to modify display configuration data, which may result in denial of service of the display. | 8.4 | [AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:H/A:H) |
| CVE‑2021‑1052 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape or IOCTL in which user-mode clients can access legacy privileged APIs, which may lead to denial of service, escalation of privileges, and information disclosure. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1053 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape or IOCTL in which improper validation of a user pointer may lead to denial of service. | 6.6 | [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:H) |
| CVE‑2021‑1054 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape in which the software does not perform or incorrectly performs an authorization check when an actor attempts to access a resource or perform an action, which may lead to denial of service. | 6.5 | [AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H) |
| CVE‑2021‑1055 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape in which improper access control may lead to denial of service and information disclosure. | 5.3 | [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L) |
| CVE‑2021‑1056 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer (`nvidia.ko`) in which it does not completely honor operating system file system permissions to provide GPU device-level isolation, which may lead to denial of service or information disclosure. | 5.3 | [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L) |


#### NVIDIA vGPU Software




NVIDIA vGPU Software| \*\*CVE IDs\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2021‑1057 | NVIDIA vGPU manager contains a vulnerability in the vGPU plugin in which it allows guests to allocate some resources for which the guest is not authorized, which may lead to integrity and confidentiality loss, denial of service, or information disclosure. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1058 | NVIDIA vGPU software contains a vulnerability in the guest kernel mode driver and vGPU plugin, in which an input data size is not validated, which may lead to tampering of data or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1059 | NVIDIA vGPU manager contains a vulnerability in the vGPU plugin, in which an input index is not validated, which may lead to integer overflow, which in turn may cause tampering of data, information disclosure, or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1060 | NVIDIA vGPU software contains a vulnerability in the guest kernel mode driver and vGPU plugin, in which an input index is not validated, which may lead to tampering of data or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1061 | NVIDIA vGPU manager contains a vulnerability in the vGPU plugin, in which a race condition may cause the vGPU plugin to continue using a previously validated resource that has since changed, which may lead to denial of service or information disclosure. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1062 | NVIDIA vGPU manager contains a vulnerability in the vGPU plugin, in which an input data length is not validated, which may lead to tampering of data or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1063 | NVIDIA vGPU manager contains a vulnerability in the vGPU plugin, in which an input offset is not validated, which may lead to a buffer overread, which in turn may cause tampering of data, information disclosure, or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1064 | NVIDIA vGPU manager contains a vulnerability in the vGPU plugin, in which it obtains a value from an untrusted source, converts this value to a pointer, and dereferences the resulting pointer, which may lead to information disclosure or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1065 | NVIDIA vGPU manager contains a vulnerability in the vGPU plugin, in which input data is not validated, which may lead to tampering of data or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1066 | NVIDIA vGPU manager contains a vulnerability in the vGPU plugin, in which input data is not validated, which may lead to unexpected consumption of resources, which in turn may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates for NVIDIA GPU Display Driver


The following table lists the NVIDIA software products affected, versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.


#### Windows




Windows
| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- | --- |
| CVE‑2021‑1051 CVE‑2021‑1052 CVE‑2021‑1053 CVE‑2021‑1054 CVE‑2021‑1055 | GeForce | Windows | R460 | All versions prior to 461.09 | 461.09 |
| NVIDIA RTX/Quadro, NVS | Windows | R460 | All versions prior to 461.09 | 461.09 |
| R450 | All versions prior to 452.77 | 452.77 |
| R390 | All versions prior to 392.63 | 392.63 |
| Tesla | Windows | R460 | All versions prior to 461.09 | 461.09 |
| R450 | All versions prior to 452.77 | 452.77 |
| R418 | All versions prior to 427.11 | 427.11 |


#### Linux




Linux
| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- | --- |
| CVE‑2021‑1052 CVE‑2021‑1053 | GeForce | Linux | R460 | All versions prior to 460.32.03 | 460.32.03 |
| R450 | All versions prior to 450.102.04 | 450.102.04 |
| NVIDIA RTX/Quadro, NVS | Linux | R460 | All versions prior to 460.32.03 | 460.32.03 |
| R450 | All versions prior to 450.102.04 | 450.102.04 |
| Tesla | Linux | R460 | All versions prior to 460.32.03 | 460.32.03 |
| R450 | All versions prior to 450.102.04 | 450.102.04 |
| CVE‑2021‑1056 | GeForce | Linux | R460 | All versions prior to 460.32.03 | 460.32.03 |
| R450 | All versions prior to 450.102.04 | 450.102.04 |
| NVIDIA RTX/Quadro, NVS | Linux | R460 | All versions prior to 460.32.03 | 460.32.03 |
| R450 | All versions prior to 450.102.04 | 450.102.04 |
| R390 | All version prior to 390.141 | 390.141 |
| Tesla | Linux | R460 | All versions prior to 460.32.03 | 460.32.03 |
| R450 | All versions prior to 450.102.04 | 450.102.04 |
| R418 | All versions prior to 418.181.07 | 418.181.07 |


#### **Notes**


* Your computer hardware vendor may provide you with Windows GPU display driver versions including 460.84, 457.49, and 452.66, which also contain the security updates.
* CVE‑2021‑1052 and CVE‑2021‑1053 affect only R460 and R450 driver branches for Windows and Linux.
* The tables above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products are also affected. If you are using an earlier branch release, upgrade to the latest branch release.


### Security Updates for NVIDIA vGPU Software


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Log in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal.




The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Log in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal
| \*\*CVE IDs Addressed\*\* | \*\*vGPU Software Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | \*\*vGPU Software\*\* | \*\*Driver\*\* |
| CVE‑2021‑1051 CVE‑2021‑1052 CVE‑2021‑1053 CVE‑2021‑1054 CVE‑2021‑1055 CVE‑2021‑1058 CVE‑2021‑1060 | vGPU software (guest driver) | Windows | All versions prior to 11.3 | All versions prior to 452.77 | 11.3 | 452.77 |
|
|
| All versions prior to 8.6 | All versions prior to 427.11 | 8.6 | 427.11 |
| CVE‑2021‑1052 CVE‑2021‑1053 CVE‑2021‑1056 CVE‑2021‑1058 CVE‑2021‑1060 | vGPU software (guest driver) | Linux | All versions prior to 11.3 | All versions prior to 450.102.04 | 11.3 | 450.102.04 |
|
| All versions prior to 8.6 | All versions prior to 418.181.07 | 8.6 | 418.181.07 |
|
| CVE‑2021‑1057 CVE‑2021‑1058 CVE‑2021‑1059 CVE‑2021‑1060 CVE‑2021‑1061 CVE‑2021‑1062 CVE‑2021‑1063 CVE‑2021‑1064 CVE‑2021‑1065 CVE‑2021‑1066 | vGPU software (Virtual GPU Manager) | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM, Nutanix AHV | All versions prior to 11.3 | All versions prior to 450.102 | 11.3 | 450.102 |
|
| All versions prior to 8.6 | All versions prior to 418.181 | 8.6 | 418.181 |
|


**Notes:**


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products are also affected. If you are using an earlier branch release, upgrade to the latest vGPU software branch release, namely, 11.3.


### Mitigations


See [Security Updates for NVIDIA GPU Display Driver](#security-updates-display-driver) or [Security Updates for NVIDIA vGPU Software](#security-updates-vgpu-software) for the version to install.


### Acknowledgements


NVIDIA thanks Xinyuan Lyu of Intelligent Mobile Systems Group, MOE KLINNS Lab, Xi'an Jiaotong University for reporting CVE‑2021‑1056.


Issues CVE‑2021‑1057, CVE‑2021‑1058, CVE-2021-1059, and CVE‑2021‑1062 were discovered by the NVIDIA Product Security Team.


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
| 6.0 | June 23, 2021 | Updated the description of CVE‑2021‑1051 |
| 5.0 | January 25, 2021 | Updated the Security Updates table for vGPU software to clarify which CVE IDs listed for GPU Display Driver also apply to the vGPU software guest drivers |
| 4.0 | January 21, 2021 | Re-arranged the Security Updates table for GPU Display Driver for Linux |
| 3.0 | January 19, 2021 | Updated the availability of the Linux drivers for Tesla |
| 2.0 | January 11, 2021 | Added acknowledgement for CVE-2021-1059 |
| 1.0 | January 7, 2021 | Initial release |


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


* [ NVIDIA GPU Display Driver - June 2020](/app/answers/detail/a_id/5031/related/1)
* [ NVIDIA GPU Display Driver - November 2019](/app/answers/detail/a_id/4907/related/1)
* [ NVIDIA GPU Display Driver - April 2021](/app/answers/detail/a_id/5172/related/1)
* [ NVIDIA GPU Display Driver - September 2020](/app/answers/detail/a_id/5075/related/1)
* [ NVIDIA GPU Display Driver - February 2019](/app/answers/detail/a_id/4772/related/1)








