# WVU Pattern Library - Footer Credits Module

Footer Credits module is a global module that is applied to the footer of all external marketing websites at WVU.  

## Installing

Use [Bower](http://bower.io/) to install this module.

```bash
$ bower install --save wvu-patterns-footer-credits
```

## Override Default Breakpoint Values

To override the default value place the new variable before the default value. Below is an example of how you can override the default breakpoint value. The override will not work if you place it after the default value.


##### Example:

```scss
$wvu-footer-breakpoint: 'min-width: 80em';
$wvu-footer-breakpoint: 'min-width: 48em' !default;
```
