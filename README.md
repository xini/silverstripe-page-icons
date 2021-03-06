# Silverstripe Page Icons

[![Version](http://img.shields.io/packagist/v/innoweb/silverstripe-page-icons.svg?style=flat-square)](https://packagist.org/packages/innoweb/silverstripe-page-icons)
[![License](http://img.shields.io/packagist/l/innoweb/silverstripe-page-icons.svg?style=flat-square)](license.md)

## Overview

A simple library of SVG page type icons for enhancing your SilverStripe CMS interface. 

## Requirements

* SilverStripe CMS 4.x

## Installation

Install the module using composer:
```
composer require innoweb/silverstripe-page-icons dev-master
```

Then run dev/build.

## Configuration

You can reference the page type icons in your configuration like this:

```
Your\Namespace\ExampleLocationPage:
  icon: 'innoweb/silverstripe-page-icons: client/icons/location.svg'
```

For page types that use the Silverstripe built-in icon classes, you need to also disable the icon class:

```
SilverStripe\UserForms\Model\UserDefinedForm:
  icon: 'innoweb/silverstripe-page-icons: client/icons/form.svg'
  icon_class: false
```

The module by default replaces the icons for the default page types SiteTree/Page, ErrorPage, VirtualPage and RedirectorPage.
It also replaces the page types for the following modules:
* [Blog](https://github.com/silverstripe/silverstripe-blog)
* [Multisites](https://github.com/symbiote/silverstripe-multisites)
* [UserForms](https://github.com/silverstripe/silverstripe-userforms)

## Available icons

<img src="./client/icons/account.svg" height="24" width="24" style="vertical-align: middle;"> account

<img src="./client/icons/application.svg" height="24" width="24" style="vertical-align: middle;"> application

<img src="./client/icons/award.svg" height="24" width="24" style="vertical-align: middle;"> award

<img src="./client/icons/bacteria.svg" height="24" width="24" style="vertical-align: middle;"> bacteria

<img src="./client/icons/blog.svg" height="24" width="24" style="vertical-align: middle;"> blog

<img src="./client/icons/cart.svg" height="24" width="24" style="vertical-align: middle;"> cart

<img src="./client/icons/checkout.svg" height="24" width="24" style="vertical-align: middle;"> checkout

<img src="./client/icons/chemistry.svg" height="24" width="24" style="vertical-align: middle;"> chemistry

<img src="./client/icons/documents.svg" height="24" width="24" style="vertical-align: middle;"> documents

<img src="./client/icons/education.svg" height="24" width="24" style="vertical-align: middle;"> education

<img src="./client/icons/elemental.svg" height="24" width="24" style="vertical-align: middle;"> elemental

<img src="./client/icons/email.svg" height="24" width="24" style="vertical-align: middle;"> email

<img src="./client/icons/emails.svg" height="24" width="24" style="vertical-align: middle;"> emails

<img src="./client/icons/error.svg" height="24" width="24" style="vertical-align: middle;"> error

<img src="./client/icons/faq.svg" height="24" width="24" style="vertical-align: middle;"> faq

<img src="./client/icons/folder.svg" height="24" width="24" style="vertical-align: middle;"> folder

<img src="./client/icons/form.svg" height="24" width="24" style="vertical-align: middle;"> form

<img src="./client/icons/gallery.svg" height="24" width="24" style="vertical-align: middle;"> gallery

<img src="./client/icons/globe.svg" height="24" width="24" style="vertical-align: middle;"> globe

<img src="./client/icons/home.svg" height="24" width="24" style="vertical-align: middle;"> home

<img src="./client/icons/info.svg" height="24" width="24" style="vertical-align: middle;"> info

<img src="./client/icons/landing.svg" height="24" width="24" style="vertical-align: middle;"> landing

<img src="./client/icons/legal.svg" height="24" width="24" style="vertical-align: middle;"> legal

<img src="./client/icons/listing.svg" height="24" width="24" style="vertical-align: middle;"> listing

<img src="./client/icons/location.svg" height="24" width="24" style="vertical-align: middle;"> location

<img src="./client/icons/microscope.svg" height="24" width="24" style="vertical-align: middle;"> microscope

<img src="./client/icons/newsletter.svg" height="24" width="24" style="vertical-align: middle;"> newsletter

<img src="./client/icons/overview.svg" height="24" width="24" style="vertical-align: middle;"> overview

<img src="./client/icons/page.svg" height="24" width="24" style="vertical-align: middle;"> page

<img src="./client/icons/pages.svg" height="24" width="24" style="vertical-align: middle;"> pages

<img src="./client/icons/photo.svg" height="24" width="24" style="vertical-align: middle;"> photo

<img src="./client/icons/recipe.svg" height="24" width="24" style="vertical-align: middle;"> recipe

<img src="./client/icons/redirect.svg" height="24" width="24" style="vertical-align: middle;"> redirect

<img src="./client/icons/science.svg" height="24" width="24" style="vertical-align: middle;"> science

<img src="./client/icons/search.svg" height="24" width="24" style="vertical-align: middle;"> search

<img src="./client/icons/sitemap.svg" height="24" width="24" style="vertical-align: middle;"> sitemap

<img src="./client/icons/statistics.svg" height="24" width="24" style="vertical-align: middle;"> statistics

<img src="./client/icons/sustainability.svg" height="24" width="24" style="vertical-align: middle;"> sustainability

<img src="./client/icons/video.svg" height="24" width="24" style="vertical-align: middle;"> video

<img src="./client/icons/virtual-reality.svg" height="24" width="24" style="vertical-align: middle;"> virtual-reality

<img src="./client/icons/virtual.svg" height="24" width="24" style="vertical-align: middle;"> virtual

<img src="./client/icons/website.svg" height="24" width="24" style="vertical-align: middle;"> website

## License

BSD 3-Clause License, see [License](license.md)
