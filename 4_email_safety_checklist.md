---
document set: DIGITAL SECURITY CHECKLISTS FOR U.S. NON-PROFITS
title: Email Safety Checklist
author: Jonah Silas Sheridan, Lisa Jervis
version: "1.1, DRAFT - NOT REVIEWED FOR PUBLIC USE"
last modified: 11/28/2016
---
# Email Safety Checklist
## Introduction

This checklist provides a number of practices that can help protect you and your staff when using email to communicate. Before sending an email, ask yourself, would I put this on a postcard that might be kept forever? If the answer is no, consider using other means to communicate.

Think about the emails you receive like a shut up envelope. If you don't know who sent it or what is in the envelope, you should open it very carefully. Especially since, in the case of email, it may contain viruses or other threats to your organization.

Email is a very wide reaching communications platform that was not built with a lot of security in mind. Although the risks associated with using it for work purposes continue to be illustrated through embarrassing and damaging breaches of military, government and celebrity account privacy, we all depend on it every day to connect with people across the globe. The following checklist items can help to minimize those risks. 

**If performing work using sensitive or confidential information including that required to be protected by law (such as personal health information, employment records and credit card numbers) you are must avoid the use of regular (non-encrypted) email to communicate that information. Where email is your only communication option, you may need to implement an encryption scheme as found in the final checklist item below.**


## Key
:heavy_check_mark: Record actions  
:rocket: Difficulty rating   
:wrench: Technical skill level  
:fire: Work flow disruption  

