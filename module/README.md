# Honeypot

## Description

**Honeypot** is an OpenCart anti-spambot extension that prevents spambots from registering new accounts, placing requests, fake orders, etc.
Compatible with OpenCart 3.x/4.x versions and PHP >= 7.1.

### What is a honeypot?

*Honeypot* is an anti-spam technique that baits bots into filling out hidden form fields and then rejects their form submissions. Human customers cannot see the field so they don’t fill it out. However, bots will download the HTML code and attempt to fill out every field within the form. We can use this behavior to guess which submissions are from automated bots and reject them. Unlike traditional CAPTCHAs, which hinder user experience (UX) by interrupting and slowing down the customer journey, honeypot is invisible to customers and requires no action from them.

## Features

* Two-layer protection.
* Easy to install and configure (just like any other captcha) .
* Along with the standard pages, it also protects the page of gift certificates (vouchers).
* Invisible to customers.
* Spambot attempts log.
* Journal theme compatibility.
* Does not modify files due to the use of the OC Events System.

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
