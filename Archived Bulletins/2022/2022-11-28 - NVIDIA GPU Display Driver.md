# NVIDIA GPU Display Driver (Bulletin ID: 5415)



 NVIDIA GPU Display Driver - November 2022
============================================================




 Updated 12/20/2022 09:54 AM



NVIDIA has released a software security update for NVIDIA GPU Display Driver. This update addresses issues that may lead to code execution, denial of service, escalation of privileges, information disclosure, or data tampering.


To protect your system, download and install this software update through the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page or, for the vGPU software and NVIDIA Cloud Gaming updates, through the NVIDIA Licensing Portal.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.


#### NVIDIA GPU Driver




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*CWE and Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑34669 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the user mode layer, where an unprivileged regular user can access or modify system files or other files that are critical to the application, which may lead to code execution, denial of service, escalation of privileges, information disclosure, or data tampering. | 8.8 | [CWE: 73](https://cwe.mitre.org/data/definitions/73.html) [AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2022‑34671 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the user mode layer, where an unprivileged regular user can cause an out-of-bounds write, which may lead to code execution, denial of service, escalation of privileges, information disclosure, or data tampering. | 8.5 | [CWE: 787](https://cwe.mitre.org/data/definitions/787.html) [AV:N/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2022‑34672 | NVIDIA Control Panel for Windows contains a vulnerability where an unauthorized user or an unprivileged regular user can compromise the security of the software by gaining privileges, reading sensitive information, or executing commands. | 7.8 | [CWE: 284](https://cwe.mitre.org/data/definitions/284.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑34670 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer handler, where an unprivileged regular user can cause truncation errors when casting a primitive to a primitive of smaller size causes data to be lost in the conversion, which may lead to denial of service or information disclosure. | 7.8 | [CWE: 197](https://cwe.mitre.org/data/definitions/197.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42267 | NVIDIA GPU Display Driver for Windows contains a vulnerability where a regular user can cause an out-of-bounds read, which may lead to code execution, denial of service, escalation of privileges, information disclosure, or data tampering. | 7.8 | [CWE-345](https://cwe.mitre.org/data/definitions/345.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42263 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer handler, where an Integer overflow may lead to denial of service or information disclosure. | 7.1 | [CWE: 190](https://cwe.mitre.org/data/definitions/190.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:H) |
| CVE‑2022‑34676 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer handler, where an out-of-bounds read may lead to denial of service, information disclosure, or data tampering. | 7.1 | [CWE-197](https://cwe.mitre.org/data/definitions/197.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H) |
| CVE‑2022‑42264 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer, where an unprivileged regular user can cause the use of an out-of-range pointer offset, which may lead to data tampering, data loss, information disclosure, or denial of service. | 7.1 | [CWE-823](https://cwe.mitre.org/data/definitions/823.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N) |
| CVE‑2022‑34674 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer handler, where a helper function maps more physical pages than were requested, which may lead to undefined behavior or an information leak. | 6.8 | [CWE: 200](https://cwe.mitre.org/data/definitions/200.html) [AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:L/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:L/A:N) |
| CVE‑2022‑34678 | NVIDIA GPU Display Driver for Windows and Linux contains a vulnerability in the kernel mode layer, where an unprivileged user can cause a null-pointer dereference, which may lead to denial of service. | 6.5 | [CWE: 476](https://cwe.mitre.org/data/definitions/476.html) [AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:N/I:N/A:H) |
| CVE‑2022‑34679 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer handler, where an unhandled return value can lead to a null-pointer dereference, which may lead to denial of service. | 5.5 | [CWE: 476](https://cwe.mitre.org/data/definitions/476.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2022‑34680 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer handler, where an integer truncation can lead to an out-of-bounds read, which may lead to denial of service. | 5.5 | [CWE: 197](https://cwe.mitre.org/data/definitions/197.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2022‑34677 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer handler, where an unprivileged regular user can cause an integer to be truncated, which may lead to denial of service or data tampering. | 5.5 | [CWE-125](https://cwe.mitre.org/data/definitions/125.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N) |
| CVE‑2022‑34681 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler, where improper input validation of a display-related data structure may lead to denial of service. | 5.5 | [CWE: 20](https://cwe.mitre.org/data/definitions/20.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2022‑34682 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer, where an unprivileged regular user can cause a null-pointer dereference, which may lead to denial of service. | 5.5 | [CWE: 476](https://cwe.mitre.org/data/definitions/476.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2022‑34683 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape, where a null-pointer dereference occurs, which may lead to denial of service. | 5.5 | [CWE: 476](https://cwe.mitre.org/data/definitions/476.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |
| CVE‑2022‑42266 | NVIDIA GPU Display Driver for Windows contains a vulnerability in the kernel mode layer (`nvlddmkm.sys`) handler for DxgkDdiEscape, where an unprivileged regular user can cause exposure of sensitive information to an actor that is not explicitly authorized to have access to that information, which may lead to limited information disclosure. | 5.5 | [CWE: 200](https://cwe.mitre.org/data/definitions/200.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N) |
| CVE‑2022‑42257 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer (`nvidia.ko`), where an integer overflow may lead to information disclosure, data tampering or denial of service. | 5.3 | [CWE-190](https://cwe.mitre.org/data/definitions/190.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L) |
| CVE‑2022‑42265 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer (`nvidia.ko`), where an integer overflow may lead to information disclosure or data tampering. | 5.3 | [CWE-190](https://cwe.mitre.org/data/definitions/190.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L) |
| CVE‑2022‑34684 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer (`nvidia.ko`), where an off-by-one error may lead to data tampering or information disclosure. | 5.3 | [CWE: 125](https://cwe.mitre.org/data/definitions/125.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L) |
| CVE‑2022‑42254 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer (`nvidia.ko`), where an out-of-bounds array access may lead to denial of service, data tampering, or information disclosure. | 5.3 | [CWE: 125](https://cwe.mitre.org/data/definitions/125.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L) |
| CVE‑2022‑42258 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer (`nvidia.ko`), where an integer overflow may lead to denial of service, data tampering, or information disclosure. | 5.3 | [CWE-190](https://cwe.mitre.org/data/definitions/190.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L) |
| CVE‑2022‑42255 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer (`nvidia.ko`), where an out-of-bounds array access may lead to denial of service, information disclosure, or data tampering. | 5.3 | [CWE: 787](https://cwe.mitre.org/data/definitions/787.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L) |
| CVE‑2022‑42256 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer (`nvidia.ko`), where an integer overflow in index validation may lead to denial of service, information disclosure, or data tampering. | 5.3 | [CWE: 190](https://cwe.mitre.org/data/definitions/190.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L) |
| CVE‑2022‑34673 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer (`nvidia.ko`), where an out-of-bounds array access may lead to denial of service, information disclosure, or data tampering. | 4.4 | [CWE-190](https://cwe.mitre.org/data/definitions/190.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:L) |
| CVE‑2022‑42259 | NVIDIA GPU Display Driver for Linux contains a vulnerability in the kernel mode layer (`nvidia.ko`), where an integer overflow may lead to denial of service. | 4.4 | [CWE: 190](https://cwe.mitre.org/data/definitions/190.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:L) |


#### NVIDIA vGPU Software




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*CWE and Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑42260 | NVIDIA vGPU Display Driver for Linux guest contains a vulnerability in a D-Bus configuration file, where an unauthorized user in the guest VM can impact protected D-Bus endpoints, which may lead to code execution, denial of service, escalation of privileges, information disclosure, or data tampering. | 7.8 | [CWE: 281](https://cwe.mitre.org/data/definitions/281.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42261 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where an input index is not validated, which may lead to buffer overrun, which in turn may cause data tampering, information disclosure, or denial of service. | 7.8 | [CWE: 120](https://cwe.mitre.org/data/definitions/120.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑42262 | NVIDIA vGPU software contains a vulnerability in the Virtual GPU Manager (vGPU plugin), where an input index is not validated, which may lead to buffer overrun, which in turn may cause data tampering, information disclosure, or denial of service. | 7.1 | [CWE: 787](https://cwe.mitre.org/data/definitions/787.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H) |
| CVE‑2022‑34675 | NVIDIA Display Driver for Linux contains a vulnerability in the Virtual GPU Manager, where it does not check the return value from a null-pointer dereference, which may lead to denial of service. | 5.5 | [CWE-476](https://cwe.mitre.org/data/definitions/476.html) [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates for NVIDIA GPU Display Driver


#### CVE IDs Addressed in Each Windows Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows driver branch.




| \*\*Windows Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R525, R515, R450 | CVE‑2022‑42266, CVE‑2022‑42267, CVE‑2022‑34669, CVE‑2022‑34671, CVE‑2022‑34672, CVE‑2022‑34681, CVE‑2022‑34683 |
| R510, R470 | CVE‑2022‑42266, CVE‑2022‑42267, CVE‑2022‑34669, CVE‑2022‑34671, CVE‑2022‑34672, CVE‑2022‑34678, CVE‑2022‑34681, CVE‑2022‑34683 |


#### Security Updates for NVIDIA GPU Windows Display Driver


The following table lists the NVIDIA software products affected, Windows driver versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Windows | R525 | All driver versions prior to 526.98 | 526.98 |
| Windows 10 and 11 | R470 | All drivers versions prior to 474.14 for support of [GeForce Kepler desktop](https://nvidia.custhelp.com/app/answers/detail/a\_id/5202/kw/kepler%20desktop) | 474.14 |
| Windows 7 and 8.\*x\* | R470 | All driver versions prior to 474.11 | 474.11 |
| Studio | Windows | R525 | All driver versions prior to 526.98 | 526.98 |
| NVIDIA RTX, Quadro, NVS | Windows | R525 | All driver versions prior to 527.27 | 527.27 |
| R515 | All driver versions prior to 517.88 | 517.88 |
| R510 | All driver versions prior to 514.08 | 514.08 |
| R470 | All driver versions prior to 474.14 | 474.14 |
| Tesla | Windows | R525 | All driver versions prior to 527.41 | 527.41 |
| R515 | All driver versions prior to 517.88 | 517.88 |
| R510 | All driver versions prior to 514.08 | 514.08 |
| R470 | All driver versions prior to 474.14 | 474.14 |
| R450 | All driver versions prior to 454.02 | 454.02 |


#### CVE IDs Addressed in Each Linux Driver Branch


The following table lists the CVE IDs addressed by the update in each Linux driver branch.



| \*\*Linux Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R515 | CVE‑2022‑34670, CVE‑2022‑34673, CVE‑2022‑34674, CVE‑2022‑34675, CVE‑2022‑34677, CVE‑2022‑34679, CVE‑2022‑34680, CVE‑2022‑34682, CVE‑2022‑34684, CVE‑2022‑42254, CVE‑2022‑42255, CVE‑2022‑42256, CVE‑2022‑42257, CVE‑2022‑42258, CVE‑2022‑42259, CVE‑2022‑42263, CVE‑2022‑42264, CVE‑2022‑42265 |
| R510 | CVE‑2022‑34670, CVE‑2022‑34674, CVE‑2022‑34675, CVE‑2022‑34677, CVE‑2022‑34679, CVE‑2022‑34680, CVE‑2022‑34682, CVE‑2022‑34684, CVE‑2022‑42254, CVE‑2022‑42255, CVE‑2022‑42256, CVE‑2022‑42257, CVE‑2022‑42258, CVE‑2022‑42259, CVE‑2022‑42260, CVE‑2022‑42261, CVE‑2022‑42262, CVE‑2022‑42263, CVE‑2022‑42264 |
| R470 | CVE‑2022‑34670, CVE‑2022‑34674, CVE‑2022‑34675, CVE‑2022‑34677, CVE‑2022‑34679, CVE‑2022‑34680, CVE‑2022‑34682, CVE‑2022‑42254, CVE‑2022‑42255, CVE‑2022‑42256, CVE‑2022‑42257, CVE‑2022‑42258, CVE‑2022‑42259, CVE‑2022‑42260, CVE‑2022‑42261, CVE‑2022‑42262, CVE‑2022‑42263, CVE‑2022‑42264 |
| R450 | CVE‑2022‑34670, CVE‑2022‑34674, CVE‑2022‑34675, CVE‑2022‑34677, CVE‑2022‑34679, CVE‑2022‑34680, CVE‑2022‑34682, CVE‑2022‑42254, CVE‑2022‑42256, CVE‑2022‑42257, CVE‑2022‑42258, CVE‑2022‑42259, CVE‑2022‑42260, CVE‑2022‑42261, CVE‑2022‑42262, CVE‑2022‑42263, CVE‑2022‑42264 |
| R390 | CVE‑2022‑34670, CVE‑2022‑34674, CVE‑2022‑34675, CVE‑2022‑34677, CVE‑2022‑34680, CVE‑2022‑42257, CVE‑2022‑42258, CVE‑2022‑42259 |


#### Security Updates for NVIDIA GPU Linux Display Driver


The following table lists the NVIDIA software products affected, Linux driver versions affected, and the updated version available from nvidia.com that includes this security update. Download the updates from the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx) page.




| \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Driver Branch\*\* | \*\*Affected Driver Versions\*\* | \*\*Updated Driver Version\*\* |
| --- | --- | --- | --- | --- |
| GeForce | Linux | R525 | All driver versions prior to 525.60.11 | 525.60.11 |
| R515 | All driver versions prior to 515.86.01 | 515.86.01 |
| R510 | All driver versions prior to 510.108.03 | 510.108.03 |
| R470 | All driver versions prior to 470.161.03 | 470.161.03 |
| R390 | All driver versions prior to 390.157 | 390.157 |
| NVIDIA RTX, Quadro, NVS | Linux | R525 | All driver versions prior to 525.60.11 | 525.60.11 |
| R515 | All driver versions prior to 515.86.01 | 515.86.01 |
| R510 | All driver versions prior to 510.108.03 | 510.108.03 |
| R470 | All driver versions prior to 470.161.03 | 470.161.03 |
| R390 | All driver versions prior to 390.157 | 390.157 |
| Tesla | Linux | R525 | All driver versions prior to 525.60.13 | 525.60.13 |
| R515 | All driver versions prior to 515.86.01 | 515.86.01 |
| R510 | All driver versions prior to 510.108.03 | 510.108.03 |
| R470 | All driver versions prior to 470.161.03 | 470.161.03 |
| R450 | All driver versions prior to 450.216.04 | 450.216.04 |


**Notes:** 


* Your computer hardware vendor may provide you with Windows GPU display driver versions including 526.56, 522.35, 517.66, and 474.04, which also contain the security updates.
* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, upgrade to the latest branch release.


### Security Updates for NVIDIA vGPU Software


#### CVE IDs Addressed in Each vGPU Driver Branch


The following table lists the CVE IDs addressed by the update in each Windows driver branch.




| \*\*Windows Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R525 | CVE‑2022‑42266, CVE‑2022‑42267, CVE‑2022‑34669, CVE‑2022‑34681, CVE‑2022‑34683, CVE‑2022‑34672 |
| R510, R470, R450 | CVE‑2022‑42266, CVE‑2022‑34669, CVE‑2022‑34681, CVE‑2022‑34683, CVE‑2022‑34672 |


The following table lists the CVE IDs addressed by the update in each Linux driver branch.




| \*\*Linux Driver Branch\*\* | \*\*CVE IDs Addressed\*\* |
| --- | --- |
| R510 | CVE‑2022‑34670, CVE‑2022‑34674, CVE‑2022‑34675, CVE‑2022‑34677, CVE‑2022‑34679, CVE‑2022‑34680, CVE‑2022‑34682, CVE‑2022‑34684, CVE‑2022‑42254, CVE‑2022‑42255, CVE‑2022‑42256, CVE‑2022‑42257, CVE‑2022‑42258, CVE‑2022‑42259, CVE‑2022‑42260, CVE‑2022‑42261, CVE‑2022‑42262, CVE‑2022‑42263, CVE‑2022‑42264 |
| R470 | CVE‑2022‑34670, CVE‑2022‑34674, CVE‑2022‑34675, CVE‑2022‑34677, CVE‑2022‑34679, CVE‑2022‑34680, CVE‑2022‑34682, CVE‑2022‑42254, CVE‑2022‑42255, CVE‑2022‑42256, CVE‑2022‑42257, CVE‑2022‑42258, CVE‑2022‑42259, CVE‑2022‑42260, CVE‑2022‑42261,  CVE‑2022‑42262, CVE‑2022‑42263, CVE‑2022‑42264 |
| R450 | CVE‑2022‑34670, CVE‑2022‑34674, CVE‑2022‑34675, CVE‑2022‑34677, CVE‑2022‑34679, CVE‑2022‑34680, CVE‑2022‑34682, CVE‑2022‑42254, CVE‑2022‑42256, CVE‑2022‑42257, CVE‑2022‑42258, CVE‑2022‑42259, CVE‑2022‑42260, CVE‑2022‑42261, CVE‑2022‑42262, CVE‑2022‑42263, CVE‑2022‑42264 |


#### Affected Products, Affected Versions, and Updated Versions


The following table lists NVIDIA software products affected, versions affected, and the updated version that includes this security update.




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*vGPU Software\*\* | \*\*Driver\*\* | \*\*vGPU Software\*\* | \*\*Driver\*\* |
| CVE‑2022‑34669 CVE‑2022‑34681 CVE‑2022‑34683 CVE‑2022‑42266 CVE‑2022‑42267 CVE‑2022‑34678 CVE‑2022‑34672 | vGPU software (guest driver) | Windows | All versions prior to and including 14.3 | 513.91 | 14.4 | 514.08 |
| All versions prior to and including 13.5 | 474.04 | 13.6 | 474.14 |
| All versions prior to and including 11.10 | 453.94 | 11.11 | 454.02 |
| CVE‑2022‑34670 CVE‑2022‑42263 CVE‑2022‑34674 CVE‑2022‑34677 CVE‑2022‑42264 CVE‑2022‑34679 CVE‑2022‑34680 CVE‑2022‑34682 CVE‑2022‑34676 CVE‑2022‑34684 CVE‑2022‑42254 CVE‑2022‑42255 CVE‑2022‑42256 CVE‑2022‑42257 CVE‑2022‑42258 CVE‑2022‑42259 CVE‑2022‑42260 CVE‑2022‑34678 | vGPU software (guest driver) | Linux | All versions prior to and including 14.3 | 510.85.02 | 14.4 | 510.108.03 |
| All versions prior to and including 13.5 | 470.141.03 | 13.6 | 470.161.03 |
| All versions prior to and including 11.10 | 450.203.02 | 11.11 | 450.216.04 |
| CVE‑2022‑34670 CVE‑2022‑42263 CVE‑2022‑34674 CVE‑2022‑34677 CVE‑2022‑42264 CVE‑2022‑34679 CVE‑2022‑34680 CVE‑2022‑34682 CVE‑2022‑34676 CVE‑2022‑34684 CVE‑2022‑42254 CVE‑2022‑42255 CVE‑2022‑42256 CVE‑2022‑42257 CVE‑2022‑42258 CVE‑2022‑42259 CVE‑2022‑42261 CVE‑2022‑42262 CVE‑2022‑34675 CVE‑2022‑34678 | vGPU software (Virtual GPU Manager) | Citrix Hypervisor, VMware vSphere, Red Hat Enterprise Linux KVM | All versions prior to and including 14.3 | 510.85.03 | 14.4 | 510.108.03 |
| All versions prior to and including 13.5 | 470.141.05 | 13.6 | 470.161.02 |
| All versions prior to and including 11.10 | 450.203 | 11.11 | 450.216.04 |


**Notes:**


* The table above may not be a comprehensive list of all affected supported versions or branch releases and may be updated as more information becomes available.
* Earlier software branch releases that support these products may also be affected. If you are using an earlier branch release for which an update version is not listed above, upgrade to the latest branch release.


### Security Updates for NVIDIA Cloud Gaming


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | | \*\*Updated Version\*\* | |
| --- | --- | --- | --- | --- | --- | --- |
| \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* | \*\*Cloud Gaming Software\*\* | \*\*Driver\*\* |
| CVE‑2022‑34669 CVE‑2022‑34681 CVE‑2022‑34683 CVE‑2022‑42266 CVE‑2022‑34678 CVE‑2022‑34672 | NVIDIA Cloud Gaming (guest driver) | Windows | All versions prior to the November 2022 release | All versions prior to 522.25 | November 2022 release | 527.27 |
| CVE‑2022‑34670 CVE‑2022‑34674 CVE‑2022‑34676 CVE‑2022‑34677 CVE‑2022‑34678 CVE‑2022‑34679 CVE‑2022‑34680 CVE‑2022‑34682 CVE‑2022‑34684 CVE‑2022‑42254 CVE‑2022‑42255 CVE‑2022‑42256 CVE‑2022‑42257 CVE‑2022‑42258 CVE‑2022‑42259 CVE‑2022‑42260 CVE‑2022‑42263 CVE‑2022‑42264 | NVIDIA Cloud Gaming (guest driver) | Linux | All versions prior to the November 2022 release | All versions prior to 520.56.06 | November 2022 release | 525.60.11 |
| CVE‑2022‑34670 CVE‑2022‑34674 CVE‑2022‑34675 CVE‑2022‑34676 CVE‑2022‑34677 CVE‑2022‑34678 CVE‑2022‑34679 CVE‑2022‑34680 CVE‑2022‑34682 CVE‑2022‑34684 CVE‑2022‑42254 CVE‑2022‑42255 CVE‑2022‑42256 CVE‑2022‑42257 CVE‑2022‑42258 CVE‑2022‑42259 CVE‑2022‑42261 CVE‑2022‑42262 CVE‑2022‑42263 CVE‑2022‑42264 | NVIDIA Cloud Gaming (Virtual GPU Manager) | Citrix Hypervisor, Red Hat Enterprise Linux KVM | All versions prior to the November 2022 release | All versions prior to 520.56.06 | November 2022 release | 525.60.12 |


### Acknowledgements


NVIDIA thanks the following people for reporting the issues to us:


* CVE‑2022‑34669 - Daniel Santos (@bananabr)
* CVE‑2022‑34671 - Piotr Bania - Cisco Talos
* CVE‑2022‑34682 - Tal Lossos
* CVE‑2022‑34683 and CVE‑2022‑42266 - Wei Lei and Sergey Kornienko (@b1thvn\_) of PixiePoint Security


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to

* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 3.0 | December 20, 2022 | Changed to reflect the new versions of the updated R525, R510, R470, and R450 drivers for Windows that address CVE-2022-42267 |
| 2.0 | December 5, 2022 | Added CVE-2022-42267 and updated the availability of R525  Tesla drivers for Windows and Linux |
| 1.0 | November 28, 2022 | Initial release |


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
* [ NVIDIA Omniverse Nucleus and Omniverse Cache - April 2022](/app/answers/detail/a_id/5342/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX) - April 2022](/app/answers/detail/a_id/5343/related/1)
* [ NVIDIA Data Plane Development Kit (MLNX\_DPDK) - August 2022](/app/answers/detail/a_id/5389/related/1)








