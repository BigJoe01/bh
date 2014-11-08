# Changelog

All notable changes to this project will be documented in this file.

For more information about changelogs, check
[Keep a Changelog](http://keepachangelog.com) and
[Vandamme](http://tech-angels.github.io/vandamme).

## 1.1.2 - unreleased

* [ENHANCEMENT] Don’t render anything when `vertical` and `horizontal` are not wrapped in a `navbar`
* [ENHANCEMENT] Allow `progress_bar` to pass extra parameters to the wrapping container
* [ENHANCEMENT] Allow `progress_bar` to pass extra parameters to each bar
* [ENHANCEMENT] Wrap plain content passed to `modal` inside the modal body
* [ENHANCEMENT] Allow `panel` to pass extra parameters to the wrapping <div>
* [ENHANCEMENT] Wrap plain content passed to `panel` inside the panel body
* [ENHANCEMENT] Allow `dropdown` to display a full-width button when called with `{layout: :block, groupable: false}`
* [ENHANCEMENT] Allow `alert_box` to pass extra parameters to the alert box <div>

## 1.1.1 - 2014-09-20

* [ENHANCEMENT] Bump Bootstrap version to 3.3.0

## 1.1.0 - 2014-09-20

* [FEATURE] Add `icon` helper
* [FEATURE] Add `font_awesome_css` helper
* [FEATURE] Add `dropdown` helper
* [FEATURE] Add `progress_bar` helper
* [ENHANCEMENT] Add `:fieldset` option to decide whether `fields_for` should wrap fields in a <fieldset> tag
* [FEATURE] Add `button` helper

## 1.0.1 - 2014-09-14

* [BUGFIX] Remove `form-control` class from `file_field` (#20)
* [BUGFIX] Allow `record_object` to be passed to `fields_for` (#22)

## 1.0.0 - 2014-09-09

* No changes

## 0.0.8 - 2014-08-25

* [FEATURE] Add `button_to` helper
* [FEATURE] Add `navbar` helper

## 0.0.7 - 2014-08-25

* [FEATURE] Add `nav` helper

## 0.0.6 - 2014-08-22

* [FEATURE] Add `:prefix`, `:suffix` options to form field helpers

## 0.0.5 - 2014-08-22

* [FEATURE] Add `form_for` and form helpers for every type of field

## 0.0.4 - 2014-08-17

* [FEATURE] Add `modal`
* [FEATURE] Add `panel_row`
* [FEATURE] Add `panel`
* [FEATURE] Add `glyphicon`

## 0.0.3 - 2014-08-15

* [FEATURE] Add `bootstrap_css`, `bootstrap_theme_css` and `bootstrap_js`

## 0.0.2 - 2014-08-15

* [FEATURE] Add `alert_box` helper
