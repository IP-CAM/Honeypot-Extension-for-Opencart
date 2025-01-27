# Honeypot

## Description

The **Honeypot** is an OpenCart anti-spambot extension that prevents spambots from registering new accounts, submitting requests, and placing fake orders.
Compatible with OpenCart 3.x/4.x versions and PHP >= 7.1.

### What is a honeypot?

*Honeypot* is an anti-spam technique that baits bots into filling out hidden form fields and then rejects their submissions. Human users cannot see these fields, so they leave them empty. However, bots parse the HTML code and attempt to complete every available field. This behavior allows us to identify and block automated bot submissions.

Unlike traditional CAPTCHAs, which disrupt the user experience (UX) by creating friction and slowing down the customer journey, honeypot protection is invisible to users and requires no action from them.

[![Video](https://img.youtube.com/vi/FQ-DIdXoNWM/0.jpg)](https://www.youtube.com/watch?v=FQ-DIdXoNWM)

## Features

* Two-layer protection.
* Easy to install and configure, just like any other captcha.
* In addition to standard pages, it also protects the gift certificates (vouchers) page (OC 3.x versions only).
* Invisible to customers.
* Logs spambot attempts.
* Compatible with the Journal theme.
* Does not modify files thanks to the OC Events System.

## Restrictions

This module does not work and is not supported for stores using the following domain extensions: `.ru`,`.рф`,`.рус`,`.by`,`.бел`,`.su`.

## Live demo

* [Admin](https://demo.ocmod.space/a/admin/index.php?route=extension/captcha/honeypot) - module settings.
* [Store front](https://demo.ocmod.space/a/admin/index.php?route=extension/captcha/honeypot).

## License

* [End-User License Agreement](../EULA.txt)

## Download

* **Honeypot** on [**OpenCart Marketplace**](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=45552).
* [**Honeypot**](https://www.ocmod.space/honeypot) web page.
