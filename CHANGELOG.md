## Unreleased

## 0.5.0

* Bump pretender to 0.10
* Fix typo in option name to en/disable pretender

## 0.4.0

* Bump Pretender version to 0.9.0.

## 0.2.3

* Fix shim to add list of export modules.

## 0.2.2

* Add shim file to allow `import Pretender from 'pretender';`.
* Fix repo URL's (rjackson -> rwjblue).

## 0.2.1

* Remove hard-coded list of files to include (in package.json).

## 0.2.0

* Remove vendored code (instead, install via bower in postinstall hook).
* Export a POJO (allows us to inherit from ember-cli's Addon model).
* Add repo url to package.json.
