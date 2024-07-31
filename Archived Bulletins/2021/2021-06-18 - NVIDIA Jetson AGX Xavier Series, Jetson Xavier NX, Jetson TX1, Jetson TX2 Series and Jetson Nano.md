# NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) (Bulletin ID: 5205)



 NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) - June 2021
======================================================================================================================================================================================




 Updated 10/05/2021 02:10 PM



NVIDIA has released a software update for NVIDIA® Jetson AGX Xavier™ series, Jetson Xavier™ NX, Jetson™ TX1, Jetson TX2 series (including Jetson TX2 NX), and Jetson Nano™ devices (including Jetson Nano 2GB) in the NVIDIA JetPack™ SDK. This update addresses security issues that may lead to escalation of privileges, denial of service, and information disclosure. To protect your system, download and install the latest Debian packages from the APT repositories.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security](https://www.nvidia.com/security).
-----------------------------------------------------------------






---




### Details


This section provides a summary of potential vulnerabilities and their impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/v3.1/user-guide) standards.




This section provides a summary of potential vulnerabilities and their impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/v3.1/user-guide) standards.
| \*\*CVE IDs\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2021‑34372 | Trusty (the trusted OS produced by NVIDIA for Jetson devices) driver contains a vulnerability in the NVIDIA OTE protocol message parsing code where an integer overflow in a `malloc()` size calculation leads to a buffer overflow on the heap, which might result in information disclosure, escalation of privileges, and denial of service. | 8.2 | [AV:L/AC:L/PR:L/UI:R/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:R/S:C/C:H/I:H/A:H) |
| CVE‑2021‑34373 | Trusty trusted Linux kernel (TLK) contains a vulnerability in the NVIDIA TLK kernel where a lack of heap hardening could cause heap overflows, which might lead to information disclosure and denial of service. | 7.9 | [AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:N/A:H) |
| CVE‑2021‑34374 | Trusty contains a vulnerability in command handlers where the length of input buffers is not verified. This vulnerability can cause memory corruption, which may lead to information disclosure, escalation of privileges, and denial of service. | 7.7 | [AV:L/AC:L/PR:H/UI:R/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:R/S:C/C:H/I:H/A:H) |
| CVE‑2021‑34375 | Trusty contains a vulnerability in all trusted applications (TAs) where the stack cookie was not randomized, which might result in stack-based buffer overflow, leading to denial of service, escalation of privileges, and information disclosure. | 7.7 | [AV:L/AC:L/PR:H/UI:R/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:R/S:C/C:H/I:H/A:H) |
| CVE‑2021‑34376 | Trusty contains a vulnerability in the HDCP service TA where bounds checking in command 5 is missing. Improper restriction of operations within the bounds of a memory buffer might lead to denial of service, escalation of privileges, and information disclosure. | 7.7 | [AV:L/AC:L/PR:H/UI:R/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:R/S:C/C:H/I:H/A:H) |
| CVE‑2021‑34377 | Trusty contains a vulnerability in the HDCP service TA where bounds checking in command 9 is missing. Improper restriction of operations within the bounds of a memory buffer might lead to escalation of privileges, information disclosure, and denial of service. | 7.7 | [AV:L/AC:L/PR:H/UI:R/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:R/S:C/C:H/I:H/A:H) |
| CVE‑2021‑34378 | Trusty contains a vulnerability in the HDCP service TA where bounds checking in command 11 is missing. Improper restriction of operations within the bounds of a memory buffer might lead to information disclosure, denial of service, or escalation of privileges. | 7.7 | [AV:L/AC:L/PR:H/UI:R/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:R/S:C/C:H/I:H/A:H) |
| CVE‑2021‑34379 | Trusty contains a vulnerability in the HDCP service TA where bounds checking in command 10 is missing. The length of an I/O buffer parameter is not checked, which might lead to memory corruption. | 7.7 | [AV:L/AC:L/PR:H/UI:R/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:R/S:C/C:H/I:H/A:H) |
| CVE‑2021‑34380 | Bootloader contains a vulnerability in NVIDIA MB2 where potential heap overflow might cause corruption of the heap metadata, which might lead to arbitrary code execution, denial of service, and information disclosure during secure boot. | 7.0 | [AV:L/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑34381 | Trusty TLK contains a vulnerability in the NVIDIA TLK kernel function where a lack of checks allows the exploitation of an integer overflow on the size parameter of the `tz\_map\_shared\_mem` function, which might lead to denial of service, information disclosure, or data tampering. | 6.7 | [AV:L/AC:H/PR:L/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:R/S:U/C:H/I:H/A:H/E:P/RL:X/RC:C) |
| CVE‑2021‑34382 | Trusty TLK contains a vulnerability in the NVIDIA TLK kernel’s `tz\_map\_shared\_mem` function where an integer overflow on the size parameter causes the request buffer and the logging buffer to overflow, allowing writes to arbitrary addresses within the kernel. | 6.7 | [AV:L/AC:H/PR:L/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:R/S:U/C:H/I:H/A:H/E:P/RL:X/RC:C) |
| CVE‑2021‑34383 | Bootloader contains a vulnerability in NVIDIA MB2 where a potential heap overflow might lead to denial of service or escalation of privileges. | 6.4 | [AV:L/AC:H/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2021‑34384 | Bootloader contains a vulnerability in NVIDIA MB2 where a potential heap overflow could cause memory corruption, which might lead to denial of service or code execution. | 6.3 | [AV:L/AC:H/PR:L/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:N/S:U/C:N/I:H/A:H) |
| CVE‑2021‑34385 | Trusty TLK contains a vulnerability in the NVIDIA TLK kernel where an integer overflow in the calculation of a length could lead to a heap overflow. | 6.3 | [AV:L/AC:H/PR:H/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:R/S:U/C:H/I:H/A:H/E:P/RL:X/RC:C) |
| CVE‑2021‑34386 | Trusty TLK contains a vulnerability in the NVIDIA TLK kernel where an integer overflow in the `calloc` size calculation can cause the multiplication of count and size can overflow, which might lead to heap overflows. | 6.3 | [AV:L/AC:H/PR:H/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:R/S:U/C:H/I:H/A:H/E:P/RL:X/RC:C) |
| CVE‑2021‑34387 | The ARM® TrustZone Technology on which Trusty is based on contains a vulnerability in access permission settings where the portion of the DRAM reserved for TrustZone is identity-mapped by TLK with read, write, and execute permissions, which gives write access to kernel code and data that is otherwise mapped read only. | 6.3 | [AV:L/AC:H/PR:H/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:R/S:U/C:H/I:H/A:H/E:P/RL:X/RC:C) |
| CVE‑2021‑34388 | Bootloader contains a vulnerability in NVIDIA TegraBoot where a potential heap overflow might allow an attacker to control all the RAM after the heap block, leading to denial of service or code execution. | 6.3 | [AV:L/AC:H/PR:L/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:N/S:U/C:N/I:H/A:H) |
| CVE‑2021‑34389 | Trusty contains a vulnerability in NVIDIA OTE protocol message parsing code, which is present in all the TAs. An incorrect bounds check can allow a local user through a malicious client to access memory from the heap in the TrustZone, which may lead to information disclosure. | 5.0 | [AV:L/AC:L/PR:L/UI:R/S:U/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:R/S:U/C:H/I:N/A:N) |
| CVE‑2021‑34390 | Trusty contains a vulnerability in the NVIDIA TLK kernel function where a lack of checks allows the exploitation of an integer overflow through a specific SMC call that is triggered by the user, which may lead to denial of service. | 5.3 | [AV:L/AC:H/PR:L/UI:R/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:R/S:C/C:N/I:N/A:H/E:P/RL:X/RC:C) |
| CVE‑2021‑34391 | Trusty contains a vulnerability in the NVIDIA TLK kernel function where a lack of checks allows the exploitation of an integer overflow through a specific SMC call that is triggered by the user, which may lead to denial of service. | 5.3 | [AV:L/AC:H/PR:L/UI:R/S:C/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:R/S:C/C:N/I:N/A:H/E:P/RL:X/RC:C) |
| CVE‑2021‑34392 | Trusty TLK contains a vulnerability in the NVIDIA TLK kernel where an integer overflow in the `tz\_map\_shared\_mem` function can bypass boundary checks, which might lead to denial of service. | 4.4 | [AV:L/AC:H/PR:L/UI:R/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:R/S:U/C:N/I:N/A:H/E:P/RL:X/RC:C) |
| CVE‑2021‑34393 | Trusty contains a vulnerability in TSEC TA which deserializes the incoming messages even though the TSEC TA does not expose any command. This vulnerability might allow an attacker to exploit the deserializer to impact code execution, causing information disclosure. | 4.2 | [AV:L/AC:L/PR:H/UI:R/S:U/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:R/S:U/C:H/I:N/A:N) |
| CVE‑2021‑34394 | Trusty contains a vulnerability in the NVIDIA OTE protocol that is present in all TAs. An incorrect message stream deserialization allows an attacker to use the malicious CA that is run by the user to cause the buffer overflow, which may lead to information disclosure and data modification. | 4.2 | [AV:L/AC:L/PR:H/UI:R/S:U/C:N/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:R/S:U/C:N/I:N/A:H) |
| CVE‑2021‑34395 | Trusty TLK contains a vulnerability in its access permission settings where it does not properly restrict access to a resource from a user with local privileges, which might lead to limited information disclosure, a low risk of modifcations to data, and limited denial of service. | 3.9 | [AV:L/AC:H/PR:H/UI:N/S:U/C:L/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:U/C:L/I:L/A:L) |
| CVE‑2021‑34396 | Bootloader contains a vulnerability in access permission settings where unauthorized software may be able to overwrite NVIDIA MB2 code, which would result in limited denial of service. | 3.0 | [AV:L/AC:H/PR:H/UI:N/S:U/C:N/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:U/C:N/I:L/A:L) |
| CVE‑2021‑34397 | Bootloader contains a vulnerability in NVIDIA MB2, which may cause free-the-wrong-heap, which may lead to limited denial of service. | 1.9 | [AV:L/AC:H/PR:H/UI:N/S:U/C:N/I:N/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:U/C:N/I:N/A:L) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.




The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.
| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2021‑34372 CVE‑2021‑34374 CVE‑2021‑34375 CVE‑2021‑34376 CVE‑2021‑34377 CVE‑2021‑34378 CVE‑2021‑34379 CVE‑2021‑34380 CVE‑2021‑34383 CVE‑2021‑34384 CVE‑2021‑34389 CVE‑2021‑34393 CVE‑2021‑34394 CVE‑2021‑34396 CVE‑2021‑34397 | Jetson AGX Xavier series, Jetson Xavier NX, Jetson TX2 series, Jetson TX2 NX | Jetson Linux | Versions prior to 32.5.1 | 32.5.2 or 32.5.1 latest Debian update |
| CVE‑2021‑34389 CVE‑2021‑34393 CVE‑2021‑34394 CVE‑2021‑34396 CVE‑2021‑34397 | Jetson TX2 series | Jetson Linux | Versions prior to 28.5 | 28.5 |
| CVE‑2021‑34373 CVE‑2021‑34381 CVE‑2021‑34382 CVE‑2021‑34385 CVE‑2021‑34386 CVE‑2021‑34387 CVE‑2021‑34390 CVE‑2021‑34391 CVE‑2021‑34392 CVE‑2021‑34395 | Jetson TX1 | Jetson Linux | Versions prior to 32.5.1 (if using TLK) | 32.5.2 or 32.5.1 latest Debian update |
| Versions prior to 28.5 | 28.5 |
| CVE‑2021‑34388 | Jetson TX1, Jetson Nano, Jetson Nano 2GB | Jetson Linux | Versions prior to 32.5.1 | 32.5.2 or 32.5.1 latest Debian update |
| Jetson TX1 | Jetson Linux | Versions prior to 28.5 | 28.5 |


#### Notes


* Earlier software branch releases that support these products are also affected.
	+ If you are using an earlier branch release, upgrade to the latest 32.5.2 or 28.5 release.
	+ If you are using the 32.5.1 release, you could also update to the latest Debian packages.


### Mitigations


See [Security Updates](#security-updates) for the version to install.


### Acknowledgements


CVE‑2021‑34372 through CVE‑2021‑34397: NVIDIA thanks Frédéric Perriot of the Apple Media Products RedTeam for reporting these issues.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History




Revision History





| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 5.0 | July 15, 2021 | Updated the Security Updates table to add security updates information for r28.5 and r32.5.2 Updated the CVSS score for CVE-2021-34389 |
| 4.0 | July 2, 2021 | Updated the Security Updates table for CVE‑2021‑34388 and CVE‑2021‑34396 |
| 3.0 | June 29, 2021 | Updated the description for CVE-2021-34388 |
| 2.0 | June 25, 2021 | Updated the Security Updates table |
| 1.0 | June 18, 2021 | Initial release |


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


* [ NVIDIA Jetson AGX Xavier, TX1, TX2, and Nano L4T - July 2020](/app/answers/detail/a_id/5039/related/1)
* [ Jetson AGX Xavier, TK1, TX1, TX2, and Nano L4T- December 2019](/app/answers/detail/a_id/4910/related/1)
* [ NVIDIA GPU Display Driver - January 2021](/app/answers/detail/a_id/5142/related/1)
* [ NVIDIA Jetson TX1 and Jetson Nano L4T - July 2019](/app/answers/detail/a_id/4835/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB)- August 2021](/app/answers/detail/a_id/5216/related/1)








