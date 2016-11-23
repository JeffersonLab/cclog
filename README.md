# cclog
A Drupal module implementing Computer Center specific extensions to the 
elog module.

## Features
1.  Installer to create the initial logbook set
2.  Functions to aid migration from prior cclog.jlab.org logbooks

## Installation
Install using the normal Drupal method of module installation.
1.  Download/unpack the module in sites/all/modules
2.  Enable the module
  1. Through the web pages (admin/modules)
  2. Or using drush ( drush pm-enable cclog)

## Configuration
There is a single configuration web page (admin/config/elog/cclog) where it
is necessary to define the filesystem path where cclog-style logxml files
to be imported can be found.


