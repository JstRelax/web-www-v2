---
title: DIVD's work is of great importance, here is why
intro: |-
  Working for DIVD, we aim to make the digital world safer by reporting vulnerabilities we find in digital systems to the people who can mitigate them.

  But what are exactly are (zero-day) vulnerabilities, and why is it so important to find them as soon as possible? Find these (and other) frequently used cyber security definitions on this page.
leftblock:
  content: |-
    ## **Security Vulnerability**

    According to [NIST](https://csrc.nist.gov/glossary/term/vulnerability#:~:text=Definitions%3A,triggered%20by%20a%20threat%20source.) (National Institute of Standards and Technology), a vulnerability is a “w*eakness in an information system, system security procedures, internal controls, or implementation that could be exploited or triggered by a threat source.*”

    Essentially, a security vulnerability is a weakness or flaw in a computer system, network, or software that can be exploited by cybercriminals to gain unauthorized access to systems and/or cause damage. Common examples of vulnerabilities are misconfigurations, unpatched software or firmware, the use of weak or default passwords, and the use of old protocols and standards.

    When cybercriminals discover a vulnerability on a system,  they will try to create a way to *exploit* it, to achieve actions on objectives. An *exploit* is basically a malicious piece of code or script that can be used to take advantage of a system's vulnerability.

    When cybercriminals are able to exploit a vulnerability in a system to gain access to critical systems, they can potentially view, modify, delete and/or extract sensitive data. As soon as an intruder gets in, secrets are no longer secret. If an organisation doesn't find and mitigate vulnerabilities in time, the consequences can be severe, ranging from financial losses to irreparable damage to the organisation's reputation.

    Cybercriminals often prefer to create exploits for big, well-known issues because they can use those exploits to create powerful, cheap attacks that work for many years and on many systems.
  image: ""
  Alt tag for image: ""
  learnmore: /
  alt: null
rightblock:
  content: |-
    ## **Zero-day Vulnerability**

    A zero-day (0-day) vulnerability is a specific type of security flaw. It defines a vulnerability that is *unknown* to the software developers and the security community at the time it is discovered by hackers. Against popular belief, this does not necessarily make a zero-day vulnerability a 'critical'  or 'highly exploitable' vulnerability. It only means that there is no fix released for it yet.

    DIVD actively searches for vulnerable systems online. A discovered vulnerability is directly reported to the vendor. The vendor or partner agrees with DIVD to keep the software vulnerability a secret, so that the vulnerability can remain secret. This gives the vendor a little time to create and release a security update (a so-called 'patch' or 'hotfix') to fix the vulnerability. Thus, the vendor is aware of the issue and provides a fix.

    However, there are times when DIVD researchers uncover a vulnerability that has *never* been discovered before. For example, this could be a flaw in core components of operating systems (such as Windows, macOS, or Linux) or a vulnerability in a widely used network protocol that has previously gone unnoticed.

    Since this vulnerability is *unknown*, no one is adequately protected against it. The vendor needs to disclose information about the vulnerability to it's partners, but in doing so, they also unintentionally but unavoidably inform cybercriminals about the occurrence of a weakness in their software. This is when a race against the clock begins. Who works faster, the software vendor crafting and distributing a patch, or the cybercriminals crafting and deploying an exploit?

    🤓 *Eternal Blue is a very infamous zero-day exploit that was originally was developed by the NSA and later leaked by a hacking group. It was used in the [WannaCry ransomware attack](https://en.wikipedia.org/wiki/WannaCry_ransomware_attack), which affected hundreds of thousands of computers worldwide.*
  image: ""
  Alt tag for image: ""
  learnmore: ""
  alt: null
contenttitle: "## DIVD’s efforts are invaluable to society for several reasons"
belowwoordenboek: |-
  **Availability**\
  At DIVD, we adhere to the ‘Principle of Proportionality’ and the ‘Principle of Subsidiarity’, as described in our [Code of Conduct](https://www.divd.nl/what-we-do/code-of-conduct/). This means that our research should increase and not decrease the integrity and availability of any and all online systems. If several means are available to meet the need, we opt for the one which has the least impact on the availability of the systems and services.

  **Case**\
  When DIVD talks about a “case” we refer to a record or file created to document and manage the process of addressing a specific vulnerability. It typically includes details such as:

  - Description of the Vulnerability: Information about the nature and specifics of the vulnerability.
  - Fingerprint Creation: A unique identifier or signature for the vulnerability to help in identifying affected systems.
  - Scanning and Identification: The process of scanning systems to find instances that are vulnerable.
  - Notification: Informing the owners of the vulnerable systems about the issue so they can take corrective action.
  - This structured approach helps ensure that vulnerabilities are tracked, managed, and resolved systematically.

  **Confidentiality**\
  At DIVD, we work with sensitive data every day. Think about lists of IP addresses, types of vulnerabilities found, contact information, and metadata (e.g. timestamps, scripts, researchers working on the data). [The members of DIVD](https://www.divd.nl/who-we-are/team/) take all precautions necessary to protect the confidentiality of this data.

  **(Ethical) Hacker / White Hat Hacker**\
  DIVD members belong to the “white hat” hackers. A white hat hacker is someone who breaks into a computer system with positive intentions, without disrupting any services or processes. The motivation of a white hat hacker is to detect security vulnerabilities, without misusing or exploiting them. A white hat hacker is sometimes also referred to as an ethical hacker. Our members are skilled professionals that must always operate within legal boundaries. Please read our [Code of Conduct](https://www.divd.nl/what-we-do/code-of-conduct/) for more information. *The term ‘white hat’ comes from cowboy movies in which the hero always wore a white hat.*

  **Exploit**\
  An exploit is a malicious application, piece of code or script that can be used to take advantage of a system's vulnerability. At DIVD, we don’t use or run intrusive exploits to verify the existence of a vulnerability in a system. Destructive commands like “$ rm -rf /” or testing for denial of service are not permitted in any scenario. If several means are available to meet the need, we opt for the one which has the least impact on the availability of the systems and services.

  **Responsible disclosure**\
  In cybersecurity, responsible disclosure refers to the procedure where a security analyst, ethical hacker, or ethical hacker organisation such as DIVD notifies an organisation about a detected vulnerability in its systems or software. Notifying is done in such a way that the organisation has the opportunity to mitigate the weakness before it becomes public knowledge and possibly misused by hackers with malicious intentions. By privately notifying organisations, they can address the vulnerabilities before they are exploited by malicious hackers, thereby improving the security of their systems.

  Responsible disclosure helps protect users, maintains trust between (DIVD) researchers and organisations, and contributes to the ongoing improvement of cybersecurity practices.

  **Security.txt**\
  Security.txt is a proposed standard for websites to provide a clear and consistent way for security researchers to report security vulnerabilities. It involves placing a simple text file named security.txt in the well-known location /.well-known/ directory of a website (e.g., https://example.com/.well-known/security.txt). This file contains contact information and other details that guide researchers on how to responsibly disclose security issues to the organization. Wanna make DIVD's work easier? Put our [security.txt](https://securitytxt.org/) in the code of your website and our IP 194.5.73.0-255 on your allow list.

  **Types of vulnerabilities**\
  There are different types of vulnerabilities. Since DIVD scans IP addresses over the public internet, we mainly focus on web-based vulnerabilities. A good example of a database filled with web-based vulnerabilities is The [OWASP Top 10](https://owasp.org/www-project-top-ten/).

  **Vulnerability versus exploit**\
  A vulnerability is an issue or weakness in a system or application, whereas an exploit is an active component used to carry out an attack. The purpose of an exploit is to ‘exploit’ a vulnerability. A vulnerability itself does not cause harm by itself but creates an opportunity for an attacker to exploit it.
opener: DIVD's work is of great importance, here is why
main:
  title: More text here
---
✨ First of all, DIVD scans for both known ánd zero-day vulnerabilities. When vulnerable URLs or systems are detected, we send the owners of the website or system a notification email.

✨ Furthermore, DIVD is a CVE Numbering Authority (CNA), which means that when we identify new (previously unknown) vulnerabilities we can request the assignment of unique identifiers (CVEs).

✨ Besides all this effort, DIVD complements the work of other CSIRTs by focusing on proactive vulnerability disclosure and awareness. This approach helps in preventing cyber attacks and contributes to a safer digital world.

✨ In summary, DIVD plays a crucial role in identifying and mitigating cybersecurity threats, protecting both individuals and organizations from potential harm. By raising awareness about cybersecurity vulnerabilities and weaknesses, DIVD helps educate the public and businesses on how to protect themselves online.
