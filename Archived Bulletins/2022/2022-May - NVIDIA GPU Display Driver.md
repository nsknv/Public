# NVIDIA GPU Display Driver (Bulletin ID: 5353)



 NVIDIA GPU Display Driver - May 2022
=======================================================




 Updated 05/24/2022 10:02 AM



NVIDIA has released a software security update for NVIDIA GPU Display Driver. This update addresses issues that may lead to denial of service, information disclosure, or data tampering.


To protect your system, download and install this software update through the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software update, through the NVIDIA Licensing Portal.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.


#### NVIDIA GPU Display Driver




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑28181 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer, where an unprivileged regular user on the network can cause an out-of-bounds write through a specially crafted shader, which may lead to code execution, denial of service, escalation of privileges, information disclosure, and data tampering. The scope of the impact may extend to other components. | 8.5 | [AV:N/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2022‑28182 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the DirectX11 user mode driver (`nvwgf2um/x.dll`), where an unauthorized attacker on the network can cause an out-of-bounds write through a specially crafted shader, which may lead to code execution to cause denial of service, escalation of privileges, information disclosure, and data tampering. The scope of the impact may extend to other components. | 8.5 | [AV:N/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2022‑28183 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer, where an unprivileged regular user can cause an out-of-bounds read, which may lead to denial of service and information disclosure. | 7.7 | [AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:H) |
| CVE‑2022‑28184 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer (nvlddmkm.sys) handler for DxgkDdiEscape, where an unprivileged regular user can access administrator- privileged registers, which may lead to denial of service, information disclosure, and data tampering. | 7.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N)[N](https://cwe.mitre.org/data/definitions/284.html) |
| CVE‑2022‑28185 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the ECC layer, where an unprivileged regular user can cause an out-of-bounds write, which may lead to denial of service and data tampering. | 6.8 | [AV:L/AC:L/PR:N/UI:N/S:U/C:N/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:N/I:L/A:H) |
| CVE‑2022‑28186 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape, where the product receives input or data, but does not validate or incorrectly validates that the input has the properties that are required to process the data safely and correctly, which may lead to denial of service or data tampering. | 6.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:H) |
| CVE‑2022‑28187 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`), where the memory management software does not release a resource after its effective lifetime has ended, which may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2022‑28188 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape, where the product receives input or data, but does not validate or incorrectly validates that the input has the properties that are required to process the data safely and correctly, which may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2022‑28189 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape, where a NULL pointer dereference may lead to a system crash. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2022‑28190 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (nvlddmkm.sys) handler for DxgkDdiEscape, where improper input validation can cause denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |


#### NVIDIA vGPU Software




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑28191 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (`nvidia.ko`), where uncontrolled resource consumption can be triggered by an unprivileged regular user, which may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2022‑28192 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (`nvidia.ko`), where it may lead to a use-after-free, which in turn may cause denial of service. This attack is complex to carry out because the attacker needs to have control over freeing some host side resources out of sequence, which requires elevated privileges. | 4.1 | [AV:L/AC:H/PR:H/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:U/C:N/I:N/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates for NVIDIA GPU Display Driver


#### CVE IDs Addressed in Each Windows Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows driver branch.




| \*\*Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R510 | CVE‑2022‑28181, CVE‑2022‑28182, CVE‑2022‑28183, CVE‑2022‑28184, CVE‑2022‑28185, CVE‑2022‑28186, CVE‑2022‑28187, CVE‑2022‑28188, CVE‑2022‑28189, CVE‑2022‑28190 |
| R470 | CVE‑2022‑28181, CVE‑2022‑28182, CVE‑2022‑28183, CVE‑2022‑28184, CVE‑2022‑28185, CVE‑2022‑28186, CVE‑2022‑28188, CVE‑2022‑28189 |
| R450 | CVE‑2022‑28181, CVE‑2022‑28182, CVE‑2022‑28185, CVE‑2022‑28186, CVE‑2022‑28188, CVE‑2022‑28189 |


#### Security Updates for NVIDIA GPU Windows Display Driver


The following table lists the NVIDIA software products affected, versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Windows | R510 | All versions prior to 512.77 | 512.77 |
| Studio | Windows | R510 | All versions prior to 512.96 | 512.96 |
| NVIDIA RTX/Quadro, NVS | Windows | R510 | All versions prior to 512.78 | 512.78 |
| R470 | All versions prior to 473.47 | 473.47 |
| Tesla | Windows | R510 | All versions prior to 512.78 | 512.78 |
| R470 | All versions prior to 473.47 | 473.47 |
| R450 | All versions prior to 453.51 | 453.51 |


##### Notes:


* Your computer hardware vendor may provide you with Windows GPU display driver versions including 512.36 and 473.34 which also contain the security updates.
* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, NVIDIA recommends upgrading to the latest branch release.


#### CVE IDs Addressed in Each Linux Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux driver branch.




| \*\*Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R510 and R470 | CVE‑2022‑28181, CVE‑2022‑28183, CVE‑2022‑28184, CVE‑2022‑28185, CVE‑2022‑28191, CVE‑2022‑28192 |
| R450 | CVE‑2022‑28181, CVE‑2022‑28185, CVE‑2022‑28192 |
| R390 | CVE‑2022‑28181, CVE‑2022‑28185 |


#### Security Updates for NVIDIA GPU Linux Display Driver


The following table lists the NVIDIA software products affected, versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce, NVIDIA RTX/Quadro, NVS | Linux | R510 | All versions prior to 510.73.05 | 510.73.05 |
| R470 | All versions prior to 470.129.06 | 470.129.06 |
| R390 | All versions prior to 390.151 | 390.151 |
| Tesla | Linux | R510 | All versions prior to 510.73.08 | 510.73.08 |
| R470 | All versions prior to 470.129.06 | 470.129.06 |
| R450 | All versions prior to 450.191.01 | 450.191.01 |


### Security Updates for NVIDIA vGPU Software


The following table lists the NVIDIA vGPU software components affected, versions affected, and the updated version that includes this security update. Log in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal.




| \*\*CVE IDs Addressed\*\* | \*\*vGPU Software Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | \*\*vGPU Software\*\* | \*\*Driver\*\* |
| CVE‑2022‑28181 CVE‑2022‑28182 CVE‑2022‑28183 CVE‑2022‑28184 CVE‑2022‑28185 CVE‑2022‑28186 CVE‑2022‑28188 CVE‑2022‑28189 CVE‑2022‑28190 | vGPU software (guest driver) | Windows | All versions prior to and including 14.0 | 511.65 | 14.1 | 512.78 |
| All versions prior to and including 13.2 | 472.98 | 13.3 | 473.47 |
| All versions prior to and including 11.7 | 453.37 | 11.8 | 453.51 |
| CVE‑2022‑28181 CVE‑2022‑28183 CVE‑2022‑28184 CVE‑2022‑28185 | vGPU software (guest driver) | Linux | All versions prior to and including 14.0 | 510.47.03 | 14.1 | 510.73.08 |
| All versions prior to and including 13.2 | 470.103.01 | 13.3 | 470.129.06 |
| All versions prior to and including 11.7 | 450.172.01 | 11.8 | 450.191.01 |
| CVE‑2022‑28183 CVE‑2022‑28184 CVE‑2022‑28185 CVE‑2022‑28191 CVE‑2022‑28192 | vGPU software (Virtual GPU Manager) | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM | All versions prior to and including 14.0 | 510.47.03 | 14.1 | 510.73.06 |
| All versions prior to and including 13.2 | 470.103.02 | 13.3 | 470.129.04 |
| All versions prior to and including 11.7 | 450.172 | 11.8 | 450.191 |


#### Notes:


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, NVIDIA recommends upgrading to the latest branch release.


### Security Updates for NVIDIA Cloud Gaming


The following table lists the NVIDIA Cloud Gaming components affected, versions affected, and the updated version. Log in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal.




| \*\*CVE IDs Addressed\*\* | \*\*Cloud Gaming Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* | \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* |
| CVE‑2022‑28181 CVE‑2022‑28182 CVE‑2022‑28183 CVE‑2022‑28184 CVE‑2022‑28185 CVE‑2022‑28186 CVE‑2022‑28188 CVE‑2022‑28189 CVE‑2022‑28190 | Cloud Gaming Guest Driver | Windows | All versions prior to and including the April 2022 Cloud Gaming Release | 512.59 | May 2022 Cloud Gaming Release | 512.78 |
| CVE‑2022‑28181 CVE‑2022‑28183 CVE‑2022‑28184 CVE‑2022‑28185 | Cloud Gaming Guest Driver | Linux | All versions prior to and including the April 2022 Cloud Gaming Release | 510.68.02 | May 2022 Cloud Gaming Release | 510.73.05 |
| CVE‑2022‑28183 CVE‑2022‑28184 CVE‑2022‑28185 CVE‑2022‑28191 CVE‑2022‑28192 | Cloud Gaming Virtual GPU Manager | Citrix Hypervisor, Red Hat Enterprise Linux with KVM | All versions prior to and including the April 2022 Cloud Gaming Release | 510.68.02 | May 2022 Cloud Gaming Release | 510.73.06 |


#### Notes:


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, NVIDIA recommends upgrading to the latest branch release.


### Mitigations


None. For the version to install, refer to:


* [Security Updates for NVIDIA GPU Display Driver](#security-updates-for-nvidia-gpu-display-driver)
* [Security Updates for NVIDIA vGPU Software](#security-updates-for-nvidia-vgpu-software)
* [Security Updates for NVIDIA Cloud Gaming](#security-updates-for-nvidia-cloud-gaming)


### Acknowledgements


NVIDIA thanks Piotr Bania of Cisco Talos for reporting CVE‑2022‑28181 and CVE 2022-28182.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 2.0 | May 24, 2022 | Added version information for the updated R510 drivers for Studio and Tesla, and the vGPU software 14.1 driver |
| 1.0 | May 16, 2022 | Initial release |


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
* [ NVIDIA License System - February 2022](/app/answers/detail/a_id/5319/related/1)
* [ NVIDIA GPU Display Driver - January 2021](/app/answers/detail/a_id/5142/related/1)
* [Security Notice: NVIDIA Response to Security Incident - March 2022](/app/answers/detail/a_id/5333/related/1)








