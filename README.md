# XSS in Subrion 4.2.1 (/panel/configuration/general/ --> Site title)

**Software link**: Subrion CMS 4.2.1 [https://subrion.org/download/]

**@author**: Alejandro Amorín

**Description**: Cross-site scripting (XSS) vulnerability in /panel/configuration/general/ of Subrion v4.2.1 allow attackers to execute arbitrary web scripts or HTML via a crafted payload injected into 'Site title' parameter. This vulnerability is triggered when accessing to /panel/email-template/

## POC

