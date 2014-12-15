# Optimise Web's MobileDetect Magento Extension

MobileDetect.net is a lightweight PHP class for detecting mobile devices. Optimise Web's Magento extension allows using Mobile Detect's functions from within Magento.

## Usage

`Mage::helper('mobiledetect')->isMobile()`

You can find all the mobile detection functions that Mobile_Detect provides on their Github project page and on their MobileDetect.net website. You just have to use `Mage::helper('mobiledetect')->` instead of `$detect->`

This extension is primarily for use by developers who wish to write PHP conditionals to detect mobile devices.

## FAQs

**1. Should I backup Magento's files and database?**

Not required. This extension doesn't touch Magento's core file system and it also doesn't interface with the database. Still, please make it a point to backup your files and database before installing or upgrading any Magento module.

**2. Do you offer support for this extension?**

This is a free extension and support will be limited. Please write to us and we'll do our best to help you out.