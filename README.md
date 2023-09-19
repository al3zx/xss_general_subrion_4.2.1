# XSS in Subrion 4.2.1 (/panel/configuration/general/)

**Software link**: Subrion CMS 4.2.1 [https://subrion.org/download/]

**@author**: Alejandro Amorín

**Description**: Cross-site scripting (XSS) vulnerability in /panel/configuration/general/ of Subrion v4.2.1 allow attackers to execute arbitrary web scripts or HTML via a crafted payload injected into 'Site title' parameter. This vulnerability is triggered when accessing to /panel/email-template/

## POC

1. Go to System - General and change the 'Site title' with the payload and Save
   
![xss1](https://github.com/al3zx/xss_general_subrion_4.2.1/assets/20266218/d9641e76-cf0c-4803-aad4-726f52fb995e)

2. Go to System - E-mail Templates
   
![xss2](https://github.com/al3zx/xss_general_subrion_4.2.1/assets/20266218/59ff87d5-d6f5-4cb5-8148-f2cae446427b)
