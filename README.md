# 📧 Phishing Email Investigation

## 📌 Scenario

An employee reported a suspicious email claiming to be from the company's IT department asking them to reset their password immediately.

The SOC team investigated the email to determine whether it was a phishing attack.

---

## 📩 Suspicious Email

From: [it-support@secure-company-login.com](mailto:it-support@secure-company-login.com)
To: [employee@company.com](mailto:employee@company.com)
Subject: Urgent: Reset Your Password Immediately

Message:

Dear Employee,

Your account has been flagged for unusual activity.
Please reset your password immediately using the secure link below:

http://company-secure-login-reset.com

Failure to reset your password may result in account suspension.

IT Support Team

---

## 🔎 Investigation Findings

### 1. Suspicious Sender Domain

The sender domain **secure-company-login.com** does not match the official company domain.

Legitimate domain example:
company.com

---

### 2. Suspicious Link

The email includes a link to an external website:

http://company-secure-login-reset.com

Indicators:

* Not HTTPS
* Not official domain
* Likely credential harvesting site

---

### 3. Social Engineering Tactics

The attacker uses urgency to pressure the user.

Example phrases:

* "Urgent"
* "Immediately"
* "Account suspension"

These are common phishing techniques.

---

## ⚠ Threat Assessment

Attack Type: Phishing
Risk Level: High

Potential Impact:

* Credential theft
* Unauthorized system access
* Data breach

---

## 🛠 Security Response

1. Email reported to SOC team
2. Malicious domain blocked
3. Security alert sent to employees
4. User security awareness training reinforced

---

## 🔐 Prevention Strategies

* Always verify sender domains
* Avoid clicking links in unexpected emails
* Enable Multi-Factor Authentication (MFA)
* Report suspicious emails to security team

---

## 🎯 Skills Demonstrated

* Phishing detection
* Email threat analysis
* Social engineering awareness
* Incident reporting
* Cybersecurity risk evaluation

