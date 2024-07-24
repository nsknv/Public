# AMI Baseboard Management Controller (BMC) Firmware Vulnerabilities in NVIDIA DGX-1, DGX-2, and DGX A100 Servers (Bulletin ID: 5010)



 AMI Baseboard Management Controller (BMC) Firmware Vulnerabilities in NVIDIA DGX-1, DGX-2, and DGX A100 Servers - October 2020
=================================================================================================================================================




 Updated 10/05/2021 11:02 AM



NVIDIA has released a firmware security update for NVIDIA DGX™ servers. This update addresses security issues in the AMI Baseboard Management Controller (BMC) firmware that may lead to remote code execution, elevation of privileges, or information disclosure. All issues require network access to the BMC of the DGX server.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


To protect your system, download and install this firmware update through the [NVIDIA Enterprise Support Portal](https://nvid.nvidia.com/dashboard/).
-----------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).
------------------------------------------------------------------






---




### Details


This section summarizes the potential impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/user-guide) standards.




This section summarizes the potential impact that this security update addresses. Descriptions use CWE™, and base scores and vectors use CVSS v3.1 standards.
| \*\*CVE IDs\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2020‑11483 | NVIDIA DGX servers contain a vulnerability in the AMI BMC firmware in which the firmware includes hard-coded credentials, which may lead to elevation of privileges or information disclosure. | 9.8 | [AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2020‑11484 | NVIDIA DGX servers contain a vulnerability in the AMI BMC firmware in which an attacker with administrative privileges can obtain the hash of the BMC/IPMI user password, which may lead to information disclosure. | 8.4 | [AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2020‑11487 | NVIDIA DGX servers contain a vulnerability in the AMI BMC firmware in which the use of a hard-coded RSA 1024 key with weak ciphers may lead to information disclosure. | 8.2 | [AV:N/AC:L/PR:N/UI:N/S:U/C:L/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:N/UI:N/S:U/C:L/I:N/A:H) |
| CVE‑2020‑11485 | NVIDIA DGX servers contain a Cross-Site Request Forgery (CSRF) vulnerability in the AMI BMC firmware in which the web application does not sufficiently verify whether a well-formed, valid, consistent request was intentionally provided by the user who submitted the request, which can lead to information disclosure or code execution. | 8.1 | [AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:N/A:H) |
| CVE‑2020‑11486 | NVIDIA DGX servers contain a vulnerability in the AMI BMC firmware in which software allows an attacker to upload or transfer files that can be automatically processed within the product's environment, which may lead to remote code execution. | 8.1 | [AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:N/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:N/A:H) |
| CVE‑2020‑11615 | NVIDIA DGX servers contain a vulnerability in the AMI BMC firmware in which it uses a hard-coded RC4 cipher key, which may lead to information disclosure. | 7.5 | [AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N) |
| CVE‑2020‑11488 | NVIDIA DGX servers contain a vulnerability in the AMI BMC firmware in which software does not validate the RSA 1024 public key used to verify the firmware signature, which may lead to information disclosure or code execution. | 6.7 | [AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H/AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H) |
| CVE‑2020‑11489 | NVIDIA DGX servers contain a vulnerability in the AMI BMC firmware in which default SNMP community strings are used, which may lead to information disclosure. | 6.5 | [AV:N/AC:L/PR:N/UI:N/S:U/C:L/I:N/A:L](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:N/UI:N/S:U/C:L/I:N/A:L) |
| CVE‑2020‑11616 | NVIDIA DGX servers contain a vulnerability in the AMI BMC firmware in which the Pseudo-Random Number Generator (PRNG) algorithm used in the JSOL package that implements the IPMI protocol is not cryptographically strong, which may lead to information disclosure. | 2.9 | [AV:A/AC:H/PR:N/UI:R/S:C/C:L/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:A/AC:H/PR:N/UI:R/S:C/C:L/I:N/A:N) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Download the updates from [NVIDIA Enterprise Support Portal](https://nvid.nvidia.com/enterpriselogin).




The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update. Download the updates from [NVIDIA Enterprise Support Portal](https://nvid.nvidia.com/enterpriselogin).
| \*\*CVE IDs Addressed\*\* | \*\*Hardware Platform\*\* | \*\*System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2020‑11483 | NVIDIA DGX servers | DGX-1 | All BMC firmware versions prior to 3.38.30 | BMC firmware 3.38.30 |
| DGX-2 | All BMC firmware versions prior to 1.06.06 | BMC firmware 1.06.06 |
| CVE‑2020‑11484 | NVIDIA DGX servers | DGX-1 | All BMC firmware versions prior to 3.38.30 | BMC firmware 3.38.30 |
| CVE‑2020‑11485 | NVIDIA DGX servers | DGX-1 | All BMC firmware versions prior to 3.38.30 | BMC firmware 3.38.30 |
| CVE‑2020‑11486 | NVIDIA DGX servers | DGX-1 | All BMC firmware versions prior to 3.38.30 | BMC firmware 3.38.30 |
| CVE‑2020‑11487 | NVIDIA DGX servers | DGX-1 | All BMC firmware versions prior to 3.38.30 | BMC firmware 3.38.30 |
| DGX-2 | All BMC firmware versions prior to 1.06.06 | BMC firmware 1.06.06 |
| DGX A100 | All BMC firmware versions prior to 00.13.16 | BMC firmware 00.13.16 |
| CVE‑2020‑11488 | NVIDIA DGX servers | DGX-1 | All BMC firmware versions prior to 3.38.30 | BMC firmware 3.38.30 |
| DGX-2 | All BMC firmware versions prior to 1.06.06 | BMC firmware 1.06.06 |
| CVE‑2020‑11489 | NVIDIA DGX servers | DGX-1 | All BMC firmware versions prior to 3.38.30 | BMC firmware 3.38.30 |
| DGX-2 | All BMC firmware versions prior to 1.06.06 | BMC firmware 1.06.06 |
| CVE‑2020‑11615 | NVIDIA DGX servers | DGX-1 | All BMC firmware versions prior to 3.38.30 | BMC firmware 3.38.30 |
| CVE‑2020‑11616 | NVIDIA DGX servers | DGX-1 | All BMC firmware versions prior to 3.38.30 | BMC firmware 3.38.30 |


**Notes**


* Upgrade to the NVIDIA DGX-1 firmware container `nvfw-dgx1:20.10.2`, NVIDIA DGX-2 firmware container `nvfw-dgx2:20.10.7`, or NVIDIA DGX A100 firmware container `nvfw-dgxa100:20.10.9` to get the updated BMC firmware and SBIOS version listed in the table above. Firmware updates are available through the NVIDIA Enterprise Support Portal.
* NVIDIA is aware of CVE-2013-4786, which can be mitigated by placing the IPMI management port on a dedicated management LAN or VLAN restricted to trusted administrators to limit connectivity to the BMC, including the web user interface. See Section 12.1.1 in DGX A100 System User Guide ([PDF](https://docs.nvidia.com/dgx/pdf/dgxa100-user-guide.pdf)).


### Mitigations


To mitigate the security concerns in this bulletin, limit connectivity to the BMC, including the web user interface, to trusted management networks. See [Security Updates](#security-updates) for the version to install.


### Acknowledgements


NVIDIA thanks following individuals for reporting the issues.


* CVE‑2020‑11483, CVE‑2020‑11487, CVE‑2020‑11489: Sergey Gordeychik
* CVE‑2020‑11484: Roman Palkin and Sergey Gordeychik
* CVE‑2020‑11485: Maria Samoylova, Denis Kolegov, and Roman Palkin
* CVE‑2020‑11615, CVE‑2020‑11616: Denis Kolegov and Sergey Gordeychik
* CVE‑2020‑11486, CVE‑2020‑11488: Sergey Gordeychik, Maria Samoylova, Denis Kolegov, and Roman Palkin


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
| 4.0 | December 1, 2020 | Added the updated firmware version for DGX A100 systems |
| 3.0 | November 3, 2020 | Further updated the projected availability of the update for DGX A100 systems |
| 2.0 | November 2, 2020 | Updated the projected availability of the update for DGX A100 systems |
| 1.0 | October 28, 2020 | Initial release |


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


* [ NVIDIA GPU Display Driver - November 2019](/app/answers/detail/a_id/4907/related/1)
* [ NVIDIA GPU Display Driver - June 2020](/app/answers/detail/a_id/5031/related/1)
* [ NVIDIA GPU Display Driver - February 2020](/app/answers/detail/a_id/4996/related/1)
* [ NVIDIA GeForce Experience - July 2020](/app/answers/detail/a_id/5038/related/1)
* [Security Notice: NVIDIA Response to Ripple20 - June 2020](/app/answers/detail/a_id/5033/related/1)