## Email Safety Tasks

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Train your organization not to send sensitive or controversial information over email whenever possible.**  
:rocket::wrench::fire:   
*Information in these categories include but are not limited to credit card information, social security numbers, health information, organizational strategy, potentially damaging critiques or insults. Establish other practices for sharing this information such as instant messaging, secure downloads or plain old paper mail.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Use strong passwords for all email accounts; change them on a regular basis, and immediately if you have any suspicion of them being used by a third party.**  
:rocket::rocket::wrench::wrench::fire::fire:     
*Strong passwords generally are made with a mix of letters, numbers and symbols and are as long as possible. Teach everyone in your organization how to generate and store strong passwords as well as how to reset their own passwords to critical accounts. Good passwords can be made a variety of ways. One recommended method which you can complete with standard household items is called [Diceware]("http://world.std.com/\~reinhold/diceware.html). See the [Authentication and Passwords Checklist]("5_authenication_checklist.md") in this document set for more recommendations in this area.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Learn to recognize suspicious behavior in your email account.**  
:rocket::wrench::fire:  
*Generally anything in your email unexpected should be looked at with suspicion. Be wary of any messages that ask you to do something, including clicking a link, opening an attachment or emailing back information. Be aware that it can be easy to fake email “From” addresses so notice any emails that don't match the usual style of the sender indicated in the “From” address. If someone has broken into your account you may see reply messages you don't understand, additional sent items, new folders or filters being created or other settings changes. Suspicious emails or account behavior should be reported to a technical support person and you should preemptively change your password.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Always login to email over a private connection**   :rocket::rocket::rocket::wrench::wrench::fire:

*This means using an address that starts with https:// for webmail, and turning on mandatory SSL or TLS encryption in the settings of your email client. For GMail, connecting using a recent version of the Chrome or Firefox browser will ensure you have such a secure connection*

*This practice will help ensure that someone operating on a network between you and your email server cannot read or alter your email in transit. Note that if your email is sent to someone outside of your organization you cannot control the connections between your email server and the recipients' servers nor how the recipients access the message so it is still vulnerable to attack. Because you control your organization and mail server, following this practice may improve the overall security of internal email but is not justification to send sensitive information using email internally or externally.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Where you can, implement two factor authentication for email accounts.**  
:rocket::rocket::rocket::wrench::wrench::fire::fire::fire:

*Many email providers have begun to offer login systems that rely on more that one piece of information to identify yourself. There can be several, but usually there are just two; your password and another code you have. Often this is a code sent by text message to your phone but can also be embedded on a special type of USB device, a program that generates codes on your phone or even a piece of paper with preprinted codes. Users will have to get used to having this extra step to login to new devices, but it protects from someone who obtains either item from getting into the account.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Don't send email attachments unless using encryption**   :rocket::rocket::rocket::wrench::wrench::wrench::fire::fire:
*Unencrypted mail attachments are not protected from being viewed or altered between recipients, and they end to stay in email boxes where they are harder to control. Perhaps more important, regular use of attachments builds and encourages a culture of opening them automatically, which is a major source of viruses, malware and associated intrusions. A better practice is to have files on a server and send links to documents instead of the documents themselves. Ideally these links lead to locations that themselves are protected by passwords or other authentication, or are temporary and expire soon after use.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Be very careful clicking links or opening attachments in emails.**  
:rocket::rocket::wrench::wrench::wrench::fire::fire:

*Links, often innocuous looking or even hidden within emails, are a major way adversaries get rogue software inside networks. Before clicking a link or anywhere on an email, check that it points to a domain name (such as roadmapconsulting.org) that you recognize and expect (in most email programs, as on the web, hovering over a link displays the URL it points to). If not, check with the sender to make sure you aren't being scammed. Similarly, don't open an attachment unless you are expecting it and the filename is in line with that expectation.* **NEVER** *open links for files from unknown senders or in otherwise suspicious emails.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Don't send mass email from standard accounts; instead, use a third
party service and if possible a dedicated mass email subdomain.**
:rocket::rocket::rocket::wrench::wrench::wrench::fire::fire:
*Sending bulk email from regular email accounts can lead to all sorts of problems for mail delivery primarily by having your ip addresses, accounts or domain name marked, filtered or blocked as a source of spam. You may also wish to send bulk email using a separate domain name from your main email (such as list.roadmapconsulting.org) to further differentiate the traffic and reduce the risk of delivery problems for your regular emails. Additionally ensuring all email lists are opt-in (people have to confirm they want to receive them) and including instructions on how to discontinue them will minimize the chance of your emails being marked as spam by recipients.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Pay for a service to filter spam and viruses from email before it reaches your inbox**
:rocket::rocket::wrench::wrench::wrench::fire:

*This service comes included if you use [GMail]("https://google.com/mail"), [Electric Embers]("https://electricembers.coop") but doesn't with all email services. Filtering mail before it reaches your network lessens the chance of a virus or malware bearing link or attachment being clicked on. After initial setup this service will be nearly invisible to staff, but requires that someone is tasked with dealing with false positives and other email delivery problems. Be aware, however, that this item involves a significant tradeoff: filtering means that another company is viewing your email before it reaches you and so may increase risk of that information being exposed. The [Electric Embers Cooperative] ("https://electricembers.coop/") is an ethically aligned provider which offers such a service specifically for non-profits.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Where email is accessed on mobile or laptop devices, configure email clients and web browser to store as little information as possible**  
:rocket::rocket::wrench::wrench::wrench::fire::fire::fire::fire:
*Most web browsers can and should be set to clear their cache when closed. Most email clients can be configured to not store email offline and to clear caches when closed. Both can be configured not to store passwords as well. By configuring both this way, a lost laptop or phone will potentially result in far less information disclosure. Note that it may also mean that you need to enter a password every time you start the program and cannot access emails when not connected to the Internet so may have extreme operational impact to your team. This practice can be made unnecessary by the use of hard drive encryption on your devices, which will be covered in the associated [Endpoint Protection Checklist]("#") which will be added to this document set in the future.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Establish an email phishing training and education program and test staff through live testing.**  
:rocket::rocket::rocket::rocket::rocket::wrench::wrench::fire::fire::fire:  
*“Phishing” is where emails are crafted to look as legitimate as possible in order to get you to click a link or attachment. This is actually a social engineering attack more than a technical one, and so addressing the human element through education is the best way forward. Testing people by sending fake, innocuous phishing emails, is a hard task, but recommended to give people a chance to practice without bad consequences. Be careful as you can create a fear response rather than lasting motivation with this practice so try to be playful and emphasize the positives of these practices There are multiple companies that offer this training if you don't have internal capacity to provide it yourself. [Contact Information Ecology]("https://iecology.org/contact") for referrals.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Setup correct DKIM and SPF records for your email domains and subdomains**  
:rocket::rocket::rocket::rocket::wrench::wrench::wrench::wrench::fire:  
*These are highly technical steps made in conjunction with your email and Domain Name Service providers to minimize the ability of spammers or phishers to fake emails from your organization. “Hard fail” settings are preferred for SPF records wherever possible. Once set up, this should have minimal impact on day to day operations, though it make changing your email provider or infrastructure more complex. Find more information at [the official DKIM website]("http://dkim.org/") and [the official SPF website] ("http://www.openspf.org/").*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Use PGP or S/MIME encryption to secure your email “end to end”**  
:rocket::rocket::rocket::rocket::wrench::wrench::wrench::wrench::fire::fire::fire::fire:  
*This is a highly technical and labor-intensive initiative to undertake, but probably the most complete way to minimize any inadvertent disclosure of data through email. It will likely require significant changes to staff practices. The most common tools for using PGP encryption with email are the [Mozilla Thunderbird]("https://www.mozilla.org/en-US/thunderbird/") email client and the associated [Enigmail plugin]("https://www.enigmail.net/home/index.php"). You can find [a guide for that setup] at ("https://securityinabox.org/en/guide/thunderbird/windows") OSX's Mail program and open source add on [GPGTools] ("https://gpgtools.org") is also a workable tool set for using PGP encrypted email on Macs. Microsoft Outlook works best with a commercial add-on from [Symantec]("http://symantec.com") to use PGP encryption on Windows. For organizations with more resources, S/MIME is an alternate encryption scheme that works well with a Microsoft Exchange/Outlook environment or with GMail by installing the [Penango]("https://www.penango.com"). If interested in either of these solutions talk to your technical support provider and be prepared to invest some time and resources into planning, implementation and training.*
