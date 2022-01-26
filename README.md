# Postfix Dovecot and MySQL configuration to support EAI from THNICF
On Jan 15, 2022, THNIC organized a free, online 3-hour workshop for system administrators/developers, students and interested persons. The workshop, delivered in Thai language, was run by Titipong Parkinsri of Thai Name Server Co., Ltd. (.th / .ไทย registry operator) and Ananwin Pongsaboripat of THNICF (Thailand Network Information Center Foundation). The Email Server with EAI Support workshop taught participants to set up an email server using Postfix, Dovecot, MySQL and Roundcube on the Ubuntu operating system and configure parameters to support EAI. There were 76 participants who actively attended the workshop.

INTRODUCTION
------------
This repository contain basic configuration on Postfix, Dovecot and MySQL following on our workshop and [THNICF Wiki](https://wiki.thnic.or.th/th/%E0%B8%84%E0%B8%B9%E0%B9%88%E0%B8%A1%E0%B8%B7%E0%B8%AD%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%9E%E0%B8%B1%E0%B8%92%E0%B8%99%E0%B8%B2_EAI_Mail_Server_%E0%B8%9A%E0%B8%99_Ubuntu_20). You can copy and apply our setting to your email server as this is a minimum configuration to make email server support [EAI (Email Address Internationalization)](https://xn--12cn4frcvb5f.xn--o3cw4h/%e0%b8%8a%e0%b8%b7%e0%b9%88%e0%b8%ad%e0%b8%ad%e0%b8%b5%e0%b9%80%e0%b8%a1%e0%b8%a5%e0%b8%a0%e0%b8%b2%e0%b8%a9%e0%b8%b2%e0%b9%84%e0%b8%97%e0%b8%a2-eai/).

Please feel free to fork or modified this repositories.


Required Software
-----------------
- Ubuntu 20.04.3 LTS
- Postfix 3.4.13
- Dovecot 2.3.7.2
- MySQL 8.0.27

LICENSE
-------
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License (**with exceptions
for skins & plugins**) as published by the Free Software Foundation,
either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see [www.gnu.org/licenses/][gpl].

This file forms part of the Roundcube Webmail Software for which the
following exception is added: Plugins and Skins which merely make
function calls to the Roundcube Webmail Software, and for that purpose
include it by reference shall not be considered modifications of
the software.

If you wish to use this file in another project or create a modified
version that will not be part of the Roundcube Webmail Software, you
may remove the exception above and use this source code under the
original version of the license.

CONTACT
-------
You're always welcome to send a message to THNIC Foundation:
info(at)thnic(dot)or(dot)th.

MORE INFORMATION
----------------
1. [THNIC foundation](https://xn--42cl2bj2hxbd2g.xn--12cfi8ixb8l.xn--o3cw4h/)

2. [รู้จัก.ไทย](https://xn--12cn4frcvb5f.xn--o3cw4h/)

3. [THNICF Wiki](https://wiki.thnic.or.th/th/%E0%B8%84%E0%B8%B9%E0%B9%88%E0%B8%A1%E0%B8%B7%E0%B8%AD%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%9E%E0%B8%B1%E0%B8%92%E0%B8%99%E0%B8%B2_EAI_Mail_Server_%E0%B8%9A%E0%B8%99_Ubuntu_20). 

4. [THNICF Youtube](https://www.youtube.com/user/thnicf)
