# ☁️💰 SSRF to AWS Keys: How I Stole $15k in Cloud Credits

**Author:** [Aman Sharma](https://amannsharmaa.medium.com/)
**Category:** Web Security / SSRF  
**Published:** [Infosec Writeups](https://infosecwriteups.com/day-5-ssrf-how-i-hacked-aws-keys-stole-15-000-in-cloud-credits-ed521d7525f9)  

## 🚀 The Cloud Heist
How a simple Server-Side Request Forgery (SSRF) vulnerability led to AWS key leakage and $15,000 in compromised cloud credits.

## 🛠️ Exploitation Toolkit
- **SSRF Detection**: Found internal AWS metadata endpoint  
- **Credential Extraction**: Retrieved IAM keys via 169.254.169.254  
- **Cloud Account Takeover**: Used stolen keys to spin up expensive instances  
- **Impact Demonstration**: Quantified financial damage  

## 💡 Key Insights
- **83% of SSRF vulnerabilities** can access cloud metadata  
- **Average $8,750 value** per compromised cloud account  
- **Critical Misconfiguration**: Missing IMDSv2 enforcement  

## 📜 Full Attack Story  
[![InfosecWriteups](https://img.shields.io/badge/Read_Full_Writeup-red)](https://infosecwriteups.com/day-5-ssrf-how-i-hacked-aws-keys-stole-15-000-in-cloud-credits-ed521d7525f9)  

## ☁️ Join Our Cloud Security Squad  
[![Telegram](https://img.shields.io/badge/Telegram-Join_Cloud_Hunters-blue)](https://t.me/cybersecplayground)  

---

> 💸 **Pro Tip**: "Cloud metadata endpoints are the skeleton keys of AWS" - Senior Cloud Pentester
