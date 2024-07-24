# NVIDIA Jetson TX1 and TX2 L4T (Bulletin ID: 4787)



 NVIDIA Jetson TX1 and TX2 L4T - April 2019
=============================================================




 Updated 09/29/2021 01:10 PM



NVIDIA has released software security updates for NVIDIA® Jetson™ TX1 and TX2 in the NVIDIA® Tegra® Linux Driver Package (L4T).
-------------------------------------------------------------------------------------------------------------------------------


The update addresses issues that may lead to code execution, denial of service, escalation of privileges, or information disclosure. To protect your system, download available updates from [NVIDIA DevZone](https://developer.nvidia.com/embedded/downloads).
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security](https://www.nvidia.com/product-security/).
--------------------------------------------------------------------------






---




### Details


This section summarizes the potential impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors follow [CVSS V3](https://www.first.org/cvss/user-guide) standards.




This section summarizes the potential impact that this security update addresses. Descriptions use CWE™, and base scores and vectors follow CVSS V3 standards.
| \*\*CVE\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2018‑6269 | NVIDIA Tegra kernel driver contains a vulnerability in input/output control (IOCTL) handling for user mode requests in which a non-trusted pointer dereference may be made, which may lead to information disclosure, denial of service, escalation of privileges, or code execution. | 8.8 | [AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H/) |
| CVE‑2017‑6278 | NVIDIA Tegra kernel contains a vulnerability in the CORE dynamic voltage and frequency scaling (DVFS) thermal driver in which there is the potential to read or write a buffer using an index or pointer that references a memory location after the end of the buffer, which may lead to a denial of service or escalation of privileges. | 8.4 | [AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2018‑6267 | NVIDIA Tegra OpenMax driver (`libnvomx`) contains a vulnerability in which a missing user metadata check may allow invalid metadata to pass as valid metadata, which may lead to a denial of service or escalation of privileges. | 8.4 | [AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2018‑6271 | NVIDIA Tegra OpenMax driver (`libnvomx`) contains a vulnerability in which input is invalid or erroneously validated and could affect the control flow or data flow of a program, which may lead to denial of service or escalation of privileges. | 8.4 | [AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2019‑5673 | NVIDIA Tegra kernel driver contains a vulnerability in the ARM System Memory Management Unit (SMMU) in which an improper check for a fault condition causes transactions to be discarded, which may lead to denial of service. | 7.9 | [AV:L/AC:L/PR:N/UI:N/S:C/C:N/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=CVSS:3.0/AV:L/AC:L/PR:N/UI:N/S:C/C:N/I:L/A:H) |
| CVE‑2018‑6268 | NVIDIA Tegra OpenMax driver (`libnvomx`) contains a vulnerability in `libnvmmlite\_video.so`, in which referencing memory after it has been freed may lead to denial of service or escalation of privileges. | 7.8 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2017‑6284 | NVIDIA Security Engine contains a vulnerability in the Deterministic Random Bit Generator (DRBG) in which the data may not be properly initialized, which may lead to information disclosure. | 7.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N) |
| CVE‑2017‑0330 | NVIDIA Tegra kernel contains a vulnerability in NVIDIA crypto driver in which a pointer passed from a user to the driver is not correctly validated which may lead to denial of service or escalation of privileges. | 7.1 | [AV:L/AC:L/PR:N/UI:N/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:C/C:N/I:N/A:H) |
| CVE‑2019‑5672 | NVIDIA Linux for Tegra (L4T) contains a vulnerability in which the Secure Shell (SSH) keys provided in the sample `rootfs` are not replaced by unique host keys after sample `rootsfs` generation and flashing, which may lead to information disclosure. | 6.8 | [AV:N/AC:H/PR:N/UI:R/S:U/C:H/I:H/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:H/PR:N/UI:R/S:U/C:H/I:H/A:N) |
| CVE‑2017‑6274 | NVIDIA Tegra kernel contains a vulnerability in the CORE dynamic voltage and frequency scaling (DVFS) thermal driver in which there is the potential to read or write a buffer using an index or pointer that references a memory location after the end of the buffer, which may lead to a denial of service or escalation of privileges. | 6.7 | [AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2018‑3665 | NVIDIA Tegra TX2 contains a vulnerability, which through the use of speculative execution, may disclose register contents in an unauthorized manner which may lead to information disclosure. | 5.6 | [AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=CVSS:3.0/AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:N/A:N) |
| CVE‑2018‑6239 | NVIDIA Tegra TX2 contains a vulnerability by means of speculative execution where local and unprivileged code may access the contents of cached information in an unauthorized manner, which may lead to information disclosure. | 5.6 | [AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=CVSS:3.0/AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:N/A:N) |
| CVE‑2018‑3639 | Systems with microprocessors utilizing speculative execution and speculative execution of memory reads before the addresses of all prior memory writes are known may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis, aka Speculative Store Bypass (SSB), Variant 4. | 4.3 | [AV:L/AC:L/PR:N/UI:N/S:C/C:L/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=CVSS:3.0/AV:L/AC:L/PR:N/UI:N/S:C/C:L/I:N/A:N) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk of your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products and versions affected, and the updated versions that include this security update.


Download the updates from [NVIDIA DevZone](https://developer.nvidia.com/embedded/downloads).




The following table lists the NVIDIA software products and versions affected, and the updated versions that include this security update.
| \*\*CVE\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Versions\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2017‑6278 CVE‑2018‑6271 CVE‑2019‑5672 CVE‑2018‑3639 CVE‑2018‑6267 CVE‑2018‑6268 CVE‑2017‑6274 CVE‑2017‑6284 CVE‑2017‑0330 | Jetson TX1 | Linux for Tegra | All versions prior to R28.3 | R28.3 |
| CVE‑2018‑6269 CVE‑2017‑6278 CVE‑2018‑6271 CVE‑2019‑5673 CVE‑2019‑5672 CVE‑2018‑3639 CVE‑2018‑6267 CVE‑2018‑6268 CVE‑2017‑6274 CVE‑2017‑0330 CVE‑2018‑6239 CVE‑2018‑3665 | Jetson TX2 | Linux for Tegra | All versions prior to R28.3 | R28.3 |


**Notes**


* Affected versions include the versions listed and all earlier branches and releases.
* If you are using an unsupported version or an earlier unsupported branch, upgrade to the latest supported version. To identify products that are no longer supported,contact [NVIDIA Support](https://www.nvidia.com/object/support.html).


### Mitigations


See [Security Updates](#security-updates) for the versions to install.


### Acknowledgements


CVE-2019-5672: NVIDIA thanks Jesse Raffa for reporting this issue.


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
| 1.0 | April 2, 2019 | Initial release |


### Support


If you have any questions about this security bulletin, contact [NVIDIA Support](https://www.nvidia.com/object/support.html).


##### Disclaimer


ALL NVIDIA INFORMATION, DESIGN SPECIFICATIONS, REFERENCE BOARDS, FILES, DRAWINGS, DIAGNOSTICS, LISTS, AND OTHER DOCUMENTS (TOGETHER AND SEPARATELY, “MATERIALS”) ARE BEING PROVIDED “AS IS.” NVIDIA MAKES NO WARRANTIES, EXPRESS, IMPLIED, STATUTORY, OR OTHERWISE WITH RESPECT TO THE MATERIALS, AND ALL EXPRESS OR IMPLIED CONDITIONS, REPRESENTATIONS AND WARRANTIES, INCLUDING ANY IMPLIED WARRANTY OR CONDITION OF TITLE, MERCHANTABILITY, SATISFACTORY QUALITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT, ARE HEREBY EXCLUDED TO THE MAXIMUM EXTENT PERMITTED BY LAW.


Information is believed to be accurate and reliable at the time it is furnished. However, NVIDIA Corporation assumes no responsibility for the consequences of use of such information or for any infringement of patents or other rights of third parties that may result from its use. No license is granted by implication or otherwise under any patent or patent rights of NVIDIA Corporation. Specifications mentioned in this publication are subject to change without notice. This publication supersedes and replaces all information previously supplied. NVIDIA Corporation products are not authorized for use as critical components in life support devices or systems without express written approval of NVIDIA Corporation. 










Is this answer helpful?
-----------------------



Yes
No







Answers others found helpful
----------------------------


* [ NVIDIA Jetson TX1, Jetson TK1, Jetson TX2, and Tegra K1 L4T Security Updates for Multiple Vulnerabilities](/app/answers/detail/a_id/4635/related/1)
* [ NVIDIA SHIELD TV – October 2018](/app/answers/detail/a_id/4704/related/1)
* [ NVIDIA SHIELD TV Software Security Updates for Multiple Vulnerabilities](/app/answers/detail/a_id/4682/related/1)
* [ NVIDIA SHIELD TV Security Updates for Multiple Vulnerabilities](/app/answers/detail/a_id/4631/related/1)
* [ NVIDIA GPU Display Driver Security Updates for Multiple Vulnerabilities](/app/answers/detail/a_id/4649/related/1)








