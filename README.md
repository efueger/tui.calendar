

# ![TOAST UI Calendar](https://user-images.githubusercontent.com/26706716/39230183-7f8ff186-48a0-11e8-8d9c-9699d2d0e471.png)

> A JavaScript schedule calendar with full featured. Now your service just got the customizable calendar.

[![GitHub release](https://img.shields.io/github/release/nhnent/tui.calendar.svg)](https://github.com/nhnent/tui.calendar/releases/latest)
[![npm](https://img.shields.io/npm/v/tui-calendar.svg)](https://www.npmjs.com/package/tui-calendar)
[![GitHub license](https://img.shields.io/github/license/nhnent/tui.calendar.svg)](https://github.com/nhnent/tui.calendar/blob/master/LICENSE)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-ff69b4.svg)](https://github.com/nhnent/tui.project-name/labels/help%20wanted)
[![code with hearth by NHN Entertainment](https://img.shields.io/badge/%3C%2F%3E%20with%20%E2%99%A5%20by-NHN%20Entertainment-ff1414.svg)](https://github.com/nhnent)

![tui-calendar-demo](https://user-images.githubusercontent.com/26706716/38919146-bc596f28-432a-11e8-8bbd-b561911067c7.gif)

## 🚩 Table of Contents

* [Browser Support](#-browser-support)
* [What a cool: Monthly, Weekly, Daily and various view types.](#what-a-cool-monthly-weekly-daily-and-various-view-types)
* [Very easy to use: Dragging and Resizing a schedule](#very-easy-to-use-dragging-and-resizing-a-schedule)
* [Ready to use it right now: Default Popups](#ready-to-use-it-right-now-default-popups)
* [Features](#-features)
* [Examples](#-examples)
* [Install](#-install)
  * [Via Package Manager](#via-package-manager)
  * [Via Contents Delivery Network (CDN)](#via-contents-delivery-network-cdn)
  * [Download Source Files](#download-source-files)
* [Usage](#-usage)
  * [HTML](#html)
  * [JavaScript](#javascript)
* [Pull Request Steps](#-pull-request-steps)
  * [Setup](#setup)
  * [Develop](#develop)
  * [Pull Request Steps](#pull-request)
* [Documents](#-documents)
* [Contributing](#-contributing)
* [Dependency](#-dependency)
* [License](#-license)

## 🌏 Browser Support
| <img src="https://user-images.githubusercontent.com/1215767/34348387-a2e64588-ea4d-11e7-8267-a43365103afe.png" alt="Chrome" width="16px" height="16px" /> Chrome | <img src="https://user-images.githubusercontent.com/1215767/34348590-250b3ca2-ea4f-11e7-9efb-da953359321f.png" alt="IE" width="16px" height="16px" /> Internet Explorer | <img src="https://user-images.githubusercontent.com/1215767/34348380-93e77ae8-ea4d-11e7-8696-9a989ddbbbf5.png" alt="Edge" width="16px" height="16px" /> Edge | <img src="https://user-images.githubusercontent.com/1215767/34348394-a981f892-ea4d-11e7-9156-d128d58386b9.png" alt="Safari" width="16px" height="16px" /> Safari | <img src="https://user-images.githubusercontent.com/1215767/34348383-9e7ed492-ea4d-11e7-910c-03b39d52f496.png" alt="Firefox" width="16px" height="16px" /> Firefox |
| :---------: | :---------: | :---------: | :---------: | :---------: |
| Yes | +9 | Yes | Yes | Yes |

## What a cool: Monthly, Weekly, Daily and various view types.

| Monthly | Weekly |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/26706716/39230396-4d79a592-48a1-11e8-9849-08e80f1bedf6.png) | ![image](https://user-images.githubusercontent.com/26706716/39230459-83beac38-48a1-11e8-8cd4-11b97817f1f8.png) |

| Daily | 2 Weeks |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/26706716/39230685-60a2a1d6-48a2-11e8-9d46-ce5693277a64.png) | ![image](https://user-images.githubusercontent.com/26706716/39230638-281d5266-48a2-11e8-84d8-ab289f372051.png) |

## Very easy to use: Dragging and Resizing a schedule

| Dragging | Resizing |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/26706716/39230930-591031f8-48a3-11e8-8f62-e12e6c19920c.gif) | ![image](https://user-images.githubusercontent.com/26706716/39231671-c926d0da-48a5-11e8-959d-35fd32f2c522.gif) |


## Ready to use it right now: Default Popups

| Creation Popup | Detail Popup |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/26706716/39230798-d151a9ae-48a2-11e8-842d-b19b40432f48.png) | ![image](https://user-images.githubusercontent.com/26706716/39230820-e73fa11c-48a2-11e8-9348-8e3d81979a78.png) |

## 🎨 Features

* Supports various view types: daily, weekly, monthly(6 weeks, 2 weeks, 3 weeks)
* Supports efficient management of milestone and task schedules
* Supports the narrow width of weekend
* Supports changing start day of week
* Supports customizing the date and schedule information UI(including a header and a footer of grid cell)
* Supports adjusting a schedule by mouse dragging
* Supports customizing UI by theme

## 🐾 Examples

* [Basic](https://nhnent.github.io/tui.calendar/latest/tutorial-example01-basic.html) : Example of using default options.

## 💾 Install

TOAST UI products can be used by using the package manager or downloading the source directly.
However, we highly recommend using the package manager.

### Via Package Manager

TOAST UI products are registered in two package managers, [npm](https://www.npmjs.com/) and [bower](https://bower.io/).
You can conveniently install it using the commands provided by each package manager.
When using npm, be sure to use it in the environment [Node.js](https://nodejs.org) is installed.

#### npm

``` sh
$ npm install --save tui-calendar # Latest version
$ npm install --save tui-calendar@<version> # Specific version
```

#### bower

``` sh
$ bower install tui-calendar # Latest version
$ bower install tui-calendar#<tag> # Specific version
```

### Via Contents Delivery Network (CDN)
TOAST UI products are available over the CDN powered by [TOAST Cloud](https://www.toast.com).

You can use the CDN as below.

```html
<script src="https://uicdn.toast.com/tui-calendar/latest/tui-calendar.js"></script>
<link rel="stylesheet" type="text/css" href="https://uicdn.toast.com/tui-calendar/latest/tui-calendar.css" />
```

If you want to use a specific version, use the tag name instead of `latest` in the url's path.

The CDN directory has the following structure.

```
tui-calendar/
├─ latest/
│  ├─ tui-calendar.js
│  └─ tui-calendar.min.js
│  └─ tui-calendar.css
│  └─ tui-calendar.min.css
├─ v1.0.0/
│  ├─ ...
```


### Download Source Files

* [Download bundle files](https://github.com/nhnent/tui.calendar/tree/master/dist)
* [Download all sources for each version](https://github.com/nhnent/tui.calendar/releases)


## 🔨 Usage

### HTML

Place a `<div></div>` where you want TOAST UI Calendar rendered.

```html
<body>
...
<div id="calendar" style="height: 800px;"></div>
...
</body>
```

### JavaScript

#### Using namespace in browser environment

```javascript
var Calendar = tui.Calendar;
```

#### Using module format in node environment

```javascript
var Calendar = require('tui-calendar'); /* CommonJS */
```

```javascript
import Calendar from 'tui-calendar'; /* ES6 */
```

Then you can create a calendar instance with [options](https://nhnent.github.io/tui.calendar/latest/global.html#Options) to set configuration.

```javascript
var calendar = new Calendar('#calendar', {
  defaultView: 'month',
  taskView: true,
  template: {
    monthGridHeader: function(model) {
      var date = new Date(model.date);
      var template = '<span class="tui-full-calendar-weekday-grid-date">' + date.getDate() + '</span>';
      return template;
    }
  }
});
```

## 🔧 Pull Request Steps

TOAST UI products are open source, so you can create a pull request(PR) after you fix issues.
Run npm scripts and develop yourself with the following process.

### Setup

Fork `develop` branch into your personal repository.
Clone it to local computer. Install node modules.
Before starting development, you should check to haveany errors.

``` sh
$ git clone https://github.com/{username}/tui.calendar.git
$ cd tui.calendar
$ npm install
$ npm run test
```

### Develop

Let's start development!
You can see your code is reflected as soon as you saving the codes by running a server.
Don't miss adding test cases and then make green rights.

#### Run webpack-dev-server

``` sh
$ npm run serve
```

#### Run karma test

``` sh
$ npm run test
```

### Pull Request

Before PR, check to test lastly and then check any errors.
If it has no error, commit and then push it!

For more information on PR's step, please see links of Contributing section.

## 📙 Documents

* [Getting Started](https://github.com/nhnent/tui.calendar/blob/master/docs/getting-started.md)
* [Tutorials](https://github.com/nhnent/tui.calendar/tree/master/docs)
* [APIs](https://nhnent.github.io/tui.calendar/latest)

You can also see the older versions of API page on the [releases page](https://github.com/nhnent/tui.calendar/releases).

## 💬 Contributing

* [Code of Conduct](https://github.com/nhnent/tui.calendar/blob/master/CODE_OF_CONDUCT.md)
* [Contributing guideline](https://github.com/nhnent/tui.calendar/blob/master/CONTRIBUTING.md)
* [Issue guideline](https://github.com/nhnent/tui.calendar/blob/master/docs/ISSUE_TEMPLATE.md)
* [Commit convention](https://github.com/nhnent/tui.calendar/blob/master/docs/COMMIT_MESSAGE_CONVENTION.md)

## 🔩 Dependency

* [tui-code-snippet](https://github.com/nhnent/tui.code-snippet) >= 1.4.0
* [tui-date-picker](https://github.com/nhnent/tui.date-picker) >= 3.0.0 is optional.
* [tui-time-picker](https://github.com/nhnent/tui.time-picker) >= 1.0.0 is optional.

## 📜 License

This software is licensed under the [MIT](https://github.com/nhnent/tui.calendar/blob/master/LICENSE) © [NHN Entertainment](https://github.com/nhnent).
