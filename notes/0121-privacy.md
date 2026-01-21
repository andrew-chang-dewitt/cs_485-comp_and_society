---
title: "Comp & Society: privacy"
description: "Lecture notes on privacy in commputing; covering threats to privacy, us laws, surveillance, privacy tools, & more."
keywords:
  - "privacy"
  - "computers & society"
  - "lecture notes"
  - "computer science"
  - "cs 485"
  - "illinois tech"
meta:
  byline: Andrew Chang-DeWitt
  published: "2026-01-21T08:35-06:00"
---

## agenda

- privacy threats
- tech & risks
- information gathering
- us privacy laws
- mass surveillance
- privacy tools

## privacy threats

## tech & risks

w/ each new tech, comes new risk. some examples:

- databases, govt & private, of individual's personal information (w/ the
  advent of the consumer internet)

- tools that can be used for surveillance & data analysis, e.g. cameras, gps,
  cell phones

- search query data; full of information that can help identify a person or
  reveal info about them; used for ads & is for sale to 3rd parties

  some real examples:
  - 2006, Google v. US

    Govt subpoenaed Google for two months of user search queries & all web
    addresses Google indexes. Google fought in court on the basis of no
    warrant & invasion of privacy.

    Of course, this was too good to last. Google became mainstream media &
    now never says no&mdash;in fact, Google has contracts w/ the govt to
    provide access formally & covertly via simple back doors in all their
    products.

  - also 2006, AOL search query leak

    AOL had a leak that was able to link search queries w/ real
    individuals' names, despite AOL saying that wasn't possible

- smart phones
  - in one test, about half of apps sent the phone's ID number location
    to other companies, even when it has no relevance to the app's
    purpose
  - many apps copy user's contact lists to remote servers
  - a major bank's free mobile banking app inadvertently stored account
    numbers & security access codes in a hidden file on the user's
    phone
    all data is vulnerable; therefore, leaks will _always_ happen.
    so what does all this mean?

- all data is vulnerable; therefore, leaks will _always_ happen.
- anything we do online (& sometimes offline!) is being recorded
- much of the time people are unaware of the collection of their
  information
- software has high complexity
- collection of small, seemingly innocous data can actually give a high
  degree of information about a person
- re-identification of supposedly annonimized data is easy to do
- once information is online or in a database, it is always online or
  stored somewhere
- can basically assume that any data collected for one specific purpose
  will eventually be used for other purposes too
- govt sometimes requests/demands sensitive personal data
- we depend on business to manage & protect our data

## information gathering

gathering of information can lead to problems fitting one (or more) of the following general forms:

### problem: invisible data gathering

_**def:**_ collection of personal information w/out a person's
knowledge.

why does this matter? if a person is not aware of collection, they are
not able to consent.

### problem: secondary use

_**def:**_ reuse of data collected for one purpose in a different, alternative purpose.

