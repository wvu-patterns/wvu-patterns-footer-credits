# WVU Pattern Library - Footer Credits Module
[![Build Status](https://travis-ci.org/wvu-patterns/wvu-patterns-footer-credits.svg?branch=master)](https://travis-ci.org/wvu-patterns/wvu-patterns-footer-credits)

Footer Credits module is a global module that is applied to the footer of all external marketing websites at WVU.  

Use [Bower](http://bower.io/) to install this module.

```bash
$ bower install --save wvu-patterns-footer-credits
```

### Overrideable defaults

To override the default value place the new variable before the default value. Below is an example of how you can override the default breakpoint value. The override will not work if you place it after the default value.

```scss
$wvu-footer-breakpoint: 'min-width: 48em' !default;
```

###Pattern Development

Requires:

* Ruby 1.9.3-p484
* NodeJS
* Gulp

*RVM is Preferred* but not required

####Installation

*RVM is Preferred* but not required

* `cd {install-dir}/wvu-patterns-footer-links`
* `gem install bundler`
* `bundle install`
* `npm install`

####Pattern Testing

* `gulp test` will create a build directory so you can view pattern
* `gulp ci` will run lint test to make sure .scss file is valid