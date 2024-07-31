Security Bulletin: NVIDIA Mellanox OS, ONYX, Skyway, Metro-XC3- July 2024

**Answer ID: 5559**

NVIDIA has released a firmware update for NVIDIA Mellanox OS, ONYX, Skyway, and Metro-XC3.

To protect your system, download and install this firmware update from the [<span class="underline">NVIDIA Enterprise Support Portal</span>](https://enterprise-support.nvidia.com/s/).

Go to [<span class="underline">NVIDIA Product Security</span>](https://www.nvidia.com/security/).

### Details

This section provides a summary of potential vulnerabilities that this security update addresses and their impact. Descriptions use [<span class="underline">CWE™</span>](https://cwe.mitre.org/), and base scores and vectors use [<span class="underline">CVSS v3.1</span>](https://www.first.org/cvss/specification-document) standards.

|               |                                                                                                                                                                                                                                                                                      |                                                                                                                                                                                   |                |              |                                                                                           |                                                                  |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | ------------ | ----------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| **CVE ID**    | **Description**                                                                                                                                                                                                                                                                      | **Vector**                                                                                                                                                                        | **Base Score** | **Severity** | **CWE**                                                                                   | **Impacts**                                                      |
| CVE-2024-0101 | NVIDIA Mellanox OS, ONYX, Skyway, MetroX-2 and MetroX-3 XC contain a vulnerability in ipfilter, where improper ipfilter definitions could enable an attacker to cause a failure by attacking the switch. A successful exploit of this vulnerability might lead to denial of service. | [<span class="underline">AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H</span>](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H&version=3.1) | 7.5            | High         | [<span class="underline">CWE-693</span>](https://cwe.mitre.org/data/definitions/693.html) | Denial of service                                                |
| CVE-2024-0104 | NVIDIA Mellanox OS, ONYX, Skyway, MetroX-2 and MetroX-3 XC contain a vulnerability in the LDAP AAA component, where a user can cause improper access. A successful exploit of this vulnerability might lead to information disclosure, data tampering, and escalation of privileges. | [<span class="underline">AV:N/AC:H/PR:L/UI:N/S:U/C:L/I:L/A:N</span>](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:H/PR:L/UI:N/S:U/C:L/I:L/A:N&version=3.1) | 4.2            | Medium       | [<span class="underline">CWE-284</span>](https://cwe.mitre.org/data/definitions/284.html) | Information disclosure, data tampering, escalation of privileges |

The NVIDIA risk assessment is based on an average of risk across a diverse set of installed systems and might not represent the true risk to your local installation. NVIDIA recommends evaluating the risk to your specific configuration.

### Security Updates

The following table lists the NVIDIA products affected, versions affected, and the updated version that includes this security update.

|                       |                       |                    |                                               |                     |
| --------------------- | --------------------- | ------------------ | --------------------------------------------- | ------------------- |
| **CVE IDs Addressed** | **Affected Products** | **Platform or OS** | **Affected Versions**                         | **Updated Version** |
| CVE-2024-0101         | Mellanox OS           | Mellanox OS        | All versions prior to and including 3.11.1000 | 3.11.2002           |
|                       | ONYX                  | ONYX LTS           | All versions prior to and including 3.10.4300 | 3.10.4402           |
|                       | Skyway                | Skyway             | All versions prior to and including 8.2.1000  | 8.2.2000            |
|                       |                       | Skyway LTS         | All versions prior to and including 8.1.4300  | 8.1.4400            |
|                       | MetroX-3 XC           | MetroX             | All versions prior to and including 18.2.1000 | 18.2.2000           |
|                       | MetroX-2              | MetroX             | All versions prior to and including 3.11.1000 | 3.11.2002           |
| CVE-2024-0104         | Mellanox OS           | Mellanox OS LTS    | All versions prior to and including 3.11.2100 | 3.11.2202           |
|                       | ONYX                  | ONYX LTS           | All versions prior to and including 3.10.4302 | 3.10.4402           |
|                       | Skyway                | Skyway             | All versions prior to and including 8.2.2100  | 8.2.2202            |
|                       | MetroX-3 XC           | MetroX             | All versions prior to and including 18.2.2100 | 18.2.2200           |
|                       | MetroX-2              | MetroX             | All versions prior to and including 3.11.1000 | 3.11.2002           |

### Get the Most Up to Date Product Security Information

Visit the [<span class="underline">NVIDIA Product Security</span>](https://www.nvidia.com/security) page to

  - Subscribe to security bulletin notifications

  - See the current list of NVIDIA security bulletins

  - Report a potential security issue in any NVIDIA supported product

  - Learn more about the vulnerability management process followed by the NVIDIA Product Security Incident Response Team (PSIRT)

### Revision History

|              |               |                 |
| ------------ | ------------- | --------------- |
| **Revision** | **Date**      | **Description** |
| 1.0          | 10 July, 2024 | Initial release |

### Support

If you have any questions about this security bulletin, contact [<span class="underline">NVIDIA Support</span>](https://www.nvidia.com/object/support.html).

##### **Disclaimer**

ALL NVIDIA INFORMATION, DESIGN SPECIFICATIONS, REFERENCE BOARDS, FILES, DRAWINGS, DIAGNOSTICS, LISTS, AND OTHER DOCUMENTS (TOGETHER AND SEPARATELY, “MATERIALS”) ARE BEING PROVIDED “AS IS.” NVIDIA MAKES NO WARRANTIES, EXPRESS, IMPLIED, STATUTORY, OR OTHERWISE WITH RESPECT TO THE MATERIALS, AND ALL EXPRESS OR IMPLIED CONDITIONS, REPRESENTATIONS AND WARRANTIES, INCLUDING ANY IMPLIED WARRANTY OR CONDITION OF TITLE, MERCHANTABILITY, SATISFACTORY QUALITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT, ARE HEREBY EXCLUDED TO THE MAXIMUM EXTENT PERMITTED BY LAW.

Information is believed to be accurate and reliable at the time it is furnished. However, NVIDIA Corporation assumes no responsibility for the consequences of use of such information or for any infringement of patents or other rights of third parties that may result from its use. No license is granted by implication or otherwise under any patent or patent rights of NVIDIA Corporation. Specifications mentioned in this publication are subject to change without notice. This publication supersedes and replaces all information previously supplied. NVIDIA Corporation products are not authorized for use as critical components in life support devices or systems without express written approval of NVIDIA Corporation.
