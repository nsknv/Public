# NVIDIA GPU Display Driver (Bulletin ID: 5491)



 NVIDIA GPU Display Driver - October 2023
===========================================================




 Updated 11/01/2023 08:52 AM



NVIDIA has released a software security update for NVIDIA GPU Display Driver to address the issues that are disclosed in this bulletin.


To protect your system, download and install this software update through the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software and Cloud Gaming updates, through the NVIDIA Licensing Portal.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.


#### NVIDIA GPU Display Driver




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*CWE and Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2023‑31027 | NVIDIA GPU Display Driver for Windows contains a vulnerability that allows Windows users with low levels of privilege to escalate privileges when an administrator is updating GPU drivers, which may lead to escalation of privileges. | 8.2 | [CWE-427](https://cwe.mitre.org/data/definitions/427.html) [AV:L/AC:L/PR:L/UI:R/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:R/S:C/C:H/I:H/A:H) |
| CVE‑2023‑31019 | NVIDIA GPU Display Driver for Windows contains a vulnerability in `wksServicePlugin.dll`, where the driver implementation does not restrict or incorrectly restricts access from the named pipe server to a connecting client, which may lead to potential impersonation to the client's secure context. | 7.8 | [CWE-284](https://cwe.mitre.org/data/definitions/284.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2023‑31017 | NVIDIA GPU Display Driver for Windows contains a vulnerability where an attacker may be able to write arbitrary data to privileged locations by using reparse points. A successful exploit of this vulnerability may lead to code execution, denial of service, escalation of privileges, information disclosure, or data tampering. | 7.8 | [CWE: 552](https://cwe.mitre.org/data/definitions/552.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H)[H](https://cwe.mitre.org/data/definitions/552.html) |
| CVE‑2023‑31016 | NVIDIA GPU Display Driver for Windows contains a vulnerability where an uncontrolled search path element may allow an attacker to execute arbitrary code, which may lead to code execution, denial of service, escalation of privileges, information disclosure, or data tampering. | 7.3 | [CWE-427](https://cwe.mitre.org/data/definitions/427.html) [AV:L/AC:L/PR:L/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:R/S:U/C:H/I:H/A:H) |
| CVE‑2023‑31020 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer, where an unprivileged regular user can cause improper access control, which may lead to denial of service or data tampering. | 6.1 | [CWE-284](https://cwe.mitre.org/data/definitions/284.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:H) |
| CVE‑2023‑31022 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer, where a NULL-pointer dereference may lead to denial of service. | 5.5 | [CWE: 476](https://cwe.mitre.org/data/definitions/476.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H)[H](https://cwe.mitre.org/data/definitions/476.html) |
| CVE‑2023‑31023 | NVIDIA Display Driver for Windows contains a vulnerability where an attacker may cause a pointer dereference of an untrusted value, which may lead to denial of service. | 5.5 | [CWE: 822](https://cwe.mitre.org/data/definitions/822.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H)[H](https://cwe.mitre.org/data/definitions/822.html) |


#### NVIDIA vGPU Software




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*CWE and Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2023‑31018 | NVIDIA GPU Driver for Windows and Linux contains a vulnerability in the kernel mode layer, where an unprivileged regular user can cause a NULL-pointer dereference, which may lead to denial of service. | 6.5 | [CWE: 476](https://cwe.mitre.org/data/definitions/476.html) [AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H)[H](https://cwe.mitre.org/data/definitions/476.html) |
| CVE‑2023‑31026 | NVIDIA vGPU software for Windows and Linux contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where a NULL-pointer dereference may lead to denial of service. | 6.0 | [CWE: 476](https://cwe.mitre.org/data/definitions/476.html) [AV:L/AC:L/PR:H/UI:N/S:C/C:N/I:N/A:](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:C/C:N/I:N/A:H)[H](https://cwe.mitre.org/data/definitions/476.html) |
| CVE‑2023‑31021 | NVIDIA vGPU software for Windows and Linux contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where a malicious user in the guest VM can cause a NULL-pointer dereference, which may lead to denial of service. | 5.5 | [CWE: 476](https://cwe.mitre.org/data/definitions/476.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H)[H](https://cwe.mitre.org/data/definitions/476.html) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates for NVIDIA GPU Display Driver


#### CVE IDs Addressed in Each Windows Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows driver branch.




| \*\*Windows Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R545, R535, R525 | CVE‑2023‑31016, CVE‑2023‑31017, CVE‑2023‑31019, CVE‑2023‑31020, CVE‑2023‑31022, CVE‑2023‑31023, CVE‑2023‑31027 |
| R470 | CVE‑2023‑31017, CVE‑2023‑31019, CVE‑2023‑31020, CVE‑2023‑31022, CVE‑2023‑31023, CVE‑2023‑31027 |


#### Security Updates for NVIDIA GPU Windows Display Driver


The following table lists the NVIDIA software products affected, Windows driver versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Windows | R545 | All driver versions prior to 546.01 | 546.01 |
| Windows 10 and 11 | R470 | All driver versions prior to 474.64 for support of [GeForce Kepler desktop](https://nvidia.custhelp.com/app/answers/detail/a\_id/5202/kw/kepler%20desktop) | 474.64 |
| Windows 7 and 8.\*x\* | R470 | All driver versions prior to 474.64 | 474.64 |
| Studio | Windows | R545 | All driver versions prior to 546.01 | 546.01 |
| NVIDIA RTX, Quadro, NVS | Windows | R545 | All driver versions prior to 546.01 | 546.01 |
| R535 | All driver versions prior to 537.70 | 537.70 |
| R525 | All driver versions prior to 529.19 | 529.19 |
| R470 | All driver versions prior to 474.64 | 474.64 |
| Tesla | Windows | R535 | All driver versions prior to 537.70 | 537.70 |
| R525 | All driver versions prior to 529.19 | 529.19 |
| R470 | All driver versions prior to 474.64 | 474.64 |


#### CVE IDs Addressed in Each Linux Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux driver branch.




| \*\*Linux Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R545, R535, R525, R470 | CVE‑2023‑31022 |


#### Security Updates for NVIDIA GPU Linux Display Driver


The following table lists the NVIDIA software products affected, Linux driver versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Linux | R545 | All driver versions prior to 545.29.02 | 545.29.02 |
| R535 | All driver versions prior to 535.129.03 | 535.129.03 |
| R525 | All driver versions prior to 525.147.05 | 525.147.05 |
| R470 | All driver versions prior to 470.223.02 | 470.223.02 |
| NVIDIA RTX, Quadro, NVS | Linux | R545 | All driver versions prior to 545.29.02 | 545.29.02 |
| R535 | All driver versions prior to 535.129.03 | 535.129.03 |
| R525 | All driver versions prior to 525.147.05 | 525.147.05 |
| R470 | All driver versions prior to 470.223.02 | 470.223.02 |
| Tesla | Linux | R535 | All driver versions prior to 535.129.03 | 535.129.03 |
| R525 | All driver versions prior to 525.147.05 | 525.147.05 |
| R470 | All driver versions prior to 470.223.02 | 470.223.02 |


#### Notes


* Your computer hardware vendor may provide you with Windows GPU display driver versions including 545.91, 537.70, 529.19 and 474.64, which also contain the security updates.
* The tables above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, we recommend upgrading to the latest branch release.


### Security Updates for NVIDIA vGPU Software


#### CVE IDs Addressed in Each Windows vGPU Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows vGPU driver branch.




| \*\*Windows Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R535 | CVE‑2023‑31016, CVE‑2023‑31017, CVE‑2023‑31018, CVE‑2023‑31019, CVE‑2023‑31020, CVE‑2023‑31021, CVE‑2023‑31022, CVE‑2023‑31023, CVE‑2023‑31027 |
| R525 | CVE‑2023‑31016, CVE‑2023‑31017, CVE‑2023‑31018, CVE‑2023‑31019, CVE‑2023‑31020, CVE‑2023‑31022, CVE‑2023‑31023, CVE‑2023‑31027 |
| R470 | CVE‑2023‑31017, CVE‑2023‑31018, CVE‑2023‑31019, CVE‑2023‑31020, CVE‑2023‑31022, CVE‑2023‑31023, CVE‑2023‑31027 |


#### CVE IDs Addressed in Each Linux vGPU Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux vGPU driver branch.




| \*\*Linux Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R535, R525, R470 | CVE‑2023‑31018, CVE‑2023‑31022 |


#### CVE IDs Addressed in Each vGPU Manager Driver Branch


The following table lists the CVE IDs addressed by the update in each vGPU Manager driver branch.




| \*\*vGPU Manager Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R535 | CVE‑2023‑31018, CVE‑2023‑31021, CVE‑2023‑31022, CVE‑2023‑31026 |
| R525 | CVE‑2023‑31018, CVE‑2023‑31022, CVE‑2023‑31026 |
| R470 | CVE‑2023‑31018, CVE‑2023‑31022 |


#### Affected Components, Affected Versions, and Updated Versions


The following table lists NVIDIA vGPU software components affected, versions affected, and the updated version that includes this security update.




| \*\*CVE IDs Addressed\*\* | \*\*vGPU Software Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | \*\*vGPU Software\*\* | \*\*Driver\*\* |
| CVE‑2023‑31016 CVE‑2023‑31017 CVE‑2023‑31018 CVE‑2023‑31019 CVE‑2023‑31020 CVE‑2023‑31022 CVE‑2023‑31023 CVE‑2023‑31027 | Guest driver | Windows | All versions prior to and including 16.1 | 537.13 | 16.2 | 537.70 |
| All versions prior to and including 15.3 | 529.11 | 15.4 | 529.19 |
| All versions prior to and including 13.8 | 474.44 | 13.9 | 474.64 |
| CVE‑2023‑31018 CVE‑2023‑31022 | Guest driver | Linux | All versions prior to and including 16.1 | 535.104.05 | 16.2 | 535.109.03 |
| All versions prior to and including 15.3 | 525.125.06 | 15.4 | 525.147.05 |
| All versions prior to and including 13.8 | 470.199.02 | 13.9 | 470.223.02 |
| CVE‑2023‑31018 CVE‑2023‑31021 CVE‑2023‑31022 CVE‑2023‑31026 | Virtual GPU Manager | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM, Ubuntu | All versions prior to and including 16.1 | 535.104.06 | 16.2 | 535.109.03 |
| All versions prior to and including 15.3 | 525.125.03 | 15.4 | 525.147.01 |
| All versions prior to and including 13.8 | 470.199.03 | 13.9 | 470.223.02 |
| CVE‑2023‑31018 CVE‑2023‑31021 CVE‑2023‑31022 | Virtual GPU Manager | Azure Stack HCI | All versions prior to and including 16.1 | 537.13 | 16.2 | 537.70 |
| All versions prior to and including 15.3 | 529.06 | 15.4 | 529.19 |


#### Notes


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, we recommend upgrading to the latest branch release.


### Security Updates for NVIDIA Cloud Gaming


#### CVE IDs Addressed in Each Windows Cloud Gaming Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows Cloud Gaming driver branch.




| \*\*Windows Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R545, R535 | CVE‑2023‑31016, CVE‑2023‑31017, CVE‑2023‑31018, CVE‑2023‑31019, CVE‑2023‑31020, CVE‑2023‑31021, CVE‑2023‑31022, CVE‑2023‑31023, CVE‑2023‑31027 |
| R525 | CVE‑2023‑31016, CVE‑2023‑31017, CVE‑2023‑31018, CVE‑2023‑31019, CVE‑2023‑31020, CVE‑2023‑31022, CVE‑2023‑31023, CVE‑2023‑31027 |
| R470 | CVE‑2023‑31017, CVE‑2023‑31018, CVE‑2023‑31019, CVE‑2023‑31020, CVE‑2023‑31022, CVE‑2023‑31023, CVE‑2023‑31027 |


#### CVE IDs Addressed in Each Linux Cloud Gaming Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux Cloud Gaming driver branch




| \*\*Linux Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R545, R535, R525, R470 | CVE‑2023‑31018, CVE‑2023‑31022 |


#### CVE IDs Addressed in Each Cloud Gaming Manager Driver Branch


The following table lists the CVE IDs addressed by the update in each Cloud Gaming Manager driver branch




| \*\*Gaming Manager Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R545, R535 | CVE‑2023‑31018, CVE‑2023‑31021, CVE‑2023‑31022, CVE‑2023‑31026 |
| R525 | CVE‑2023‑31018, CVE‑2023‑31022, CVE‑2023‑31026 |
| R470 | CVE‑2023‑31018, CVE‑2023‑31022 |


#### Affected Components, Affected Versions, and Updated Versions


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.




| \*\*CVE IDs Addressed\*\* | \*\*Cloud Gaming Component\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* | \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* |
| CVE‑2023‑31016 CVE‑2023‑31017 CVE‑2023‑31018 CVE‑2023‑31019 CVE‑2023‑31020 CVE‑2023‑31022 CVE‑2023‑31023 CVE‑2023‑31027 | Guest driver | Windows | All versions prior to and including September 2023 release | 537.42 | October 2023 release | 546.01 |
| CVE‑2023‑31018 CVE‑2023‑31022 | Guest driver | Linux | All versions prior to and including September 2023 release | 535.113.01 | October 2023 release | 545.29.02 |
| CVE‑2023‑31018 CVE‑2023‑31021 CVE‑2023‑31022 CVE‑2023‑31026 | Virtual GPU Manager | Red Hat Enterprise Linux KVM, VMware vSphere | All versions prior to and including September 2023 release | 535.113.01 | October 2023 release | 545.29.02 |


### Acknowledgements


NVIDIA thanks the following people for reporting the issues to us:


CVE‑2023‑31027: Patryk Nowakowski


CVE‑2023‑31017: Lockheed Martin Red Team


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.1 | November 1, 2023 | Updated Windows Studio Display Driver version to 546.01 |
| 1.0 | October 31, 2023 | Initial release |


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


* [ NVIDIA GPU Display Driver - March 2023](/app/answers/detail/a_id/5452/related/1)
* [ NVIDIA GPU Display Driver - August 2022](/app/answers/detail/a_id/5383/related/1)
* [ NVIDIA GPU Display Driver - May 2022](/app/answers/detail/a_id/5353/related/1)
* [ NVIDIA GPU Display Drivers - July 2021](/app/answers/detail/a_id/5211/related/1)
* [ NVIDIA GPU Display Driver - April 2021](/app/answers/detail/a_id/5172/related/1)








