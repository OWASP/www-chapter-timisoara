---

layout: col-sidebar
title: OWASP Timisoara
tags: example-tag
level: 0

region: Europe

meetup-group: OWASP-Timisoara-Chapter
country: Romania
postal-code: 

---

# Welcome

## Welcome to the OWASP Timisoara Chapter Homepage


Follow us on [Twitter.](https://twitter.com/OwaspT)
Follow us on
[Meetup.](https://www.meetup.com/OWASP-Timisoara-Chapter/)
Follow us on
[Linkedin.](https://www.linkedin.com/in/owasp-timisoara-chapter/)
Subscribe on
[YouTube.](https://www.youtube.com/channel/UCjGOJAJmtSIvuOY7PcLrm0A)

Timisoara has an evolved software development community and one of the
most important aspects that we aim to achieve is to continuously improve
the application security world.

Everyone is welcome to join our chapter meetings, members and
non-members. OWASP Timisoara Chapter meetings / events are free and
open, so please join us\!

The chapter leaders are [Catalin
Curelaru](mailto:catalin.curelaru@owasp.org) and [Daniel Ilies](mailto:d.ilies@owasp.org).

The Chapter Board Members are: Monica Iovan (Education), Ioana Piroska (
PR/Marketing), Claudiu Ivan.


Anyone who wants to get involved and help the Chapter evolve is very
welcome and please just contact us.


If you want to present at one of our meetings / events (please read the
[speaker agreement](https://www.owasp.org/index.php/Speaker_Agreement)).


In case that you have any questions about the OWASP Timisoara Chapter,
send an email to
[Catalin
Curelaru](mailto:catalin.curelaru@owasp.org).


Next event:
For details please check [Upcoming
Events.](https://www.owasp.org/index.php/Timisoara#tab=Upcoming_events)\!

<li>
Past chapter leaders
2015 - 2019 Cornel Punga
2015 - 2019 Florina Rosiu
</li>

# Upcoming events

[Please see our Meetup page for more details and to register as
attendee](https://www.meetup.com/OWASP-Timisoara-Chapter/?scroll=true)

## OWASP Timisoara \#18: 18 March 2021
The next OWASP Timisoara Chapter Meeting will be online.
> Spring sessions - Theme: Security Automation & Intelligence, Code Patters

`Schedule`
Introduction, OWASP News & Updates - Catalin Curelaru

Surface Security - Security Intelligence Automation Platform - Teofil Cojocariu (Paddy Power Betfair) 

Detect complex code patterns using semantic grep - Bence Nagy (Semgrep)

**`Time:`**` 18:30 to 20:30`

`More about the speakers and topics`

Teofil Cojocariu, Application Security Engineering Lead @ Betfair Development Romania.

I'm focused on Application Security Engineering & Penetration Testing combined with CAMS mindset (Culture, Automation, Measurement, Sharing - DevSecOps) and I reported security bugs to Google, Facebook, Uber, Bitdefender, ING Bank, Yahoo or other companies. One of the most interesting thing is that I built a platform "Surface - Security Intelligence Automation Platform" which is being used by more than 900 people in Paddy Power Betfair, Flutter and I was the Security SME for a Private Cloud based on OpenStack with environments as code.

*Surface Security - Security Intelligence Automation Platform*

Abstract: Our external attack surface is constantly growing, which gives external attackers the opportunity to continuously search for new attack vectors. In order to successfully respond to Security incidents we needed a centralized platform which aggregates all the data about our premises in a single place.

Surface Security (Security Intelligence Automation Platform) is an internally built tool which assists our internal Security teams to gain a holistic view about our externally exposed assets. More than that, it facilitates faster incident response based on the information correlated by it. Surface started as a small project in which we tried to close the gaps identified in our security controls. The platform's core is built in Django which is a Python-based open-source framework which has a fast learning curve. Besides Django, we're using technologies like Ansible (automation), Dkron (fault-tolerant jobs), Elasticsearch (Security metrics storage) and Grafana (reporting). During the whole period it gained a lot of traction in our company determining people to contribute to its success by implementing and suggesting new features. We're currently utilizing it for reporting the Security gaps to other areas of key business areas and for Security controls like: monitoring our externally exposed assets, vulnerability management, security incidents, bug bounty reports and penetration testing.

Bence Nagy, software engineer @ r2c.

Bence Nagy is a software engineer at r2c, working on Semgrep, an open-source syntax-aware code search tool. At r2c, his responsibilities tend towards building various interfaces atop the core semgrep CLI. These include CI integrations, editor extensions, and the semgrep.dev web app. He previously led a developer experience team at Kiwi.com, the Czech Republic’s top startup at the time of its acquisition in 2019. You should totally ask him for video game recommendations after the talk.`

*Detect complex code patterns using semantic grep*

Abstract: We’ll discuss a program analysis tool we’re developing called Semgrep. It's a multilingual semantic tool for writing security and correctness queries on source code (for Python, Java, Go, C, and JS) with a simple “grep-like” interface. The original author, Yoann Padioleau, worked on Semgrep’s predecessor, Coccinelle, for Linux kernel refactoring, and later developed Semgrep while at Facebook. He’s now full time with us at r2c.

Semgrep is a free open-source program analysis toolkit that finds bugs using custom analysis we’ve written and OSS code checks. Semgrep is ideal for security researchers, product security engineers, and developers who want to find complex code patterns without extensive knowledge of ASTs or advanced program analysis concepts.

For example, find subprocess calls with shell=True in Python using the query:
subprocess.open(..., shell=True)
This will even find snippets like:
import subprocess as s
s.open(f'rm {args}', shell=True)

Or find hardcoded credentials using the query:
boto3.client(..., aws_secret_access_key=”...”, aws_access_key_id=”...” )


# Past events

## OWASP Timisoara \#17: 03 December 2020
Online Event - Due to #COVID19 in #Romania, we have to make the announcement that the #17 OWASP Timisoara Chapter meetup will be ONLINE.
Winter sessions - Theme: Hackers Mindset + Web Indexing and Crawlers

`More about the speakers and topics`

Per Olsson(repolsson), Application Security Engineer at Visma.
Per has a background as a developer focusing on the security aspects of software development, he has an unhealthy obsession with passwords and understanding the human behind the hoodie.

*Hackers and the hacker mindset*
Abstract: Per will talk about what hacking actually is, how a hacker thinks compared to for example a developer and about a few different types of hackers.

Tom Hudson (TomNomNom), Security Research Tech Lead at Detectify.
Tom is from Bradford in the UK and he is a Open-source tool maker, trainer, talker, fixer, eater, not really a sheep.

*The Unsearchables - Finding Things That Google Doesn't*
Abstract: Google does a fine job of indexing the web for most purposes, but we often want to find things that "regular" people aren't so interested in. Let's take a look at some places you can look, and some techniques you can use to find things that Google doesn't index. We'll look at digging into git repository histories, Docker images, and a few other things to find secrets and other useful information.

`Schedule`
**`18:30`**` Welcome participants`

**`18:40`**` Hackers and the hacker mindset - Per Olsson (Visma)`

**`19:15`**` The Unsearchables - Finding Things That Google Doesn't - Tom Hudson (Detectify)`

**`19:50`**` Networking or Other Questions`

**`Time:`**` 18:30 to 20:00`

## OWASP Timisoara \#16: 24 September 2020

Online Event - This summer at the #16 OWASP Timisoara edition you will find out from experts what pushes the industry further.
We will explore the latest cyber trends in Bug Bounty, Responsible Disclosure Programs presented by the OWASP Timisoara Board members (Ioana Piroska & Daniel Ilies) and in Cyber threat Intelligence by Julius Nicklasson from Recorded Future.
Summer sessions - Theme: Bug Bounty, Responsible Disclosure and Cyber Threat Intelligence

`Schedule`
**`18:00`**` Welcome participants`
**`18:10`**` Working with Hackers (Bug Bounty and Responsible Disclosure Program) - Ioana Piroska (Visma) & Daniel Ilies (Visma) `
**`18:45`**` Cyber Threat Intelligence - Julius Nicklasson (Recorded Future)`
**`Time:`**` 18:00 to 19:20`

## OWASP Timisoara \#15: 11 December 2019

Powered by UnifiedPost / Address: C. Brediceanu, 10, City Business Center,Building D, 5th floor, Timisoara, Romania
Winter sessions - Theme: Honeypots, Hacking and Community Building

`Schedule`
**`18:00`**` Welcome participants`
**`18:15`**` About Honeypots - Florin Patruta `
**`18:50`**` Break`
**`18:55`**` Too good to be true - Learning path: How to become a hacker - Catalin Curelaru`
**`19:30`**` Break`
**`19:35`**` Learning Security & Community Building - Radu Ticiu`
**`20:10`**` Networking`
**`Time:`**` 18:00 to 21:00`

POWERED BY UnifiedPost

\> snacks and drinks on the house

Winter sessions - Theme: Honeypots, Hacking and Community Building

<li>

Honeypots: The internet is getting bigger and bigger and the attacks on
organisations, governments, individuals etc are increasing. It's not a
matter of if you're going to be a target, but when. At some point in
time, attackers will find a way to enter a company's network, some way
or another. They usually do it by trying multiple times, after
conducting reconnaissance activity. Knowing who accesses the company
assets, creating decoys to lure attackers and gain time to implement
defense strategies could be a deal breaker. Learn more about what
honeypots are, how they can be used and what value they can provide to a
company.

</li>

<li>

Hacking: Nowadays we can see an increase in cyber-crime or state
controlled attacks and companies are starting to become more aware for
the need of people with a hacking culture. In Learning path, how to
become a hacker you will find a few steps on how you can be a good guy
into security and help organizations secure their environments.

</li>

<li>

Security Community Building: The founder and the coordinator of
CoderDojo will present the learning steps into security, how can we get
more insights if we participate into CTFs and how we can build a
stronger security community.

</li>

## OWASP Timisoara \#14: 29th August 2019

Powered by Visma / Address: Strada Aristide Demetriade, Nr 1, UBC3
building, 10th Floor, Timisoara
Summer sessions - Theme: CyberSecurity, XSS/CSRF Attacks, Transparency

`Schedule`
**`18:00`**` Welcome participants`
**`18:15`**` Intro OWASP Timisoara - Catalin Curelaru`
**`18:20`**` CyberSecurity - Behind your front door - Adrian Daniel Bacanu`
**`18:50`**` Break`
**`19:00`**` XSS & CSRF attacks - Daniel Ilies & Claudiu Ivan`
**`19:45`**` Break`
**`19:50`**` Transparency of Episode XVI: The Empire Strikes - Catalin Curelaru`
**`20:20`**` Endnote - Plans for the future - Involvement in the Chapter - Catalin Curelaru`
**`20:30`**` Networking`
**`Time:`**` 18:00 to 21:00`

POWERED BY Visma Romania

## 20th September 2016, OWASP InfoSecTM \#13

`Speakers`

Matei-Eugen Vasile, ApTI -  Digital privacy și inamicii săi

Lucian Florin Ilca, Atos - Prezentarea și dezvoltarea vulnerabilităților la nivel de routere, switch-uri și access point-uri

## 31th May 2016, OWASP InfoSecTM \#12

`Speakers`

Daniel BORCA - engine developer, <i>Bitdefender</i> - Be aware of your bugs, if you aren’t, someone else is

## 12th April 2016, OWASP InfoSecTM \#11

<b>Title: Be aware of your bugs, if you aren’t, someone else is</b>
The first session will introduce key concepts necessary in understanding
what is going on “under the hood” of your program and how this
correlates with being a possible victim of an exploit.

We will also dissect a real life exploit to see how this is done “in the
wild” and what can we do to prevent it.

<b>Speakers</b>


Daniel BORCA - engine developer, <i>Bitdefender</i>


Alin BARBATEI - malware researcher, <i>Bitdefender</i>
## 17th February 2016, OWASP InfoSecTM \#9
## 17th February 2016, OWASP InfoSecTM \#9
## 15th december 2015, OWASP InfoSecTM \#8

Previous speakers at OWASP Timisoara
`Andreea Bozesan
`Ciprian Lucaci
`Dan Negrea
`Radu Ciorbă
`Flavius Oprițoiu

# Sponsorship

Become a supporter of OWASP or of OWASP's Timisoara Chapter and help us
to make application security more visible.
All information about becoming a member/sponsor can be found
[here.](https://www.owasp.org/index.php/Membership)
<https://www.owasp.org/index.php/Local_Chapter_Supporter> <headertabs />

## Participation

OWASP Foundation ([Overview
Slides](https://docs.google.com/a/owasp.org/presentation/d/10wi1EWFCPZwCpkB6qZaBNN8mR2XfQs8sLxcj9SCsP6c/edit?usp=sharing))
is a professional association of [global members](Membership "wikilink")
and is open to anyone interested in learning more about software
security. Local chapters are run independently and guided by the
[Chapter_Leader_Handbook](Chapter_Leader_Handbook "wikilink"). As a
[501(c)(3)](About_OWASP "wikilink") non-profit professional association
your support and sponsorship of any meeting venue and/or refreshments is
tax-deductible. Financial contributions should only be made online using
the authorized online chapter donation button. To be a <b>SPEAKER</b> at
ANY OWASP Chapter in the world simply review the [speaker
agreement](Speaker_Agreement "wikilink") and then contact the local
chapter leader with details of what OWASP PROJECT, independent research
or related software security topic you would like to present on.

## Sponsorship/Membership

![Btn_donate_SM.gif](Btn_donate_SM.gif "Btn_donate_SM.gif") to this
chapter or become a local chapter supporter. Or consider the value of
[Individual, Corporate, or Academic Supporter
membership](Membership "wikilink"). Ready to become a member?
![Join_Now_BlueIcon.JPG](Join_Now_BlueIcon.JPG
"Join_Now_BlueIcon.JPG")

\#if:| }}

## Chapter Supporters

<b>Chapter Supporters</b>

[Category:OWASP Chapter](Category:OWASP_Chapter "wikilink")
[Category:](Category:{region}}} "wikilink")
