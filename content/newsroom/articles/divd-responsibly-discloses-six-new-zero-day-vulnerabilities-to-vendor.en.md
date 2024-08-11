---
title: DIVD responsibly discloses six new zero-day vulnerabilities to vendor
date: 2024-08-11T16:03:00+02:00
author: []
tag: news
intro: DIVD researchers have discovered and, in collaboration with the vendor, disclosed six new zero-day vulnerabilities in Enphase IQ Gateway devices.
image: /images/image (1).png
Alt tag for image: ""
case: null
faq_enabled: false
faq: null
---
**The Hague, Netherlands – Aug 11, 2024**
By Marieke Smits and Serena de Pater

## About the case

DIVD researchers have discovered and, in collaboration with the vendor, disclosed **six new zero-day vulnerabilities** in [Enphase IQ Gateway devices](https://enphase.com/cybersecurity/advisories/ensa-2024-6?_gl=1*ut63dx*_up*MQ..*_ga*MTU3MzcwMTgxMC4xNzIzMzY5ODY2*_ga_0L7F5QSJ7V*MTcyMzM2OTg2NS4xLjAuMTcyMzM2OTg2NS4wLjAuMA..). This investigation was performed by [Wietse Boonstra](https://www.divd.nl/who-we-are/team/people/wietse-boonstra/) and [Hidde Smit](https://www.divd.nl/who-we-are/team/people/hidde-smit/), both researchers of DIVD, in case [DIVD-2024-00011](https://csirt.divd.nl/DIVD-2024-00011). 

Additionally, DIVD has independently requested the assignment of CVEs (Common Vulnerabilities and Exposures). This is where DIVD's role as a Certification Authority (CA) distinguishes it from other similar organizations.

The six vulnerabilities were reported to Enphase by the DIVD team, and Enphase has addressed them in the upcoming release. DIVD is now working with Enphase to identify vulnerable and exposed Envoy IQ Gateways globally, aiming to assist with the patching process. 

## Impact 

With the six vulnerabilities combined, attackers could theoretically take control over the Enphase IQ Gateway device. A device is only vulnerable if you have your Enphase equipment exposed to an untrusted network (internet or home guest network). The manufacturer, Enphase, says it has about four million systems deployed in more than 150 countries. 

## Potential new trends influencing the energy sector

The energy sector is crucial to our daily lives, yet we're seeing a concerning rise in vulnerabilities, especially with the rapid energy transition. As new technologies like smart grids and IoT devices are integrated, the sector's exposure to risks increases. This surge in vulnerabilities likely stems from the fast-paced innovation that often outstrips security measures. Given the sector's importance, it's vital to prioritize cybersecurity to safeguard against these growing threats.

In 2022, a DIVD researcher found a GitHub repository that contained [SolarMan's Super Admin account login details](https://csirt.divd.nl/cases/DIVD-2022-00009/). These were visible to anyone who visited the page. This allowed cybercriminals to manage around 1 million solar panel inverters, which thankfully did not happen due to responsible disclosure. 

> *“At DIVD, we sincerely hope that preventive actions are taken to address vulnerabilities and weaknesses before any disaster occurs. We already found multiple vulnerabilities at charge points and their backends, which we reported. And according to [a research on the impact of a hack on the charging infrastructure by Berenschot](https://www.agendalaadinfrastructuur.nl/ondersteuning+gemeenten/documenten+en+links/documenten+in+bibliotheek/handlerdownloadfiles.ashx?idnv=2135552) a blackout would cost us at least multiple billions of euros each day in the Netherlands”.  - [Harm van den Brink](https://www.divd.nl/who-we-are/team/people/harm-van-den-brink/) (Researcher Energy)* 

Monday, August 12, 2024, the Dutch Enterprise Agency (Rijksdienst voor Ondernemend Nederland) published a report about an investigation into vulnerabilities in Dutch Solar Power systems, performed by [Secura](https://www.secura.com/) on behalf of the Netherlands Enterprise Agency, at the request of and in collaboration with the Top Sector Energy.

Finally, on Wednesday 7 August, another report was published by Bitdefender listing vulnerabilities of solar farms in the US. 

> *“[Hypponen's law](https://blog.f-secure.com/nl/de-wet-van-hypponen-als-het-smart-het-kwetsbaar/) also seems to apply to the energy transition: If it is "smart" it is vulnerable. So far, every solar power or charging station system that was investigated by DIVD contains some kind of serious vulnerability. DIVD is actively seeking publicity with these cases because in addition to a technical problem, a public concern is now emerging.“* *-[ Frank Breedijk](https://www.divd.nl/who-we-are/team/people/frank-breedijk/) (CSIRT Manager).* 

## **Additional sources & links:**

- [DIVD-2024-00011](https://csirt.divd.nl/DIVD-2024-00011); casefile DIVD.
- [Enphase](https://enphase.com/cybersecurity/advisories/ensa-2024-6?_gl=1*ut63dx*_up*MQ..*_ga*MTU3MzcwMTgxMC4xNzIzMzY5ODY2*_ga_0L7F5QSJ7V*MTcyMzM2OTg2NS4xLjAuMTcyMzM2OTg2NS4wLjAuMA); Informative (security advisory) from the vendor.
- [RVO rapport](https://topsectorenergie.nl/kennisbank/maatregelen-cyberveiligheid-zonpv/).
- [Bitdefender ](https://www.bitdefender.com/blog/labs/60-hurts-per-second-how-we-got-access-to-enough-solar-power-to-run-the-united-states/)report.
- [FTM](https://www.ftm.nl/artikelen/hacker-kan-stekker-uit-zonnepanelen-trekken-en-stroomnet-platleggen) article.
- EenVandaag: demonstration of the vulnerability in action, episode is released on  the 13th of August at 18:15 CET.

If you would like to contribute to DIVD’s mission, your donations are more than welcome. You can also [sign up](https://www.divd.nl/contribute/volunteers/) as a volunteer and offer your time and skills here.

Make sure to [follow](https://www.linkedin.com/company/divd-nl/?) us on LinkedIn and [X](https://x.com/DIVDnl) (formerly known as Twitter) and take notice of every important update.
