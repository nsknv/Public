# Triton Inference Server (Bulletin ID: 5535)



 Triton Inference Server - April 2024
=======================================================




 Updated 05/01/2024 10:31 PM



NVIDIA has released a software update for NVIDIA Triton Inference Server to address the issue disclosed in this bulletin. To protect your system, install the latest release from the [Triton Inference Server Releases](https://github.com/triton-inference-server/server/releases) page on GitHub, and view the [Secure Deployment Considerations Guide](https://github.com/triton-inference-server/server/blob/main/docs/customization_guide/deploy.md).


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. The description uses [CWE™](https://cwe.mitre.org/), and the base score and vector use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.





| CVE ID | Description | Vector | Base Score | Severity | CWE | Impacts |
| --- | --- | --- | --- | --- | --- | --- |
| CVE-2024-0087 | NVIDIA Triton Inference Server for Linux contains a vulnerability where a user can set the logging location to an arbitrary file. If this file exists, logs are appended to the file. A successful exploit of this vulnerability might lead to code execution, denial of service, escalation of privileges, information disclosure, and data tampering. | [AV:N/AC:L/PR:H/UI:N/S:C/C:H/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:H/UI:N/S:C/C:H/I:L/A:H) | 9.0 | Critical | [CWE-73](https://cwe.mitre.org/data/definitions/73.html) | Code execution, denial of service, escalation of privileges, information disclosure, data tampering |
| CVE-2024-0100 | NVIDIA Triton Inference Server for Linux contains a vulnerability in the tracing API, where a user can corrupt system files. A successful exploit of this vulnerability might lead to denial of service and data tampering. | [AV:N/AC:L/PR:H/UI:N/S:U/C:N/I:H/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:H/UI:N/S:U/C:N/I:H/A:H&version=3.1) | 6.5 | Medium | [CWE-73](https://cwe.mitre.org/data/definitions/73.html) | Denial of service, data tampering |
| CVE-2024-0088 | NVIDIA Triton Inference Server for Linux contains a vulnerability in shared memory APIs, where a user can cause an improper memory access issue by a network API. A successful exploit of this vulnerability might lead to denial of service and data tampering. | [AV:N/AC:H/PR:H/UI:N/S:U/C:L/I:L/A:H](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:H/PR:H/UI:N/S:U/C:L/I:L/A:H&version=3.1) | 5.5 | Medium | [CWE-119](https://cwe.mitre.org/data/definitions/119.html) | Denial of service, data tampering |


The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.



### Security Updates


The following tables list the NVIDIA systems affected, firmware versions affected, and the updated version that includes this security update.




| CVE IDs Addressed | Affected Products | Platform or OS | Affected Versions | Updated Version |
| --- | --- | --- | --- | --- |
| CVE-2024-0087 | NVIDIA Triton Inference Server | Linux | 22.09 to 24.03 | 24.04 |
| CVE-2024-0088 | NVIDIA Triton Inference Server | Linux | 20.10 to 24.03 | 24.04 |
| CVE-2024-0100 | NVIDIA Triton Inference Server | Linux | 22.09 to 24.03 | 24.04 |




### Notes



* Users deploying NVIDIA Triton Inference Server in production settings should follow the [Secure Deployment Considerations Guide](https://github.com/triton-inference-server/server/blob/main/docs/customization_guide/deploy.md) and ensure that logging and shared memory APIs are protected for use by authorized users.


### Acknowledgements


NVIDIA thanks the following finders for reporting these issues:


* CVE-2024‑0087: pinkdraconian, lawliet and Zhiniang Peng (@edwardzpeng) - Sangfor
* CVE-2024-0088: lawliet and Zhiniang Peng (@edwardzpeng) - Sangfor


### Get the Most Up to Date Product Security Information


Visit the [NVIDIA Product Security](https://www.nvidia.com/security) page to


* Subscribe to security bulletin notifications
* See the current list of NVIDIA security bulletins
* Report a potential security issue in any NVIDIA supported product
* Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)


### 


### Revision History








| \*\*Revision\*\* | \*\*Date\*\* | \*\*Description\*\* |
| --- | --- | --- |
| 1.0 | April 30, 2024 | Initial release |


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


* [ NVIDIA GPU Display Driver - October 2023](/app/answers/detail/a_id/5491/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) - March 2022](/app/answers/detail/a_id/5321/related/1)
* [ NVIDIA GPU Display Driver - August 2022](/app/answers/detail/a_id/5383/related/1)
* [ Jetson AGX Xavier, TK1, TX1, TX2, and Nano L4T- December 2019](/app/answers/detail/a_id/4910/related/1)
* [Security Notice: NVIDIA Response to Cisco Talos Report - July 2020](/app/answers/detail/a_id/5044/related/1)








