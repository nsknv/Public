# NVIDIA GPU Display Driver (Bulletin ID: 4996)



 NVIDIA GPU Display Driver - February 2020
============================================================




 Updated 09/29/2021 02:55 PM



NVIDIA has released a software security update for NVIDIA GPU Display Driver. This update addresses issues that may lead to denial of service, escalation of privileges, or information disclosure.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


To protect your system, download and install this software update through the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software update, through the NVIDIA Licensing Portal.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security.](https://www.nvidia.com/security/)
------------------------------------------------------------------






---




### Details


This section summarizes the potential impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS](https://www.first.org/cvss/user-guide) V3 standards.


#### CVEs for NVIDIA GPU Display Driver




This section summarizes the potential impact that this security update addresses. Descriptions use CWE™, and base scores and vectors use CVSS V3 standards.
| \*\*CVE\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2020‑5957 | NVIDIA Windows GPU Display Driver contains a vulnerability in the NVIDIA Control Panel component in which an attacker with local system access can corrupt a system file, which may lead to denial of service or escalation of privileges. | 8.4 | [AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:H/A:H) |
| CVE‑2020‑5958 | NVIDIA Windows GPU Display Driver contains a vulnerability in the NVIDIA Control Panel component in which an attacker with local system access can plant a malicious DLL file, which may lead to code execution, denial of service, or information disclosure. | 6.7 | [AV:L/AC:H/PR:L/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:R/S:U/C:H/I:H/A:H) |


#### CVEs for NVIDIA vGPU Software




CVEs for NVIDIA vGPU Software
| \*\*CVE\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2020‑5959 | NVIDIA Virtual GPU Manager contains a vulnerability in the vGPU plugin, in which an input index value is incorrectly validated, which may lead to denial of service. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2020‑5960 | NVIDIA Virtual GPU Manager contains a vulnerability in the kernel module (`nvidia.ko`), where a null pointer dereference may occur, which may lead to denial of service. | 6.5 | [AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H) |
| CVE‑2020‑5961 | NVIDIA vGPU graphics driver for guest OS contains a vulnerability in which an incorrect resource clean up on a failure path can impact the guest VM, leading to denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates for NVIDIA GPU Display Driver


The following table lists the NVIDIA software products affected, versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.


#### Windows




Windows
| \*\*CVE\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Versions\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2020‑5957 CVE‑2020‑5958 | GeForce | Windows | All R440 versions prior to 442.50 | 442.50 |
| Quadro, NVS | Windows | All R440 versions prior to 442.50 | 442.50 |
| All R430 versions prior to 432.28 | 432.28 |
| All R418 versions prior to 426.50 | 426.50 |
| All R390 versions prior 392.59 | 392.59 |
| Tesla | Windows | All R440 versions prior to 442.50 | 442.50 |
| All R418 versions prior to 426.50 | 426.50 |


**Notes:**


* Your computer hardware vendor may provide you with Windows GPU display driver versions including 442.05 and 436.73 which also contain the security updates.
* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products are also affected. If you are using an earlier branch release, upgrade to the latest branch release.


### Security Updates for NVIDIA vGPU Software


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Log in to the  [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Center.




The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Log in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Center.
| \*\*CVEs Addressed\*\* | \*\*vGPU Software Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | \*\*vGPU Software\*\* | \*\*Driver\*\* |
| CVE‑2020‑5661 | vGPU graphics driver for guest OS | Windows | 10.1 | 442.06 | 10.2 | 443.05 |
| 10.0 | 441.66 |
| 9.2 | 432.08 | 9.3 | 432.33 |
| 9.1 | 431.79 |
| 9.0 | 412.02 |
| 8.2 | 426.26 | 8.3 | 426.52 |
| 8.1 | 426.04 |
| 8.0 | 425.26 |
| CVE‑2020‑5961 | vGPU graphics driver for guest OS | Linux | 10.1 | 440.56 | 10.2 | 440.87 |
| 10.0 | 440.43 |
| 9.2 | 430.63 | 9.3 | 430.83 |
| 9.1 | 430.46 |
| 9.0 | 430.30 |
| 8.2 | 418.43 | 8.3 | 418.130 |
| 8.1 | 418.92 |
| 8.0 | 418.70 |
| CVE‑2020‑5959 CVE‑2020‑5960 | Virtual GPU Manager | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM, Nutanix AHV | 10.1 | 440.53 | 10.2 | 440.87 |
| 10.0 | 440.43 |
| 9.2 | 430.67 | 9.3 | 430.83 |
| 9.1 | 430.46 |
| 9.0 | 430.27 |
| 8.2 | 418.109 | 8.3 | 418.130 |
| 8.1 | 418.92 |
| 8.0 | 418.66 |


**Notes:**


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products are also affected. If you are using an earlier branch release, upgrade to the latest branch release.


### Mitigations


None. See [Security Updates for NVIDIA GPU Display Driver](#security-updates-display-driver) or [Security Updates for NVIDIA vGPU Software](#security-updates-vgpu-software) for the version to install.


### Acknowledgements


CVE‑2020‑5957 - NVIDIA thanks Zhiniang Peng (@edwardzpeng) of Qihoo 360 Core Security and Xuefeng Li for reporting the issues.


### Get the Most Up to Date Product Security Information


Visit the  [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History




Revision History





| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 4.0 | May 5, 2020 | Added information about driver updates for vGPU software 10.2 |
| 3.0 | March 10, 2020 | Added information about the Tesla R440 driver update and driver updates for vGPU software 9.3 |
| 2.0 | March 5, 2020 | Corrected an error in a CVE number in the table of security updates for NVIDIA vGPU software |
| 1.0 | February 28, 2020 | Initial release |


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


* [ NVIDIA GPU Display Driver - August 2019](/app/answers/detail/a_id/4841/related/1)
* [ NVIDIA GPU Display Driver - February 2019](/app/answers/detail/a_id/4772/related/1)
* [ NVIDIA GPU Display Driver - November 2019](/app/answers/detail/a_id/4907/related/1)
* [ NVIDIA GPU Display Driver Security Updates for Multiple Vulnerabilities](/app/answers/detail/a_id/4649/related/1)
* [ NVIDIA GPU Display Driver - June 2020](/app/answers/detail/a_id/5031/related/1)








