# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [3.5.0](https://github.com/alioguzhan/react-editext/compare/v3.4.1...v3.5.0) (2019-08-08)

### Features

* make `value` prop controllable ([361ac3b](https://github.com/alioguzhan/react-editext/commit/361ac3b))


## [3.4.1](https://github.com/alioguzhan/react-editext/compare/v3.3.1...v3.4.1) (2019-08-07)



## [3.4.0](https://github.com/alioguzhan/react-editext/compare/v3.3.1...v3.4.0) (2019-08-06)

### Features

* add editOnViewClick prop to activate the edit mode by clicking the view instead of edit button ([119b28b](https://github.com/alioguzhan/react-editext/commit/119b28b))

### [3.3.1](https://github.com/alioguzhan/react-editext/compare/v3.3.0...v3.3.1) (2019-08-05)

# [3.3.0](https://github.com/alioguzhan/react-editext/compare/v3.2.1...v3.3.0) (2019-07-05)


### Features

* add `buttonsAlign` prop to let users change the buttons location ([d24360e](https://github.com/alioguzhan/react-editext/commit/d24360e))



## [3.2.1](https://github.com/alioguzhan/react-editext/compare/v3.2.0...v3.2.1) (2019-06-05)


### Bug Fixes

* upgrade dev deps due to a vulnerability in `handlebars` ([9fbbd30](https://github.com/alioguzhan/react-editext/commit/9fbbd30))



# [3.2.0](https://github.com/alioguzhan/react-editext/compare/v3.1.1...v3.2.0) (2019-06-05)


### Bug Fixes

* example/package.json to reduce vulnerabilities ([fe71d62](https://github.com/alioguzhan/react-editext/commit/fe71d62))


### Features

* add new props to allow to override container styles. see [#11](https://github.com/alioguzhan/react-editext/issues/11) ([18b914d](https://github.com/alioguzhan/react-editext/commit/18b914d))



## [3.1.2](https://github.com/alioguzhan/react-editext/compare/v3.1.1...v3.1.2) (2019-04-26)


### Bug Fixes

* example/package.json to reduce vulnerabilities ([fe71d62](https://github.com/alioguzhan/react-editext/commit/fe71d62))
* [#10](https://github.com/alioguzhan/react-editext/pull/10) fix typescript errors in `index.d.ts` file ([@wesoft-systems](https://github.com/wesoft-systems))



<a name="3.1.1"></a>
## [3.1.1](https://github.com/alioguzhan/react-editext/compare/v3.1.0...v3.1.1) (2019-03-24)


### Bug Fixes

* **package:** add `index.d.ts` file to npm package ([b40af98](https://github.com/alioguzhan/react-editext/commit/b40af98))


<a name="3.1.0"></a>
# [3.1.0](https://github.com/alioguzhan/react-editext/compare/v3.0.1...v3.1.0) (2019-03-05)


### Features
* add typescript definition file [`d.ts`] ([245a406](https://github.com/alioguzhan/react-editext/commit/245a406))


<a name="3.0.1"></a>
## [3.0.1](https://github.com/alioguzhan/react-editext/compare/v3.0.0...v3.0.1) (2019-03-04)



<a name="3.0.0"></a>
# [3.0.0](https://github.com/alioguzhan/react-editext/compare/v2.1.1...v3.0.0) (2019-02-27)


### Bug Fixes

* **styling:** minor fixes in default styles ([d76d8c2](https://github.com/alioguzhan/react-editext/commit/d76d8c2))


### Features

* allow any valid element for action buttons ([c1bea76](https://github.com/alioguzhan/react-editext/commit/c1bea76))
* allow users to disable default icons ([784dd48](https://github.com/alioguzhan/react-editext/commit/784dd48))


### BREAKING CHANGES

* prop names for buttons are now changed. see `README.md`



<a name="2.1.2"></a>
## [2.1.2](https://github.com/alioguzhan/react-editext/compare/v2.1.1...v2.1.2) (2018-10-07)


### Bug Fixes

* **styling:** minor fixes in default styles ([b33b5c4](https://github.com/alioguzhan/react-editext/commit/b33b5c4))



<a name="2.1.1"></a>
## [2.1.1](https://github.com/alioguzhan/react-editext/compare/v2.1.0...v2.1.1) (2018-10-07)


### Bug Fixes

* **styling:** some styles override global css rules ([14656d5](https://github.com/alioguzhan/react-editext/commit/14656d5))



<a name="2.1.0"></a>
# [2.1.0](https://github.com/alioguzhan/react-editext/compare/v2.0.1...v2.1.0) (2018-10-05)


### Bug Fixes

* revert React.Fragment usage ([3eaf836](https://github.com/alioguzhan/react-editext/commit/3eaf836))


### Features

* allow any valid element for hint prop ([1d802b6](https://github.com/alioguzhan/react-editext/commit/1d802b6))



## 2.0.1 - October 2, 2018

- fix - move inputProps top to prevent overrides to component logic.

## 2.0.0 - September 30, 2018 :rocket: :fire: :pushpin:
This version brings some important and breaking changes. Please consider to upgrade v2.

And very special thanks to [Oririner](https://www.reddit.com/user/Oririner) from Reddit for [such a great and detailed review](https://www.reddit.com/r/reactjs/comments/9i1z7s/react_editext_inline_editable_text_component/e6gedgh/). This feedback helped me a lot especially to release this version.

- `inputProps` and `viewProps` for both input and content div. :tada:
  > You can customize `input` element and the `div` that shows edited value. See Examples pages for detailes usage.
- `onValidationFail` prop. :tada: :lock:
  > You don't have to stick to the default validation message and styling. You can track the `validity` and act based on its value. See the examples page.
- Add `hint` prop.
  > Useful if you want to show a simple hint message at the bottom of input element.
- Support for more input types. :white_check_mark:
  > New Types -> `date`, `datetime-local`, `time`, `month`, `url`, `week`, `tel`
- Add more examples -> https://alioguzhan.github.io/react-editext/
- Remove `inputClassName` and `containerClassName` props :warning: :x:
  > Since we added `inputProps` and `viewProps` these are no longer needed.
- Remove `save on press Enter` feature. :warning: :x:
  > This blocks new line feature in textarea.


## 1.2.1 - September 29, 2018
- Added `type=button` to all buttons.
- Improve tests

## 1.2.0 - September 23, 2018
- Added `className` prop for custom styling to text content
- Added tests

## 1.1.0 - September 22, 2018
- Trigger save action on press Enter
- Improve default styling for Firefox and Safari
- Added this changelog

## 1.0.1 - September 22, 2018
- Add `validation` feature. Now we can pass a function to validate the content before save it. See [examples page](https://alioguzhan.github.io/react-editext/) for more details.

## 1.0.0 - September 21, 2018

- Initial Release
