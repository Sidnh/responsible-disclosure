# 🔐 Responsible Disclosure Reports

This repository showcases my **responsible vulnerability disclosures** and ethical hacking demonstrations, highlighting real-world security flaws in platforms like **Quizlet** and **Skyscanner**.

---

## 📄 Disclosed Vulnerabilities

### 🧪 Quizlet – Clickjacking Vulnerability Demo

🛡️ As part of my cybersecurity skills development, I built a **Clickjacking** demonstration to showcase how attackers can trick users into taking unintended actions on trusted websites.

#### 🔎 What I Did:
- ✅ Created a malicious HTML page that frames the legitimate Quizlet website using an `<iframe>`.
- ✅ Overlaid a fake button ("🎁 Claim Your Gift!") to simulate a social engineering lure.
- ✅ Demonstrated how the vulnerability exists due to missing `X-Frame-Options` or `Content-Security-Policy` headers.
- ✅ Explained prevention techniques such as frame-busting scripts and secure HTTP response headers.

#### 💡 Key Takeaways:
- 🔒 Clickjacking can lead to unauthorized clicks and actions, seriously impacting user trust and security.
- 🔒 Web developers should enforce proper security headers to prevent such exploits.

#### 💻 Tech Stack:
- HTML  
- CSS

#### 📝 Why This Matters:
This project gave me **hands-on exposure** to a real-world web security issue and strengthened my understanding of both the **attack surface** and the **defensive measures** needed to mitigate it.

> `#CyberSecurity #EthicalHacking #WebSecurity #OWASP #Clickjacking #Infosec #BugBounty #CyberAwareness`

---

### ✈️ Skyscanner – Broken Authentication Vulnerability

🛫 I recently discovered a **critical authentication vulnerability** in the **Skyscanner** platform during a Bugcrowd private program.

#### 🔓 Issue Summary:
- The flaw allowed **full unauthorized access** to user accounts simply by knowing their email address — **no password or OTP** required.
- An attacker could:
  - Log in as any user.
  - View sensitive booking details.
  - Delete the account without re-authentication.

#### ✅ Outcome:
- Although my report was marked as a **duplicate**, the issue was **validated and confirmed**.
- I gained valuable experience in:
  - Identifying broken authentication mechanisms.
  - Performing **cross-platform testing** (Web + Mobile).
  - Understanding **session management** and identity flaws in production environments.

#### 💡 Takeaway:
> Every bug teaches something new. Even a duplicate means I’m on the right path as a bug bounty hunter.

> `#BugBounty #CyberSecurity #EthicalHacking #Bugcrowd #Skyscanner #AppSec #InfoSec #WebSecurity #MobileSecurity`

---


## 🛡️ Disclaimer

This repository is intended for **educational and ethical** purposes **only**. Unauthorized exploitation of vulnerabilities is strictly prohibited. Always follow legal and responsible disclosure guidelines.
