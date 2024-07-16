# Triton Inference Server (Bulletin ID: 5509)



 Triton Inference Server - December 2023
==========================================================




 Updated 12/27/2023 07:14 AM



NVIDIA has released a software update for NVIDIA Triton Inference Server to address the issue disclosed in this bulletin. This issue affects **only** nondefault deployments that enable dynamic model loading through the model control APIs by using the command line option **`--model-control explicit`**. Deployments that use default settings are **not** affected. To protect your system, install the latest release from the [Triton Inference Server Releases](https://github.com/triton-inference-server/server/releases) page on GitHub, and view the [Secure Deployment Considerations Guide](https://github.com/triton-inference-server/server/blob/main/docs/customization_guide/deploy.md).


Go to [NVIDIA Product Security](https://www.nvidia.com/security/).






---




### Details


This section provides a summary of potential vulnerabilities that this security update addresses and their impact. The description uses [CWE™](https://cwe.mitre.org/), and the base score and vector use [CVSS v3.1](https://www.first.org/cvss/specification-document) standards.





| \*\*CVE ID\*\* | \*\*Description\*\* | \*\*Vector\*\* | Base Score | Severity | CWE | Impacts |
| --- | --- | --- | --- | --- | --- | --- |
| CVE-2023-31036 | NVIDIA Triton Inference Server for Linux and Windows contains a vulnerability where, when it is launched with the non-default command line option \*\*--model-control explicit,\*\*an attacker may use the model load API to cause a relative path traversal. A successful exploit of this vulnerability may lead to code execution, denial of service, escalation of privileges, information disclosure, and data tampering. | [AV:N/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:N/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H) | 7.5 | High | [CWE-23](https://cwe.mitre.org/data/definitions/23.html) | Code execution, denial of service, escalation of privileges, information disclosure, and data tampering |



The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and may not represent the true risk to your local installation. NVIDIA recommends consulting a security or IT professional to evaluate the risk to your specific configuration.



### Security Updates


The following tables list the NVIDIA systems affected, firmware versions affected, and the updated version that includes this security update.








| \*\*CVE IDs Addressed\*\* | Affected Product(s) | Platform/OS | Affected Version(s) | Updated Version |
| --- | --- | --- | --- | --- |
| CVE-2023-31036 | Triton Inference Server | Windows, Linux | All versions prior to 2.40 | 2.40 |





### Notes




* This vulnerability affects **only** nondefault deployments that enable dynamic model loading through the model control APIs by using the command line option **`--model-control explicit`**. Deployments that use default settings are **not** affected.


The following items were made available in the development branch on November 10,2023 and are available in the release branch on December 4, 2023.


* Updated software that behaves as follows:


	+ Provides the ability to restrict the HTTP endpoint of the model load API
	+ Prevents the model load API from accessing directories outside the model directory
* A [Secure Deployment Considerations Guide](https://github.com/triton-inference-server/server/blob/main/docs/customization_guide/deploy.md)  intended to provide some key points and best practices that users deploying Triton based solutions should consider.


### Acknowledgements


NVIDIA thanks l1k3beef @ tencent-zhuquelab for reporting issue CVE-2023-31036.


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
| 1.0 | December 19, 2023 | Initial release |


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
* [ NVIDIA GeForce NOW for Android - August 2023](/app/answers/detail/a_id/5476/related/1)
* [ NVIDIA GeForce Experience - January 2023](/app/answers/detail/a_id/5384/related/1)
* [ NVIDIA Jetson AGX Xavier Series, Jetson Xavier NX, Jetson TX1, Jetson TX2 Series (including Jetson TX2 NX), and Jetson Nano (including Jetson Nano 2GB) - June 2023](/app/answers/detail/a_id/5466/related/1)
* [ NVIDIA CUDA Toolkit - March 2023](/app/answers/detail/a_id/5446/related/1)








