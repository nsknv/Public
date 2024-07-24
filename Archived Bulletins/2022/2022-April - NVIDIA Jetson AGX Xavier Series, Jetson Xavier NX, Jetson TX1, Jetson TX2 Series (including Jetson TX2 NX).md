# NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX) (Bulletin ID: 5343)



 NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX) - April 2022
==========================================================================================================================================




 Updated 05/26/2022 12:55 PM



NVIDIA has released a software update for NVIDIA® Jetson AGX Xavier™ series, Jetson Xavier™ NX, Jetson TX1, Jetson TX2 series (including Jetson TX2 NX) in the NVIDIA JetPack™ software development kit (SDK). The update addresses security issues that may lead to denial of service, escalation of privileges, and impacts to data integrity and confidentiality. To protect your system, download and install the latest NVIDIA JetPack SDK from [NVIDIA DevZone](https://developer.nvidia.com/embedded/downloads).


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/v3.1/user-guide) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑28193 | NVIDIA Jetson Linux Driver Package contains a vulnerability in the Cboot module `tegrabl\_cbo.c`, where insufficient validation of untrusted data may allow a local attacker with elevated privileges to cause a memory buffer overflow, which may lead to code execution, loss of integrity, limited denial of service, and some impact to confidentiality. | 5.6 | [AV:L/AC:L/PR:H/UI:N/S:U/C:L/I:H/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:L/I:H/A:L) |
| CVE‑2022‑28194 | NVIDIA Jetson Linux Driver Package contains a vulnerability in the Cboot module `tegrabl\_cbo.c`, where, if TFTP is enabled, a local attacker with elevated privileges can cause a memory buffer overflow, which may lead to code execution, loss of Integrity, limited denial of service, and some impact to confidentiality. | 5.6 | [AV:L/AC:L/PR:N/UI:N/S:U/C:L/I:H/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:L/I:H/A:L) |
| CVE‑2022‑28195 | NVIDIA Jetson Linux Driver Package contains a vulnerability in the Cboot `ext4\_read\_file` function, where insufficient validation of untrusted data may allow a highly privileged local attacker to cause a integer overflow, which may lead to code execution, escalation of privileges, limited denial of service, and some impact to confidentiality and integrity. The scope of impact can extend to other components. | 5.7 | [AV:L/AC:L/PR:H/UI:N/S:C/C:L/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:C/C:L/I:L/A:L) |
| CVE‑2022‑28196 | NVIDIA Jetson Linux Driver Package contains a vulnerability in the Cboot `blob\_decompress` function, where insufficient validation of untrusted data may allow a local attacker  with elevated privileges to cause a memory buffer overflow, which may lead to code execution, limited loss of Integrity, and limited denial of service.The scope of impact can extend to other components. | 4.6 | [AV:L/AC:L/PR:H/UI:N/S:C/C:N/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:C/C:N/I:L/A:L) |
| CVE‑2022‑28197 | NVIDIA Jetson Linux Driver Package contains a vulnerability in the Cboot `ext4\_mount` function, where Insufficient validation of untrusted data may allow a highly privileged local attacker to cause an integer overflow. This difficult- to-exploit vulnerability may lead to code execution, escalation of privileges, limited denial of service, and some impact to confidentiality and integrity. The scope of impact can extend to other components. | 5.0 | [AV:L/AC:H/PR:H/UI:N/S:C/C:L/I:L/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:C/C:L/I:L/A:L) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. 




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2022‑28193 CVE‑2022‑28194 CVE‑2022‑28195 CVE‑2022‑28197 | Jetson AGX Xavier series, Jetson Xavier NX | Jetson Linux | All versions prior to 32.7.2 | 32.7.2 |
| CVE‑2022‑28196 | Jetson AGX Xavier series, Jetson Xavier NX, Jetson TX2 NX, Jetson TX2 series | Jetson Linux | All versions prior to 32.7.2 | 32.7.2 |


**Notes:**


* Earlier software branch releases that support this product are also affected. If you are using an earlier branch release, upgrade to the latest branch release.


### Mitigations


None. See [Security Updates](#security-updates) for the version to install.


### Acknowledgements


NVIDIA thanks Galen Schretlen of Worldcoin for reporting issues CVE‑2022‑28193, CVE‑2022‑28194, CVE‑2022‑28195, CVE‑2022‑28196, and CVE‑2022‑28197.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| Revision | Date | Description |
| --- | --- | --- |
| 2.0 | May 26, 2022 | Updated the description text and the CVSS scoring information to reflect new information about the CVE IDs |
| 1.0 | April 26, 2022 | Initial release |


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


* [ NVIDIA SHIELD TV - January 2022](/app/answers/detail/a_id/5259/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) - March 2022](/app/answers/detail/a_id/5321/related/1)
* [ NVIDIA License System - February 2022](/app/answers/detail/a_id/5319/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB)- August 2021](/app/answers/detail/a_id/5216/related/1)
* [ NVIDIA Omniverse Launcher - January 2022](/app/answers/detail/a_id/5318/related/1)