can be done via data mining, computer matching (combining & comparing
info from diff. dbs), computer proiling (analyzing data to determine

### principles of (good) data collection

the following practices will help manage user data in an ethical, responsible way:

- informed consent
- opt-in & opt-out policies
- fair information practices
- data retention

let's look at each in detail.

#### informed consent

user must be allowed to grant (or deny) permission to collect their
data. this consent must be _informed_, i.e. the user must be told what
data they are giving & how it will be used in clear & detailed terms.
they should be allowed to grant granular permissions, withdraw suchpermissions later, & must be giving their consent freely.

#### opt-in/out policies

users should have control over how their data is used, including secondary uses. how that control is given is important. there are two opposing ways of giving permission: opt-in & opt-out.

1. opt-out: the default in the US, a user must specifically indicate
   they do _**not**_ want to give their consent. if they do not take
   some specific action, it is implied that they have given consent by
   the assumption that not opting out means the opted in.
2. opt-in: the default in the EU & other countries w/ stronger privacy
   laws, the user must grant specific permission for each use & if they
   do not it is assumed they do not consent.

#### fair information practices

- inform about PII
- collect only the required data
- offer opt-out from communications, advertising, etc.
- stronger protection of sensitive data
- keep data only as long as needed
- maintain accuracy of data
- published policies for responding to law enforcement
- protect security of data

#### data retention

most companies (esp. in the US) currently keep poor records identifying
their data, while holding the data for long (or indefinite) amounts of
time, using manual or ad-hoc processes to handle data deletion
requests, & have no regular, centralized process for disposing of data.

instead, they should have clear, easily identified data records managed
w/ up to date data retention policies & tools.

## us privacy laws

us has some constitutional right to privacy provided in the 4th
amendment & expanded in court precedent.

4th amendment requires probable cause for search & seizure & typically
requires a warrant. this is difficult when applied to new technologies
because...

- our data is often not in our home or other private location managed
  by us
- we carry much much more information than the writers of the
  constitution could have imagined on us at nearly all times; either
  immediately on our devices or stored online & accessible via our
- many laws allow govt access to this information w/out involving the courts at all; most notably:
  - the Patriot Act
- as new tech emerges, it invariably finds use to expand govt ability
  to search our homes & our persons w/ out entering or physically

### patriot act

passed as a reaction to 9/11/2001, this law greatly expanded govt
surveillance powers w/ 3 major components:

1. enhanced surveillance procedures

   expanded wiretapping & electronic surveillance w/out a warrant

2. financial regulations & anti-money laundering measures

   required fin. inst.s to report currency transactions over some
   amount, implemented anti-money laundering programs maintaining

3. border security & immigration control

   established electronic monitoring system for visa holder's entry &
   exit of US

the patriot act is easily characterized as an over-reaction enabling
govt overreach, infringing on the right to privacy & other civil

later, USA FREEDOM act, was passed in 2015 in attempt to scale back
some of those powers; most notably the end of the bulk data collection

### legal precedents

for more, read about the following cases (see course book, &sect;2.2.2; or wikipedia):

1. [Olmstead v. United States (1928)](https://en.wikipedia.org/wiki/Olmstead_v._United_States)
2. [Katz v. United States (1967)](https://en.wikipedia.org/wiki/Katz_v._United_States)
3. [Smith v. Maryland (1979)](https://en.wikipedia.org/wiki/Smith_v._Maryland)
4. [United States v. Miller (1976)](<https://en.wikipedia.org/wiki/United_States_v._Miller_(1976)>)
5. [Kyllo v. United States (2001)](https://en.wikipedia.org/wiki/Kyllo_v._United_States)
6. [United States v. Jones (2012)](https://en.wikipedia.org/wiki/United_States_v._Jones_%282012%29)

## mass surveillance

while the Patriot Act enabled massive govt surveillance in the US, it
is far from the only problem in this area.

- the proliferation of video surveillance systems, supposedly
  implemented to monitor traffic, are used to monitor & track drivers
  by law enforcement

- after 9/11/2001 D.C. police installed cameras w/ zooms capable of
  identifying people up to half a mile away

- facial recognition systems have sprung up everywhere, from simple
  systems able to be used on a smart phone or body camera, to large
  scale applications, such as the 2001 Super Bowl where Tampa police
  employees who entered the area.
  - this system searched for matches in crimminal databases, giving
    results in seconds. attendees/employees weren't given any notice or
    opportunity to consent
  - Tampa later installed a similar system in a popular nightlife
    neighborhood; in two years of use, this system never had a single
    true positive match; however, it did have multiple false positives

- cities have had varied implementations/approaches; where some have
  abandoned facial recognition & video surveillance systems because of
  the lack of apparent reduction in crime, others have only increased
  surveillance

- in Toronto, the city denied police reqest to have direct, unfettered
  access to traffic cameras during a protest because of strong Canadian
  privacy laws

- England was the first to implement large-scale, widespread cctv
  systems to deter crime; studies have shown many violations by
  operators using the systems for personal or reasons otherwise not
  intended to be allowed

## privacy tools

privacy in terms of electronic data, can be discussed in terms of
_ownership_. it is easy to conclude that privacy should include
information about oneself, such as electronic data. this then implies
that property rights (such as those provided by the 4th ammendment in
the US) should apply to personal data.

this gets complicated w/ data that involves 2+ people; how to determine
ownership & how to resolve opposing consents?

a growing area of technology is solutions intended to sovle some of the problems of privacy discussed above, e.g. cookie blockers/filters, ad blockers, spyware/malware scanners, perhaps most important of these is encryption of personal data

### encryption

_**def:**_ the process of encoding information. typ. done to obfuscate
data so that it can't be read by anyone w/out the decoding key.

perhaps the most common form is via _**public key cryptography**_,
where one key is used to encrypt messages (& is kept private) while
another is used to decrypt (& is kept public). this can be used to
securely share sensitive information only w/ intended recipients, as
well as to verify who the original encrypter is.
