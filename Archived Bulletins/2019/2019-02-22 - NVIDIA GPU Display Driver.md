# NVIDIA GPU Display Driver (Bulletin ID: 4772)



 NVIDIA GPU Display Driver - February 2019
============================================================




 Updated 09/29/2021 01:10 PM



NVIDIA has released a software security update for the NVIDIA GPU Display Driver. This update addresses issues that may lead to denial of service, escalation of privileges, code execution, or information disclosure. To protect your system, download and install this software update through [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx).
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security](http://www.nvidia.com/product-security/).
-------------------------------------------------------------------------






---




### Details


This section summarizes the potential impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors follow [CVSS V3](https://www.first.org/cvss/user-guide) standards.




This section summarizes the potential impact that this security update addresses. Descriptions use CWE™, and base scores and vectors follow CVSS V3 standards.
| \*\*CVE\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*CVSS V3 Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2019‑5665 | NVIDIA Windows GPU Display driver contains a vulnerability in the 3D vision component in which the stereo service software, when opening a file, does not check for hard links. This behavior may lead to code execution, denial of service or escalation of privileges. | 8.8 | [AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2019‑5666 | NVIDIA Windows GPU Display Driver contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) create context command DDI `DxgkDdiCreateContext` in which the product uses untrusted input when calculating or using an array index, but the product does not validate or incorrectly validates the index to ensure the index references a valid position within the array, which may lead to denial of service or escalation of privileges. | 8.8 | [AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=CVSS:3.0/AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2019‑5667 | NVIDIA Windows GPU Display Driver contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for `DxgkDdiSetRootPageTable` in which the application dereferences a pointer that it expects to be valid, but is NULL, which may lead to code execution, denial of service or escalation of privileges. | 8.8 | [AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=CVSS:3.0/AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2019‑5668 | NVIDIA Windows GPU Display Driver contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for `DxgkDdiSubmitCommandVirtual` in which the application dereferences a pointer that it expects to be valid, but is NULL, which may lead to denial of service or escalation of privileges. | 8.8 | [AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2019‑5669 | NVIDIA Windows GPU Display Driver contains a vulnerability in the kernel mode layer handler for `DxgkDdiEscape` in which the software uses a sequential operation to read from or write to a buffer, but it uses an incorrect length value that causes it to access memory that is outside of the bounds of the buffer, which may lead to denial of service or escalation of privileges. | 8.8 | [AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2019‑5670 | NVIDIA Windows GPU Display Driver contains a vulnerability in the kernel mode layer handler for `DxgkDdiEscape` in which the software uses a sequential operation to read from or write to a buffer, but it uses an incorrect length value that causes it to access memory that is outside of the bounds of the buffer which may lead to denial of service, escalation of privileges, code execution or information disclosure. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2019‑5671 | NVIDIA Windows GPU Display Driver contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape in which the software does not release a resource after its effective lifetime has ended, which may lead to denial of service. | 6.5 | [AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H) |
| CVE‑2018‑6260 | NVIDIA graphics driver contains a vulnerability that may allow access to application data processed on the GPU through a side channel exposed by the GPU performance counters. Local user access is required. This vulnerability is not a network or remote attack vector. | 2.2 | [AV:L/AC:H/PR:L/UI:R/S:U/C:L/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:R/S:U/C:L/I:N/A:N) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk of your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following table lists the software products and versions affected, and the updated version that includes this security update.


Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.


#### Windows




The following table lists the software products and versions affected, and the updated version that includes this security update.
| \*\*CVEs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Versions\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2019‑5665 through CVE‑2019‑5671 CVE‑2018‑6260 | GeForce | Windows | All R418 versions prior to 419.17 | 419.17 |
| CVE‑2019‑5665 through CVE‑2019‑5671 CVE‑2018‑6260 | Quadro, NVS | Windows | All R418 versions prior to 419.17 | 419.17 |
| All R400 versions prior to 412.29 | 412.29 |
| CVE‑2019‑5665 CVE‑2019‑5667 through CVE‑2019‑5671 CVE‑2018‑6260 | Quadro, NVS | Windows | All R390 versions prior to 392.37 | 392.37 |
| CVE‑2019‑5665 through CVE‑2019‑5671 CVE‑2018‑6260 | Tesla | Windows | All R418 versions prior to 418.96 | 418.96 |
| All R400 versions prior to 412.29 | 412.29 |
| CVE‑2019‑5667 through CVE‑2019‑5671 CVE‑2018‑6260 | vGPU 4.x | Windows, Windows Server with Hyper-V | vGPU releases prior to 4.8 | 4.8 (contains Windows driver version 370.35) |


#### Linux




Linux
| \*\*CVE Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Versions\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2018‑6260 | GeForce | Linux, FreeBSD, Solaris | All R418 versions prior to 418.43 | 418.43 |
| All R400 versions prior to 410.104 | 410.104 |
| All R390 versions prior to 390.116 | 390.116 |
| Quadro, NVS | Linux, FreeBSD, Solaris | All R418 versions prior to 418.43 | 418.43 |
| All R400 versions prior to 410.104 | 410.104 |
| All R390 versions prior to 390.116 | 390.116 |
| Tesla | Linux | All R418 versions prior to 418.39 | 418.39 |
| All R400 versions prior to 410.104 | 410.104 |
| All R396 versions prior to 396.82 | 396.82 |
| All R390 versions prior to 390.116 | 390.116 |
| All R384 versions prior to 384.183 | 384.183 |
| vGPU 4.\*x\* | Linux | vGPU releases prior to 4.8 | 4.8 (contains Linux driver version 367.130) |
| Citrix XenServer, VMware vSphere, Huawei FusionCompute, Red Hat Enterprise Linux KVM | vGPU releases prior to 4.8 | 4.8 (contains Virtual GPU Manager version 367.130) |


**Notes:**


* Affected versions include the versions listed and all earlier branches and releases.
* If you are using an unsupported version or an earlier unsupported branch, upgrade to the latest supported version. To identify products that are no longer supported, check the product EOL pages [Windows legacy GPU releases](https://nvidia.custhelp.com/app/answers/detail/a_id/3473) and [UNIX legacy GPU releases](http://nvidia.custhelp.com/app/answers/detail/a_id/3142), or contact [NVIDIA Support](http://www.nvidia.com/object/support.html).
* The table above may not be a comprehensive list of all impacted software versions or driver branches and may be updated as more information becomes available.
* Your computer hardware vendor may provide you with a driver version not listed in the table above. If so, check the vendor’s security bulletin to determine which versions from the vendor contain the security updates.
* If you are an Enterprise Services customer using an NVIDIA DGX system, visit the [NVIDIA Enterprise Support Portal](https://nvid.nvidia.com/enterpriselogin) for guidance.
* After installing the security update more action is required for CVE-2018-6260:
	+ **Windows Graphics Driver** 
	Refer to the *Developer->Manage GPU Performance Counters* section of the *NVIDIA Control Panel Help*  for the additional steps required.
	
	
	If you are an enterprise customer, refer to the instructions in the **Product Release Notes**.
	+ **Linux Graphics Driver**
	
	
	Refer to the *Restricting Access to GPU Performance Counters* section of the Linux driver *Readme*.
	+ **NVIDIA virtual GPU (vGPU) software**
	
	
	Refer to *Restricting Access to GPU Performance Counters* in the release notes for the hypervisor that you are using.


### Mitigations


None. See [Security Updates](#security-updates) for the versions to install.


### Acknowledgements


CVE-2018-6260: NVIDIA thanks Hoda Naghibijouybari, Ajaya Neupane, Zhiyun Qian, and Nael Abu-Ghazaleh for reporting this issue.


CVE-2019-5665: NVIDIA thanks Christoffer Wiman for reporting this issue.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](http://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential vulnerability in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History




Revision History





| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 4.0 | March 19, 2019 | Added information to the Security Updates section about the availability of updates for vGPU 4.x. |
| 3.0 | February 28, 2019 | Updated the availability of Tesla driver branch R400 for the Windows and Linux operating systems, and branches R396 and 390 for the Linux operating system. |
| 2.0 | February 27, 2019 | Updated the availability of Tesla driver branch R418 for the Windows and Linux operating systems and branch R384 for the Linux operating system. |
| 1.0 | February 22, 2019 | Initial release |


### Support


If you have any questions about this security bulletin, contact [NVIDIA Support](http://www.nvidia.com/object/support.html).


### Frequently Asked Questions (FAQs)


#### How do I know what driver version I have installed?


1. Launch Windows Device Manager.
2. Select **Display Adapters**.
3. Select the **NVIDIA GPU** node and right-click.
4. Go to the **Driver** tab.


The driver version can be deciphered as shown in the following examples: 10.18.13.6472 is 364.72 and 10.18.13.472 is 304.72


##### Disclaimer


ALL NVIDIA INFORMATION, DESIGN SPECIFICATIONS, REFERENCE BOARDS, FILES, DRAWINGS, DIAGNOSTICS, LISTS, AND OTHER DOCUMENTS (TOGETHER AND SEPARATELY, “MATERIALS”) ARE BEING PROVIDED “AS IS.” NVIDIA MAKES NO WARRANTIES, EXPRESS, IMPLIED, STATUTORY, OR OTHERWISE WITH RESPECT TO THE MATERIALS, AND ALL EXPRESS OR IMPLIED CONDITIONS, REPRESENTATIONS AND WARRANTIES, INCLUDING ANY IMPLIED WARRANTY OR CONDITION OF TITLE, MERCHANTABILITY, SATISFACTORY QUALITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT, ARE HEREBY EXCLUDED TO THE MAXIMUM EXTENT PERMITTED BY LAW.


Information is believed to be accurate and reliable at the time it is furnished. However, NVIDIA Corporation assumes no responsibility for the consequences of use of such information or for any infringement of patents or other rights of third parties that may result from its use. No license is granted by implication or otherwise under any patent or patent rights of NVIDIA Corporation. Specifications mentioned in this publication are subject to change without notice. This publication supersedes and replaces all information previously supplied. NVIDIA Corporation products are not authorized for use as critical components in life support devices or systems without express written approval of NVIDIA Corporation. 










Is this answer helpful?
-----------------------



Yes
No







Answers others found helpful
----------------------------


* [ NVIDIA GPU Display Driver Security Updates for Multiple Vulnerabilities](/app/answers/detail/a_id/4649/related/1)
* [ NVIDIA GPU Display Driver - August 2019](/app/answers/detail/a_id/4841/related/1)
* [ NVIDIA GPU Display Driver - June 2020](/app/answers/detail/a_id/5031/related/1)
* [ NVIDIA GPU Display Driver - November 2019](/app/answers/detail/a_id/4907/related/1)
* [ NVIDIA GPU Display Driver - February 2020](/app/answers/detail/a_id/4996/related/1)








