
# Ressourcen

## Web Application Security

* [OWASP Top Ten 2017](https://www.owasp.org/images/7/72/OWASP_Top_10-2017_%28en%29.pdf.pdf)
* [OWASP Security Cheat Sheets - Old](https://www.owasp.org/index.php/OWASP_Cheat_Sheet_Series)
* [OWASP Security Cheat Sheets - New/GitHub](https://github.com/OWASP/CheatSheetSeries)


## Cyber Kill Chain

* https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html
* https://en.wikipedia.org/wiki/Kill_chain 

* From Lockheed Martin 
  * **RECONNAISSANCE**: Harvesting email addresses, conference information, etc.
  * **WEAPONIZATION**: Coupling exploit with backdoor into deliverable payload
  * **DELIVERY**: Delivering weaponized bundle to the victim via email, web, USB, etc.
  * **EXPLOITATION**: Exploiting a vulnerability to execute code on victim's system
  * **INSTALLATION**: Installing malware on the asset
  * **COMMAND & CONTROL (C2)**: Command channel for remote manipulation of victim
  * **ACTIONS ON OBJECTIVES**: With 'Hands on keyboard' access, intruders accomplish their goals

# Tools

## Postman
* https://www.getpostman.com/
* Proxy Settings > History

## Web Developer Toolkit
* aka **F12**
* Firefox: Edit and resend requests

## Burp Suite
* Community Edition Free
* https://portswigger.net/burp/communitydownload

## Galileo
* Web Application Audit Framework
* https://securityonline.info/galileo-web-application-audit-framework

## sqlmap-cli
* Automatic database injection and takeover tool
* http://sqlmap.org/

## ZAP
* Zed Attack Proxy
* https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project

# Juice Shop

## Some comments about the project
## Juice Shop

>The most trustworthy online shop out there. ([dschadow](https://twitter.com/dschadow/status/706781693504589824)) 

>The best juice shop on the whole internet! ([shehackspurple](https://twitter.com/shehackspurple/status/907335357775085568)) 

>Actually the most bug-free vulnerable application in existence! ([vanderaj](https://youtu.be/TXAztSpYpvE?t=26m35s))

>First you 😂😂then you 😢 ([kramse](https://twitter.com/kramse/status/1073168529405472768))

## Project
* https://twitter.com/owasp_juiceshop
* Autor Björn Kimminich (https://twitter.com/bkimminich)
* https://www.owasp.org/index.php/OWASP_Juice_Shop_Project
* GitHub https://github.com/bkimminich/juice-shop
* Online Demo https://juice-shop.herokuapp.com/#/


## Documentation
* [Juice Shop Documentation](https://bkimminich.gitbooks.io/pwning-owasp-juice-shop/content/)
* [Juice Shop Architecture](https://bkimminich.gitbooks.io/pwning-owasp-juice-shop/content/introduction/architecture.html)
* [Run Juice Shop](https://bkimminich.gitbooks.io/pwning-owasp-juice-shop/content/part1/running.html)
* [Vulnerability Categories](https://bkimminich.gitbooks.io/pwning-owasp-juice-shop/content/part1/categories.html)
* [Challenges](https://bkimminich.gitbooks.io/pwning-owasp-juice-shop/content/part1/challenges.html)
* [Rules for the Workshop](https://bkimminich.gitbooks.io/pwning-owasp-juice-shop/content/part1/rules.html)
  * Do not google for solutions before trying yourself!
  * Do not look at the Juice Shop Source Code
  * Do not look at the github repo
  * Hands off the database table **Challenges**
  * Do not look at the configuration REST endpoint
  * Score Board HTML/CSS

## Happy Path
* Login
  * Email/Password
  * Remember Me
  * Login with Google
  * Password Reset
  * Register
* Customer Feedback
  * Comments
  * Ratings
* Switch UI Language
* Product Search
* About us
  * History
  * Recent customer feedback
* Github / Redirect Service
* Products
  * Display list of products
  * Display product details
  * Rate product
* Shopping Basket
  * Add products
  * Coupon codes
  * Checkout / Order confirmation
* Recycle Products
* Track order
* Reset password
* Edit user profile
* Logout