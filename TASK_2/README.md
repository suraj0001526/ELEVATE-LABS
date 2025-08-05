# 📧 Phishing Email Analysis: Fake Wipro Internship Scam

## 🎯 What This Is About

This project looks into a suspicious email that claims to offer a Wipro-certified internship to students at Jain University. We checked the email carefully and used online tools to see if it's real or fake. The goal is to spot signs of phishing and understand how scammers try to trick people.

---

---

## ✉️ Email Details

- **Subject:** ATTENTION !! KINDLY REGISTER FOR WIPRO CERTIFIED TRAINING INTERNSHIP & PLACEMENT MENTORSHIP PROGRAM
- **Sender:** [gowtham@corizo.work](mailto\:gowtham@corizo.work)
- **Recipients:** BCC (no direct email listed)
- **Date Sent:** July 9, 2025
- **Sender Name:** Gowtham Y

---

##  Warning Signs Found

| What We Saw                 | Screenshot/Proof                      | Why It’s Suspicious                                           |
| --------------------------- | ------------------------------------- | ------------------------------------------------------------- |
| ✉️ **Weird sender address** | `@corizo.work`                        | Wipro would use an official Wipro email, not a random one     |
| ❌ **DMARC failed**          | See header screenshot                 | This makes it easier for attackers to fake the email          |
| ❗ **Bad DNS setup**         | MXToolbox results                     | A legit company would have proper DNS records                 |
| Strange link                | Google Form link                      | Real companies don’t collect data through public Google Forms |
|  **Rush tactics**           | “ONLY 21 SCHOLARSHIP SLOT LEFT!”      | Pressures the reader to act fast — a common scam trick        |
| Name dropping               | Mentions Wipro, AICTE, Deloitte, etc. | Tries to sound official by listing big names                  |
|  **Strange formatting**     | Caps, bold red text                   | Real professional emails don’t look like this                 |

## Tools We Used

- Gmail’s “Show Original” message feature to see hidden email info
- [MXToolbox](https://mxtoolbox.com/EmailHeaders.aspx) to check technical email settings
- Manual check by hovering over links
- Screenshots to save evidence

##  Final Thoughts

This email is **very likely a scam**. It tries to look like it's from Wipro and Jain University, but it uses a fake email address and a free Google Form link to collect information. The setup is unprofessional and fails technical security checks.

### What You Should Do:

- **Don’t click** any links or fill out the form
- **Report** the email to your university or IT team
- Forward it to **[reportphishing@apwg.org](mailto\:reportphishing@apwg.org)**
- **Mark it as phishing** in your email account

---

##  What You Learn From This

- Always check who sent the email — not just the name, but the full email address.
- Don’t trust emails that ask for personal info through Google Forms.
- Be careful with messages that sound urgent or too good to be true.
- If it mentions a big name (like Wipro), check their official website to confirm.
