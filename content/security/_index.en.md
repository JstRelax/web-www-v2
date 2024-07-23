---
title: Responsible Disclosure
---
**General**

At DIVD, the security of our systems is our top priority. Despite our best efforts, vulnerabilities may still exist in our systems. If you discover a vulnerability, please inform us so we can take action to resolve it. We appreciate your assistance in helping us protect our systems.

**Please do the following:**

Submit your findings by using the following URL: <https://app.zerocopter.com/en/rd/f9afbf32-ce59-48ed-96f2-ac4410595aa4.>

**Do’s:**

* Report the vulnerability as quickly as reasonably possible, to minimize the risk of hostile actors finding and exploiting it.
* Report in a manner that safeguards the confidentiality of the report, so that others do not gain access to the information.
* Provide enough details to reproduce the issue so that we can address it effectively. Typically, the IP address or URL of the affected system and a description of the vulnerability will suffice. However, more complex vulnerabilities might need additional explanation.

**Don’ts:**

* Do not reveal the vulnerability or weakness to others until it has been resolved.
* Do not create your own backdoor in the system to demonstrate the vulnerability, as this can cause additional damage and introduce unnecessary security risks.
* Do not exploit the vulnerability beyond what is necessary to confirm its existence.
* Do not copy, modify, or delete data on the vulnerable system. Instead, create a directory listing of the system as an alternative.
* Do not make changes to the vulnerable system.
* Do not repeatedly access the vulnerable system or share access with others.
* Do not use brute force attacks, physical security breaches, social engineering, distributed denial of service attacks, spam, or third-party applications to gain access to the vulnerable system.
* Do not access or attempt to access any data or information that does not belong to you.
* Do not destroy, corrupt, or attempt to destroy or corrupt any data or information that does not belong to you.

**What we promise:**

* We will respond to your report within three business days, providing an evaluation of the report and an estimated resolution date.
* If you have adhered to the guidelines of our Responsible Disclosure policy, we will not take any legal action against you regarding the report.
* We will not share your personal information with third parties without your consent, except when necessary to fulfill a legal obligation.
* Reporting can be done under a pseudonym or anonymously.
* We will keep you updated on the progress of resolving the issue.
* In any public information about the reported issue, we will credit you as the discoverer (unless you prefer otherwise).
* We aim to resolve all issues as quickly as possible and are eager to participate in the public disclosure of the problem once it is resolved.
* This Responsible Disclosure policy is based on an example provided by Floor Terra and the Responsible Disclosure Guideline of the NCSC.

**In-Scope Systems**

The following assets are explicitly within the scope of DIVD. If you discover a vulnerability in a system that you believe belongs to us but is not listed here, we will review it on a case-by-case basis.

* ```
  divd.nl
  ```
* ```
  divd.academy
  ```
* ```
  as50559.com
  ```
* ```
  as50559.nl
  ```
* ```
  as50559.org
  ```
* ```
  haveyoubeenpwned.nl
  ```
* ```
  divd.network
  ```
* ```
  divdfonds.nl
  ```
* ```
  divd.fund
  ```
* ```
  csirt.global
  ```
* ```
  divd.charity
  ```
* ```
  divd.club
  ```
* ```
  divd.space
  ```
* ```
  divd.community
  ```
* ```
  cyber-wear.nl
  ```
* ```
  divd.today
  ```
* ```
  divd.global
  ```
* ```
  divd.family
  ```
* ```
  divd.org
  ```
* ```
  divd.observer
  ```

**Out of Scope**

* Spam, social engineering and physical intrusion are out of scope. This includes phishing attempts.
* DoS/DDoS attacks or brute force attacks.
* Vulnerabilities that only impact non-current browsers (older than 3 versions).
* Attacks requiring the usage of shared computers, man in the middle or already compromised accounts or devices.
* Recently disclosed zero-day vulnerabilities in products where no patch or a recent patch is available.
* Attacks requiring unrealistic amounts of user interaction.
* Reports from automated scanners that involve no testing specific to this program.
* Not following industry standards.
* Missing best practices.

**Non qualifying vulnerabilities**

Reports for any vulnerabilities listed here will not be accepted.

* Self-XSS that cannot be used to exploit other users
* Verbose messages/files/directory listings without disclosing any sensitive information
* CORS misconfiguration on non-sensitive endpoints
* Missing cookie flags
* Missing security headers
* Cross-site Request Forgery with no or low impact
* Presence of autocomplete attribute on web forms
* Reverse tabnabbing
* Bypassing rate-limits or the non-existence of rate-limits
* Best practices violations (password complexity, expiration, re-use, etc.)
* Clickjacking on pages with no sensitive actions
* CSV Injection
* Host Header Injection
* Sessions not being invalidated (logout, password reset, ..)
* Session cookie is not invalidated after logout or password reset
* Older browser sessions stay active after password change
* Hyperlink injection/takeovers
* Mixed content type issues
* Cross-domain referrer leakage
* Anything related to email spoofing, SPF, DMARC or DKIM
* Content injection
* Username / email enumeration
* E-mail bombing
* HTTP Request smuggling without any proven impact
* Homograph attacks
* XMLRPC enabled
* Banner grabbing / Version disclosure
* Open ports without demonstrating a vulnerability
* Weak SSL configurations and SSL/TLS scan reports
* Not stripping metadata of images
* Disclosing API keys without proven impact
* Same-site scripting
* Subdomain takeover without taking over the subdomain
* Arbitrary file upload without proof of the existence of the uploaded file
* Known vulnerabilities in techniques used without a working Proof of Concept

What to do if you find a vulnerability at one of our suppliers or cooperation partners?

Vulnerabilities are best reported to those who can also resolve them. If you encounter any problems, we are, of course, willing to help you.
