# WannaCry-Forensics

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Educational Purposes Only](https://img.shields.io/badge/Purpose-Educational%20Only-red.svg)](https://github.com/username/WannaCry-Forensics)
[![Forensic Sample](https://img.shields.io/badge/Type-Forensic%20Sample-orange.svg)](https://github.com/username/WannaCry-Forensics)

## ⚠️ **EDUCATIONAL PURPOSE ONLY - FORENSIC SAMPLE** ⚠️

> **DANGER**: This repository contains potentially harmful code samples intended **SOLELY** for cybersecurity education and forensic analysis in controlled environments. Misuse is illegal and unethical.

![image](https://github.com/user-attachments/assets/27fe9470-88e8-4230-afcf-5939367f8ade)


This repository contains malware samples and analysis tools related to the WannaCry ransomware for educational purposes in cybersecurity courses and controlled laboratory environments.

---

## Contents

* [About WannaCry](#about)
* [Extreme Safety Warning](#warning)
* [Educational Objectives](#objectives)
* [Safe Handling Instructions](#handling)
* [Analysis Resources](#resources)
* [Legal Disclaimer](#disclaimer)
* [License](#license)

---

<a name="about"></a>
## About WannaCry

WannaCry (also known as WannaCrypt, WannaCry0r, or WCry) was a devastating ransomware attack that spread globally in May 2017. It was one of history's largest and most damaging cyberattacks.

### Key Characteristics:

- **Exploitation Method**: Leveraged the EternalBlue exploit targeting SMBv1 vulnerability (MS17-010)
- **Origin**: EternalBlue was allegedly developed by the NSA and leaked by the Shadow Brokers hacker group
- **Encryption**: Used RSA-2048 and AES-128 encryption to lock files with .WNCRY extension
- **Distribution**: Self-propagating worm capability that spread across networks
- **Impact**: Affected over 200,000 computers across 150+ countries with damages estimated at billions of USD
- **Notable Targets**: National Health Service (UK), Telefónica (Spain), FedEx, Deutsche Bahn, and many others
- **Kill Switch**: Contained a domain check that, when registered, stopped the malware's spread

### 📊 Timeline of the Attack

| Date (2017) | Event |
|-------------|-------|
| March 14 | Microsoft releases patch for MS17-010 vulnerability |
| April 14 | EternalBlue exploit released by Shadow Brokers |
| May 12 | WannaCry ransomware attack begins |
| May 12 | Security researcher registers kill switch domain, slowing the spread |
| May 14 | "WannaDecrypt0r 2.0" variant without kill switch appears |
| May 15 | Marcus Hutchins (MalwareTech) recognized for discovering kill switch |

---

<a name="warning"></a>
## Extreme Safety Warning ⚠️

**The WannaCry.exe sample included in this repository is ACTUAL MALWARE and should be treated with extreme caution:**

- **NEVER** execute this file on any production system or personal computer
- **ALWAYS** use in isolated, air-gapped virtual environments specifically configured for malware analysis
- **ENSURE** all network connectivity is disabled before analysis
- **CREATE** snapshots of your analysis environment before beginning work
- **UNDERSTAND** that running this file outside a controlled environment may result in:
  - Permanent encryption of files
  - Lateral movement to other network-connected systems
  - Data loss
  - Privacy breaches
  - Legal liability

> ⚠️ **CRITICAL WARNING**: The actual WannaCry ransomware encrypts files and demands payment in Bitcoin. Recovery without the decryption key is extremely difficult or impossible.

---

<a name="objectives"></a>
## Educational Objectives 🎓

This repository is designed to help cybersecurity students:

1. **Understand** ransomware infection vectors and propagation methods
2. **Analyze** malware artifacts, encryption techniques, and persistence mechanisms
3. **Practice** forensic investigation techniques on compromised systems
4. **Develop** detection and prevention methodologies
5. **Study** historical cyberattack techniques in a safe environment
6. **Learn** about network security vulnerabilities and proper patching procedures

---

<a name="handling"></a>
## Safe Handling Instructions 🛡️

| Requirement | Instructions |
|-------------|--------------|
| **Environment** | Use dedicated forensic workstations or isolated virtual machines |
| **Network** | Disable all network connectivity before analysis |
| **Snapshots** | Create VM snapshots before beginning analysis |
| **Tools** | Use proper malware analysis tools (debuggers, network monitors, etc.) |
| **Storage** | Use write-blocked storage devices when applicable |
| **Documentation** | Document all findings thoroughly for educational purposes |
| **Supervision** | Always work under appropriate academic/professional supervision |
| **Protocols** | Follow your institution's security protocols |

---

<a name="resources"></a>
## Analysis Resources 📚

- [Microsoft Security Bulletin MS17-010](https://learn.microsoft.com/en-us/security-updates/securitybulletins/2017/ms17-010)
- [US-CERT Alert (TA17-132A)](https://us-cert.cisa.gov/ncas/alerts/TA17-132A)
- [Malware Traffic Analysis](https://www.malware-traffic-analysis.net/)
- [VirusTotal](https://www.virustotal.com/)
- [SANS Internet Storm Center](https://isc.sans.edu/)

---

<a name="disclaimer"></a>
## Legal Disclaimer ⚖️

This material is provided **SOLELY** for legitimate educational and research purposes within appropriate academic and professional contexts. Users are responsible for complying with all applicable laws, regulations, and institutional policies.

**The creator(s) of this repository:**
1. Assume no liability for misuse or damages resulting from use or misuse
2. Make no warranties regarding accuracy or completeness
3. Do not condone, encourage, or support malicious use
4. Provide this material exclusively for cybersecurity education

> **IMPORTANT**: Using this material for any malicious purpose, including but not limited to unauthorized system access, data encryption, or extortion is **STRICTLY PROHIBITED** and may violate local, state, national, and international laws.

---

<a name="license"></a>
## License 📜

This repository is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the [LICENSE](./LICENSE) file for details.

```
MIT License

Copyright (c) 2025 [Yaakulya/ New York Univesirty]

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

<div align="center">

**Created for educational forensic analysis only**  
The study of malware is essential for cybersecurity professionals to develop better defenses against real-world threats.

</div>
