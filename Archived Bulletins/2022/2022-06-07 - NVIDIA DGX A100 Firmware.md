# NVIDIA DGX A100 Firmware (Bulletin ID: 5367)



 NVIDIA DGX A100 Firmware - June 2022
=======================================================




 Updated 06/07/2022 12:23 PM



NVIDIA has released a security update for NVIDIA DGX A100 firmware. This update addresses issues that may lead to information disclosure, denial of service, or escalation of privileges.


To protect your system, download and install this firmware update through the [NVIDIA Enterprise Support Portal](https://nvid.nvidia.com/dashboard/).


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑28200 | NVIDIA DGX A100 contains a vulnerability in SBIOS in the BiosCfgTool, where a local user with elevated privileges can read and write beyond intended bounds in SMRAM, which may lead to code execution, escalation of privileges, denial of service, and information disclosure. The scope of impact can extend to other components. | 8.2 | [AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2022‑31599 | NVIDIA DGX A100 contains a vulnerability in SBIOS in the Ofbd, where a local user with elevated privileges can cause access to an uninitialized pointer, which may lead to code execution, escalation of privileges, denial of service, and information disclosure. The scope of impact can extend to other components. | 8.2 | [AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2022‑31600 | NVIDIA DGX A100 contains a vulnerability in SBIOS in the SmmCore, where a user with high privileges can chain another vulnerability to this vulnerability, causing an integer overflow, possibly leading to code execution, escalation of privileges, denial of service, compromised integrity, and information disclosure. The scope of impact can extend to other components. | 7.5 | [AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:C/C:H/I:H/A:H) |
| CVE‑2022‑31601 | NVIDIA DGX A100 contains a vulnerability in SBIOS in the SmbiosPei, which may allow a highly privileged local attacker to cause an out-of-bounds write, which may lead to code execution, denial of service, compromised integrity, and information disclosure. | 6.7 | [AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑31602 | NVIDIA DGX A100 contains a vulnerability in SBIOS in the IpSecDxe, where a user with elevated privileges and a preconditioned heap can exploit an out-of-bounds write vulnerability, which may lead to code execution, denial of service, data integrity impact, and information disclosure. | 6.4 | [AV:L/AC:H/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2022‑31603 | NVIDIA DGX A100 contains a vulnerability in SBIOS in the IpSecDxe, where a user with high privileges and preconditioned IpSecDxe global data can exploit improper validation of an array index to cause code execution, which may lead to denial of service, data integrity impact, and information disclosure. | 6.4 | [AV:L/AC:H/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:H/UI:N/S:U/C:H/I:H/A:H) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.


To protect your system, download and install this firmware update through the [NVIDIA Enterprise Support Portal](https://nvid.nvidia.com/dashboard/).




| \*\*Hardware Platform\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- |
| NVIDIA DGX A100 | All versions prior to 22.5.5 | 22.5.5 |


#### Notes:


* Upgrade to NVIDIA DGX A100 firmware container `nvfw‑nvfw‑dgxa100_22.5.5_220518.tar.gz` to get the updated firmware and SBIOS version listed in the table above. Firmware updates are available through the NVIDIA Enterprise Support Portal.


### Mitigations


None. See [Security Updates](#security-updates) for the version to install.


### Acknowledgements


The NVIDIA Product Security Team discovered these issues.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | June 7, 2022 | Initial release |


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


* [ NVIDIA License System - February 2022](/app/answers/detail/a_id/5319/related/1)
* [ NVIDIA Omniverse Launcher - January 2022](/app/answers/detail/a_id/5318/related/1)
* [Security Notice: NVIDIA Response to Security Incident - March 2022](/app/answers/detail/a_id/5333/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) - March 2022](/app/answers/detail/a_id/5321/related/1)
* [ NVIDIA SHIELD TV - January 2022](/app/answers/detail/a_id/5259/related/1)








