# 🛫 Skyscanner Authentication Bypass Vulnerability (Bugcrowd Private Program)

## 🔎 Overview

During my participation in a Bugcrowd private program, I discovered a **critical authentication vulnerability** affecting Skyscanner’s user account system.

---

## 🚨 Vulnerability Details

- **Type:** Broken Authentication  
- **Impact:** Full account takeover with only a valid email address  
- **Severity:** Critical  
- **Scope:** Web and Mobile platforms  
- **Report Status:** Marked as duplicate, but validated as real by Skyscanner Security  


---

## 🧩 Technical Summary

This flaw allowed an attacker to:
- Authenticate as any user simply by knowing their registered email
- Completely bypass password or OTP validation
- Access personal booking and travel details
- Delete accounts without re-authentication

The vulnerability stemmed from improperly validated session tokens and insufficient identity checks after user enumeration.

*Exploit details are withheld to protect user security.*

---

## 💡 Lessons Learned

Even though my report was a duplicate, this engagement taught me a lot about:
- Identifying broken authentication mechanisms  
- Testing across Web + Mobile environments  
- Understanding complex session and identity flaws in production applications  
- The importance of responsible disclosure, even if not first to report

---

## 🤝 Acknowledgements

Thanks to **Bugcrowd** for triaging and validating this issue quickly, and for a valuable learning experience.

---

## 🏷️ Tags

`#BugBounty` `#CyberSecurity` `#EthicalHacking` `#Bugcrowd` `#Skyscanner` `#AppSec` `#InfoSec` `#WebSecurity` `#MobileSecurity`

---


