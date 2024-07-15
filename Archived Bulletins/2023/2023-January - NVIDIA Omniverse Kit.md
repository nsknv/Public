# NVIDIA Omniverse Kit (Bulletin ID: 5418)



 NVIDIA Omniverse Kit - January 2023
======================================================




 Updated 01/10/2023 12:17 PM



NVIDIA has released a software update for NVIDIA Omniverse™ Kit to address a security issue that may lead to code execution, information disclosure, data tampering, and denial of service.


To protect your system, open the Omniverse Launcher and apply the appropriate update.


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [CWE™](https://cwe.mitre.org/), and base scores and vectors use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.




| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Base Score\*\* | \*\*Vector\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑42268 | Omniverse Kit contains a vulnerability in the reference applications Create, Audio2Face, Isaac Sim, View, Code, and Machinima. These applications allow executable Python code to be embedded in Universal Scene Description (USD) files to customize all aspects of a scene. If a user opens a USD file that contains embedded Python code in one of these applications, the embedded Python code automatically runs with the privileges of the user who opened the file. As a result, an unprivileged remote attacker could craft a USD file containing malicious Python code and persuade a local user to open the file, which may lead to information disclosure, data tampering, and denial of service. | 7.8 | [AV:L/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:L/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H&version=3.1) |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.


### Security Updates


The following table lists the NVIDIA software products affected, software versions affected, and the updated version that includes this security update.


The updated versions in the table disable the functionality that automatically runs embedded Python code when a USD file is opened. If you enable this functionality, open USD files only from trusted sources.




| \*\*CVE IDs Addressed\*\* | \*\*Software Product\*\* | \*\*Affected Versions\*\* | \*\*Updated Version\*\* |
| --- | --- | --- | --- |
| CVE‑2022‑42268 | Omniverse Audio2Face | All versions prior to 2022.2 | 2022.2 |
| Omniverse Create | All versions prior to 2022.3 | 2022.3 |
| NVIDIA Isaac Sim | All versions prior to 2022.2.0 | 2022.2.0 |
| Omniverse Machinima | All versions prior to 2022.3 | 2022.3 |
| Omniverse Code | All versions prior to 2022.3.0 | 2022.3.0 |
| Omniverse View | All versions prior to 2022.2.1 | 2022.2.1 |


To protect your system, update your software by following the instructions for the launcher that you are using:


* **Workstation Launcher** (all users): Click the **Library** tab and follow the instructions in [Updating an App](https://docs.omniverse.nvidia.com/prod_launcher/prod_launcher/workstation-launcher.html#updating-an-app) in the *User Guide* for **Omniverse Launcher**.
* **IT Managed Launcher**, formerly known as the Enterprise Launcher (IT administrators only): Download the updated version from the [Omniverse](https://enterprise.launcher.omniverse.nvidia.com/exchange) Enterprise portal and follow the instructions in [Install Applications](https://docs.omniverse.nvidia.com/prod_launcher/prod_launcher/it-managed-launcher.html#install-applications) in the *User Guide* for **Omniverse Launcher**.


The IT Managed Launcher is designed for air-gapped networks. NVIDIA will notify enterprise contacts by email when an update is available.


After the application is updated, any extensions that support running embedded Python code in USD files will be disabled. To enable these extensions, follow the instructions in the [Extension Manager Documentation](https://docs.omniverse.nvidia.com/prod_extensions/prod_extensions/ext_extension-manager.html).


#### Notes


* Earlier software releases that support this product also enable this functionality by default. If you are using an earlier release, upgrade to the latest release.


### Mitigations


If you cannot install the updated versions, manually disable the following extensions:


* `omni.kit.embedded_script`
* `omni.script.prim`
* `omni.graph.scriptnode`


To disable these extensions, follow the instructions and video in the [Extension Manager Documentation](https://docs.omniverse.nvidia.com/prod_extensions/prod_extensions/ext_extension-manager.html).


### Acknowledgements


CVE‑2022‑42268 - NVIDIA thanks Shashi Bhushan for reporting this issue.


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | January 10, 2023 | Initial release |


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


* [ NVIDIA Omniverse Nucleus and Omniverse Cache - April 2022](/app/answers/detail/a_id/5342/related/1)
* [ NVIDIA Omniverse Launcher - January 2022](/app/answers/detail/a_id/5318/related/1)
* [Security Notice: NVIDIA Response to OpenSSL Vulnerabilities - November 2022](/app/answers/detail/a_id/5405/related/1)
* [ NVIDIA Data Plane Development Kit (MLNX\_DPDK) - August 2022](/app/answers/detail/a_id/5389/related/1)
* [ NVIDIA GPU Display Driver - August 2022](/app/answers/detail/a_id/5383/related/1)








