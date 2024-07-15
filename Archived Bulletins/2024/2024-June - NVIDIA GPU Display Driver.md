# NVIDIA GPU Display Driver (Bulletin ID: 5551)



 NVIDIA GPU Display Driver - June 2024
========================================================




 Updated 06/06/2024 09:07 PM



NVIDIA has released a software security update for NVIDIA GPU Display Driver to address the issues that are disclosed in this bulletin.


To protect your system, download and install this software update through the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software and Cloud Gaming updates, through the NVIDIA Licensing Portal.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.


#### NVIDIA GPU Display Driver




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Vector\*\* | \*\*Base Score\*\* | \*\*Severity\*\* | \*\*CWE\*\* | \*\*Impacts\*\* |
| --- | --- | --- | --- | --- | --- | --- |
| CVE‑2024‑0090 | NVIDIA GPU driver for Windows and Linux contains a vulnerability where a user can cause an out-of-bounds write. A successful exploit of this vulnerability might lead to code execution, denial of service, escalation of privileges, information disclosure, and data tampering. | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) | 7.8 | High | [CWE‑787](https://cwe.mitre.org/data/definitions/787.html) | Code execution, denial of service, escalation of privileges, information disclosure, data tampering |
| CVE‑2024‑0089 | NVIDIA GPU Display Driver for Windows contains a vulnerability where the information from a previous client or another process could be disclosed. A successful exploit of this vulnerability might lead to code execution, information disclosure, or data tampering. | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) | 7.8 | High | [CWE‑665](https://cwe.mitre.org/data/definitions/665.html) | Code execution, information disclosure, data tampering |
| CVE‑2024‑0091 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability where a user can cause an untrusted pointer dereference by executing a driver API. A successful exploit of this vulnerability might lead to denial of service, information disclosure, and data tampering. | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) | 7.8 | High | [CWE‑822](https://cwe.mitre.org/data/definitions/822.html) | Denial of service, information disclosure, data tampering |
| CVE‑2024‑0093 | NVIDIA GPU software for Linux contains a vulnerability where it can expose sensitive information to an actor that is not explicitly authorized to have access to that information. A successful exploit of this vulnerability might lead to information disclosure. | [AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:N/A:N) | 6.5 | Medium | [CWE‑200](https://cwe.mitre.org/data/definitions/200.html) | Information disclosure |
| CVE‑2024‑0092 | NVIDIA GPU Driver for Windows and Linux contains a vulnerability where an improper check or improper handling of exception conditions might lead to denial of service. | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) | 5.5 | Medium | [CWE‑703](https://cwe.mitre.org/data/definitions/703.html) | Denial of service |


#### NVIDIA vGPU Software




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Vector\*\* | \*\*Base Score\*\* | \*\*Severity\*\* | \*\*CWE\*\* | \*\*Impacts\*\* |
| --- | --- | --- | --- | --- | --- | --- |
| CVE‑2024‑0099 | NVIDIA vGPU software for Linux contains a vulnerability in the Virtual GPU Manager, where the guest OS could cause buffer overrun in the host. A successful exploit of this vulnerability might lead to information disclosure, data tampering, escalation of privileges, and denial of service. | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) | 7.8 | High | [CWE‑120](https://cwe.mitre.org/data/definitions/120.html) | Information disclosure, data tampering, escalation of privileges, denial of service |
| CVE‑2024‑0084 | NVIDIA vGPU software for Linux contains a vulnerability in the Virtual GPU Manager, where the guest OS could execute privileged operations. A successful exploit of this vulnerability might lead to information disclosure, data tampering, escalation of privileges, and denial of service. | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) | 7.8 | High | [CWE‑250](https://cwe.mitre.org/data/definitions/250.html) | Information disclosure, data tampering, escalation of privileges, denial of service |
| CVE‑2024‑0085 | NVIDIA vGPU software for Windows and Linux contains a vulnerability where unprivileged users could execute privileged operations on the host. A successful exploit of this vulnerability might lead to data tampering, escalation of privileges, and denial of service. | [AV:L/AC:H/PR:L/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:N/S:U/C:N/I:H/A:H) | 6.3 | Medium | [CWE‑266](https://cwe.mitre.org/data/definitions/266.html) | Data tampering, escalation of privileges, denial of service |
| CVE‑2024‑0094 | NVIDIA vGPU software for Linux contains a vulnerability in the Virtual GPU Manager, where an untrusted guest VM can cause improper control of the interaction frequency in the host. A successful exploit of this vulnerability might lead to denial of service. | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) | 5.5 | Medium | [CWE‑799](https://cwe.mitre.org/data/definitions/799.html) | Denial of service |
| CVE‑2024‑0086 | NVIDIA vGPU software for Linux contains a vulnerability where the software can dereference a NULL pointer. A successful exploit of this vulnerability might lead to denial of service and undefined behavior in the vGPU plugin. | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) | 5.5 | Medium | [CWE‑476](https://cwe.mitre.org/data/definitions/476.html) | Denial of service, undefined behavior |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates for NVIDIA GPU Display Driver


#### CVE IDs Addressed in Each Windows Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows driver branch.




| \*\*Windows Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R555, R550 | CVE‑2024‑0089, CVE‑2024‑0090, CVE‑2024‑0091, CVE‑2024‑0092 |
| R535, R470 | CVE‑2024‑0089, CVE‑2024‑0090, CVE‑2024‑0092 |


#### Security Updates for NVIDIA GPU Windows Display Driver


The following table lists the NVIDIA software products affected, Windows driver versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Windows | R555 | All driver versions prior to 555.99 | 555.99 |
| Windows 10 and 11 | R470 | All driver versions prior 475.06 to for support of [GeForce Kepler desktop](https://nvidia.custhelp.com/app/answers/detail/a\_id/5202/kw/kepler%20desktop) | 475.06 |
| Windows 7 and 8.x | R470 | All driver versions prior to 475.06 | 475.06 |
| Studio | Windows | R555 | All driver versions prior to 555.99 | 555.99 |
| NVIDIA RTX, Quadro, NVS | Windows | R555 | All driver versions prior to 555.99 | 555.99 |
| R550 | All driver versions prior to 552.55 | 552.55 |
| R535 | All driver versions prior to 538.67 | 538.67 |
| R470 | All driver versions prior to 475.06 | 475.06 |
| Tesla | Windows | R550 | All driver versions prior to 552.55 | 552.55 |
| R535 | All driver versions prior to 538.67 | 538.67 |
| R470 | All driver versions prior to 475.06 | 475.06 |


#### CVE IDs Addressed in Each Linux Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux driver branch.




| \*\*Linux Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R555, R550 | CVE‑2024‑0090, CVE‑2024‑0091, CVE‑2024‑0092 |
| R535, R470 | CVE‑2024‑0090, CVE‑2024‑0092 |


#### Affected Components, Affected Versions, and Updated Versions


The following table lists the NVIDIA software products affected, Linux driver versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Linux | R555 | All driver versions prior to 555.52.04 | 555.52.04 |
| R550 | All driver versions prior to 550.90.07 | 550.90.07 |
| R535 | All driver versions prior to 535.183.01 | 535.183.01 |
| R470 | All driver versions prior to 470.256.02 | 470.256.02 |
| NVIDIA RTX, Quadro, NVS | Linux | R555 | All driver versions prior to 555.52.04 | 555.52.04 |
| R550 | All driver versions prior to 550.90.07 | 550.90.07 |
| R535 | All driver versions prior to 535.183.01 | 535.183.01 |
| R470 | All driver versions prior to 470.256.02 | 470.256.02 |
| Tesla | Linux | R550 | All driver versions prior to 550.90.07 | 550.90.07 |
| R535 | All driver versions prior to 535.183.01 | 535.183.01 |
| R470 | All driver versions prior to 470.256.02 | 470.256.02 |


#### Notes


* Your computer hardware vendor might provide you with Windows GPU display driver versions including 555.94, 555.91, 552.23, and 475.04, which also contain the security updates.
* The tables above might not be a comprehensive list of all affected supported versions or branch releases and might be updated as more information becomes available.
* Earlier software branch releases that support these products might also be affected. If you are using an earlier branch release for which an update version is not listed above, upgrade to the latest branch release.


### Security Updates for NVIDIA vGPU Software


#### CVE IDs Addressed in Each Windows vGPU Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows vGPU driver branch.




| \*\*Windows Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R550, R535, R470 | CVE‑2024‑0089, CVE‑2024‑0090, CVE‑2024‑0091 |


#### CVE IDs Addressed in Each Linux vGPU Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux vGPU driver branch.




| \*\*Linux Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R550, R535, R470 | CVE‑2024‑0090, CVE‑2024‑0091, |


#### CVE IDs Addressed in Each vGPU Manager Driver Branch


The following table lists the CVE IDs addressed by the update in each vGPU Manager driver branch.




| \*\*vGPU Manager Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R550 | CVE‑2024‑0084, CVE‑2024‑0085, CVE‑2024‑0086, CVE‑2024‑0090, CVE‑2024‑0091, CVE‑2024‑0092, CVE‑2024‑0093, CVE‑2024‑0094, CVE‑2024‑0099 |
| R535 | CVE‑2024‑0084, CVE‑2024‑0085, CVE‑2024‑0086, CVE‑2024‑0090, CVE‑2024‑0091, CVE‑2024‑0092, CVE‑2024‑0093, CVE‑2024‑0094 |
| R470 | CVE‑2024‑0084, CVE‑2024‑0090, CVE‑2024‑0091, CVE‑2024‑0092, CVE‑2024‑0093, CVE‑2024‑0094 |


#### Affected Components, Affected Versions, and Updated Versions


The following table lists NVIDIA vGPU software components affected, versions affected, and the updated version that includes this security update. Download the updates through the NVIDIA Licensing Portal.




| \*\*CVE IDs Addressed\*\* | \*\*vGPU Software Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | \*\*vGPU Software\*\* | \*\*Driver\*\* |
| CVE‑2024‑0089 CVE‑2024‑0090 CVE‑2024‑0091 | Guest driver | Windows | All versions up to and including 17.1 | 551.78 | 17.2 | 552.55 |
| All versions up to and including 16.5 | 538.46 | 16.6 | 538.67 |
| All versions up to and including 13.10 | 474.82 | 13.11 | 475.06 |
| CVE‑2024‑0090 CVE‑2024‑0091 | Guest driver | Linux | All versions up to and including 17.1 | 550.54.15 | 17.2 | 550.90.07 |
| All versions up to and including 16.5 | 535.161.08 | 16.6 | 535.183.01 |
| All versions up to and including 13.10 | 470.239.06 | 13.11 | 470.256.02 |
| CVE‑2024‑0084 CVE‑2024‑0085 CVE‑2024‑0086 CVE‑2024‑0090 CVE‑2024‑0091 CVE‑2024‑0092 CVE‑2024‑0093 CVE‑2024‑0094 CVE‑2024‑0099 | Virtual GPU Manager | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM, Ubuntu | All versions up to and including 17.1 | 550.54.16 | 17.2 | 550.90.05 |
| All versions up to and including 16.5 | 535.161.05 | 16.6 | 535.183.04 |
| All versions up to and including 13.10 | 470.239.01 | 13.11 | 470.256.02 |
| CVE‑2024‑0085 CVE‑2024‑0090 CVE‑2024‑0091 CVE‑2024‑0092 | Virtual GPU Manager | Azure Stack HCI | All versions up to and including 17.1 | 551.60 | 17.2 | 552.55 |


**Notes:**


* The table above might not be a comprehensive list of all affected supported versions or branch releases and might be updated as more information becomes available.
* Earlier software branch releases that support these products might also be affected. If you are using an earlier branch release for which an update version is not listed above, upgrade to the latest branch release.


### Security Updates for NVIDIA Cloud Gaming


#### Affected Components, Affected Versions, and Updated Versions


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Download the updates through the NVIDIA Licensing Portal.




| \*\*CVE IDs Addressed\*\* | \*\*Cloud Gaming Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* | \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* |
| CVE‑2024‑0089 CVE‑2024‑0090 CVE‑2024‑0091 | Guest driver | Windows | All versions up to and including the April 2024 release | 552.12 | May 2024 release | 555.99 |
| CVE‑2024‑0090 CVE‑2024‑0091 | Guest driver | Linux | All versions up to and including the April 2024 release | 550.73 | May 2024 release | 555.52.04 |
| CVE‑2024‑0084 CVE‑2024‑0085 CVE‑2024‑0086 CVE‑2024‑0090 CVE‑2024‑0091 CVE‑2024‑0092 CVE‑2024‑0093 CVE‑2024‑0094 CVE‑2024‑0099 | Virtual GPU Manager | Red Hat Enterprise Linux KVM, VMware vSphere | All versions prior to and including the April 2024 release | 550.73 | May 2024 release | 555.52.04 |


### Mitigations


See [Security Updates for NVIDIA GPU Display Driver](#security-updates-gpu-display-driver), [Security Updates for NVIDIA vGPU Software](#security-updates-vgpu-software), or [Security Updates for NVIDIA Cloud Gaming](#security-updates-cloud-gaming) for the version to install.


### Acknowledgements


NVIDIA thanks the following people for reporting the issues to us:


CVE‑2024‑0089: CYS DET PEN - Siemens


CVE‑2024‑0090: Jisoo Jang, Joonkyo Jung, Yongwan Jo, and Dokyung Song - Yonsei University


CVE‑2024‑0093: Frederik Pustelnik


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | June 6, 2024 | Initial release |


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


* [How do I determine which NVIDIA display driver version is currently installed on my PC?](/app/answers/detail/a_id/2039/related/1)
* [Support Plan for Kepler-series GeForce GPUs for Desktop](/app/answers/detail/a_id/5202/related/1)
* [ NVIDIA GPU Display Driver - October 2023](/app/answers/detail/a_id/5491/related/1)
* [ NVIDIA DCGM - August 2021](/app/answers/detail/a_id/5219/related/1)
* [Security Notice: NVIDIA Response to OpenSSL Vulnerabilities - November 2022](/app/answers/detail/a_id/5405/related/1)








