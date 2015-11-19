---
document set: DIGITAL SECURITY CHECKLISTS FOR U.S. NON-PROFITS
title: Introduction
author: Jonah Silas Sheridan, Lisa Jervis
last modified: 11/18/2015
version: "1.0, PEER REVIEWED VERSION FOR PUBLIC USE"
---
# Introduction

## What is this document set?

This set of documents was made to help small non-profits and NGOs improve their digital security outcomes despite limited resources and technical skill availability. The content was commissioned as part of the [Weathering The Storms]("http://www.roadmapconsulting.org/WTS") initiative of [RoadMap Consulting]("http://www.roadmapconsulting.org/WTS") and fiscally sponsored by [Common Counsel Foundation]("http://commoncounsel.org") of [Oakland, California]("https://localwiki.org/oakland/"). The content was researched and prepared by Jonah Silas Sheridan and Lisa Jervis, Principals of [Information Ecology]("https://iecology.org"), a capacity building consultancy specializing in non-profit and movement technology management, and was peer reviewed by generous members of our community. Many other eyes and hands have helped tune the recommendations to ensure technical accuracy and ease of use. We are grateful to all the members of our community that have helped bring these documents to life.

**If you have feedback or questions about this document set, its contents or how to use it, please contact Information Ecology using [our secure contact form]("https://iecology.org/contact") or PGP encrypted email to info@iecology.org using [this key]("https://iecology.org/0x3C2BACE5E10F3C7A_pub.txt")**

## About digital security

The typical technical definition of digital security says that it is the set of processes and practices used to **manage the risk**of an **adversary**exploiting **vulnerabilities** in your systems such that they may become a **threat** to the **confidentiality**, **integrity**, or **availability** of **digital assets** (e.g., file stores, cloud services, emails) or communication **channels** (e.g., instant messaging, telephone, video chats). What does that really mean? It means digital security is the work of protecting your organization's information from being accessed, changed, or blocked by anyone — internal or external, intentionally or not — who shouldn't be able to do so. Effective security strategies, digital or operational are based on the specific threats, vulnerabilities, and adversaries of your organization. This does not mean that a detailed analysis is necessary to get started improving your digital security practices. Many small U.S. organizations share a set of basic threats and vulnerabilities, which these documents are meant to help them address.

All security practices require a **strong organizational commitment**, as they dictate changes to how you and your team work together, in addition to demanding ongoing attention to ensure that software and practices are regularly updated and working properly. The more you can understand about the threats your organization faces, the better you can select and commit to practices that will be useful for protecting your organization and its operating environment.

We have identified solutions and practices across a range of levels of technical skill and organizational commitment. The effectiveness of these practices to protect from real threats is directly correlated with the level of investment you make in implementing them. With current tools, security measures are nearly always at odds with convenience. The
more you can understand what actual threats there are to your systems and specific sets of data the more directed (and therefore less impactful to operations) your security practices will be. In this way you assure that the more you put in to securing your systems, the more you will lower your risk of bad outcomes.

## Why digital security checklists?

While computers have revolutionized how non-profits work, the last
several years have begun to reveal to the general public the many risks
associated with digital communication and information storage. While all
organizations want to protect their information—and that of their
partners and allies—few have a strong understanding of the relevant
risks and most effective responses. These checklists represent
recommendations for a set of baseline digital security practices. They
have been created as a harm reduction step in response to incident
reports, current research and community feedback about the threats faced
by non-profits' computer systems.

The public-health concept of harm reduction is a useful approach to any
situation for which a perfect solution is not available. Despite being
an incomplete solution, regular hand washing is an important part of
limiting the risk of getting certain illnesses. Similarly a set of
standard best practices represented by checklists cannot mitigate all
risks, yet they can help protect you and your organization from some of
the serious threats that come with using computers to manage your
information. These checklists are meant as a starting point in
understanding and responding to the most basic threats computer users
face today. They are a necessary first step to secure our movements.
They are not sufficient for those of us working in extremely hostile
environments, for instance against highly repressive regimes and in
risky areas like conflict journalism; in no case should they be a
substitute for a more aggressive security response where warranted.

## What these checklists are not (and cannot be)

Effective security is an ongoing process. It requires consistent
practices to be undertaken by all staff, periodic review and adjustment
to practices, and strong leadership from board and senior staff. Every
organization faces a specific set of threats to its information, some of
which may be completely outside the digital realm (e.g., infiltration of
organizing meetings by a political adversary). As no set of checklists
can address all situations, these checklists do not represent a complete
solution for securing your organization.

It is also important to recognize that security and convenience are
generally at odds. Most security practices, both in the digital realm
and the “real world,” consist of trade-offs between security and
efficiency. Following the checklist recommendations will generally not
make your work smoother and easier. Instead, many will likely create
some disruption and training needs. In order to make meaningful strides
in security, your organization must be prepared to make these trade-offs
whether steep or shallow. These investments in time and attention will
repay the organization in decreased risk to critical data and systems.

## Who these checklists are for

Due to the variety of threats, vulnerabilities, and adversaries that
arise in different contexts of geopolitics and scale, the
recommendations in these checklists apply only to organizations meeting
the following criteria:

-   The organization has one or more primary locations in the United
    States each with an office network that allows staff computers to
    connect to each other, internal services and the Internet. Each
    internal network is trusted to be free from outside interference and
    is segmented from the open Internet or hosting organizations'
    networks by a firewall device.

-   The organization can successfully protect physical access to its
    office spaces and office network equipment.

-   These office networks do not host any websites or other information
    resources that are meant to accessible to all users on the public
    Internet (as opposed to resources such as printers and file servers
    that are available only to users who are connected to the office
    network).

-   The organization uses primarily Windows or Mac computers with some
    limited use of mobile devices to access its information systems.

-   Although the organization may communicate with partners abroad, its
    staff do not cross international borders while carrying the
    organization's equipment or data nor regularly work in a foreign
    country.

-   The organization is broadly seeking to protect itself from security
    threats from non-persistent general adversaries with limited
    resources (e.g., disgruntled individuals, identity thieves,
    political opponents, internal threats) rather than the U.S.
    government, other governments or other large global entities
    including multinational corporations.

If these assumptions don't apply to you, these recommendations are
inadequate; a more rigorous information security approach, in
partnership with a provider of professional security services, is
strongly recommended. [Contact RoadMap]("mailto:info@roadmapconsulting.org") for help or referrals .

## How to use these checklists

The items on these checklists are meant to be actionable and accessible;
each checklist item includes a brief explanation of what it means as
well as, where possible, next steps for implementation. The icons
accompanying each item will help you identify how difficult, disruptive
and costly a given step might be to undertake.

The first checklist deals with Digital Security Readiness. If you cannot
check off the items on that list, your organization should concentrate
first on building the capacity to address these foundational elements
before undertaking additional digital security improvements.

***Although these practices are highly recommended they do
not in and of themselves constitute a successful security practice.
Information security is an ongoing process of managing risk and no list
of procedures is an adequate replacement for a thorough review of what
information you are protecting, why and from whom paired with an
organizational commitment to shifting operations to mitigate risk.
Information Ecology, RoadMap Consulting and Common Counsel are not
liable for negative outcomes associated with following these practices.***
