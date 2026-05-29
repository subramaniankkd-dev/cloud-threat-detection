# cloud-threat-detection
Cloud-native threat detection rules for AWS CloudTrail, GuardDuty, and Microsoft Defender for Cloud, mapped to MITRE ATT&amp;CK Cloud Matrix.
# Cloud Threat Detection

Cloud-native threat detection rules for **AWS** and **Azure**, mapped to the **MITRE ATT&CK Cloud Matrix**. Focuses on identity abuse, API misuse, defense evasion, and persistence in cloud environments.

## About

I'm **Subramanian V**, a Senior Cyber Security Engineer with deep SIEM + cloud security background. This repo extends my detection engineering work into cloud-specific attack patterns.

- **AWS Certified Security – Specialty (SCS-C02)**
- 13+ years in cyber security, focused on detection engineering and cloud threat detection & response

## Scope

### AWS Detections
- CloudTrail-based detections (API abuse, IAM misuse, defense evasion)
- GuardDuty finding correlation and enrichment
- Security Hub integration patterns

### Azure Detections
- Microsoft Sentinel KQL analytics rules
- Defender for Cloud + Entra ID Protection patterns
- Identity-based threat detection (sign-in anomalies, token abuse)

## MITRE ATT&CK Cloud Matrix Coverage

| Tactic | Technique | ID | Detection |
|--------|-----------|-----|-----------|
| Defense Evasion | Impair Defenses: Disable Cloud Logs | T1562.008 | _Coming soon_ |
| Persistence | Account Manipulation: Additional Cloud Credentials | T1098.001 | _Coming soon_ |
| Initial Access | Valid Accounts: Cloud Accounts | T1078.004 | _Coming soon_ |
| Discovery | Cloud Service Discovery | T1526 | _Coming soon_ |

## Repository Structure
/aws/           — AWS detections (CloudTrail, GuardDuty)
/azure/         — Azure detections (Sentinel KQL, Defender)
/docs/          — Threat models, attack walkthroughs

## Contact

- **LinkedIn:** https://www.linkedin.com/in/subramanian-v-183942251/
- **Email:** subramanian.kkd@gmail.com

---

*Built alongside my [Detection Engineering Portfolio](https://github.com/subramaniankkd-dev/detection-engineering-portfolio).*
