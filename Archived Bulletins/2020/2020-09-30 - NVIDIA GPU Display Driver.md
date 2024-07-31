# NVIDIA GPU Display Driver (Bulletin ID: 5075)



 NVIDIA GPU Display Driver - September 2020
=============================================================




 Updated 10/05/2021 11:32 AM



NVIDIA has released a software security update for NVIDIA® GPU Display Driver. This update addresses issues that may lead to denial of service, code execution, escalation of privileges, or information disclosure.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


To protect your system, download and install this software update from the [NVIDIA Driver Downloads page](https://www.nvidia.com/Download/index.aspx) or, for the vGPU software update, through the NVIDIA Licensing Portal.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security.](https://www.nvidia.com/security/)
------------------------------------------------------------------






---




### Details


This section provides a summary of potential vulnerabilities and their impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS](https://www.first.org/cvss/user-guide) v3.0 standards.


#### NVIDIA GPU Display Driver




This section provides a summary of potential vulnerabilities and their impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS](https://www.first.org/cvss/user-guide) v3.0 standards.
| \*\*CVE IDs\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2020‑5979 | NVIDIA Display Driver contains a vulnerability in the Control Panel component in which a user is presented with a dialog box for input by a high-privilege process, which may lead to escalation of privileges. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2020‑5980 | NVIDIA Windows GPU Display Driver contains a vulnerability in multiple components in which a securely loaded system DLL will load its dependencies in an insecure fashion, which may lead to code execution or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2020‑5981 | NVIDIA Windows GPU Display Driver contains a vulnerability in the DirectX11 user mode driver (`nvwgf2um/x.dll`), in which a specially crafted shader can cause an out of bounds access, which may lead to denial of service or code execution. | 7.8 | [AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2020‑5982 | NVIDIA Windows GPU Display Driver contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) scheduler, in which the software does not properly limit the number or frequency of interactions that it has with an actor, such as the number of incoming requests, which may lead to denial of service. | 4.4 | [AV:L/AC:L/PR:H/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:U/C:N/I:N/A:H) |


#### NVIDIA vGPU Software




NVIDIA vGPU Software
| \*\*CVE IDs\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2020‑5983 | NVIDIA Virtual GPU Manager contains a vulnerability in the vGPU plugin and the host driver kernel module, in which the potential exists to write to a memory location that is outside the intended boundary of the frame buffer memory allocated to guest operating systems, which may lead to denial of service or information disclosure. | 8.8 | [AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2020‑5984 | NVIDIA Virtual GPU Manager contains a vulnerability in the vGPU plugin in which it may have the use-after-free vulnerability while freeing some resources, which may lead to denial of service, code execution, and information disclosure. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2020‑5985 | NVIDIA Virtual GPU Manager contains a vulnerability in the vGPU plugin, in which an input data length is not validated, which may lead to tampering or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2020‑5986 | NVIDIA Virtual GPU Manager contains a vulnerability in the vGPU plugin, in which an input data size is not validated, which may lead to tampering or denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2020‑5987 | NVIDIA Virtual GPU Manager contains a vulnerability in the vGPU plugin in which guest-supplied parameters remain writable by the guest after the plugin has validated them, which may lead to the guest being able to pass invalid parameters to plugin handlers, which may lead to denial of service or escalation of privileges. | 7.3 | [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:H/A:H) |
| CVE‑2020‑5988 | NVIDIA Virtual GPU Manager contains a vulnerability in the vGPU plugin, in which allocated memory can be freed twice, which may lead to information disclosure or denial of service. | 7.0 | [AV:L/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2020‑5989 | NVIDIA Virtual GPU Manager contains a vulnerability in the vGPU plugin, in which it can dereference a NULL pointer, which may lead to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration. 


### Security Updates for NVIDIA GPU Display Driver


The following table lists the NVIDIA software products affected, versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page. 


#### Windows




Windows
| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- | --- |
| CVE‑2020‑5980 CVE‑2020‑5979 CVE‑2020‑5981 CVE‑2020‑5982 | GeForce | Windows | R455 | All versions prior to 456.71 | 456.71 |
| Quadro, NVS | Windows | R455 | All versions prior to 456.71 | 456.71 |
| R450 | All versions prior to 452.39 | 452.39 |
| R440 | All versions prior to 443.66 | 443.66 |
| R390 | All versions prior to 392.62 | 392.62 |
| Tesla | Windows | R450 | All versions prior to 452.39 | 452.39 |
| R440 | All versions prior to 443.66 | 443.66 |
| R418 | All versions prior to 426.94 | 426.94 |


**Notes:**


* Your computer hardware vendor may provide you with Windows GPU display driver versions including 456.41, 452.11, and 446.29 which also contain the security updates.
* CVE‑2020‑5979 does not affect the R390 driver branch.
* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products are also affected. If you are using an earlier branch release, upgrade to the latest branch release.


### Security Updates for NVIDIA vGPU Software


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Log in to the  [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal.




The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Log in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal.
| \*\*CVE IDs Addressed\*\* | \*\*vGPU Software Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | \*\*vGPU Software\*\* | \*\*Driver\*\* |
| CVE‑2020‑5983 CVE‑2020‑5984 CVE‑2020‑5985 CVE‑2020‑5986 CVE‑2020‑5987 CVE‑2020‑5988 | Virtual GPU Manager | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM, Nutanix AHV | 11.0 | 450.55 | 11.1 | 450.80 |
| 10.3 | 440.107 | 10.4 | 440.121 |
| 10.2 | 440.87 |
| 10.1 | 440.53 |
| 10.0 | 440.43 |
| 8.4 | 418.149 | 8.5 | 418.165.01 |
| 8.3 | 418.130 |
| 8.2 | 418.109 |
| 8.1 | 418.92 |
| 8.0 | 418.66 |


**Notes:**


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products are also affected. If you are using an earlier branch release, upgrade to the latest branch release.


### 


### Mitigations


See [Security Updates for NVIDIA GPU Display Driver](#security-updates-display-driver) or [Security Updates for NVIDIA vGPU Software](#security-updates-vgpu-software) for the version to install.


### Acknowledgements


NVIDIA thanks the following individuals for reporting the issues:


* CVE‑2020‑5979 - Jo Hemmerlein of Microsoft
* CVE‑2020‑5980 - Andy Gill of Pen Test Partners LLP
* CVE‑2020‑5981 - Piotr Bania of Cisco Talos
* CVE-2020-5983 - NVIDIA Product Security Team
* CVE-2020-5986 - NVIDIA Product Security Team


### Get the Most Up to Date Product Security Information


Visit the  [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History




Revision Histor





| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 3.0 | October 7, 2020 | Added information about the R455 driver updates for GeForce and Quadro, and acknowledgements for CVE-2020-5983 and CVE-2020-5986 |
| 2.0 | October 1, 2020 | Updated CVE‑2020‑5981 to include code execution as a potential security impact |
| 1.0 | September 30, 2020 | Initial release |


### 


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


* [ NVIDIA GPU Display Driver - June 2020](/app/answers/detail/a_id/5031/related/1)
* [ NVIDIA GPU Display Driver - February 2020](/app/answers/detail/a_id/4996/related/1)
* [ NVIDIA GPU Display Driver - November 2019](/app/answers/detail/a_id/4907/related/1)
* [ NVIDIA GPU Display Driver - August 2019](/app/answers/detail/a_id/4841/related/1)
* [ NVIDIA GPU Display Driver - February 2019](/app/answers/detail/a_id/4772/related/1)








