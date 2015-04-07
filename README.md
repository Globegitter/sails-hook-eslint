# sails-hook-eslint
[![npm version](https://badge.fury.io/js/sails-hook-eslint.svg)](https://npmjs.org/package/sails-hook-eslint) [![Dependency Status](https://img.shields.io/david/artificialio/sails-hook-eslint.svg?style=flat)](https://david-dm.org/globegitter/sails-hook-eslint)

*Needs at least Sails version 0.11.0 to work*

[Sails JS](http://sailsjs.org) hook to activate [ESLint](http://eslint.org/) for your whole sails app.

### Installation

`npm install sails-hook-eslint`

### Usage

Just lift your app as normal, and enjoy linting of your app. To see how to create a `.eslintrc` and what is possible, see: http://eslint.org/

### Configuration

By default, configuration lives in `sails.config.eslint`.  The configuration key (`eslint`) can be changed by setting `sails.config.hooks['sails-hook-eslint'].configKey`.

Parameter      | Type                | Details
-------------- | ------------------- |:---------------------------------
check        | ((boolean)) | Whether or not sails should lint your JS code.  Defaults to `true`.
formatter   | ((string)) | Which formatter to use.  Defaults to 'stylish'.
patterns          | ((array)) | Which folders or glob patterns to lint.  Defaults to ['api', 'config'].

That&rsquo;s it!
