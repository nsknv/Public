# NVIDIA GPU Display Driver (Bulletin ID: 5452)



 NVIDIA GPU Display Driver - March 2023
=========================================================




 Updated 03/30/2023 09:05 AM



NVIDIA has released a software security update for NVIDIA GPU Display Driver. This update addresses issues that may lead to code execution, denial of service, escalation of privileges, information disclosure, and data tampering.


To protect your system, download and install this software update through the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software update, through the NVIDIA Licensing Portal.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.


#### NVIDIA GPU Display Driver




| CVE ID | Description | Base Score | CWE and Vector |
| --- | --- | --- | --- |
| CVE-2023-0189 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer handler, which may lead to code execution, denial of service, escalation of privileges, information disclosure, and data tampering. | 8.8 | [CWE: 822](https://cwe.mitre.org/data/definitions/822.html) [AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2023‑0184 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer handler, which may lead to denial of service, escalation of privileges, information disclosure, and data tampering. | 8.8 | [CWE: 822](https://cwe.mitre.org/data/definitions/822.html) [AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE-2023-0182 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer, where an out-of-bounds write can lead to denial of service, information disclosure, and data tampering. | 7.8 | [CWE-787](https://cwe.mitre.org/data/definitions/787.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE-2023-0181 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in a kernel mode layer handler, where memory permissions are not correctly checked, which may lead to denial of service and data tampering. | 7.1 | [CWE: 280](https://cwe.mitre.org/data/definitions/280.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H) |
| CVE-2023-0191 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer handler, where an out-of-bounds access may lead to denial of service or data tampering. | 7.1 | [CWE: 119](https://cwe.mitre.org/data/definitions/119.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H) |
| CVE-2023-0183 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer where an out-of-bounds write can lead to denial of service and data tampering. | 7.1 | [CWE-787](https://cwe.mitre.org/data/definitions/787.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H) |
| CVE-2023-0180 | NVIDIA GPU Display Driver for Linux contains a vulnerability in a kernel mode layer handler, which may lead to denial of service or information disclosure. | 7.1 | [CWE: 125](https://cwe.mitre.org/data/definitions/125.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:H) |
| CVE-2023-0185 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer, where sign conversion issues may lead to denial of service or information disclosure. | 6.7 | [CWE: 196](https://cwe.mitre.org/data/definitions/196.html) [AV:L/AC:H/PR:H/UI:N/S:C/C:L/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:C/C:L/I:L/A:H) |
| CVE-2023-0198 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer, where improper restriction of operations within the bounds of a memory buffer can lead to denial of service, information disclosure, and data tampering. | 6.6 | [CWE: 119](https://cwe.mitre.org/data/definitions/119.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:H) |
| CVE-2023-0187 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer handler, where an out-of-bounds read can lead to denial of service. | 6.1 | [CWE: 125](https://cwe.mitre.org/data/definitions/125.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:N/A:H) |
| CVE-2023-0199 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer handler, where an out-of-bounds write can lead to denial of service and data tampering. | 6.1 | [CWE: 787](https://cwe.mitre.org/data/definitions/787.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:H) |
| CVE-2023-0186 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer, where an out-of-bounds write can lead to denial of service and data tampering. | 6.1 | [CWE-787](https://cwe.mitre.org/data/definitions/787.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:H) |
| CVE-2023-0190 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer, where a NULL pointer dereference may lead to denial of service. | 5.5 | [CWE: 476](https://cwe.mitre.org/data/definitions/476.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE-2023-0188 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer handler, where an unprivileged user can cause an out-of-bounds read, which may lead to denial of service. | 5.5 | [CWE: 119](https://cwe.mitre.org/data/definitions/119.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE-2023-0192 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer handler, where improper privilege management can lead to escalation of privileges and information disclosure. | 4.7 | [CWE-269](https://cwe.mitre.org/data/definitions/269.html) [AV:L/AC:H/PR:H/UI:N/S:U/C:H/I:N/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:U/C:H/I:N/A:L) |
| CVE-2023-0194 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer driver, where an invalid display configuration may lead to denial of service. | 2.0 | [CWE: 1284](https://cwe.mitre.org/data/definitions/1284.html) [AV:P/AC:H/PR:N/UI:N/S:U/C:N/I:N/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:P/AC:H/PR:N/UI:N/S:U/C:N/I:N/A:L) |
| CVE-2023-0195 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer driver, where an invalid display configuration may lead to information disclosure. | 2.0 | [CWE: 1284](https://cwe.mitre.org/data/definitions/1284.html) [AV:P/AC:H/PR:N/UI:N/S:U/C:L/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:P/AC:H/PR:N/UI:N/S:U/C:L/I:N/A:N) |


#### NVIDIA vGPU Software




| CVE ID | Description | Base Score | CWE and Vector |
| --- | --- | --- | --- |
| CVE‑2023‑0197 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager, where a malicious user in a guest VM can cause a NULL-pointer dereference, which may lead to denial of service. | 5.5 | [CWE: 476](https://cwe.mitre.org/data/definitions/476.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates for NVIDIA GPU Display Driver


#### CVE IDs Addressed in Each Windows Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows driver branch.




| Windows Driver Branch | CVE IDs Addressed |
| --- | --- |
| R530, R525 | CVE-2023-0184, CVE-2023-0182, CVE-2023-0191, CVE-2023-0181, CVE-2023-0199, CVE-2023-0186, CVE-2023-0187, CVE-2023-0188, CVE-2023-0192, CVE-2023-0194, CVE-2023-0195 |
| R515 | CVE-2023-0184, CVE-2023-0182, CVE-2023-0191, CVE-2023-0181, CVE-2023-0199, CVE-2023-0186, CVE-2023-0187, CVE-2023-0188, CVE-2023-0194, CVE-2023-0195 |
| R470 | CVE-2023-0184, CVE-2023-0191, CVE-2023-0181, CVE-2023-0199, CVE-2023-0186, CVE-2023-0187, CVE-2023-0188, CVE-2023-0194, CVE-2023-0195 |
| R450 | CVE-2023-0184, CVE-2023-0191, CVE-2023-0199, CVE-2023-0186, CVE-2023-0188, CVE-2023-0194, CVE-2023-0195 |


#### Security Updates for NVIDIA GPU Windows Display Driver


The following table lists the NVIDIA software products affected, Windows driver versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| Software Product | Operating System | Driver Branch | Affected Driver Versions | Updated Driver Version |
| --- | --- | --- | --- | --- |
| GeForce | Windows | R530 | All driver versions prior to 531.41 | 531.41 |
| Windows 10 and 11 | R470 | All drivers versions prior to 474.30 for support of [GeForce Kepler desktop](https://nvidia.custhelp.com/app/answers/detail/a\_id/5202/kw/kepler%20desktop) | 474.30 |
| Windows 7 and 8.\*x\* | R470 | All driver versions prior to 474.30 | 474.30 |
| Studio | Windows | R530 | All driver versions prior to 531.41 | 531.41 |
| R525 | All driver versions prior to 528.89 | 528.89 |
| NVIDIA RTX, Quadro, NVS | Windows | R530 | All driver versions prior to 531.41 | 531.41 |
| R525 | All driver versions prior to 528.89 | 528.89 |
| R515 | All driver versions prior to 518.03 | 518.03 |
| R470 | All driver versions prior to 474.30 | 474.30 |
| Tesla | Windows | R525 | All driver versions prior to 528.89 | 528.89 |
| R515 | All driver versions prior to 518.03 | 518.03 |
| R470 | All driver versions prior to 474.30 | 474.30 |
| R450 | All driver versions prior to 454.14 | 454.14 |


#### CVE IDs Addressed in Each Linux Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux driver branch.




| Linux Driver Branch | CVE IDs Addressed |
| --- | --- |
| R530, R525, R515 | CVE-2023-0184, CVE-2023-0189, CVE-2023-0180, CVE-2023-0183, CVE-2023-0185, CVE-2023-0187, CVE-2023-0198, CVE-2023-0199, CVE-2023-0188, CVE-2023-0190, CVE-2023-0194, CVE-2023-0195, CVE-2023-0191 |
| R470 | CVE-2023-0184, CVE-2023-0189, CVE-2023-0180, CVE-2023-0185, CVE-2023-0187, CVE-2023-0198, CVE-2023-0199, CVE-2023-0188, CVE-2023-0190, CVE-2023-0194, CVE-2023-0195, CVE-2023-0191 |
| R450 | CVE-2023-0184, CVE-2023-0189, CVE-2023-0180, CVE-2023-0185, CVE-2023-0198, CVE-2023-0199, CVE-2023-0188, CVE-2023-0190, CVE-2023-0194, CVE-2023-0195, CVE-2023-0191 |


### Security Updates for NVIDIA GPU Linux Display Driver


The following table lists the NVIDIA software products affected, Linux driver versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| Software Product | Operating System | Driver Branch | Affected Driver Versions | Updated Driver Version |
| --- | --- | --- | --- | --- |
| GeForce | Linux | R530 | All driver versions prior to 530.41.03 | 530.41.03 |
| R525 | All driver versions prior to 525.105.17 | 525.105.17 |
| R515 | All driver versions prior to 515.105.01 | 515.105.01 |
| R470 | All driver versions prior to 470.182.03 | 470.182.03 |
| NVIDIA RTX, Quadro, NVS | Linux | R530 | All driver versions prior to 530.41.03 | 530.41.03 |
| R525 | All driver versions prior to 525.105.17 | 525.105.17 |
| R515 | All driver versions prior to 515.105.01 | 515.105.01 |
| R470 | All driver versions prior to 470.182.03 | 470.182.03 |
| Tesla | Linux | R525 | All driver versions prior to 525.105.17 | 525.105.17 |
| R515 | All driver versions prior to 515.105.01 | 515.105.01 |
| R470 | All driver versions prior to 470.182.03 | 470.182.03 |
| R450 | All driver versions prior to 450.236.01 | 450.236.01 |


**Notes:**


* Your computer hardware vendor may provide you with Windows GPU display driver versions including 531.30, 528.59, 518.01, and 474.26, which also contain the security updates.
* The tables above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, upgrade to the latest branch release.


### Security Updates for NVIDIA vGPU Software


#### CVE IDs Addressed in Each Windows vGPU Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows driver branch.




| Windows Driver Branch | CVE IDs Addressed |
| --- | --- |
| R525 | CVE-2023-0182, CVE-2023-0191, CVE-2023-0181, CVE-2023-0186, CVE-2023-0187, CVE-2023-0188, CVE-2023-0194, CVE-2023-0195 |
| R470 | CVE-2023-0191, CVE-2023-0181, CVE-2023-0186, CVE-2023-0187, CVE-2023-0188, CVE-2023-0194, CVE-2023-0195 |
| R450 | CVE-2023-0191, CVE-2023-0186, CVE-2023-0188, CVE-2023-0194, CVE-2023-0195 |


#### CVE IDs Addressed in Each Linux vGPU Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux vGPU driver branch





| Linux Driver Branch | CVE IDs Addressed |
| --- | --- |
| R525 | CVE-2023-0189, CVE-2023-0191, CVE-2023-0180, CVE-2023-0183, CVE-2023-0198, CVE-2023-0188 |
| R470 | CVE-2023-0181, CVE-2023-0189, CVE-2023-0191, CVE-2023-0180, CVE-2023-0198 |
| R450 | CVE-2023-0189, CVE-2023-0191, CVE-2023-0180, CVE-2023-0198 |



#### CVE IDs Addressed in Each vGPU Manager Driver Branch


The following table lists the CVE IDs addressed by the update in each vGPU Manager driver branch





| vGPU Manager Driver Branch | CVE IDs Addressed |
| --- | --- |
| R525 | CVE-2023-0197, CVE-2023-0191, CVE-2023-0180, CVE-2023-0183, CVE-2023-0198, CVE-2023-0188, CVE-2023-0185, CVE-2023-0181 , CVE-2023-0192 |
| R470 | CVE-2023-0181, CVE-2023-0191, CVE-2023-0180, CVE-2023-0198, CVE-2023-0185 |
| R450 | CVE-2023-0191, CVE-2023-0180, CVE-2023-0198, CVE-2023-0185 |



#### Affected Products, Affected Versions, and Updated Versions


The following table lists NVIDIA software products affected, versions affected, and the updated version that includes this security update.




| CVE IDs Addressed | Software Product | Operating System | Affected Versions | | Updated Version | |
| --- | --- | --- | --- | --- | --- | --- |
| vGPU Software | Driver | vGPU Software | Driver |
| CVE‑2023‑0182 CVE‑2023‑0191 CVE‑2023‑0181 CVE‑2023‑0186 CVE‑2023‑0187 CVE‑2023‑0188 CVE‑2023‑0194 CVE‑2023‑0195 | vGPU software (guest driver) | Windows | All versions prior to and including 15.1 | 528.24 | 15.2 | 528.89 |
| All versions prior to and including 13.6 | 474.14 | 13.7 | 474.30 |
| All versions prior to and including 11.11 | 454.02 | 11.12 | 454.14 |
| CVE-2023-0189 CVE‑2023‑0191 CVE‑2023‑0180 CVE‑2023‑0181 CVE‑2023‑0183 CVE‑2023‑0198 CVE‑2023‑0188 | vGPU software (guest driver) | Linux | All versions prior to and including 15.1 | 525.85.05 | 15.2 | 525.105.17 |
| All versions prior to and including 13.6 | 470.161.03 | 13.7 | 470.182.03 |
| All versions prior to and including 11.11 | 450.216.04 | 11.12 | 450.236.01 |
| CVE-2023-0197 CVE‑2023‑0191 CVE‑2023‑0180 CVE‑2023‑0181 CVE‑2023‑0183 CVE‑2023‑0185 CVE‑2023‑0198 CVE‑2023‑0188 CVE‑2023‑0192 | vGPU software (Virtual GPU Manager) | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM | All versions prior to and including 15.1 | 525.85.07 | 15.2 | 525.105.14 |
| All versions prior to and including 13.6 | 470.161.02 | 13.7 | 470.182.02 |
| All versions prior to and including 11.11 | 450.216.04 | 11.12 | 450.236.03 |


**Notes:**


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, upgrade to the latest branch release.


### Security Updates for NVIDIA Cloud Gaming


#### CVE IDs Addressed in Each Windows Cloud Gaming Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows driver branch.




| Windows Driver Branch | CVE IDs Addressed |
| --- | --- |
| R525 | CVE-2023-0182, CVE-2023-0191, CVE-2023-0181, CVE-2023-0186, CVE-2023-0187, CVE-2023-0188, CVE-2023-0194, CVE-2023-0195 |
| R470 | CVE-2023-0191, CVE-2023-0181, CVE-2023-0186, CVE-2023-0187, CVE-2023-0188, CVE-2023-0194, CVE-2023-0195 |
| R450 | CVE-2023-0191, CVE-2023-0186, CVE-2023-0188, CVE-2023-0194, CVE-2023-0195 |


#### CVE IDs Addressed in Each Linux Cloud Gaming Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux Cloud Gaming driver branch




| Linux Driver Branch | CVE IDs Addressed |
| --- | --- |
| R525 | CVE-2023-0189, CVE-2023-0191, CVE-2023-0180, CVE-2023-0183, CVE-2023-0198, CVE-2023-0188, CVE-2023-0181 |
| R470 | CVE-2023-0181, CVE-2023-0189, CVE-2023-0191, CVE-2023-0180, CVE-2023-0198 |
| R450 | CVE-2023-0189, CVE-2023-0191, CVE-2023-0180, CVE-2023-0198 |


#### CVE IDs Addressed in Each Cloud Gaming Manager Driver Branch


The following table lists the CVE IDs addressed by the update in each Cloud Gaming Manager driver branch




| vGPU Manager Driver Branch | CVE IDs Addressed |
| --- | --- |
| R525 | CVE-2023-0197, CVE-2023-0191, CVE-2023-0180, CVE-2023-0183, CVE-2023-0198, CVE-2023-0188, CVE-2023-0185, CVE-2023-0181, CVE-2023-0192 |
| R470 | CVE-2023-0181, CVE-2023-0191, CVE-2023-0180, CVE-2023-0198, CVE-2023-0185 |
| R450 | CVE-2023-0191, CVE-2023-0180, CVE-2023-0198, CVE-2023-0185 |


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.




| CVE IDs Addressed | Software Product | Operating System | Affected Versions | | Updated Version | |
| --- | --- | --- | --- | --- | --- | --- |
| Cloud Gaming Software | Driver | Cloud Gaming Software | Driver |
| CVE‑2023‑0182 CVE‑2023‑0191 CVE‑2023‑0181 CVE‑2023‑0186 CVE‑2023‑0187 CVE‑2023‑0188 CVE‑2023‑0194 CVE‑2023‑0195 | NVIDIA Cloud Gaming (guest driver) | Windows | All versions prior to and including February 2023 release | All versions prior to 528.49 | March 2023 release | 531.41 |
| CVE‑2023‑0189 CVE‑2023‑0191 CVE‑2023‑0180 CVE‑2023‑0181 CVE‑2023‑0183 CVE‑2023‑0198 CVE‑2023‑0188 | NVIDIA Cloud Gaming (guest driver) | Linux | All versions prior to and including February 2023 release | All versions prior to 525.89.02 | March 2023 release | 530.41.03 |
| CVE‑2023‑0197 CVE‑2023‑0191 CVE‑2023‑0180 CVE‑2023‑0181 CVE‑2023‑0183 CVE‑2023‑0185 CVE‑2023‑0198 CVE‑2023‑0188 CVE‑2023‑0192 | NVIDIA Cloud Gaming (Virtual GPU Manager) | Red Hat Enterprise Linux KVM | All versions prior to and including February 2023 release | All versions prior to 525.89.02 | March 2023 release | 530.41.03 |


### Acknowledgements


NVIDIA thanks the following people for reporting the issues to us:


CVE-2023-0194, CVE-2023-0195: Imre Kis


### Get the Most Up to Date Product Security Information


Visit the  [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | March 30, 2023 | Initial release |


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


* [ NVIDIA GPU Display Driver - August 2022](/app/answers/detail/a_id/5383/related/1)
* [ NVIDIA GPU Display Driver - May 2022](/app/answers/detail/a_id/5353/related/1)
* [ NVIDIA GPU Display Drivers - July 2021](/app/answers/detail/a_id/5211/related/1)
* [ NVIDIA GPU Display Driver - January 2021](/app/answers/detail/a_id/5142/related/1)
* [ NVIDIA GPU Display Driver - April 2021](/app/answers/detail/a_id/5172/related/1)








