# 关于javascript的一切

* [Awesome JavaScript](#awesome-javascript)
  * [Package Managers-包管理](#package-managers)
  * [Loaders-加载器](#loaders)
  * [Bundlers-打包](#bundlers)
  * [Testing Frameworks-测试框架](#testing-frameworks)
  * [QA Tools-QA工具](#qa-tools)
  * [MVC Frameworks and Libraries-MVC框架和库](#mvc-frameworks-and-libraries)
  * [Node-Powered CMS Frameworks-基于Node的CMS的框架](#node-powered-cms-frameworks)
  * [Templating Engines-模板引擎](#templating-engines)
  * [Data Visualization-数据可视化](#data-visualization)
    * [Timeline-时间轴](#timeline)
    * [Spreadsheet-表格](#spreadsheet)
  * [Editors-编辑器](#editors)
  * [Documentation-文档](#documentation)
  * Utilities-工具
    * [Files-文件](#files)
    * [Functional Programming-函数式编程](#functional-programming)
    * [Reactive Programming-响应式编程](#reactive-programming)
    * [Data Structure-数据结构](#data-structure)
    * [Date-日期](#date)
    * [String-字符串](#string)
    * [Number-数字](#number)
    * [Storage-存储](#storage)
    * [Color-颜色](#color)
    * [I18n And L10n](#i18n-and-l10n)
    * [Control Flow-控制流](#control-flow)
    * [Routing-路由](#routing)
    * [Security-安全](#security)
    * [Log-日志](#log)
    * [RegExp-正则表达式](#regexp)
    * [Media-媒体](#media)
    * [Voice Command-语音](#voice-command)
    * [API-API](#api)
    * [Streaming-流](#streaming)
    * [Vision Detection-视觉检测](#vision-detection)
    * [Browser Detection-浏览器检测](#browser-detection)
    * [Benchmark-基准测试](#benchmark)
    * [Machine Learning-机器学习](#machine-learning)
  * UI
    * [Code Highlighting-代码高亮](#code-highlighting)
    * [Loading Status-加载状态](#loading-status)
    * [Validation-表单验证](#validation)
    * [Keyboard Wrappers-键盘封装](#keyboard-wrappers)
    * [Tours And Guides-指南](#tours-and-guides)
    * [Notifications-通知](#notifications)
    * [Sliders-滑块](#sliders)
    * [Range Sliders-范围划扣](#range-sliders)
    * [Form Widgets-表单组件](#form-widgets)
    * [Tips-提示](#tips)
    * [Modals and Popups-弹出层](#modals-and-popups)
    * [Scroll-滚轴](#scroll)
    * [Menu-菜单](#menu)
    * [Table/Grid-表格](#tablegrid)
    * [Frameworks-框架](#frameworks-1)
    * [Boilerplates-样板](#boilerplates)
  * [Gesture-手势](#gesture)
  * [Maps-地图](#maps)
  * [Typography-排版](#typography)
  * [Animations-动画](#animations)
  * [Image processing-图片处理](#image-processing)
  * [ES6-ES6](#es6)
  * [SDK-SDK](#sdk)
  * [Misc-杂项](#misc)
  * [Podcasts-播客](#podcasts)
* [Worth Reading-阅读](#worth-reading)
* [Other Awesome Lists-其他](#other-awesome-lists)

----


## Package Managers-包管理
*包管理打包.*

* [npm](https://www.npmjs.com/) - npm is the package manager for javascript.
* [Bower](https://github.com/bower/bower) - A package manager for the web.
* [component](https://github.com/componentjs/component) - Client package management for building better web applications.
* [yarn](https://yarnpkg.com/) - Fast, reliable, and secure dependency management.


## Loaders-加载器
*Module or loading system for JavaScript.*

* [RequireJS](https://github.com/requirejs/requirejs) - A file and module loader for JavaScript.
* [browserify](https://github.com/substack/node-browserify) - Browser-side require() the node.js way.
* [SeaJS](https://github.com/seajs/seajs) - A Module Loader for the Web.
* [systemjs](https://github.com/systemjs/systemjs) - AMD, CJS & ES6 spec-compliant module loader.


## Bundlers-打包

* [browserify](https://github.com/substack/node-browserify) - Browserify lets you require('modules') in the browser by bundling up all of your dependencies.
* [webpack](https://github.com/webpack/webpack) - Packs CommonJs/AMD modules for the browser.
* [Rollup](https://github.com/rollup/rollup) - Next-generation ES6 module bundler.
* [Parcel](https://github.com/parcel-bundler/parcel) - Blazing fast, zero configuration web application bundler.


## Testing Frameworks-测试框架

### Frameworks-框架

* [mocha](https://github.com/mochajs/mocha) - Simple, flexible, fun javascript test framework for node.js & the browser.
* [jasmine](https://github.com/jasmine/jasmine) - DOM-less simple JavaScript testing framework.
* [qunit](https://github.com/jquery/qunit) - An easy-to-use JavaScript Unit Testing framework.
* [jest](https://github.com/facebook/jest) - Painless Javascript Unit Testing.
* [tape](https://github.com/substack/tape) - Tap-producing test harness for node and browsers.
* [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing for the modern web development stack.
* [ava](https://github.com/avajs/ava) - 🚀 Futuristic JavaScript test runner

### Assertion-断言

* [chai](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework.
* [Enzyme](http://airbnb.io/enzyme/index.html) - Enzyme is a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components' output.
* [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs, and mocks for JavaScript.

### Coverage-覆盖率

* [istanbul](https://github.com/gotwarlost/istanbul) - Yet another JS code coverage tool.
* [blanket](https://github.com/alex-seville/blanket) - A simple code coverage library for javascript. Designed to be easy to install and use, for both browser and nodejs.
* [JSCover](https://github.com/tntim96/JSCover) - JSCover is a tool that measures code coverage for JavaScript programs.

### Runner-运行器

* [phantomjs](https://github.com/ariya/phantomjs) - Scriptable Headless WebKit.
* [casperjs](https://github.com/casperjs/casperjs) - Navigation scripting & testing utility for PhantomJS and SlimerJS.
* [zombie](https://github.com/assaf/zombie) - Insanely fast, full-stack, headless browser testing using node.js.
* [karma](https://github.com/karma-runner/karma) - Spectacular Test Runner for JavaScript.
* [nightwatch](https://github.com/nightwatchjs/nightwatch) - UI automated testing framework based on node.js and selenium webdriver.
* [intern](https://github.com/theintern/intern) - A next-generation code testing stack for JavaScript.
* [yolpo](http://www.yolpo.com) - A statement-by-statement javascript interpreter in the browser.


## QA Tools-QA工具

* [prettier](https://github.com/prettier/prettier) - Prettier is an opinionated code formatter.
* [JSHint](https://github.com/jshint/jshint/) - JSHint is a tool that helps to detect errors and potential problems in your JavaScript code.
* [jscs](https://github.com/jscs-dev/node-jscs) - JavaScript Code Style checker.
* [ESLint](https://github.com/eslint/eslint) - A fully pluggable tool for identifying and reporting on patterns in JavaScript.
* [JSLint](https://github.com/douglascrockford/JSLint) - High-standards, strict & opinionated code quality tool, aiming to keep only good parts of the language.
* [JavaScript Standard Style](https://github.com/feross/standard) - Opinionated, no-configuration style guide, style checker, and formatter


## MVC Frameworks and Libraries-MVC框架和库

* [angular.js](https://github.com/angular/angular.js) - HTML enhanced for web apps.
* [aurelia](http://aurelia.io) - A Javascript client framework for mobile, desktop and web.
* [backbone](https://github.com/jashkenas/backbone) - Give your JS App some Backbone with Models, Views, Collections, and Events.
* [ember.js](https://github.com/emberjs/ember.js) - A JavaScript framework for creating ambitious web applications.
* [meteor](https://github.com/meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework.
* [ractive](https://github.com/ractivejs/ractive) - Next-generation DOM manipulation.
* [vue](https://github.com/vuejs/vue) - Intuitive, fast & composable MVVM for building interactive interfaces.
* [knockout](https://github.com/knockout/knockout) - Knockout makes it easier to create rich, responsive UIs with JavaScript.
* [spine](https://github.com/spine/spine) - Lightweight MVC library for building JavaScript applications.
* [react](https://facebook.github.io/react/) - A library for building user interfaces. It's declarative, efficient, and extremely flexible. Works with a Virtual DOM.
* [hyperapp](https://github.com/hyperapp/hyperapp) - 1kb JavaScript library for building frontend applications.
* [preact](https://github.com/developit/preact) - Fast 3kb React alternative with the same ES6 API. Components & Virtual DOM.
* [nativescript](https://github.com/NativeScript/NativeScript) - Build truly native cross-platform iOS and Android apps with JavaScript
* [react-native](https://github.com/facebook/react-native) - A framework for building native apps with React.
* [riot](https://github.com/riot/riot) - React-like library, but with very small size.
* [marionette](https://github.com/marionettejs/backbone.marionette) - A composite application library for Backbone.js that aims to simplify the construction of large scale JavaScript applications.
* [rivets](https://github.com/mikeric/rivets) - Lightweight and powerful data binding + templating solution.
* [derby](https://github.com/derbyjs/derby) - MVC framework making it easy to write realtime, collaborative applications that run in both Node.js and browsers.
    * [derby-awesome](https://github.com/russll/awesome-derby) - A collection of awesome derby components
* [way.js](https://github.com/gwendall/way.js) - Simple, lightweight, persistent two-way databinding.
* [mithril.js](https://github.com/lhorie/mithril.js) - Mithril is a client-side MVC framework (Light-weight, Robust, Fast).
* [jsblocks](https://github.com/astoilkov/jsblocks) - jsblocks is better MV-ish framework.
* [LiquidLava](http://www.lava-framework.com/) - Transparent MVC framework for building user interfaces.
* [feathers](https://github.com/feathersjs/feathers) - A minimalist real-time JavaScript framework for tomorrow's apps.

## Node-Powered CMS Frameworks-基于NODE的CMS

* [KeystoneJS](https://github.com/keystonejs/keystone) - powerful CMS and web app framework
* [Reaction Commerce](https://github.com/reactioncommerce/reaction) - reactive CMS, real-time architecture and design
* [Ghost](https://github.com/tryghost/Ghost) - simple, powerful publishing platform
* [Apostrophe](https://github.com/punkave/apostrophe) - CMS with content editing and essential services
* [PencilBlue](https://github.com/pencilblue/pencilblue/) - CMS and blogging platform

## Templating Engines-模板引擎

* [mustache.js](https://github.com/janl/mustache.js) - Minimal templating with {{mustaches}} in JavaScript.
* [handlebars.js](https://github.com/wycats/handlebars.js/) - An extension to the Mustache templating language.
* [hogan.js](https://github.com/twitter/hogan.js) - A compiler for the Mustache templating language.
* [doT](https://github.com/olado/doT) - The fastest + concise javascript template engine for nodejs and browsers.
* [dustjs](https://github.com/linkedin/dustjs/) - Asynchronous templates for the browser and node.js.
* [Pug](https://github.com/pugjs/pug) - Robust, elegant, feature rich template engine for nodejs. (formerly known as Jade)
* [EJS](https://github.com/mde/ejs) - Effective JavaScript templating.
* [marko](https://github.com/marko-js/marko) - A fast, lightweight, HTML-based templating engine for Node.js and the browser with async, streaming, custom tags and CommonJS modules as compiled output.
* [swig](http://paularmstrong.github.io/swig/) - A simple, powerful, and extendable Node.js and browser-based JavaScript template engine.


## Data Visualization-数据可视化
*web数据的可视化.*

* [d3](https://github.com/d3/d3) - A JavaScript visualization library for HTML and SVG.
  * [metrics-graphics](https://github.com/mozilla/metrics-graphics) - A library optimized for concise, principled data graphics and layouts.
* [three.js](https://github.com/mrdoob/three.js) - JavaScript 3D library.
* [Chart.js](https://github.com/chartjs/Chart.js) - Simple HTML5 Charts using the <canvas> tag.
* [paper.js](https://github.com/paperjs/paper.js) - The Swiss Army Knife of Vector Graphics Scripting – Scriptographer ported to JavaScript and the browser, using HTML5 Canvas.
* [fabric.js](https://github.com/kangax/fabric.js) - Javascript Canvas Library, SVG-to-Canvas (& canvas-to-SVG) Parser.
* [peity](https://github.com/benpickles/peity) - Progressive <svg> bar, line and pie charts.
* [raphael](https://github.com/DmitryBaranovskiy/raphael) - JavaScript Vector Library.
* [echarts](https://github.com/ecomfe/echarts) - Enterprise Charts.
* [vis](https://github.com/almende/vis) - Dynamic, browser-based visualization library.
* [two.js](https://github.com/jonobr1/two.js) - A renderer agnostic two-dimensional drawing api for the web.
* [sigma.js](https://github.com/jacomyal/sigma.js) - A JavaScript library dedicated to graph drawing.
* [arbor](https://github.com/samizdatco/arbor) - A graph visualization library using web workers and jQuery.
* [cubism](https://github.com/square/cubism) - A D3 plugin for visualizing time series.
* [dc.js](https://github.com/dc-js/dc.js) - Multi-Dimensional charting built to work natively with crossfilter rendered with d3.js
* [processing.js](http://processingjs.org/) - Processing.js makes your data visualizations work using web standards and without any plug-ins
* [envisionjs](https://github.com/HumbleSoftware/envisionjs) - Dynamic HTML5 visualization.
* [rickshaw](https://github.com/shutterstock/rickshaw) - JavaScript toolkit for creating interactive real-time graphs.
* [flot](https://github.com/flot/flot) - Attractive JavaScript charts for jQuery.
* [morris.js](https://github.com/morrisjs/morris.js) - Pretty time-series line graphs.
* [nvd3](https://github.com/novus/nvd3) - Build re-usable charts and chart components for d3.js
* [svg.js](https://github.com/wout/svg.js) - A lightweight library for manipulating and animating SVG.
* [heatmap.js](https://github.com/pa7/heatmap.js) - JavaScript Library for HTML5 canvas based heatmaps.
* [trianglify](https://github.com/qrohlf/trianglify) - Low poly style background generator with d3.js
* [dimple.js](http://dimplejs.org) -  Easy charts for business analytics powered by d3
* [chartist-js](https://github.com/gionkunz/chartist-js) - Simple responsive charts.
* [epoch](https://github.com/epochjs/epoch) - A general purpose real-time charting library.
* [c3](https://github.com/c3js/c3) - D3-based reusable chart library.
* [BabylonJS](https://github.com/BabylonJS/Babylon.js) - A framework for building 3D games with HTML 5 and WebGL.
* [recharts](https://github.com/recharts/recharts) - Redefined chart library built with React and D3
* [GraphicsJS](https://www.graphicsjs.org) - A lightweight JavaScript graphics library with the intuitive API, based on SVG/VML technology.

There're also some great commercial libraries, like [amchart](https://www.amcharts.com/), [anychart](http://www.anychart.com), [plotly](https://plot.ly/), and [highchart](http://www.highcharts.com/).


## Timeline-时间轴

* [TimelineJS v3](https://github.com/NUKnightLab/TimelineJS3) - A Storytelling Timeline built in JavaScript.
* [timesheet.js](https://github.com/sbstjn/timesheet.js) - JavaScript library for simple HTML5 & CSS3 time sheets.

## Spreadsheet-电子表格

* [HANDSONTABLE](https://github.com/handsontable/handsontable) - Handsontable is a JavaScript/HTML5 Spreadsheet Library for Developers

## Editors-编辑器

* [ace](https://github.com/ajaxorg/ace) - Ace (Ajax.org Cloud9 Editor).
* [CodeMirror](https://github.com/codemirror/CodeMirror) - In-browser code editor.
* [quill](https://github.com/quilljs/quill) - A cross browser rich text editor with an API.
* [medium-editor](https://github.com/yabwe/medium-editor) - Medium.com WYSIWYG editor clone.
* [pen](https://github.com/sofish/pen) - enjoy live editing (+markdown).
* [bootstrap-wysiwyg](https://github.com/mindmup/bootstrap-wysiwyg) - Tiny bootstrap-compatible WYSIWYG rich text editor.
* [editor](https://github.com/lepture/editor) - A markdown editor. still on development.
* [EpicEditor](https://github.com/OscarGodson/EpicEditor) - An embeddable JavaScript Markdown editor with split fullscreen editing, live previewing, automatic draft saving, offline support, and more.
* [jsoneditor](https://github.com/josdejong/jsoneditor) - A web-based tool to view, edit and format JSON.
* [vim.js](https://github.com/coolwanglu/vim.js) - JavaScript port of Vim with a persistent ~/.vimrc
* [Squire](https://github.com/neilj/Squire) - HTML5 rich text editor.
* [TinyMCE](https://github.com/tinymce/tinymce) - The JavaScript Rich Text editor.
* [trix](https://github.com/basecamp/trix) - A rich text editor for everyday writing. By Basecamp.
* [Draft.js](https://github.com/facebook/draft-js) - A React framework for building text editors.
* [bootstrap-wysihtml5](https://github.com/jhollingworth/bootstrap-wysihtml5) - Simple, beautiful wysiwyg editor
* [wysihtml5](https://github.com/xing/wysihtml5) - Open source rich text editor based on HTML5 and the progressive-enhancement approach. Uses a sophisticated security concept and aims to generate fully valid HTML5 markup by preventing unmaintainable tag soups and inline styles.


## Documentation-文档

* [DevDocs](http://devdocs.io/) is an all-in-one API documentation reader with a fast, organized, and consistent interface.
* [dexy](http://www.dexy.it/) is a free-form literate documentation tool for writing any kind of technical document incorporating code.
* [docco](http://jashkenas.github.io/docco/) is a quick-and-dirty, hundred-line-long, literate-programming-style documentation generator.
* [styledocco](http://jacobrask.github.io/styledocco/) generates documentation and style guide documents from your stylesheets.
* [ESDoc](https://github.com/esdoc/esdoc) is a good documentation generator for JavaScript.
* [coddoc](http://doug-martin.github.io/coddoc/) is a jsdoc parsing library. Coddoc is different in that it is easily extensible by allowing users to add tag and code parsers through the use of coddoc.addTagHandler and coddoc.addCodeHandler. coddoc also parses source code to be used in APIs.
* [sphinx](http://www.sphinx-doc.org/) a tool that makes it easy to create intelligent and beautiful documentation
* [Using JSDoc](http://usejsdoc.org/)
* [Beautiful docs](http://beautifuldocs.com/) is a documentation viewer based on markdown files.
* [documentation.js](http://documentation.js.org) - API documentation generator with support for ES2015+ and flow annotation.


## Files-文件

* [Papa Parse](https://github.com/mholt/PapaParse) - A powerful CSV library that supports parsing CSV files/strings and also exporting to CSV.
* [diff2html](https://github.com/rtfpessoa/diff2html) - Git diff output parser and pretty HTML generator.
* [jsPDF](https://github.com/MrRio/jsPDF) - JavaScript PDF generation.


## Functional Programming-函数式编程

* [underscore](https://github.com/jashkenas/underscore) - JavaScript's utility _ belt.
* [lodash](https://github.com/lodash/lodash) - A utility library delivering consistency, customization, performance, & extras.
* [Sugar](https://github.com/andrewplummer/Sugar) - A Javascript library for working with native objects.
* [lazy.js](https://github.com/dtao/lazy.js) - Like Underscore, but lazier.
* [mout](https://github.com/mout/mout) - Modular JavaScript Utilities.
* [mesh](https://github.com/crcn/mesh.js) - Streamable data synchronization utility.


## Reactive Programming-响应式编程

* [RxJs](https://github.com/Reactive-Extensions/RxJS) - The Reactive Extensions for JavaScript.
* [Bacon](https://github.com/baconjs/bacon.js) - FRP (functional reactive programming) library for Javascript.
* [Highland](http://highlandjs.org/) - Re-thinking the JavaScript utility belt, Highland manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
* [Most.js](https://github.com/cujojs/most) - high performance FRP library.
* [MobX](https://github.com/mobxjs/mobx) - TFRP library for simple, scalable state management.
* [Cycle.js](https://cycle.js.org) - A functional and reactive JavaScript library for cleaner code.

## Data Structure-数据结构

* [immutable-js](https://github.com/facebook/immutable-js) - Immutable Data Collections including Sequence, Range, Repeat, Map, OrderedMap, Set and a sparse Vector.
* [mori](https://github.com/swannodette/mori) - A library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.



## Date-日期

* [moment](https://github.com/moment/moment) - Parse, validate, manipulate, and display dates in javascript.
* [moment-timezone](https://github.com/moment/moment-timezone) - Timezone support for moment.js.
* [jquery-timeago](https://github.com/rmm5t/jquery-timeago) - A jQuery plugin that makes it easy to support automatically updating fuzzy timestamps (e.g. "4 minutes ago").
* [date](https://github.com/MatthewMueller/date) - Date() for humans.
* [countdown.js](https://github.com/gumroad/countdown.js) - Super simple countdowns.
* [timeago.js](https://github.com/hustcc/timeago.js) - Simple library (less then 2kb) used to format date with `*** time ago` statement.
* [fecha](https://github.com/taylorhakes/fecha) - Lightweight date formatting and parsing (~2KB). Meant to replace parsing and formatting functionality of moment.js.
* [date-fns](https://github.com/date-fns/date-fns) - Modern JavaScript date utility library.

## String-字符串

* [voca](https://github.com/panzerdp/voca) - The ultimate JavaScript string library
* [underscore.string](https://github.com/epeli/underscore.string) - String manipulation extensions for Underscore.js javascript library.
* [string.js](https://github.com/jprichardson/string.js) - Extra JavaScript string methods.
* [he](https://github.com/mathiasbynens/he) - A robust HTML entity encoder/decoder written in JavaScript.
* [multiline](https://github.com/sindresorhus/multiline) - Multiline strings in JavaScript.
* [query-string](https://github.com/sindresorhus/query-string) - Parse and stringify URL query strings.
* [URI.js](https://github.com/medialize/URI.js/) - Javascript URL mutation library.
* [sprintf.js](https://github.com/alexei/sprintf.js) - A sprintf implementation.

## Number-数字

* [Numeral-js](https://github.com/adamwdraper/Numeral-js) - A javascript library for formatting and manipulating numbers.
* [chance.js](https://github.com/chancejs/chancejs) - Random generator helper in Javascript. Can generate numbers, strings etc.
* [odometer](https://github.com/HubSpot/odometer) - Smoothly transitions numbers with ease.


## Storage-存储

* [store.js](https://github.com/marcuswestin/store.js) - LocalStorage wrapper for all browsers without using cookies or flash. Uses localStorage, globalStorage, and userData behavior under the hood.
* [localForage](https://github.com/mozilla/localForage) - Offline storage, improved. Wraps IndexedDB, WebSQL, or localStorage using a simple but powerful API.
* [jStorage](https://github.com/andris9/jStorage) - jStorage is a simple key/value database to store data on browser side.
* [jquery-cookie](https://github.com/carhartl/jquery-cookie) - A simple, lightweight jQuery plugin for reading, writing and deleting cookies.
* [js-cookie](https://github.com/js-cookie/js-cookie) - A simple, lightweight JavaScript API for handling browser cookies
* [lawnchair.js](https://github.com/brianleroux/lawnchair/) - Simple client-side JSON storage.
* [sql.js](https://github.com/kripken/sql.js) - SQLite compiled to JavaScript through Emscripten.


## Color-颜色

* [randomColor](https://github.com/davidmerfield/randomColor) - A color generator for JavaScript.
* [chroma.js](https://github.com/gka/chroma.js) - JavaScript library for all kinds of color manipulations.
* [color](https://github.com/Qix-/color) - JavaScript color conversion and manipulation library.
* [colors](https://github.com/mrmrs/colors) - Smarter defaults for colors on the web.
* [PleaseJS](https://github.com/Fooidge/PleaseJS) - JavaScript Library for creating random pleasing colors and color schemes.
* [TinyColor](https://github.com/bgrins/TinyColor) - Fast, small color manipulation and conversion for JavaScript.
* [Vibrant.js](https://github.com/jariz/vibrant.js/) - Extract prominent colors from an image.

## I18n And L10n

* [i18next](https://github.com/i18next/i18next) - internationalisation (i18n) with javascript the easy way.
* [polyglot](https://github.com/airbnb/polyglot.js) - tiny i18n helper library.

## Control Flow-流程控制

* [async](https://github.com/caolan/async) - Async utilities for node and the browser.
* [q](https://github.com/kriskowal/q) - A tool for making and composing asynchronous promises in JavaScript.
* [step](https://github.com/creationix/step/) - An async control-flow library that makes stepping through logic easy.
* [Bluebird](https://github.com/petkaantonov/bluebird/) - fully featured promise library with focus on innovative features and performance.
* [when](https://github.com/cujojs/when) - A solid, fast Promises/A+ and when() implementation, plus other async goodies.


## Routing-路由

* [director](https://github.com/flatiron/director) - A tiny and isomorphic URL router for JavaScript.
* [page.js](https://github.com/visionmedia/page.js) - Micro client-side router inspired by the Express router (~1200 bytes).
* [crossroads](https://github.com/millermedeiros/crossroads.js) - JavaScript Routes.


## Security-安全

* [DOMPurify](https://github.com/cure53/DOMPurify) - A DOM-only, super-fast, uber-tolerant XSS sanitizer for HTML, MathML and SVG.
* [js-xss](https://github.com/leizongmin/js-xss) - Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist.
* [xss-filters](https://github.com/yahoo/xss-filters) - Secure XSS Filters by Yahoo


## Log-日志

* [log](https://github.com/adamschwartz/log) - Console.log with style.
* [console.log-wrapper](https://github.com/patik/console.log-wrapper) - Log to the console in any browser with clarity.
* [loglevel](https://github.com/pimterry/loglevel) - Minimal lightweight logging for JavaScript, adding reliable log level methods to wrap any available console.log methods.
* [minilog](http://mixu.net/minilog/) – Lightweight client & server-side logging with Stream-API backends
* [storyboard](http://guigrpa.github.io/storyboard/) - Universal logging library + Chrome extension; it lets you see all client and server tasks triggered by a user action in a single place.

## RegExp-正则表达式
* [RegEx101](https://regex101.com/#javascript) - Online regex tester and debugger for JavaScript. Also supports Python, PHP and PCRE.
* [RegExr](http://regexr.com) - HTML/JS based tool for creating, testing, and learning about Regular Expressions.
* [RegExpBuilder](https://github.com/thebinarysearchtree/regexpbuilderjs) - Create regular expressions using chained methods.


## Voice Command-语音

* [annyang](https://github.com/TalAter/annyang) - A JavaScript library for adding voice commands to your site, using speech recognition.
* [voix.js](https://github.com/pazguille/voix) - A JavaScript library to add voice commands to your sites, apps or games.


## API-API

* [bottleneck](https://github.com/SGrondin/bottleneck) - A powerful rate limiter that makes throttling easy.
* [amygdala](https://github.com/lincolnloop/amygdala) - RESTful HTTP client for JavaScript powered web applications.
* [jquery.rest](https://github.com/jpillora/jquery.rest) - A jQuery plugin for easy consumption of RESTful APIs.

## Streaming-流

* [Tailor](https://github.com/zalando/tailor) - Streaming layout service for front-end microservices, inspired by Facebook's BigPipe.


## Vision Detection-视觉检测

* [tracking.js](https://github.com/eduardolundgren/tracking.js) - A modern approach for Computer Vision on the web.
* [ocrad.js](https://github.com/antimatter15/ocrad.js) - OCR in Javascript via Emscripten.


## Machine Learning

* [ConvNetJS](https://github.com/karpathy/convnetjs) - Deep Learning in Javascript. Train Convolutional Neural Networks (or ordinary ones) in your browser.
* [DN2A](https://github.com/dn2a/dn2a-javascript) - Digital Neural Networks Architecture.
* [Brain.js](https://github.com/harthur/brain) - Neural networks in JavaScript.
* [Mind.js](https://github.com/stevenmiller888/mind) - A flexible neural network library.
* [Synaptic.js](https://github.com/cazala/synaptic) - Architecture-free neural network library for node.js and the browser.
* [deeplearn.js](https://deeplearnjs.org/) - A hardware-accelerated machine intelligence library for the web.


## Browser Detection-浏览器检测

* [bowser](https://github.com/ded/bowser) - a browser detector

## Benchmark-基准测试

* [benchmark.js](https://github.com/bestiejs/benchmark.js) - A benchmarking library. As used on jsPerf.com.
* [matcha](https://github.com/logicalparadox/matcha) - A caffeine driven, simplistic approach to benchmarking.

## Code highlighting-代码高亮

* [Highlight.js](https://github.com/isagalaev/highlight.js) - Javascript syntax highlighter.
* [PrismJS](https://github.com/PrismJS/prism) - Lightweight, robust, elegant syntax highlighting.


## Loading Status-加载状态


* [Mprogress.js](https://github.com/lightningtgc/MProgress.js) - Create Google Material Design progress linear bars.
* [NProgress](http://ricostacruz.com/nprogress/) - Slim progress bars for Ajax'y applications.
* [Spin.js](https://github.com/fgnass/spin.js) - A spinning activity indicator.
* [progress.js](https://github.com/usablica/progress.js) - Create and manage progress bar for every objects on the page.
* [progressbar.js](https://github.com/kimmobrunfeldt/progressbar.js) - Beautiful and responsive progress bars with animated SVG paths.
* [pace](https://github.com/HubSpot/pace) - Automatically add a progress bar to your site.
* [nanobar](https://github.com/jacoborus/nanobar) - Very lightweight progress bars. No jQuery.
* [SpinKit](https://github.com/tobiasahlin/SpinKit) - A collection of loading indicators animated with CSS.
* [Ladda](https://github.com/hakimel/Ladda) - Buttons with built-in loading indicators.
* [css-loaders](https://github.com/lukehaas/css-loaders) - A collection of loading spinners animated with CSS

Besides libraries, there're [Collection on Codepen](http://codepen.io/collection/HtAne/), and generators like [Ajaxload](http://www.ajaxload.info/), [Preloaders](http://preloaders.net/) and [CSSLoad](http://cssload.net/).


## Validation-验证

* [Parsley.js](https://github.com/guillaumepotier/Parsley.js) - Validate your forms, frontend, without writing a single line of javascript.
* [jquery-validation](https://github.com/jzaefferer/jquery-validation) - jQuery Validation Plugin.
* [validator.js](https://github.com/chriso/validator.js) - String validation and sanitization.
* [validate.js](https://github.com/rickharrison/validate.js) - Lightweight JavaScript form validation library inspired by CodeIgniter.
* [FormValidation](http://formvalidation.io/) - The best jQuery plugin to validate form fields. Formerly BootstrapValidator.
* [is.js](https://github.com/arasatasaygin/is.js) -  Check types, regexps, presence, time and more.


## Keyboard Wrappers-键盘封装

* [mousetrap](https://github.com/ccampbell/mousetrap) - Simple library for handling keyboard shortcuts in Javascript.
* [keymaster](https://github.com/madrobby/keymaster) - A simple micro-library for defining and dispatching keyboard shortcuts.
* [Keypress](https://github.com/dmauro/Keypress) - A keyboard input capturing utility in which any key can be a modifier key.
* [KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) - A JavaScript library for binding keyboard combos without the pain of key codes and key combo conflicts.
* [jquery.hotkeys](https://github.com/jeresig/jquery.hotkeys) - jQuery Hotkeys lets you watch for keyboard events anywhere in your code supporting almost any key combination.
* [jwerty](https://github.com/keithamus/jwerty) - Awesome handling of keyboard events.


## Tours And Guides-指南

* [intro.js](https://github.com/usablica/intro.js) - A better way for new feature introduction and step-by-step users guide for your website and project.
* [shepherd](https://github.com/HubSpot/shepherd) - Guide your users through a tour of your app.
* [bootstrap-tour](https://github.com/sorich87/bootstrap-tour) - Quick and easy product tours with Twitter Bootstrap Popovers.
* [chardin.js](https://github.com/heelhook/chardin.js) - Simple overlay instructions for your apps.
* [hopscotch](https://github.com/linkedin/hopscotch) - A framework to make it easy for developers to add product tours to their pages.
* [joyride](https://github.com/zurb/joyride) - jQuery feature tour plugin.
* [focusable](https://github.com/zzarcon/focusable) - Set a spotlight focus on DOM element adding a overlay layer to the rest of the page.

## Notifications-通知

* [iziToast](https://github.com/dolce/iziToast) - Elegant, responsive, flexible and lightweight notification plugin with no dependencies.
* [messenger](https://github.com/HubSpot/messenger) - Growl-style alerts and messages for your app.
* [noty](https://github.com/needim/noty) - jQuery notification plugin.
* [pnotify](https://github.com/sciactive/pnotify) - JavaScript notifications for Bootstrap, jQuery UI, and the Web Notifications Draft.
* [toastr](https://github.com/CodeSeven/toastr) - Simple javascript toast notifications.
* [humane-js](https://github.com/wavded/humane-js) - A simple, modern, browser notification system.
* [smoke.js](https://github.com/hxgf/smoke.js) - Framework-agnostic styled alert system for javascript.
* [notie](https://github.com/jaredreich/notie) - Simple notifications and inputs with no dependencies.


## Sliders-滑块

* [Swiper](https://github.com/nolimits4web/Swiper) - Mobile touch slider and framework with hardware accelerated transitions.
* [slick](https://github.com/kenwheeler/slick) - The last carousel you'll ever need.
* [slidesJs](http://www.slidesjs.com) - Is a ressponsive slideshow plug-in for JQuery(1.7.1+) with features like touch and CSS3 transitions
* [FlexSlider](https://github.com/woothemes/FlexSlider) - An awesome, fully responsive jQuery slider plugin.
* [unslider](https://github.com/idiot/unslider) - The simplest jQuery slider there is.
* [sly](https://github.com/darsain/sly) - JavaScript library for one-directional scrolling with item based navigation support.
* [vegas](https://github.com/jaysalvat/vegas) - A jQuery plugin to add beautiful fullscreen backgrounds to your webpages. It even allows Slideshows.
* [Sequence](https://github.com/IanLunn/Sequence) - CSS animation framework for creating responsive sliders, presentations, banners, and other step-based applications.
* [reveal.js](https://github.com/hakimel/reveal.js) - A framework for easily creating beautiful presentations using HTML.
* [impress.js](https://github.com/impress/impress.js) - It's a presentation framework based on the power of CSS3 transforms and transitions in modern browsers and inspired by the idea behind prezi.com.
* [bespoke.js](https://github.com/bespokejs/bespoke) - DIY Presentation Micro-Framework
* [Strut](https://github.com/tantaman/Strut) - Strut - An Impress.js and Bespoke.js Presentation Editor
* [PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe) - JavaScript image gallery for mobile and desktop, modular, framework independent.
* [slidr](https://github.com/bchanx/slidr) - add some slide effects.
* [Flickity](https://github.com/metafizzy/flickity) - Touch, responsive, flickable galleries.
* [Glide.js](https://github.com/jedrzejchalubek/glidejs) - Responsive and touch-friendly jQuery slider. It's simple, lightweight and fast.

## Range Sliders-范围滑块

* [Ion.RangeSlider](https://github.com/IonDen/ion.rangeSlider) - Powerful and easily customizable range slider with many options and skin support.
* [jQRangeSlider](https://github.com/ghusse/jQRangeSlider) - A javascript slider selector that supports dates.
* [noUiSlider](https://github.com/leongersen/noUiSlider) - A lightweight, highly customizable range slider without bloat.
* [rangeslider.js](https://github.com/andreruffert/rangeslider.js) - HTML5 input range slider element polyfill.


## Form Widgets-表单组件

### Input-输入

* [typeahead.js](https://github.com/twitter/typeahead.js) - A fast and fully-featured autocomplete library.
* [tag-it](https://github.com/aehlke/tag-it) - A jQuery UI plugin to handle multi-tag fields as well as tag suggestions/autocomplete.
* [At.js](https://github.com/ichord/At.js) - Add Github like mentions autocomplete to your application.
* [Placeholders.js](https://github.com/jamesallardice/Placeholders.js) - A JavaScript polyfill for the HTML5 placeholder attribute.
* [fancyInput](https://github.com/yairEO/fancyInput) - Makes typing in input fields fun with CSS3 effects.
* [jQuery-Tags-Input](https://github.com/xoxco/jQuery-Tags-Input) - Magically convert a simple text input into a cool tag list with this jQuery plugin.
* [awesomplete](https://github.com/LeaVerou/awesomplete) - Ultra lightweight, usable, beautiful autocomplete with zero dependencies. - http://leaverou.github.io/awesomplete/

### Calendar-日历

* [pickadate.js](https://github.com/amsul/pickadate.js) - The mobile-friendly, responsive, and lightweight jQuery date & time input picker.
* [bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker) - A datepicker for @twitter bootstrap forked from Stefan Petre's (of eyecon.ro), improvements by @eternicode.
* [Pikaday](https://github.com/dbushell/Pikaday) - A refreshing JavaScript Datepicker — lightweight, no dependencies, modular CSS.
* [fullcalendar](https://github.com/fullcalendar/fullcalendar) - Full-sized drag & drop event calendar (jQuery plugin).
* [rome](https://github.com/bevacqua/rome) - A customizable date (and time) picker. Dependency free, opt-in UI.
* [datedropper](https://github.com/felicegattuso/datedropper) -  datedropper is a jQuery plugin that provides a quick and easy way to manage dates for input fields.


### Select-选择

* [selectize.js](https://github.com/brianreavis/selectize.js) - Selectize is the hybrid of a textbox and select box. It's jQuery based and it has autocomplete and native-feeling keyboard navigation; useful for tagging, contact lists, etc.
* [select2](https://github.com/select2/select2) - a jQuery based replacement for select boxes. It supports searching, remote data sets, and infinite scrolling of results.
* [chosen](https://github.com/harvesthq/chosen) - A library for making long, unwieldy select boxes more friendly.

### File Uploader-文件上传

* [jQuery-File-Upload](https://github.com/blueimp/jQuery-File-Upload) - File Upload widget with multiple file selection, drag&amp;drop support, progress bar, validation and preview images, audio and video for jQuery.
* [dropzone](https://github.com/enyo/dropzone) - Dropzone is an easy to use drag'n'drop library. It supports image previews and shows nice progress bars.
* [flow.js](https://github.com/flowjs/flow.js) - A JavaScript library providing multiple simultaneous, stable, fault-tolerant and resumable/restartable file uploads via the HTML5 File API.
* [fine-uploader](https://github.com/FineUploader/fine-uploader) - Multiple file upload plugin with progress-bar, drag-and-drop, direct-to-S3 uploading.
* [FileAPI](https://github.com/mailru/FileAPI) - A set of javascript tools for working with files. Multiupload, drag'n'drop and chunked file upload. Images: crop, resize and auto orientation by EXIF.
* [plupload](https://github.com/moxiecode/plupload) - A JavaScript API for dealing with file uploads it supports features like multiple file selection, file type filtering, request chunking, client side image scaling and it uses different runtimes to achieve this such as HTML 5, Silverlight and Flash.

### Other-其他

* [form](https://github.com/malsup/form) - jQuery Form Plugin.
* [Garlic.js](https://github.com/guillaumepotier/Garlic.js) - Automatically persist your forms' text and select field values locally, until the form is submitted.
* [Countable](https://github.com/RadLikeWhoa/Countable) - A JavaScript function to add live paragraph-, word- and character-counting to an HTML element.
* [card](https://github.com/jessepollak/card) - Make your credit card form better in one line of code.


## Tips-提示

* [tipsy](https://github.com/jaz303/tipsy) - Facebook-style tooltips plugin for jQuery.
* [opentip](https://github.com/enyo/opentip) - An open source javascript tooltip based on the prototype framework.
* [qTip2](https://github.com/qTip2/qTip2) - Pretty powerful tooltips.
* [tooltipster](https://github.com/iamceege/tooltipster) - A jQuery tooltip plugin.
* [toolbar](https://github.com/paulkinzett/toolbar) - A tooltip style toolbar jQuery plugin
* [hint.css](https://github.com/chinchang/hint.css) - A tooltip library in CSS for your lovely websites.

## Modals and Popups-弹出层

* [Magnific-Popup](https://github.com/dimsemenov/Magnific-Popup) - Light and responsive lightbox script with focus on performance.
* [jquery.avgrund.js](https://github.com/voronianski/jquery.avgrund.js) - A jQuery plugin with new modal concept for popups.
* [vex](https://github.com/HubSpot/vex) - A modern dialog library which is highly configurable and easy to style.
* [bootstrap-modal](https://github.com/jschr/bootstrap-modal) - Extends the default Bootstrap Modal class. Responsive, stackable, ajax and more.
* [css-modal](https://github.com/drublic/css-modal) - A modal built out of pure CSS.
* [SweetAlert](https://github.com/t4t5/sweetalert) - An awesome replacement for JavaScript's alert.
* [colorbox](https://github.com/jackmoore/colorbox) - A light-weight, customizable lightbox plugin for jQuery.
* [fancyBox](https://github.com/fancyapps/fancyBox) - A tool that offers a nice and elegant way to add zooming functionality for images, html content and multi-media on your webpages.
* [swipebox](https://github.com/brutaldesign/swipebox) - A touchable jQuery lightbox

## Scroll-滚轴

* [scrollMonitor](https://github.com/stutrek/scrollMonitor) - A simple and fast API to monitor elements as you scroll.
* [headroom](https://github.com/WickyNilliams/headroom.js) - Give your pages some headroom. Hide your header until you need it.
* [onepage-scroll](https://github.com/peachananr/onepage-scroll) - Create an Apple-like one page scroller website (iPhone 5S website) with One Page Scroll plugin.
* [iscroll](https://github.com/cubiq/iscroll) - iScroll is a high performance, small footprint, dependency free, multi-platform javascript scroller.
* [skrollr](https://github.com/Prinzhorn/skrollr) - Stand-alone parallax scrolling library for mobile (Android + iOS) and desktop. No jQuery.
* [parallax](https://github.com/wagerfield/parallax) - Parallax Engine that reacts to the orientation of a smart device.
* [stellar.js](https://github.com/markdalgleish/stellar.js) - Parallax scrolling made easy.
* [plax](https://github.com/cameronmcefee/plax) - jQuery powered parallaxing.
* [jparallax](https://github.com/stephband/jparallax) - jQuery plugin for creating interactive parallax effect.
* [fullPage](https://github.com/alvarotrigo/fullPage.js) - A simple and easy to use plugin to create fullscreen scrolling websites (also known as single page websites).
* [Clusterize.js](https://github.com/NeXTs/Clusterize.js) - Tiny vanilla JS plugin to display large data sets easily.


## Menu-菜单

* [jQuery-menu-aim](https://github.com/kamens/jQuery-menu-aim) - jQuery plugin to fire events when user's cursor aims at particular dropdown menu items. For making responsive mega dropdowns like Amazon's.
* [Slideout](https://github.com/mango/slideout) - A responsive touch slideout navigation menu for mobile web apps.


## Table/Grid-表格

* [jTable](https://github.com/hikalkan/jtable) - A jQuery plugin to create AJAX based CRUD tables.
* [DataTables](https://www.datatables.net/) - (jQuery plug-in) It is a highly flexible tool, based upon the foundations of progressive enhancement, and will add advanced interaction controls to any HTML table.
* [Masonry](http://masonry.desandro.com/) - A cascading grid layout library.
* [Isotope](http://isotope.metafizzy.co/) - A filterable, sortable, grid layout library. Can implement Masonry, Packery, and other layouts.
* [flexboxgrid](https://github.com/kristoferjoseph/flexboxgrid/) - Grid based on CSS3 flexbox

## Frameworks-框架

* [Semantic UI](http://semantic-ui.com/) - UI Kit with lots of themes and elements
* [w2ui](http://w2ui.com/) - A set of jQuery plugins for front-end development of data-driven web applications.
* [fluidity](https://github.com/mrmrs/fluidity) - The worlds smallest fully-responsive css framework
* [Ink](https://github.com/sapo/Ink) - An HTML5/CSS3 framework used at SAPO for fast and efficient website design and prototyping

## Boilerplates-样板

 * [html5-boilerplate](https://github.com/h5bp/html5-boilerplate) - A professional front-end template for building fast, robust, and adaptable web apps or sites.
 * [mobile-boilerplate](https://github.com/h5bp/mobile-boilerplate) - A front-end template that helps you build fast, modern mobile web apps.
 * [Cerberus](https://github.com/TedGoas/Cerberus) - A few simple, but solid patterns for responsive HTML emails. Even in Outlook.
 * [this-is-responsive](https://github.com/bradfrost/this-is-responsive) - This Is Responsive


## Gesture-手势

* [hammer.js](https://github.com/hammerjs/hammer.js) - A javascript library for multi-touch gestures.
* [Dragula](https://github.com/bevacqua/dragula/) - Drag and drop so simple it hurts


## Maps-地图

* [Leaflet](https://github.com/Leaflet/Leaflet) - JavaScript library for mobile-friendly interactive maps.
* [Cesium](https://github.com/AnalyticalGraphicsInc/cesium) - Open Source WebGL virtual globe and map engine.
* [gmaps](https://github.com/HPNeo/gmaps) - The easiest way to use Google Maps.
* [polymaps](https://github.com/simplegeo/polymaps) - A free JavaScript library for making dynamic, interactive maps in modern web browsers.
* [kartograph.js](https://github.com/kartograph/kartograph.js) - Open source JavaScript renderer for Kartograph SVG maps.
* [mapbox.js](https://github.com/mapbox/mapbox.js) - Mapbox JavaScript API, a Leaflet Plugin.
* [jqvmap](https://github.com/manifestinteractive/jqvmap) - jQuery Vector Map Library.
* [OpenLayers3](http://openlayers.org/) - A high-performance, feature-packed library for all your mapping needs.

## Video/Audio-视频/音频

 * [prettyembed.js](https://github.com/mike-zarandona/prettyembed.js) - Prettier embeds for your YouTubes - with nice options like high-res preview images, advanced customization of embed options, and optional FitVids support.
 * [html5media](https://github.com/etianen/html5media) -  Enables <video> and <audio> tags in all major browsers. <https://html5media.info/>
 * [flowplayer](https://github.com/flowplayer/flowplayer) -  The HTML5 video player for the web
 <https://flowplayer.org/>
 * [mediaelement](https://github.com/johndyer/mediaelement) -  HTML5 <audio> or <video> player with Flash and Silverlight shims that mimics the HTML5 MediaElement API, enabling a consistent UI in all browsers. <http://mediaelementjs.com/>
 * [SoundJS](https://github.com/CreateJS/SoundJS) - A library to make working with audio on the web easier. It provides a consistent API for playing audio in different browsers.
 * [video.js](https://github.com/videojs/video.js) - Video.js - open source HTML5 & Flash video player
 * [FitVids.js](https://github.com/davatron5000/FitVids.js) - A lightweight, easy-to-use jQuery plugin for fluid width video embeds.
 * [photobooth-js](https://github.com/WolframHempel/photobooth-js) - A widget that allows users to take their avatar pictures on your site
 * [clappr](https://github.com/clappr/clappr) - An extensible media player for the web http://clappr.io

## Typography-排版

 * [FlowType.JS](https://github.com/simplefocus/FlowType.JS) - Web typography at its finest: font-size and line-height based on element width.
 * [BigText](https://github.com/zachleat/BigText) - jQuery plugin, calculates the font-size and word-spacing needed to match a line of text to a specific width.
 * [slabText](https://github.com/freqDec/slabText/) - A jQuery plugin for producing big, bold & responsive headlines
 * [FitText.js](https://github.com/davatron5000/FitText.js) - A jQuery plugin for inflating web type
 * [Lettering.js](https://github.com/davatron5000/Lettering.js) - A lightweight, easy to use Javascript `<span>` injector for radical Web Typography


## Animations-动画

* [velocity](https://github.com/julianshapiro/velocity) - Accelerated JavaScript animation.
* [jquery.transit](https://github.com/rstacruz/jquery.transit) - Super-smooth CSS3 transformations and transitions for jQuery.
* [impress.js](https://github.com/impress/impress.js) - Make Prezi-like presentations with CSS3 transformations/transitions in an HTML document.
* [bounce.js](https://github.com/tictail/bounce.js) - Create tasty CSS3 powered animations in no time.
* [GreenSock-JS](https://github.com/greensock/GreenSock-JS) - High-performance HTML5 animations that work in all major browsers.
* [Dynamic.js](https://github.com/michaelvillar/dynamics.js) - Javascript library to create physics-based CSS animations.
* [Effeckt.css](https://github.com/h5bp/Effeckt.css) - A Performant Transitions and Animations Library
* [animate.css](https://github.com/daneden/animate.css) - A cross-browser library of CSS animations. As easy to use as an easy thing.
* [textillate](https://github.com/jschr/textillate) - A simple plugin for CSS3 text animations
* [move.js](https://github.com/visionmedia/move.js) - CSS3 backed JavaScript animation framework
* [animatable](https://github.com/LeaVerou/animatable) - One property, two values, endless possiblities
* [smoothState.js](https://github.com/miguel-perez/smoothState.js) - Unobtrusive page transitions with jQuery. http://smoothstate.com/

## Image Processing-图片处理

* [lena.js](https://github.com/davidsonfellipe/lena.js) - A Library for image processing with filters and util functions.
* [pica](https://github.com/nodeca/pica) - High quality image resize (with fast Lanczos filter, implemented in pure JS).
* [cropper](https://github.com/fengyuanchen/cropper) - A simple jQuery image cropping plugin.


## ES6-ES6

* [es6features](https://github.com/lukehoban/es6features) - Overview of ECMAScript 6 features.
* [es6-features](https://github.com/rse/es6-features) - ECMAScript 6: Feature Overview & Comparison.
* [es6-cheatsheet](https://github.com/DrkSephy/es6-cheatsheet) - ES2015 [ES6] cheatsheet containing tips, tricks, best practices and code snippets.
* [ECMAScript 6 compatibility table](http://kangax.github.io/compat-table/es6/) - Compatibility tables for all ECMAScript 6 features on a variety of environments.
* [Babel (Formerly 6to5)](https://github.com/babel/babel) - Turn ES6+ code into vanilla ES5 with no runtime.
* [Traceur compiler](https://github.com/google/traceur-compiler) - ES6 features > ES5. Includes classes, generators, promises, destructuring patterns, default parameters & more.


## SDK-SDK

* [javascript-sdk-design](https://github.com/huei90/javascript-sdk-design) - Javascript SDK design guide extracted from work and personal experience
* [Spotify SDK](https://github.com/loverajoel/spotify-sdk) - Entity oriented SDK to work with the Spotify Web API.


## Misc-杂项

* [echo](https://github.com/toddmotto/echo) - Lazy-loading images with data-* attributes.
* [picturefill](https://github.com/scottjehl/picturefill) - A responsive image polyfill for &lt;picture&gt;, srcset, sizes.
* [platform.js](https://github.com/bestiejs/platform.js) - A platform detection library that works on nearly all JavaScript platforms.
* [json3](https://github.com/bestiejs/json3) - A modern JSON implementation compatible with nearly all JavaScript platforms.
* [Logical Or Not](http://gabinaureche.com/logicalornot/) - A game about JavaScript specificities.
* [list.js](https://github.com/javve/list.js) -  Adds search, sort, filters and flexibility to tables, lists and various HTML elements. Built to be invisible and work on existing HTML.
http://www.listjs.com
* [mixitup](https://github.com/patrickkunka/mixitup) - MixItUp - A Filter & Sort Plugin
* [grid](https://github.com/hootsuite/grid) - Drag and drop library for two-dimensional, resizable and responsive lists.
* [jquery-match-height](https://github.com/liabru/jquery-match-height) - a responsive equal heights plugin for jQuery.
* [survey.js](https://github.com/surveyjs/surveyjs) - JavaScript Survey Engine. It uses JSON for survey metadata and results. http://surveyjs.org/
* [Array Explorer](https://github.com/sdras/array-explorer) and [Object Explorer](https://sdras.github.io/object-explorer/) - Resources to help figure out what native JavaScript method would be best to use at any given time

## Podcasts-播客
* [JavaScript Air](https://javascriptair.com/) - The live video broadcast podcast all about JavaScript and the Web platform.
* [Web of Tomorrow](http://www.weboftomorrowpodcast.com/) - Podcast about JavaScript for beginners.
* [Javascript Jabber](https://devchat.tv/js-jabber) - A weekly podcast about JavaScript, including Node.js, Front-End Technologies, Careers, Teams and more.

# Worth Reading-阅读
* [braziljs/js-the-right-way](https://github.com/braziljs/js-the-right-way/)
* [JSbooks](https://github.com/revolunet/JSbooks)
* [Superhero.js](http://superherojs.com) - A collection of resources about creating, testing and maintaining a large JavaScript code base.
* [SJSJ](https://github.com/HugoGiraudel/SJSJ) - Simplified JavaScript Jargon is a community-driven attempt at explaining the loads of buzzwords making the current JavaScript ecosystem in a few simple words.
* [How to Write an Open Source JavaScript Library](https://github.com/sarbbottam/write-an-open-source-js-lib) - A comprehensive guide through a set of steps to publish a JavaScript open source library.
* [Jaavascript tutorial](https://hackr.io/tutorials/learn-javascript) - Learn Javascript online from a diverse range of user ranked online tutorials.
