# NVIDIA GPU Display Driver (Bulletin ID: 5230)



 NVIDIA GPU Display Driver - October 2021
===========================================================




 Updated 11/02/2021 11:41 AM



NVIDIA has released a software security update for NVIDIA GPU Display Driver. This update addresses issues that may lead to multiple security impacts.


To protect your system, download and install this software update through the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software update, through the NVIDIA Licensing Portal.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.


#### NVIDIA GPU Display Driver




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2021‑1115 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for private IOCTLs, where an attacker with local unprivileged system access may cause a NULL pointer dereference, which may lead to denial of service in a component beyond the vulnerable component. | 6.5 | [AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H) |
| CVE‑2021‑1116 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`), where a NULL pointer dereference in the kernel, created within user mode code, may lead to a denial of service in the form of a system crash. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2021‑1117 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape, where an attacker through specific configuration and with local unprivileged system access may cause improper input validation, which may lead to denial of service. | 4.7 | [AV:L/AC:H/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:N/S:U/C:N/I:N/A:H) |


#### NVIDIA vGPU Software




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2021‑1118 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where there is the potential to execute privileged operations by the guest OS, which may lead to information disclosure, data tampering, escalation of privileges, and denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1119 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where it can double-free a pointer, which may lead to denial of service. This flaw may result in a write-what-where condition, allowing an attacker to execute arbitrary code impacting integrity and availability. | 7.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H) |
| CVE‑2021‑1120 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where a string provided by the guest OS may not be properly null terminated. The guest OS or attacker has no ability to push content to the plugin through this vulnerability, which may lead to information disclosure, data tampering, unauthorized code execution, and denial of service. | 7.0 | [AV:L/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑1121 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager kernel driver, where a vGPU can cause resource starvation among other vGPUs hosted on the same GPU, which may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2021‑1122 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where it can dereference a NULL pointer, which may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2021‑1123 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where it can deadlock, which may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates for NVIDIA GPU Display Driver


The following table lists the NVIDIA software products affected, versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.


#### Windows




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- | --- |
| CVE‑2021‑1115 CVE‑2021‑1116 CVE‑2021‑1117 | GeForce | Windows | R495 | All drivers versions prior to 496.49 | 496.49 |
| R470 | All driver versions prior to 472.39 | 472.39 |
| Studio | Windows | R470 | All drivers versions prior to 472.39 | 472.39 |
| NVIDIA RTX/Quadro, NVS | Windows | R495 | All driver versions 496.49 | 496.49 |
| R470 | All driver versions prior to 472.39 | 472.39 |
| R460 | All driver versions prior to 463.15 | 463.15 |
| R390 | All driver versions prior to T392.68 | 392.68 |
| Tesla | Windows | R470 | All driver versions prior to 472.50 | 472.50 |
| R460 | All driver versions prior to 463.15 | 463.15 |
| R450 | All driver versions prior to 453.23 | 453.23 |
| R418 | All driver versions prior to 427.60 | 427.60 |


##### Notes


* Your computer hardware vendor may provide you with Windows GPU display driver versions including 472.08, which also contain the security updates.
* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, NVIDIA recommends upgrading to the latest branch release.


### Security Updates for NVIDIA vGPU Software


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Log in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal.




| \*\*CVE IDs Addressed\*\* | \*\*vGPU Software Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | \*\*vGPU Software\*\* | \*\*Driver\*\* |
| CVE‑2021‑1117 | vGPU software (guest driver) | Windows | All versions prior to 13.1 | 471.68 | 13.1 | 472.39 |
| All versions prior to 12.4 | 462.96 | 12.4 | 463.15 |
| All versions prior to 11.6 | 453.10 | 11.6 | 453.23 |
| All versions prior 8.9 | 427.48 | 8.9 | 427.60 |
| CVE‑2021‑1118 CVE‑2021‑1119 CVE‑2021‑1120 CVE‑2021‑1121 CVE‑2021‑1122 CVE‑2021‑1123 | vGPU software (Virtual GPU Manager) | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM, Nutanix AHV | All versions prior to 13.1 | 470.63 | 13.1 | 470.82 |
| All versions prior to 12.4 | 460.91.03 | 12.4 | 460.107 |
| All versions prior to 11.6 | 450.142 | 11.6 | 450.156 |
| All versions prior 8.9 | 418.213 | 8.9 | 418.226.00 |


#### Notes


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an updated version is not listed above, NVIDIA recommends upgrading to the latest branch release.


### Mitigations


See [Security Updates for NVIDIA GPU Display Driver](#security-updates-display-driver) or [Security Updates for NVIDIA vGPU Software](#security-updates-vgpu-software) for the version to install.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 3.0 | November 2, 2021 | Added version information for the updated vGPU software 13.1 drivers and the Tesla R470 Windows driver |
| 2.0 | October 28, 2021 | Updated the availability date for vGPU software 13.1 and the Tesla R470 Windows driver release |
| 1.0 | October 26, 2021 | Initial release |


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


* [ NVIDIA GPU Display Drivers - July 2021](/app/answers/detail/a_id/5211/related/1)
* [ NVIDIA GPU Display Driver - April 2021](/app/answers/detail/a_id/5172/related/1)
* [ NVIDIA GPU Display Driver - January 2021](/app/answers/detail/a_id/5142/related/1)
* [ NVIDIA GPU Display Driver - September 2020](/app/answers/detail/a_id/5075/related/1)
* [ NVIDIA GPU Display Driver - June 2020](/app/answers/detail/a_id/5031/related/1)








