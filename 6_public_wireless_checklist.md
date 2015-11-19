---
document set: DIGITAL SECURITY CHECKLISTS FOR U.S. NON-PROFITS
title: Password and Authentication Safety Checklist
author: Jonah Silas Sheridan, Lisa Jervis
last modified: 11/18/2015
version: "1.0, PEER REVIEWED VERSION FOR PUBLIC USE"
---

# Public Wireless Network Safety Checklist

## Introduction
This checklist provides a number or practices that can help protect you and your staff when using publicly available wireless networks such as those in hotels, cafés and airports. Because there are so many ways that wireless networks can be compromised, this checklist is not exhaustive. You are always safest on networks you own and/or control.

**If performing work using sensitive or confidential information including that required to be protected by law (such as personal health information) you are best off avoiding the use of public networks for those tasks.**

**Key:**  
:heavy_check_mark: Record actions  
:rocket: Difficulty rating   
:wrench: Technical skill level  
:fire: Work flow disruption  

## Public Wireless Network Safety Tasks

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Keep all web browser software, including extensions, updated to the latest version. Prefer Firefox or Chrome browsers. Only use Internet Explorer and Safari when required.**  
:rocket::wrench::fire:  
*Internet Explorer has had a much higher incidence of vulnerabilities than Chrome and Firefox while Safari has suffered some recent security concerns. Although nearly all of the latest browsers support “certificate pinning” which makes it harder to intercept secure connections, [Chrome]("https://google.com/chrome") and [Firefox]("https://getfirefox.com/") have led the development of this important feature.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Install the HTTPS Everywhere extension for all of the web browsers you use on your system.**  
:rocket::wrench::fire:  

*This step will help ensure that more sites you visit and information you submit to them cannot be seen by others on the wireless network or the operator of the network itself.You can install that plugin from [this page]
("https://www.eff.org/HTTPS-EVERYWHERE").*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Install Privacy Badger, a browser add-on which will limit the “cookies” - small persistent chunks of information - set on your computer by websites**  
:rocket::wrench::fire:  

*Privacy Badger is software produced by the non-profit [Electronic Frontier Foundation] ("https://eff.org") to help reduce the privacy breaches and tracking that come with the use of cookies. These cookies can be transferred insecurely so can, if poorly implemented, expose login credentials or other information in transit. As an extra benefit, you will increase you privacy and lessen your online tracking as a result of using this software. Download it [here]("https://privacybadger.org.").*


:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Prefer wireless networks that use a password, ideally a unique one for each person connecting, and preferably using WPA or WPA2 encryption rather than WEP encryption.**  
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

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Confirm the network details before you connect.**  
:rocket::rocket::wrench::fire:  

*An attacker can setup an access point with a name similar or identical to a legitimate one, so that you connect to it instead of the network you intend. Make sure to ask the proprietor of a public network what the network name and password are, and connect to the network with that name that accepts that password. This doesn't completely guarantee that the network you are connecting to isn't hostile or compromised, but it makes the difficulty of hijacking your connection much higher.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Turn off the built-in file sharing functionality on your computer or device**  
:rocket::wrench::fire::fire:  
*Although handy for sharing files with peers, the built-in file sharing functionality on your computer is vulnerable to abuse or accidental information leakage. It is preferable to set up alternate tools and practices for sharing files, such as a central file repository.*

*To turn off file sharing on a Mac, go to Apple menu \> System Preferences, then click Sharing and make sure all the boxes are unchecked. See [this article]("https://support.microsoft.com/en-us/kb/307874") for turning off file sharing on a Windows computer.*

*Recognize that if you are currently using the built-in file sharing functionality to share files inside an office, doing this will disrupt current work practices.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Turn on your computer's firewall and disallow all external connections**  
:rocket::rocket::wrench::wrench::fire::fire: 
*A firewall prevents unauthorized connections from other computers on the wireless network. There is a built in firewall in every computer, but it is not turned on by default and may allow connections to certain services. The firewall settings can be found on Macs in System Preferences > Security. On Windows computers, the firewall settings are in the System and Security tool in Control Panel. More information about Windows Firewall can be found [here] ("http://www.microsoft.com/security/pc-security/firewalls-using.aspx")*


:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Ensure that the wireless network is not presenting false certificates**  
:rocket::rocket::rocket::rocket::wrench::wrench::wrench::fire::fire::fire:  
*Increasingly, networks are set up to monitor traffic for various reasons such as ad placement or content filtering. However, this potentially compromises all secure connections, as it allows traffic to be monitored via the same mechanism in what is called a Man-In-The-Middle (MITM) attack. The network device will replace the security certificate from the service you are connecting to with one of its own. Anyone with access to that device can see any communication between you and that service. Learning to view certificates in your web browser, or installing and learning to use a tool such as Certificate Patrol (available only for Firefox [here]("http://patrol.psyced.org/") will help you identify certificate changes but also causes many alert windows to appear.*  

*Google has created [a document]("https://support.google.com/chrome/answer/95617?hl=en")on viewing certificate information in Chrome. Mozilla has [a similar document]("https://support.mozilla.org/en-US/kb/secure-website-certificate
") for Firefox as well as some [overall instructions] ("https://support.mozilla.org/en-US/kb/how-do-i-tell-if-my-connection-is-secure") on connection security that you may wish to review.*

:heavy_check_mark:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
**Use a Virtual Private Network (VPN) to securely tunnel out of public networks**  
:rocket::rocket::rocket::rocket::wrench::wrench::wrench::wrench::fire::fire::fire:  

*A VPN creates a secure connection for your computers to use to access the office network and the Internet. This connection, or tunnel, can be used to hide all information moving from your computers to the Internet or office network from the operator or other users of the wireless network. Use of a VPN severely limits the amount of trust you have to place in the owner and operator of the network you are on and so limits your exposure to them. These factors make VPNs a very effective way to protect your self on untrusted networks.*

*A VPN is implemented via a device you own located in your office or at an offsite facility, or that a third party provides you use of for a fee. Choosing a VPN provider and setting up computers to use it are not simple tasks, and critically important – a misstep in setup or use can expose your information or bring your work to a crawl. In addition VPNs add a layer of network traffic and will slow down your Internet access so your distance to and bandwidth available from your VPN provider (or office if hosting your own) will make a difference to performance.*

*Consider if the speed tradeoff is acceptable to you before choosing to implement a VPN. If you do, the investment in implementation, setup and hassle is repaid by a solution that increases connection security across many situations.*
