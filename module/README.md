# Honeypot

## Description
The **Honeypot** is an OpenCart anti-spambot extension that prevents spambots from registering new accounts, submitting requests, and placing fake orders.

Compatible with OpenCart 2.3.x (PHP 5.6) and 3.x/4.x (PHP 7.x and above).

**Note**: The source code is encrypted for security reasons. For purchasing and licensing details, please refer to the OpenCart Marketplace link in the **Download** section below.

### What is a honeypot?
*Honeypot* is an anti-spam technique that baits bots into filling out hidden form fields and then rejects their submissions. Human users cannot see these fields, so they leave them empty. However, bots parse the HTML code and attempt to complete every available field. This behavior allows us to identify and block automated bot submissions.

Unlike traditional CAPTCHAs, which disrupt the user experience (UX) by creating friction and slowing down the customer journey, honeypot protection is invisible to users and requires no action from them.

## Features
* Easy to install and configure, just like any other captcha.
* In addition to standard pages, this also protects the gift certificate and forgotten password pages.
* Invisible to customers.
* Spambot attempts logging.
* No core file modifications (OCMOD).
* Seamless compatibility with the **Journal** theme.

## Restrictions
This module does not work and is not supported for stores using the following domain extensions: `.ru`,`.рф`,`.рус`,`.by`,`.бел`,`.su`.

## Live demo
* [Admin dashboard](https://demo.ocmod.space/a/admin/index.php?route=extension/captcha/honeypot) - module settings.
* [Storefront](https://demo.ocmod.space/a/admin/index.php?route=extension/captcha/honeypot)
* [Installation video](https://www.youtube.com/watch?v=FQ-DIdXoNWM)

## License
[End-User License Agreement](../EULA.en.txt)

## Download
[OpenCart Marketplace](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=45552)
