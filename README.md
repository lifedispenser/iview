<p align="center">
    <a href="https://www.iviewui.com">
        <img width="200" src="https://raw.githubusercontent.com/iview/iview/master/assets/logo.png">
    </a>
</p>

# iView  [![](https://img.shields.io/travis/iview/iview.svg?style=flat-square)](https://travis-ci.org/iview/iview) [![iView](https://img.shields.io/npm/v/iview.svg?style=flat-square)](https://www.npmjs.org/package/iview) [![NPM downloads](http://img.shields.io/npm/dm/iview.svg?style=flat-square)](https://npmjs.org/package/iview) [![Join the chat at https://gitter.im/iview/iview](https://badges.gitter.im/iview/iview.svg)](https://gitter.im/iview/iview?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

### A high quality  UI Components Library with Vue.js

> This branch is for Vue 2.x

## Docs

### [中文文档](https://www.iviewui.com)
### English (Coming soon)

## Programming
- [x] Grid
- [x] Layout
- [x] Button
- [x] Icon
- [x] Input
- [x] Radio
- [x] Checkbox
- [x] Switch
- [ ] Table
- [x] Select
- [x] Slider
- [x] DatePicker
- [x] TimePicker
- [x] Cascader
- [x] Transfer
- [x] InputNumber
- [x] Rate
- [x] Upload
- [ ] Form
- [x] Alert
- [x] Card
- [ ] Message
- [ ] Notice
- [ ] Modal
- [x] Progress
- [x] Badge
- [x] Collapse
- [x] Timeline
- [x] Tag
- [x] Tooltip
- [x] Poptip
- [x] Carousel
- [x] Tree
- [x] Menu
- [x] Tabs
- [x] Dropdown
- [x] Page
- [x] Breadcrumb
- [x] Steps
- [ ] LoadingBar
- [x] Circle
- [x] Affix
- [x] BackTop
- [x] Spin

## Overview

### [组件概览（Component Overview）](https://www.iviewui.com/overview)

## Features

- High quality and rich functions
- Friendly APIs,free and flexible
- Great Documentation
- It is quite beautiful
- Using .vue file development mode
- Based on npm + webpack + babel, using ES2015

## Install

### Install vue-webpack project in the first place

Use [iview-project](https://github.com/iview/iview-project)(Recommended) Or [vue-cli](https://github.com/vuejs/vue-cli)

### Install iView

using npm
```
npm install iview --save
```
Or using script tag for global use
```
<script type="text/javascript" src="iview.min.js"></script>
```

## Usage

```html
<template>
    <Slider :value.sync="value" range></Slider>
</template>
<script>
    export default {
        data () {
            return {
                value: [20, 50]
            }
        }
    }
</script>
```
Use css
```js
import 'iview/dist/styles/iview.css';
```

## Browser Support

Normal browsers and Internet Explorer 9+.

## Links

- [TalkingData](https://github.com/TalkingData)
- [Vue](https://github.com/vuejs/vue)
- [Webpack](https://github.com/webpack/webpack)
- [ionicons](https://github.com/driftyco/ionicons)
- [Ant Design](https://github.com/ant-design/ant-design)
