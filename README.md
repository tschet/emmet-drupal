# [Emmet](http://emmet.io) &lt;textarea&gt; plugin for Drupal 7

CONTENTS OF THIS FILE
---
 * Introduction
 * Installation
 * Configuration
 * Current Maintainers
 * Warning
 

Introduction
---
This is simple, single purpose, Drupal 7 module that embeds the 
[Emmet TextArea](https://github.com/emmetio/textarea) js library into the 
current Drupal theme for development purposes. When installed, this module 
allows Emmet code to be processed in TextArea fields on both Public and Admin 
themes.

This was developed to assist with the placement of large blocks of html within 
Drupal content and configuration pages. It uses the same 
[Emmet](http://emmet.io) js tool available with development tools like 
PHPStorm, Dreamweaver, etc.

All credit for anything Emmet related goes to the people at 
[Emmet](http://emmet.io). I am in no way associated or affiliated with 
the Emmet Project.

 * For a full description of the module, visit the sandbox page:
   https://www.drupal.org/sandbox/tschet/2563319

Installation
---
Install as you would normally install a contributed Drupal module. See: 
https://drupal.org/documentation/install/modules-themes/modules-7 
for further information.

It has one module dependency
 
 * [Libraries](https://www.drupal.org/project/libraries)

and one library dependency
 
 * [Emmet](https://github.com/emmetio/textarea/archive/master.zip). 

There is an example Drush file (emmet.make.example) in the module folder to 
assist in downloading the Emmet Library. 

Configuration
---
There is currently only one configuration setting. The output profile can be 
set to HTML, XHTML, XML, or Line. This changes the format of the output code 
to more closely match the desired format.

Current Maintainers
---
 * Douglas Tschetter (tschet) - https://www.drupal.org/u/tschet
 
Warning
---

 **This is intended for development only.**
