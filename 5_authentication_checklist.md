---
document set: DIGITAL SECURITY CHECKLISTS FOR U.S. NON-PROFITS
title: Password and Authentication Safety Checklist
author: Jonah Silas Sheridan, Lisa Jervis
version: "1.0, PEER REVIEWED VERSION FOR PUBLIC USE"
last modified: 11/18/2015
---

# Password and Authentication Safety Checklist

## Introduction

This checklist provides a number of practices that can help you and your staff better curate your organization's passwords and control who accesses your information. While passwords are the most common form of authentication (that is, proving your identity to a computer system), other systems are emerging that offer better protection. Some are mentioned below.

In the recommendations below, the term “organizational” is used to identify the group of accounts that grant access to your organization's online identity, backups, administrative controls and other critical systems. These tend to be used infrequently, but are very powerful. As such these passwords should be treated different from “everyday” credentials (the set of passwords that staff members need to perform their regular duties using databases, communication tools, and other platforms used for daily work).

## Key
:heavy_check_mark: Record actions  
:rocket: Difficulty rating   
:wrench: Technical skill level  
:fire: Work flow disruption  

## Password and Authentication Safety Tasks

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Use strong passwords for all accounts, organizational and everyday**  
:rocket::wrench::fire:   
*Strong passwords are generally longer that 8 characters, use a mix of symbols, numbers and both upper and lowercase letters, and do not include any dictionary words or personal information.*   

*There are many ways to generate strong passwords. There is an online guide to creating passwords as part of the the excellent [Security In a Box website]("https://securityinabox.org/en/guide/passwords"). Most password managers will also make a random password for you, as will other available software for that specific purpose.*

*[Diceware]("http://world.std.com/~reinhold/diceware.html") is a fun and effective scheme for creating random passwords using everyday objects and a word list. If you trust a service's password reset process and it uses an email address that you are certain you will control in the future you can make and immediately forget a long random password for a site you seldom use or will never use again.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Don't use the same password for more than one site or service**  
:rocket::wrench::fire::fire:   
*Following this practice is a great way to minimize the risk of using third party technology services. If you don't reuse passwords someone learning your username and password for one service through a leak or break-in won't make it easy to access the other accounts you use. Use different passwords for each service so you aren't relying
on the provider to protect your most important secret.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Try to limit written password storage**  
:rocket::wrench::fire:  
*Instead use techniques found in the Security In a Box online guide listed above to create memorable but strong passwords. If you initially need a written copy of your password, protect it physically by storing it someplace where it won't be lost, stolen and easily identified with you. Try to type your password with less looking at the copy each time, and destroy the paper copy when you have memorized the password.If you are having trouble memorizing passwords, use a password manager as indicated below.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Do not tell anyone else your password(s), ever**  
:rocket::wrench::fire:
*Even if someone claims to be from IT or technical support, do not give them your password. Nearly every system allows for administrative reset of passwords for maintenance. This creates an auditable trail that you account was accessed and alerts you as well. Although changing your password afterwards is an extra step, it will ensure that you and only you have access to your digital information and that you can know who in your organization is responsible for what changes*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Consider making single use passwords for sites you rarely use**  
:rocket::wrench::fire::fire:     
*If you need to create an account for something that you do not expect to use frequently and where you can reset the password easily by email, you may just wish to generate a very long random string of numbers, letters and symbols and not record it anywhere or remember it. Most password managers will make a random password for you, as will other available software for that specific purpose. This service will now have a password stronger than if you made one and tried to remember it.*

*The next time you need to login to that service you can hit the “forgot password link” to get a login link and repeat the process. This is a little slower , perhaps, than a stored password but the benefit is that you will never leak your password for that tool – because you don't know it! Of course you wouldn't do this with an account you use all the time or where the password reset process is difficult or uses an email address you may not always have access to - but it is useful to ease the password management load. Recognize that this reduces the security of the account using a “single use” password to the security of the associated email account (since you use that to get back into the service) so that email account's password needs to be strong and memorable.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Have all staff use password manager software**  
:rocket::rocket::wrench::wrench::fire::fire::fire:    
*There are many passwords associated with modern work flows. Because they could be used to disrupt your work in various ways passwords need to be protected. They shouldn't be stored in spreadsheets, text files or word processor documents (even password protected ones as they are simple to break open).*

*Instead password manager software is available which stores all of your passwords in a secure file and can easily take care of all of the checklist items above. You just remember a single password to open that
file up and then can have an array of unique, complex passwords for all your services.*

*KeePass and KeePassX use the same encrypted file format, can run on most any computer and so are recommended password managers. Security In a Box also has a [KeePass overview]("https://securityinabox.org/en/guide/keepass/windows")

*Web browsers are insecure environments for password storage and handling, but their central role in many organizations has made web-based tools for password management very popular. Evaluating online services and their current security claims is outside of the scope of this document. We acknowledge that online password management tools often have adequate security levels for many organizations' everyday password handling needs; however,the benefits do not outweigh the risks when storing rarely used core organizational passwords or other highly sensitive information.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Separate organizational and everyday passwords**  
:rocket::rocket::rocket::wrench::wrench::fire::fire::fire:  
*Organizational passwords include any passwords that grant
administrative control of your organization's information systems or online identity. These are very powerful credentials and so should be stored separately from passwords that just get staff into their personal user accounts. You can do this by making a separate login or file in your password manager application, or by choosing a completely different manager altogether.*

*Placing organizational passwords in a KeePass or otherwise encrypted file that only a few key staff members can access will lessen the risks of adopting an online password manager for everyday passwords, but will also place a burden on those staff members. Balancing these needs should be factored in your decision.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Set minimum password lengths and enforce complexity rules on services where you can do so, and regularly monitor user password strength.**  
:rocket::rocket::rocket::rocket::wrench::wrench::wrench::wrench::fire::fire::fire:   
*On many platforms including Windows Active Directory and Google Apps you can set controls at an administrative level to ensure people use strong passwords. It takes some advance planning and staff training, as setting up these controls without being clear on the implications can
lock people out of their computers or work files . In addition, someone will need to be designated as the point person for resolving problems that arise from these controls. This step does however improve the security of all users at one time so is highly recommended.*
