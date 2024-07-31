# NVIDIA GPU Display Driver (Bulletin ID: 5312)



 NVIDIA GPU Display Driver - February 2022
============================================================




 Updated 02/02/2022 09:35 AM



NVIDIA has released a software security update for NVIDIA GPU Display Driver. This update addresses issues that may lead to denial of service or memory corruption.


To protect your system, download and install this software update through the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software update, through the NVIDIA Licensing Portal.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities  that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.


#### NVIDIA GPU Display Driver




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑21813 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel driver, where improper handling of insufficient permissions or privileges may allow an unprivileged local user limited write access to protected memory, which can lead to denial of service. | 6.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:H) |
| CVE‑2022‑21814 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel driver package, where improper handling of insufficient permissions or privileges may allow an unprivileged local user limited write access to protected memory, which can lead to denial of service. | 6.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:H) |
| CVE‑2022‑21815 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for private IOCTLs where a NULL pointer dereference in the kernel, created within user mode code, may lead to a denial of service in the form of a system crash. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |


#### NVIDIA vGPU Software




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑21816 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (`nvidia.ko`), where a user in the guest OS can cause a GPU interrupt storm on the hypervisor host, leading to a denial of service. | 5.5 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates for NVIDIA GPU Display Driver


The following table lists the NVIDIA software products affected, versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.


#### Windows




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- | --- |
| CVE‑2022‑21815 | GeForce | Windows | R510 | All versions prior to 511.65 | 511.65 |
| Windows 10 and 11 | R470 | All drivers versions prior to 472.98 for support of [GeForce Kepler desktop](https://nvidia.custhelp.com/app/answers/detail/a\_id/5202/kw/kepler%20desktop) | 472.98 |
| Windows 7 and 8.\*x\* | R470 | All drivers versions prior to 473.04 | 473.04 |
| Studio | Windows | R510 | All driver versions prior to 511.65 | 511.65 |
| NVIDIA RTX/Quadro, NVS | Windows | R510 | All driver versions prior to 511.65 | 511.65 |
| R470 | All drivers versions prior to 472.98 | 472.98 |
| Tesla | Windows | R510 | All drivers versions prior to 511.65 | 511.65 |
| R470 | All drivers versions prior to 472.98 | 472.98 |
| R450 | All drivers versions prior to 453.37 | 453.37 |


#### Linux




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- | --- |
| CVE‑2022‑21813 CVE‑2022‑21814 | GeForce | Linux | R510 | All drivers versions prior to 510.47.03 | 510.47.03 |
| R470 | All drivers versions prior to 470.103.01 | 470.103.01 |
| NVIDIA RTX/ Quadro, NVS | Linux | R510 | All drivers versions prior to 510.47.03 | 510.47.03 |
| R470 | All drivers versions prior to 470.103.01 | 470.103.01 |
| Tesla | Linux | R510 | All drivers versions prior to 510.47.03 | 510.47.03 |
| R470 | All drivers versions prior to 470.103.01 | 470.103.01 |


**Notes:**


* Your computer hardware vendor may provide you with Windows GPU display driver versions including 511.66, 497.30, 472.91, and 453.35 which also contain the security updates.
* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, we recommend upgrading to the latest branch release.


### Security Updates for NVIDIA vGPU Software


The following table lists the NVIDIA software products affected, versions affected, and the updated version. Log in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal.




| \*\*CVE IDs Addressed\*\* | \*\*vGPU Software Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | \*\*vGPU Software\*\* | \*\*Driver\*\* |
| CVE‑2022‑21815 | vGPU software (guest driver) | Windows | All versions prior to and including 13.1 | 472.39 | 13.2 | 472.98 |
| All versions prior to and including 11.6 | 453.23 | 11.7 | 453.37 |
| All versions prior to and including 8.9 | 427.60 | 8.10 | 427.71 |
| CVE‑2022‑21813 | vGPU software (guest driver) | Linux | All versions prior to and including 13.1 | 470.82.00 | 13.2 | 470.103.01 |
| All versions prior to and including 11.6 | 450.156.00 | 11.7 | 450.172.01 |
| All versions prior to and including 8.9 | 418.226.00 | 8.10 | 418.240 |
| CVE‑2022‑21816 | vGPU software (Virtual GPU Manager) | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux with KVM, Ubuntu, Nutanix AHV | All versions prior to and including 13.1 | 470.82 | 13.2 | 470.103.02 |
| All versions prior to and including 11.6 | 450.156 | 11.7 | 450.172 |
| All versions prior to and including 8.9 | 418.226.00 | 8.10 | 418.240 |


**Notes:**


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, we recommend upgrading to the latest branch release.


### Security Updates for NVIDIA Cloud Gaming


The following table lists the NVIDIA software products affected, versions affected, and the updated version. Log in to the [NVIDIA Enterprise Application Hub](https://nvid.nvidia.com/dashboard/) to download updates from the NVIDIA Licensing Portal.





| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* | \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* |
| CVE‑2022‑21815 | Cloud Gaming Guest Driver | Windows | All versions prior to and including the November 2021 Cloud Gaming Release | 497.09 | January 2022 Cloud Gaming Release | 511.65 |
| CVE‑2022‑21813 | Cloud Gaming Guest Driver | Linux | All versions prior to and including the November 2021 Cloud Gaming Release | 495.50 | January 2022 Cloud Gaming Release | 510.47.03 |
| CVE‑2022‑21816 | Cloud Gaming Virtual GPU Manager | Citrix Hypervisor, Red Hat Enterprise Linux with KVM | All versions prior to and including the November 2021 Cloud Gaming Release | 495.50 | January 2022 Cloud Gaming Release | 510.47.03 |



**Notes**:


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, we recommend upgrading to the latest branch release.


### Mitigations


None. See [Security Updates for NVIDIA GPU Display Driver](#security-updates-display-driver), [Security Updates for NVIDIA vGPU Software](#security-updates-vgpu-software), or [Security Updates for NVIDIA Cloud Gaming](#security-updates-cloud-gaming) for the version to install.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | February 1, 2022 | Initial release |


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


* [ NVIDIA GPU Display Driver - October 2021](/app/answers/detail/a_id/5230/related/1)
* [Security Notice: NVIDIA GPU and Tegra Hardware - November 2021](/app/answers/detail/a_id/5263/related/1)
* [ NVIDIA GeForce Experience - December 2021](/app/answers/detail/a_id/5295/related/1)
* [ NVIDIA GPU Display Drivers - July 2021](/app/answers/detail/a_id/5211/related/1)
* [Security Notice: NVIDIA Response to Log4j Vulnerabilities - December 2021](/app/answers/detail/a_id/5294/related/1)








