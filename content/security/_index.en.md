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
* Provide sufficient information to reproduce the problem, so we will be able to resolve it. Usually, the IP address or the URL of the affected system and a description of the vulnerability is sufficient. Complex vulnerabilities may require further explanation.

**Don’ts:**

* Reveal the vulnerability or problem to others until it has been resolved.
* Build your own backdoor in an information system with the intention of using it to demonstrate the vulnerability, because doing so can cause additional damage and create unnecessary security risks.
* Exploit the vulnerability further than necessary to confirm its existence.
* Copy, modify or delete data on the vulnerable system. Instead, you can create a directory listing of the system as an alternative.
* Make changes to the vulnerable system.
* Repeatedly gain access to the vulnerable system or sharing access to the vulnerable system with others.
* Use brute force attacks, attacks on physical security, utilizing social engineering, initiating distributed denial of service, disseminating spam, or use third-party applications to gain access to the vulnerable system.
* Access or attempt to access any data or information that does not belong to you.
* Destroy or corrupt, or attempt to destroy or corrupt any data or information that does not belong to you.

**What we promise:**

* We will respond to your report within three business days, providing our evaluation of the report and an expected resolution date.
* If you have followed the instructions of the Responsible Disclosure policy, we will not take any legal action against you concerning the report.
* We will not pass on your personal details to third parties without your permission, unless it is necessary to comply with a legal obligation.
* It is possible to report under a pseudonym or anonymous.
* We will keep you informed of the progress towards resolving the problem.
* In the public information concerning the reported problem, we will give your name as the discoverer of the problem (unless you desire otherwise).
* We strive to resolve all problems as quickly as possible, and we would like to play an active role in the ultimate publication on the problem after it is resolved.
* This Responsible Disclosure policy is based on an example written by Floor Terra and the Responsible Disclosure Guideline of the NCSC.

**Scope**

In Scope systems

Our following assets are explicitly in scope, if you find a vulnerability in a system you believe belongs to us but is not listed here we will review this on a case-by-case basis.

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
