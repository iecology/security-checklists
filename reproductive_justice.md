---

Title: Reproductive Justice Org Digital Security Tasks
Project: DIGITAL SECURITY CHECKLISTS FOR U.S. NON-PROFITS
Date: 2016-11-09T19:05:29.250Z
Author: Jonah Silas Sheridan
version: "0.1, DRAFT - NOT REVIEWED OR FOR PUBLIC USE"
---

## Password and Authentication Safety Tasks

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Use strong, memorable passwords for all accounts, organizational and everyday or as master passwords for password manager software**  
:rocket::wrench::fire:

*Strong passwords and memorable passwords are not the same thing. The strongest passwords are generally random, long and contain a large range of characters including a mix of symbols, numbers and both upper and lowercase letters, and do not include any dictionary words or personal information. But that makes them hard to remember*   

*See above for some of the many ways to generate strong, memorable passwords. There is an online guide to creating passwords as part of the the excellent [Security In a Box website](https://securityinabox.org/en/guide/passwords). Most password managers will also make a random password for you, as will other available software for that specific purpose.*

*[Diceware](http://world.std.com/~reinhold/diceware.html") is a fun and effective scheme for creating random passwords using everyday objects and a word list. If you trust a service's password reset process and it uses an email address that you are certain you will control in the future you can make and immediately forget a long random password for a site you seldom use or will never use again.*

**Mitigates: Brute force attacks against organizational accounts from political opponents, thieves, etc.**

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Don't use the same password for more than one site or service**  
:rocket::wrench::fire::fire:   
*Following this practice is a great way to minimize the risk of using third party technology services. If you don't reuse passwords someone learning your username and password for one service through a leak or break-in won't make it easy to access the other accounts you use. Use different passwords for each service so you aren't relying
on the provider to protect your most important secret.*

**Mitigates: Scope of breach of a single account. Best practice.**


:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Try to limit carrying written passwords. When necessary to write down passwords, secure them in locked storage when not in use, preferably inside your office**  
:rocket::wrench::fire:  
*There are rare occasions such as disaster recovery or onboarding process that written or printed passwords and phrases should be necessary. In those cases, secure the information to at least the level that you do your human resources files and other sensitive information, preferably in locked storage. Before distributing an initial password to a new volunteer or staff member, physically protect it by storing it with other sensitive information. Encourage users to immediately change that password to something strong and memorable for them. If they need a period of relying on a written copy, it should be stored someplace where it won't be lost, stolen and easily identified with their work. Try not to carry written passwords around with you in a wallet or briefcase. If you lose a written copy of a password, change that password immediately*

**Mitigates: Lost or stolen credentials impact. Limits local actors who might be motivated to steal your physical affects or physically assault staff or volunteers.**


:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Consider making single use passwords for sites you rarely use**  
:rocket::wrench::fire::fire:     
*If you need to create an account for something that you do not expect to use frequently and where you can reset the password easily by email, you may just wish to generate a very long random string of numbers, letters and symbols and not record it anywhere or remember it. Most password managers will make a random password for you, as will other available software for that specific purpose. This service will now have a password stronger than if you made one and tried to remember it.*

*The next time you need to login to that service you can hit the “forgot password link” to get a login link and repeat the process. This is a little slower , perhaps, than a stored password but the benefit is that you will never leak your password for that tool – because you don't know it! Of course you wouldn't do this with an account you use all the time or where the password reset process is difficult or uses an email address you may not always have access to - but it is useful to ease the password management load. Recognize that this reduces the security of the account using a “single use” password to the security of the associated email account (since you use that to get back into the service) so that email account's password needs to be strong and memorable and possibly needs to employ two factor authentication.*

**Mitigates: Brute force attacks against organizational accounts from political opponents, thieves, etc.**

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Separate organizational and everyday passwords**  
:rocket::rocket::rocket::wrench::wrench::fire::fire::fire:  
*Organizational passwords include any passwords that grant
administrative control of your organization's information systems or online identity. These are very powerful credentials and so should be stored separately from passwords that just get staff into their personal user accounts. You can do this by making a separate login or file in your password manager application, or by choosing a completely different manager altogether.*

*Placing organizational passwords in a KeePass or otherwise encrypted file that only a few key staff members can access will lessen the risks of adopting an online password manager for everyday passwords, but will also place a burden on those staff members. Balancing these needs should be factored in your decision.*

**Mitigates: Limits impact of a breach of an individual's accounts or computer by phishing or other attack.**

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Set minimum password lengths and enforce complexity rules on services where you can do so, and regularly monitor user password strength.**  
:rocket::rocket::rocket::rocket::wrench::wrench::wrench::wrench::fire::fire::fire:   
*On many platforms including Windows Active Directory and Google Apps you can set controls at an administrative level to ensure people use strong passwords. It takes some advance planning and staff training, as setting up these controls without being clear on the implications can
lock people out of their computers or work files . In addition, someone will need to be designated as the point person for resolving problems that arise from these controls. This step does however improve the security of all users at one time so is highly recommended.*

**Mitigates: Brute force attacks against organizational accounts from political opponents, thieves, etc.**

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Where you can, implement two factor authentication for all accounts and set auto-logout to as short a time as possible.**  
:rocket::rocket::rocket::wrench::wrench::fire::fire::fire:

*Many service providers have begun to offer login systems that rely on more that one piece of information, or factor, to identify yourself. There can be several, but usually there are just two; your password and another code you have. Often this is a code sent by text message to your phone but can also be embedded on a special type of USB device, a program that generates codes on your phone or even a piece of paper with preprinted codes. Users will have to get used to having this extra step to login to new devices, but it protects from someone who obtains either item from getting into the account. Be aware that all smartphone based factors rely on that device being charged and functional and text messaged codes rely on a cell signal (not just wifi) so operating conditions need to be examined and considered. For staff that travel out of cell signal coverage regularly backup codes or the [Google Authenticator application](https://support.google.com/accounts/answer/1066447?hl=en) can be critical while for others who often drain batteries backup text messaging options, extra phones or portable chargers may be necessary.*

**Mitigates: Locks down account, making impersonation of one of your staff members very difficult. Increases security on key accounts that grant access to sensitive data. Limits impact & possibility of phishing attacks**

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Choose a second authentication factor that matches your operating conditions. If you are often in rural areas on wifi network, you may want an option  does not depend on text messages and hence cell signal. If your mobile device is often battery drained or needs to be turned off, consider options that do not depend on a smart phone including hardware keys such as the [Yubikey]("https://yubico.com").**  
:rocket::rocket::rocket::rocket::wrench::wrench::wrench::fire::fire:

*As two factor authentication systems have been more broadly used we have seen the various risks associated with smartphone based authentication. Of biggest concern is the security and reliability of text messaging whereby a simple phone call to tech support can redirect your secret codes to a third party or where a dead battery or cell dead zone can lock you out of your accounts. In addition we find many busy organizers and leaders are routinely using up all of their battery, potentially making accounts inaccessible until the decide can be charged. Instead second factors that rely on time based codes or other advanced mathematics are preferred as they can be used offline, on multiple devices and may not even need power. Options include the [Google Authenticator application](https://support.google.com/accounts/answer/1066447?hl=en) or [Yubikey](https://yubico.com) or even [paper backup codes](https://support.google.com/accounts/answer/1187538?hl=en)*

**Mitigates: Challenges with cell phone security and availability. Protects against more committed attackers.**

##  Staff Computer Security Tasks

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Keep all web browser software, including extensions, updated to the latest version. Prefer Firefox or Chrome browsers. Only use Internet Explorer and Safari when required.**  
:rocket::wrench::fire:  
*Internet Explorer has had a much higher incidence of vulnerabilities than Chrome and Firefox while Safari has suffered some recent security concerns. Although nearly all of the latest browsers support “certificate pinning” which makes it harder to intercept secure connections, [Chrome](https://google.com/chrome) and [Firefox](https://getfirefox.com/) have led the development of this important feature.*

**Mitigates: Limits well known attacks from less skilled attackers, including opportunistic ones**

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Install the HTTPS Everywhere extension for all of the web browsers you use on your system.**  
:rocket::wrench::fire:  

*This step will help ensure that more sites you visit and information you submit to them cannot be seen by others on the wireless network or the operator of the network itself.You can install that plugin from [this page]
(https://www.eff.org/HTTPS-EVERYWHERE).*

**Mitigates: Minimizes capture of information when office network or public networks are breached**

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Install Privacy Badger, a browser add-on which will limit the “cookies” - small persistent chunks of information - set on your computer by websites**  
:rocket::wrench::fire:  

*Privacy Badger is software produced by the non-profit [Electronic Frontier Foundation](https://eff.org) to help reduce the privacy breaches and tracking that come with the use of cookies. These cookies can be transferred insecurely so can, if poorly implemented, expose login credentials or other information in transit. As an extra benefit, you will increase you privacy and lessen your online tracking as a result of using this software. Download it [here]("https://privacybadger.org.").*

**Mitigates: Limits exposure to attacker on the same network.**

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Turn on your computer's firewall and disallow all external connections**  
:rocket::rocket::wrench::wrench::fire::fire:
*A firewall prevents unauthorized connections from other computers on the wireless network. There is a built in firewall in every computer, but it is not turned on by default and may allow connections to certain services. The firewall settings can be found on Macs in System Preferences > Security. On Windows computers, the firewall settings are in the System and Security tool in Control Panel. More information about Windows Firewall can be found [here] (http://www.microsoft.com/security/pc-security/firewalls-using.aspx)*

**Mitigates: Limits exposure to attacker on the same network.**

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Turn off the built-in file sharing functionality on your computer or device**  
:rocket::wrench::fire::fire:  
*Although handy for sharing files with peers, the built-in file sharing functionality on your computer is vulnerable to abuse or accidental information leakage. It is preferable to set up alternate tools and practices for sharing files, such as a central file repository.*

*To turn off file sharing on a Mac, go to Apple menu \> System Preferences, then click Sharing and make sure all the boxes are unchecked. See [this article](https://support.microsoft.com/en-us/kb/307874) for turning off file sharing on a Windows computer.*

*Recognize that if you are currently using the built-in file sharing functionality to share files inside an office, doing this will disrupt current work practices.*

**Mitigates: Limits exposure to attacker on the same network.**

##  Office Wireless Network Safety Tasks
:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Configure your wireless networks to use a password, ideally a unique one for each person connecting, and preferably using WPA2 encryption rather than WEP or WPA encryption.**  
:rocket::wrench::fire:  

*A password on a wireless network means the information moving across it
is less easily captured and decoded by someone nearby. If everyone has a
unique password this gets even harder. WPA and WPA2 offer stronger
protection than WEP, which is now relatively easily compromised. You can
easily view what encryption is in use on most computers. In OSX, hold
down the Option key and click the wireless indicator in the top right
corner to reveal extra information about each wireless network. The
method for viewing these details is different in each version of Windows
so ask your tech support provider for assistance for the software you
use..*

**Mitigates: Limits passive attacks where just being in the vicinity of your wireless network is enough to capture and decode traffic from it.**

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Change the password to your wireless networks at least once a year.**  
:rocket::rocket::wrench::wrench::fire::fire:

*It is hard to control wireless network passwords, but anyone on the network can potentially see your traffic. By their very nature these passwords are information that is shared broadly, posted and written down. Staff, volunteers and guests come and go and take that information with them. In addition, depending on the level of encryption on your network (WEP is specifically vulnerable) traffic analysis can reveal that password. To shorten the window someone with the password has to capture traffic, we can change the password regularly.*

**Mitigates: Limits time window of exposure to someone with internal wireless access**

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**If you can, configure host isolation on your wireless access points and/or separate wireless networks just for guests.**  
:rocket::rocket::rocket::wrench::wrench::wrench::fire::fire::fire:

*You can tune a wireless network's configuration to make it harder for a bad actor to capture the information you send over it. "Host isolation" means that the access point will only let computers connect to the Internet, but not to anything else on the wireless or wired network. Note that if you have a server or printer or any other device you connect to on your network this will make it unavailable. In that case a better option is to configure your wireless access point to make two wireless networks: one for staff and internal use and one just for guests with a password that can be shared broadly.*

**Mitigates: Risks associated with unknown or untrusted users or devices on your networks.**
