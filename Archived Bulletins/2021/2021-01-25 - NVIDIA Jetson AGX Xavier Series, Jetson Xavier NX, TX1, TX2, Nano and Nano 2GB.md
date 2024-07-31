# NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, TX1, TX2, Nano and Nano 2GB (Bulletin ID: 5147)



 NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, TX1, TX2, Nano and Nano 2GB - January 2021
================================================================================================================




 Updated 10/05/2021 01:44 PM



NVIDIA has released a software update for Jetson AGX Xavier™, Jetson Xavier NX, Jetson™ TX1, Jetson TX2, Jetson Nano™, and Jetson Nano 2GB in the NVIDIA® JetPack™ software development kit (SDK) 4.5. The update addresses security issues that may lead to denial of service, data loss, and information disclosure. To protect your system, download and install the latest NVIDIA JetPack SDK from [NVIDIA DevZone](https://developer.nvidia.com/embedded/downloads).
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Go to [NVIDIA Product Security.](https://www.nvidia.com/security/)
------------------------------------------------------------------

 



---




### Details


This section provides a summary of potential vulnerabilities and their impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/v3.1/user-guide) standards.




This section provides a summary of potential vulnerabilities and their impact that this security update addresses. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/v3.1/user-guide) standards.
| \*\*CVE IDs\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2021‑1070 | NVIDIA L4T contains a vulnerability in the `apply\_binaries.sh` script used to install NVIDIA components into the root file system image, in which improper access control is applied, which may lead to an unprivileged user being able to modify system device tree files, leading to denial of service. | 7.1 | [AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:H) |
| CVE‑2021‑1069 | NVIDIA Tegra® kernel driver contains a vulnerability in `NVHost` in which the variable can be null, which may lead to a null pointer dereference and unexpected reboot, leading to data loss. | 6.1 | [AV:L/AC:L/PR:N/UI:N/S:U/C:N/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:N/S:U/C:N/I:L/A:H) |
| CVE‑2021‑1071 | NVIDIA Tegra kernel contains a vulnerability in the INA3221 driver in which improper access control may lead to unauthorized users gaining access to system power usage data, which may lead to information disclosure. | 5.6 | [AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:N/A:N](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:N/A:N) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.




The following table lists the NVIDIA software products affected, versions affected, and the updated version that includes this security update.
| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Operating System\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- | --- |
| CVE‑2021‑1069 CVE‑2021‑1070 CVE‑2021‑1071 | Jetson TX1, TX2 series,Jetson AGX Xavier series, Jetson Xavier NX, Jetson Nano, and Jetson Nano 2GB | Linux for Tegra (L4T) | All versions prior to L4T release r32.5 | L4T release r32.5 |


**Notes:**


* Earlier software branch releases that support this product are also affected. If you are using an earlier branch release, upgrade to the latest branch release.


### Mitigations


See [Security Updates](#security-updates) for the version to install.


### Acknowledgements


NVIDIA thanks following individuals for reporting the issues:


* CVE-2020-1069: Billy Laws
* CVE‑2021‑1070: Michael de Gans


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
| 1.0 | January 25, 2021 | Initial release |


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


* [ NVIDIA GeForce NOW - September 2020](/app/answers/detail/a_id/5052/related/1)
* [ NVIDIA Jetson AGX Xavier, TX1, TX2, and Nano L4T - July 2020](/app/answers/detail/a_id/5039/related/1)
* [ NVIDIA GPU Display Driver - September 2020](/app/answers/detail/a_id/5075/related/1)
* [ NVIDIA GeForce Experience - October 2020](/app/answers/detail/a_id/5076/related/1)
* [Security Notice: NVIDIA Response to Cisco Talos Report - July 2020](/app/answers/detail/a_id/5044/related/1)








