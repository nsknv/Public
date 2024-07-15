# NVIDIA GPU Display Driver (Bulletin ID: 4797)



 NVIDIA GPU Display Driver - May 2019
=======================================================




 Updated 09/29/2021 01:10 PM



NVIDIA has released a software security update for the NVIDIA GPU Display Driver. This update addresses issues that may lead to denial of service, escalation of privileges, code execution, or information disclosure. To protect your system, download and install this software update through [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx).
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security](https://www.nvidia.com/product-security/).
--------------------------------------------------------------------------

 



---




### Details


This section summarizes the potential impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS V3](https://www.first.org/cvss/user-guide) standards.




This section summarizes the potential impact that this security update addresses. Descriptions use CWE™, and base scores and vectors use CVSS V3 standards.
| \*\*CVE\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2019‑5675 | NVIDIA Windows GPU Display Driver contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for `DxgkDdiEscape` where the product does not properly synchronize shared data, such as static variables across threads, which can lead to undefined behavior and unpredictable data changes, which may lead to denial of service, escalation of privileges, or information disclosure. | 7.7 | [AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=CVSS:3.0/AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:L/A:H) |
| CVE‑2019‑5676 | NVIDIA Windows GPU Display Driver installer software contains a vulnerability in which it incorrectly loads Windows system DLLs without validating the path or signature (also known as a binary planting or DLL preloading attack), leading to escalation of privileges through code execution. | 7.2 | [AV:L/AC:H/PR:H/UI:R/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:R/S:C/C:H/I:H/A:H) |
| CVE‑2019‑5677 | NVIDIA Windows GPU Display Driver contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for `DeviceIoControl` where the software reads from a buffer using buffer access mechanisms such as indexes or pointers that reference memory locations after the targeted buffer, which may lead to denial of service. | 5.6 | [AV:L/AC:H/PR:L/UI:N/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=CVSS:3.0/AV:L/AC:H/PR:L/UI:N/S:C/C:N/I:N/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk of your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated versions that include this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.


#### Windows




The following table lists the NVIDIA software products affected, versions affected, and the updated versions that include this security update. Download the updates from the NVIDIA Driver Downloads page.
| \*\*CVE\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2019‑5675 CVE‑2019‑5676 CVE‑2019‑5677 | GeForce | Windows | All R430 versions prior to 430.64 | 430.64 |
| CVE‑2019‑5675 CVE‑2019‑5676 CVE‑2019‑5677 | Quadro, NVS | Windows | All R430 versions prior to 430.64 | 430.64 |
| All R418 versions prior to 425.51 | 425.51 |
| All R410 versions prior to 412.36 | 412.36 |
| CVE‑2019‑5666 CVE‑2019‑5675 CVE‑2019‑5677 | Quadro, NVS | Windows | All R390 versions prior to 392.53 | 392.53 |
| CVE‑2019‑5675 CVE‑2019‑5676 CVE‑2019‑5677 | Tesla | Windows | All R418 versions prior to 425.25 | 425.25 |
| All R410 versions prior to 412.36 | 412.36 |


**Notes:**


* In addition to updated versions listed above, Windows driver versions 430.23, 425.25, and 422.02 provided by computer hardware vendors also include the security update.
* If you are using an unsupported version or an earlier unsupported branch, upgrade to the latest supported version. To identify products that are no longer supported check the product EOL pages [Windows legacy GPU releases](https://nvidia.custhelp.com/app/answers/detail/a_id/3473) and [Unix legacy GPU releases](https://nvidia.custhelp.com/app/answers/detail/a_id/3142), or contact [NVIDIA Support](https://www.nvidia.com/object/support.html).
* The table above may not be a comprehensive list of all affected versions or branches and may be updated as more information becomes available.
* R390 driver branch versions include updates for **CVE-2019-5666**, previously disclosed in [ NVIDIA GPU Display Driver - February 2019](https://nvidia.custhelp.com/app/answers/detail/a_id/4772).
* **CVE-2019-5676** - If the GPU driver is installed on Windows 7, Microsoft KB2533623 must be installed as a prerequisite to address this CVE. This CVE does not affect driver packages provided by your hardware vendor and applies only to driver packages that are downloaded from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) public web page.


### Mitigations


None. See [Security Updates](#security-updates) for the versions to install.


### Acknowledgements


CVE-2019-5676: NVIDIA thanks multiple reporters for reporting this issue: Kushal Arvind Shah of Fortinet's FortiGuard Labs; Łukasz 'zaeek'; Yasin Soliman; Marius Gabriel Mihai; and Stefan Kanthak.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential vulnerability in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History




Revision History





| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 4.0 | May 30, 2019 | Updated the availability of Quadro and NVS driver branch R390 for the Windows operating system. |
| 3.0 | May 24, 2019 | Updated the availability of Quadro, NVS, and Tesla driver branch R390 for the Windows operating system. |
| 2.0 | May 14, 2019 | Updated the availability of Quadro, NVS, and Tesla driver branch R410 for the Windows operating system. |
| 1.0 | May 09, 2019 | Initial release |


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


* [ NVIDIA SHIELD TV Software Security Updates for Multiple Vulnerabilities](/app/answers/detail/a_id/4682/related/1)
* [ NVIDIA GeForce Experience Software Security Updates for Multiple Vulnerabilities When GameStream is Enabled](/app/answers/detail/a_id/4685/related/1)
* [ NVIDIA GeForce Experience - September 2018](/app/answers/detail/a_id/4725/related/1)
* [ NVIDIA GPU Display Driver Security Updates for Multiple Vulnerabilities](/app/answers/detail/a_id/4649/related/1)
* [ NVIDIA SHIELD TV – October 2018](/app/answers/detail/a_id/4704/related/1)








