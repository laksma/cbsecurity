# CHANGELOG

## 2.0.0

### Features

* Adobe 2016,2018 Support
* New Module Layout
* Settings transferred to ColdBox 4/5 `moduleSettings` approach instead of root approach.

### Compat

* Adobe 11 Dropped
* Lucee 4.5 Dropped
* Migrate your root `cbSecurity` settings in your `config/ColdBox.cfc` to inside the `moduleSettings`

### Bugs

* Removed entry point for avoiding adding routes

## 1.3.0

* Travis integration
* DocBox updates
* Build process updates

## 1.2.0

* Updated documentation
* Updated doc references
* New docs build process
* Update root builder dependencies

## 1.1.0

* Updated documentation
* Ability for interceptor to auto-register via new `cbsecurity` settings in master config.

## 1.0.2

* Removed `getPlugin()` deprecated calls to new approach.
* https://ortussolutions.atlassian.net/browse/CCM-26 cbsecurity ocm rules not ColdBox 4 compat 

## 1.0.1

* Fixed missing `$throw()` method to native `throw()` method.

## 1.0.0

* Created first module version