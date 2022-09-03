# Front-end technology list

> Last update: 2019/10/09 [What's new (diff) >>](https://github.com/alienzhou/frontend-tech-list/commit/9e73eb648cb1b7413ecca0c5fe3ebb81f4dea0fe?short_path=04c6e90#diff-04c6e90faac2675aa89e2176d2eec7d8)

Knowledge of learning articles is often fragmented. The front-end involves a wide range of areas. If this knowledge is not effectively sorted out, it cannot be connected to each other and form a system. Therefore, based on my work experience, I will abstract some basic front-end capabilities, and organize some good articles I have read and written to form a (pure) front-end technology list.

Whether you're teaching yourself front-end, or you're proficient in some front-end technologies but haven't yet, I hope this list will help you review some of the basic front-end capabilities.

- [0. annual report] (#0-annual report)
- [1. Basic Supplements] (#1-Basic Supplements)
  - [1.1.JavaScript](#11-javascript)
  - [1.2. CSS] (#12-css)
  - [1.3. browser] (#13-browser)
- [2. Engineering and Tools] (#2-Engineering and Tools)
  - [2.1.webpack](#21-webpack)
  - [2.2. Gulp] (#22-gulp)
  - [2.3. Linter](#23-linter)
  - [2.4. Static typing (Typescript/Flow)](#24-static typing typescriptflow)
  - [2.5. Babel] (#25-babel)
  - [2.6. CSS preprocessing and modularization] (#26-css preprocessing and modularization)
- [3. Performance optimization](#3-performance optimization)
  - [3.1. Loading performance] (#31-loading performance)
  - [3.2. runtime performance] (#32 - runtime performance)
  - [3.3. Frontend Cache] (#33 - Frontend Cache)
  - [3.4. Performance debugging and practice] (#34-performance debugging and practice)
  - [3.5. Performance metrics] (#35-performance metrics)
- [4. Security] (#4-Security)
  - [4.1. XSS] (#41-xss)
  - [4.2. CSRF] (#42-csrf)
  - [4.3. CSP] (#43-csp)
  - [4.4.HTTPS](#44-https)
  - [4.5. Security Record] (#45-Security Record)
  - [4.6. Code Protection] (#46-Code Protection)
  - [4.7. JS sandbox] (#47-js sandbox)
  - [4.8.Other](#48-Other)
- [5. Automated Tests] (#5 - Automated Tests)
  - [5.1. Unit tests] (#51-unit tests)
  - [5.2. End-to-end testing (E2E)] (#52-end-to-end-testing-e2e)
  - [5.3. other] (#53-other)
- [6. Framework and Class Library](#6-Framework and Class Library)
  - [6.1. React] (#61-react)
  - [6.2.Vue] (#62-vue)
  - [6.3. Redux] (#63-redux)
  - [6.4. RxJS] (#64-rxjs)
- [7. New Technology/Direction] (#7 - New Technology Orientation)
  - [7.1. PWA] (#71-pwa)
  - [7.2. CSS Houdini] (#72-css-houdini)
  - [7.3. Web Components](#73-web-components)
  - [7.4. Micro Frontends](#74-micro-frontends)
  - [7.5. HTTP/2] (#75-http2)
  - [7.6.WebAssembly](#76-webassembly)
  - [7.7. applet] (#77-applet)
  - [7.8.Serverless](#78-serverless)
- [8. Business related] (#8-Business related)
  - [8.1. Data management report](#81-Data management report)
  - [8.2. Front-end monitoring] (#82-Front-end monitoring)
  - [8.3. A/B testing] (#83-ab testing)
  - [8.4. "Server Push"](#84-Server Push)
  - [8.5. Animation] (#85-Animation)
- [9. other](#9-other)
## 0. Annual Report

- [2018 Frontend Tooling Survey Report](https://ashleynolan.co.uk/blog/frontend-tooling-survey-2018-results)
- [2018 JavaScript Survey Report](https://2018.stateofjs.com/)

## 1. Basic Supplements

> Review the old to learn the new, and learn from it if you don't know it, so as to strengthen the foundation.

### 1.1. JavaScript

- [You-Dont-Know-JS \[English\]](https://github.com/getify/You-Dont-Know-JS)
- JavaScript basic operating mechanism:
  - [JS Engine, Runtime and Call Stack Overview\[English\]](https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf)
  - [Introduction to V8 Engine\[English\]](https://blog.sessionstack.com/how-javascript-works-inside-the-v8-engine-5-tips-on-how-to-write-optimized- code-ac089e62b12e)
  - [Memory Management and Common Leaks in 4\[English\]](https://blog.sessionstack.com/how-javascript-works-memory-management-how-to-handle-4-common-memory-leaks -3f28b94cfbec)
- Event Loop (there is always a question about Event Loop in interviews…):
  - [Exploring JavaScript asynchrony and browser update rendering timing from the Event Loop specification](https://github.com/aooy/blog/issues/5)
  - [Event Loop of Async \[English\]](https://blog.sessionstack.com/how-javascript-works-event-loop-and-the-rise-of-async-programming-5-ways-to -better-coding-with-2f077c4438b5)
  - [Event Loop, Timers and `process.nextTick()` in NodeJS \[English\]](https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/)
  - [Tasks, Microtasks, Queues and Schedules \[English\]](https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/)
- [Web Workers and 5 Common Use Cases\[English\]](https://blog.sessionstack.com/how-javascript-works-the-building-blocks-of-web-workers-5-cases- when-you-should-use-them-a547c0757f6a)
- [How to avoid async/await hell \[English\]](https://medium.freecodecamp.org/avoiding-the-async-await-hell-c77a0fb71c4c)
- [Summary of Solutions to "Callback Hell"](https://www.jianshu.com/p/bc7b8d542dcd)

### 1.2. CSS

- [You-Need-to-Know-CSS](https://lhammer.cn/You-need-to-know-css/#/)
- [CSSOM and its related browser API usage guide \[English\]](https://css-tricks.com/an-introduction-and-guide-to-the-css-object-model-cssom/)
- [CSS Layout Guidelines](https://juejin.im/post/5b3b56a1e51d4519646204bb)
- [Various line breaks in CSS\[English\]](https://css-tricks.com/where-lines-break-is-complicated-heres-all-the-related-css-and-html /): handles the classic newline problem
- [What should I do if there is a precision error when the browser converts rem to px? ](https://www.zhihu.com/question/264372456)
- [Precisely controlled scrolling experience, on the new standard Scroll Snap](https://juejin.im/post/5ba079e86fb9a05d1227fddb)
- [How to implement a button that is not a `button` element perfectly \[English\]](https://www.scottohara.me/blog/2018/10/03/unbutton-buttons.html)
- [Use CSS Grid to create horizontal scrolling containers\[English\]](https://uxdesign.cc/creating-horizontal-scrolling-containers-the-right-way-css-grid-c256f64fc585)
- [How to deal with gaps in inline elements \[English\]](https://css-tricks.com/fighting-the-space-between-inline-block-elements/)
- [Those little-known pits in CSS Stacking Context](https://segmentfault.com/a/1190000002783265)
- [4½ Ways to Implement Theme Functionality in (S)CSS](https://juejin.im/post/5c0feb3bf265da616d5409a5)

### 1.3. Browser

- [How browsers work](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)
- How modern browsers work internally:
  - [Chrome browser overview](https://developers.google.com/web/updates/2018/09/inside-browser-part1)
  - [What happened while browsing? ](https://developers.google.com/web/updates/2018/09/inside-browser-part2)
  - [Inner workings of the rendering process](https://developers.google.com/web/updates/2018/09/inside-browser-part3)
  - [How does the compositor improve interactive performance? ](https://developers.google.com/web/updates/2018/09/inside-browser-part4)
- [Complete Introduction to Page Lifecycle API\[English\]](https://developers.google.com/web/updates/2018/07/page-lifecycle-api)
- [Four new observers: Intersection / Mutation / Resize / Performance (Observer)](https://www.zeolearn.com/magazine/different-types-of-observers-supported-by-modern-browsers)
- [How the rendering engine works and optimization suggestions\[English\]](https://blog.sessionstack.com/how-javascript-works-the-rendering-engine-and-tips-to-optimize-its-performance- 7b95553baeda)
- [Browser Kernel Rendering: Rebuild Engine](https://juejin.im/post/5bbaa7da6fb9a05d3761aafe)
- [Cross-domain solution summary](https://www.jianshu.com/p/438183ddcea8)

## 2. Engineering and Tools

> The expansion of software scale brings the need for engineering, and the front end is no exception. With the advent of NodeJS, front-end engineers can use the familiar JS tools they need for rapid development. The prosperity of the tool chain ecology is also a portrayal of the prosperity of the front-end circle.

### 2.1. webpack

- [The Chunk graph algorithm in webpack\[English\]](https://medium.com/webpack/the-chunk-graph-algorithm-week-26-29-7c88aa5e4b4e)
- [Webpack Advanced Series](https://juejin.im/post/5bc1a73df265da0a8d36b74f#heading-13)
- Compile optimization:
  - [How to improve webpack performance in large projects 🎥 \[English\]](https://www.youtube.com/watch?v=AifDI71uqF0)
  - [Runtime optimization: Separating a Manifest \[English\]](https://survivejs.com/webpack/optimizing/separating-manifest)
  - [Use \<link rel=”prefetch/preload”> in webpack \[English\]](https://medium.com/webpack/link-rel-prefetch-preload-in-webpack-51a52358f84c)
  - [How to better use webpack tree-shaking](https://juejin.im/post/5b8ce49df265da438151b468)
- Discussion on webpack compilation cache:
  - [mzgoddard's comment](https://github.com/webpack/webpack/issues/250#issuecomment-240643985)
  - [\[spec: webpack 5\] - A module disk cache between build processes](https://github.com/webpack/webpack/issues/6527)

### 2.2. Gulp

- [Gulp 4 Introduction \[English\]](https://fettblog.eu/gulp-4-parallel-and-series/)
- [Gulp-based multi-page application practice guide](https://www.jianshu.com/p/35571124770f)
### 2.3. Linter

- [JS Linter Evolutionary History](https://zhuanlan.zhihu.com/p/34656263)
- [Why use ESLint in your project summary \[English\]](https://medium.com/the-node-js-collection/why-and-how-to-use-eslint-in-your-project- 742d0bc61ed7)

### 2.4. Static typing (Typescript/Flow)

- [Typescript Overall Architecture\[English\]](https://github.com/Microsoft/TypeScript/wiki/Architectural-Overview)
- Why static type checking in JavaScript:
  - [Part 1](https://www.jianshu.com/p/bda750e2d15e)
  - [Parts II and III](https://www.jianshu.com/p/289b3c734a9f)
  - [Part IV](https://www.jianshu.com/p/d23f93be8821)

### 2.5. Babel

- [Babel User Manual](https://github.com/jamiebuilds/babel-handbook/blob/master/translations/zh-Hans/user-handbook.md)
- [Babel Plugin Handbook](https://github.com/jamiebuilds/babel-handbook/blob/master/translations/zh-Hans/plugin-handbook.md)
- [How to implement your custom JS syntax with Babel](https://lihautan.com/creating-custom-javascript-syntax-with-babel/)

### 2.6. CSS Preprocessing and Modularization

- [CSS Evolution History\[English\]](https://medium.com/@perezpriego7/css-evolution-from-css-sass-bem-css-modules-to-styled-components-d4c1da3a659b)
- [CSS Modular Solution Series](https://juejin.im/post/5b20e8e0e51d4506c60e47f5)

## 3. Performance optimization

> Performance optimization is actually "according to local conditions" on the basis of understanding the browser, so it can be understood in conjunction with the "Browser" section in Section 1.3.

It is highly recommended to read all the articles in the [Google Web Performance Optimization](https://developers.google.com/web/fundamentals/performance/why-performance-matters/) Tab, which basically covers modern browsers. All points of performance optimization. The author also sorted out a ["Front-end Performance Optimization Guide 🚀"](https://alienzhou.github.io/fe-performance-journey/), which can help you systematically understand and learn front-end performance optimization.

Below are excerpts of some of the articles that I personally think are very good.

### 3.1. Loading performance

- [PRPL pattern \[English\]](https://developers.google.com/web/fundamentals/performance/prpl-pattern/)
- [The Complete Guide to Lazy Loading Images \[English\]](https://css-tricks.com/the-complete-guide-to-lazy-loading-images)
- [Lazy loading images using Intersection Observer\[English\]](http://deanhume.com/lazy-loading-images-using-intersection-observer/)
- [Detailed guide to lazy loading of images and videos \[English\]](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
- [Using the Application Shell architecture to implement the app \[English\]](https://developers.google.com/web/updates/2015/11/app-shell)

### 3.2. Runtime performance

- [Avoid large, complex layouts and layout thrashing\[English\]](https://developers.google.com/web/fundamentals/performance/rendering/avoid-large-complex-layouts-and-layout-thrashing? hl=en-us#avoid-forced-synchronous-layouts)
- [What causes forced sync layout (reflow)? \[English\]](https://gist.github.com/paulirish/5d52fb081b3570c81e3a)
- [How to diagnose forced synchronous layouts\[English\]](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/forced-synchronous-layouts?hl=en-us)
- [Wireless Performance Optimization: Composite](http://taobaofed.org/blog/2016/04/25/performance-composite/)
- [How to unscrupulously improve the performance of scroll events](https://zhuanlan.zhihu.com/p/30078937)
- [Use passive event listener to improve scrolling fluidity\[English\]](https://github.com/WICG/EventListenerOptions/blob/gh-pages/explainer.md)
- throttle & debounce
  - [JavaScript function throttling and function debounce application scenario analysis](https://github.com/hanzichi/underscore-analysis/issues/20)
  - [Implementation of underscore function debounce](https://github.com/hanzichi/underscore-analysis/issues/21)
- requestIdleCallback
  - [Getting started with requestIdleCallback\[English\]](https://developers.google.com/web/updates/2015/08/using-requestidlecallback)
  - [Idle Until Urgent \[English\]](https://philipwalton.com/articles/idle-until-urgent): The magic of requestIdleCallback

### 3.3. Frontend Cache

- [Introduction to Web Caching: An Example of Buying Milk \[English\]](https://dev.to/kbk0125/web-caching-explained-by-buying-milk-at-the-supermarket-9k4)
- [Atale of Four-caches\[English\]](https://calendar.perfplanet.com/2016/a-tale-of-four-caches/)
- [Cache (1) - Cache Overview: Cache from the Perspective of Performance Optimization](https://github.com/amandakelake/blog/issues/43)
- [Cache (2) - Browser caching mechanism: strong cache, negotiation cache](https://github.com/amandakelake/blog/issues/41)
- [Cache (3) - Data storage: cookie, Storage, indexedDB](https://github.com/amandakelake/blog/issues/13)

### 3.4. Performance debugging and practice

- [Improve page speed with Chrome DevTools \[English\]](https://developers.google.com/web/tools/chrome-devtools/speed/get-started): Practical explanation of Chrome DevTools
- [Understanding Resource Timing in DevTools](https://developers.google.com/web/tools/chrome-devtools/network-performance/understanding-resource-timing)
- [Taobao New Force Week H5 Performance Optimization Practice](https://segmentfault.com/a/1190000014359615)
- [Optimize packaging strategy to improve page loading speed](https://juejin.im/post/5aed037b6fb9a07aa047e1e1)
- [Debugging skills you may not know in Chrome DevTools](https://zhuanlan.zhihu.com/p/42059158)
- [Front-end performance measurement \[English\]](https://speedcurve.com/blog/user-timing-and-custom-metrics/)

### 3.5. Performance Metrics

- [User-centric front-end performance metrics \[English\]](https://developers.google.com/web/fundamentals/performance/user-centric-performance-metrics): The ins and outs of front-end performance metrics
- DOMContentLoaded:
  - [DOMContentLoaded you don't know](https://zhuanlan.zhihu.com/p/25876048)
  - [Deciphering the Critical Rendering Path \[English\]](https://calendar.perfplanet.com/2012/deciphering-the-critical-rendering-path/)
- FP (First Paint):
  - [First Paint for Chrome](http://eux.baidu.com/blog/fe/Chrome%E7%9A%84First%20Paint)
- FCP (First Contentful Paint):
  - [First Contentful Paint Explained \[English\]](https://gtmetrix.com/blog/first-contentful-paint-explained/)
  - [First Contentful Paint \[English\]](https://developers.google.com/web/tools/lighthouse/audits/first-contentful-paint)
- FMP (First Meaningful Paint):
  - [First Meaningful Paint in Chrome](https://juejin.im/entry/598080226fb9a03c5d535cd5)
  - [Time to First Meaningful Paint](https://docs.google.com/document/d/1BR94tJdZLsin5poeet0XoTW60M0SjvOJQttKT-JK8HI/view?hl=zh-cn#heading=h.k50nnyhtptq0)
- TTI (Time to interactive):
  - [Time to Interactive Explainer](https://github.com/WICG/time-to-interactive)
  - [A new standard for measuring user experience](https://calendar.perfplanet.com/2017/time-to-interactive-measuring-more-of-the-user-experience/)
- TTFB (Time To First Byte):
  - [TTFB, and the time node of page loading](https://zhuanlan.zhihu.com/p/23588780)
- FID (First Input Delay):
  - [First Input Delay](https://developers.google.com/web/updates/2018/05/first-input-delay)
- Speed ​​Index:
  - [WebPagetest: Speed ​​Index](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index)

## 4. Safety

> Many security risks are clichéd, but they are often not taken seriously or realized until a problem occurs.

- [Eight Front-End Security Problems Part 1](https://insights.thoughtworks.cn/eight-security-problems-in-front-end/)
- [Eight Front-End Security Problems Part 2](http://insights.thoughtworks.cn/eight-security-problems-in-front-end-2/)
- [Concept Explained: Encoding, Encryption, Hashing and Obfuscation \[English\]](https://danielmiessler.com/study/encoding-encryption-hashing-obfuscation)
- [Summary of Common Web Security Attacks and Defenses](https://zoumiaojiang.com/article/common-web-security/)

### 4.1. XSS

- [How to prevent XSS attack? ](https://tech.meituan.com/fe_security.html)

### 4.2. CSRF

- [How to prevent CSRF attack? ](https://juejin.im/post/5bc009996fb9a05d0a055192)
- [Site Isolation \[English\]](https://developers.google.com/web/updates/2018/07/site-isolation): New features in Chrome

### 4.3. CSP

- [Introduction to Content Security Policy](http://www.ruanyifeng.com/blog/2016/09/csp.html)
- [Content Security Policy (CSP) \[English\]](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP)

### 4.4. HTTPS

- [The principle of image and text restoration HTTPS](https://mp.weixin.qq.com/s/3NKOCOeIUF2SGJnY7II9hA)
- [A brief discussion on the promotion of HTTPS throughout the site](https://segmentfault.com/a/1190000013635363)

### 4.5. Safety record

- [About `rel=noopener` \[English\]](https://mathiasbynens.github.io/rel-noopener/): How opening a new page is a security risk
- [A new type of "fishing" method \[English\]](http://www.azarask.in/blog/post/a-new-type-of-phishing-attack/)
- [Cross-site risk caused by a media file request \[English\]](https://jakearchibald.com/2018/i-discovered-a-browser-bug)
- [Mitigating Spectre \[English\]](https://security.googleblog.com/2018/07/mitigating-spectre-with-site-isolation.html): Cross-Site Security Issues in Chrome
### 4.6. Code Protection

- [JavaScript Obfuscation Security Hardening](https://segmentfault.com/a/1190000019423501)
- [Front-end core code protection technology aspects] (https://zhuanlan.zhihu.com/p/61651310)

### 4.7. JS Sandbox

- [How to Implement a Plugin System on the Web\[English\]](https://www.figma.com/blog/how-we-built-the-figma-plugin-system/)
- [How to Safely Run User's JavaScript Script](https://zhuanlan.zhihu.com/p/46571509)

### 4.8. Others

- [Some security-related HTTP response headers](https://imququ.com/post/web-security-and-response-header.html)

## 5. Automated testing

> Automated testing is one of the important parts of software engineering, but it is easily overlooked.

- [2018 Front-end Automated Testing Overview \[English\]](https://medium.com/welldone-software/an-overview-of-javascript-testing-in-2018-f68950900bc3)
- [Testing your front-end code (introduction)\[English\]](https://hackernoon.com/testing-your-frontend-code-part-i-introduction-7e307eac4446)

### 5.1. Unit Testing

- [Test your front-end code (unit testing)\[English\]](https://hackernoon.com/testing-your-frontend-code-part-ii-unit-testing-1d05f8d50859)
- [Fakes, Mocks and Stubs are clearly defined](https://zhuanlan.zhihu.com/p/26942686)
- [What is the use of test coverage (rate)? ](http://www.infoq.com/cn/articles/test-coverage-rate-role)

### 5.2. End-to-End Testing (E2E)

- [Test your frontend code (E2E test)\[English\]](https://hackernoon.com/testing-your-frontend-code-part-iii-e2e-testing-e9261b56475)
- [What is a good E2E test? \[English\]](https://testing.googleblog.com/2016/09/testing-on-toilet-what-makes-good-end.html)
- [Balancing unit tests and end-to-end tests](http://www.infoq.com/cn/articles/balancing-unit-and-end-to-end-tests)
- [Say "no" to too many E2E tests \[English\]](https://testing.googleblog.com/2015/04/just-say-no-to-more-end-to-end-tests .html)

### 5.3. Others

- [Test your front-end code (integration test)\[English\]](https://hackernoon.com/testing-your-frontend-code-part-iv-integration-testing-f1f4609dc4d9)
- [Test your frontend code (visual testing)\[English\]](https://medium.com/@giltayar/testing-your-frontend-code-part-v-visual-testing-935864cfb5c7)
- [Introduction to Property Based Testing \[English\]](https://medium.com/criteo-labs/introduction-to-property-based-testing-f5236229d237)

## 6. Frameworks and Class Libraries

> If basic knowledge is Tao, then frameworks and tools may be art; learn and understand them, but never become their slaves.

### 6.1. React

- [Teach you how to implement a simple React \[English\]](https://engineering.hexacta.com/didact-learning-how-react-works-by-building-it-from-scratch-51007984e5c5)
- [Under the hood of React \[English\]](https://bogdan-lyashenko.github.io/Under-the-hood-ReactJS/)
- [React details you need to know](https://github.com/hateonion/react-bits-CN)
- [React Fiber Architecture](https://zhuanlan.zhihu.com/p/37095662)
- [React 16 Fiber source code overview](http://zxc0328.github.io/2017/09/28/react-16-source/)
- [How React is Made](https://segmentfault.com/a/1190000013365426): The evolutionary path of React in the early days
- Implementing a React from scratch:
  - [1. JSX and virtual DOM](https://github.com/hujiulong/blog/issues/4)
  - [2. Components and Lifecycle](https://github.com/hujiulong/blog/issues/5)
  - [3. diff algorithm](https://github.com/hujiulong/blog/issues/6)
  - [4. Asynchronous setState](https://github.com/hujiulong/blog/issues/7)
- [Quick Start of "React Technology Stack" Single-Page Application Practice](https://www.jianshu.com/p/0b2acb50f321)
- [React Lifecycle Diagram](http://projects.wojtekmaj.pl/react-lifecycle-methods-diagram/)

### 6.2. Vue

- [In-depth explanation - vue change detection principle](https://github.com/berwin/Blog/issues/17)
- [Vue template compilation principle](https://github.com/berwin/Blog/issues/18)

### 6.3. Redux

- [Redesigning Redux \[English\]](https://hackernoon.com/redesigning-redux-b2baee8b8a38): Rematch
- [How to replace Redux with GraphQL \[English\]](https://hackernoon.com/how-graphql-replaces-redux-3fff8289221d)
- [Interpretation of the design ideas and usage of Redux](https://div.io/topic/1309)
- [(Redux) The Three Principles of Application Building \[English\]](https://jaysoo.ca/2016/02/28/organizing-redux-application/#rule-1-organize-by-feature)
- [React-Redux development history and implementation \[English\]](https://blog.isquaredsoftware.com/2018/11/react-redux-history-implementation/)

### 6.4. RxJS

- [ReactiveX official website](http://reactivex.io/): The gem map is really very vivid and easy to read
- [Reactive programming is a wise choice](https://www.cnblogs.com/android-blogs/p/5586395.html)
- [Graphic RxJS \[English\]](https://blog.angularindepth.com/learn-to-combine-rxjs-sequences-with-super-intuitive-interactive-diagrams-20fce8e6511)
- [Debugging RxJS: Tooling \[English\]](https://blog.angularindepth.com/debugging-rxjs-4f0340286dd3)
- [Debugging RxJS: Logging \[English\]](https://blog.angularindepth.com/debugging-rxjs-part-2-logging-56904459f144)

## 7. New technologies/directions

> New technologies and new directions in the front-end field are emerging one after another. Here are some new technology directions; as a developer, you need to know more but don’t blindly follow

### 7.1. PWAs

- [PWA Learning and Practice Series](https://juejin.im/post/5ac8a67c5188255c5668b0b8#heading-3)
- [Introduction to Service Workers\[English\]](https://medium.freecodecamp.org/service-workers-the-little-heroes-behind-progressive-web-apps-431cc22d0f16)
- [PWA Special Issues on iOS Platform\[English\]](https://medium.com/@firt/pwas-are-coming-to-ios-11-3-cupertino-we-have-a- problem-2ff49fd7d6ea)
- [Use iOS meta tags carefully in your PWA\[English\]](https://medium.com/@firt/dont-use-ios-web-app-meta-tag-irresponsibly-in-your -progressive-web-apps-85d70f4438cb)
- [Ele.me's PWA upgrade practice](https://medium.com/elemefe/upgrading-ele-me-to-progressive-web-app-2a446832e509)
- [Offline Guide](https://developers.google.com/web/fundamentals/instant-and-offline/offline-cookbook/)
- [WebAPKs in Android \[English\]](https://developers.google.cn/web/fundamentals/integration/webapks?hl=en-us)
- [Pinterest's PWA Practice \[English\]](https://medium.com/@Pinterest_Engineering/a-one-year-pwa-retrospective-f4a2f4129e05)
- [Asynchronous HTTP Cookies API \[English\]](https://developers.google.com/web/updates/2018/09/asynchronous-access-to-http-cookies): Enable Service Worker

### 7.2. CSS Houdini

- [Meet Houdini and the CSS Paint API \[English\]](https://codersblock.com/blog/say-hello-to-houdini-and-the-css-paint-api/)
- [Save CSS Polyfill with Houdini \[English\]](https://philipwalton.com/articles/the-dark-side-of-polyfilling-css/)

### 7.3. Web Components

- [Basic Concepts and Usage of Web Components](https://developer.mozilla.org/zh-CN/docs/Web/Web_Components)
- [Web Components Guide \[English\]](https://css-tricks.com/modular-future-web-components/)
- [Introduction to Shadow DOM usage](http://web.jobbole.com/87088/)
- [The Story of HTMLUnknownElement and HTML5 Custom Elements](http://www.zhangxinxu.com/wordpress/2018/03/htmlunknownelement-html5-custom-elements/)

### 7.4. Micro Frontends

- [Micro-frontends homepage \[English\]](https://micro-frontends.org/)
- [Those things about micro frontend](https://microfrontend.cn/)
- [Technology Radar "Micro Front-end" - Extending the concept of micro-services to front-end development] (https://zhuanlan.zhihu.com/p/32378432)

### 7.5. HTTP/2

- [HTTP/2 Under the Hood](https://www.ibm.com/developerworks/cn/web/wa-http2-under-the-hood/index.html)
- [Full Introduction to HTTP/2 \[English\]](https://hpbn.co/http2/)
- [HTTP/2 Homepage](https://http2.github.io/):
  - [HTTP/2 Protocol \[English\]](https://httpwg.org/specs/rfc7540.html)
  - [HPACK: HTTP/2 Header Compression \[English\]](https://httpwg.org/specs/rfc7541.html)

### 7.6. WebAssembly

- [WebAssembly official website](https://webassembly.org/)
- [WebAssembly Status and Reality](https://www.ibm.com/developerworks/cn/web/wa-lo-webassembly-status-and-reality/index.html)
- WebAssembly family:
  - [1. A vivid introduction to WebAssembly](https://segmentfault.com/a/1190000008714589)
  - [2. How JavaScript Just-in-time (JIT) works](https://segmentfault.com/a/1190000008632441)
  - [3. How the compiler generates assembly](https://segmentfault.com/a/1190000008664761)
  - [4. How WebAssembly works](https://segmentfault.com/a/1190000008686643)
  - [V. Why is WebAssembly faster? ](https://segmentfault.com/a/1190000008699213)
  - [6. The present and future of WebAssembly](https://segmentfault.com/a/1190000008714515)

### 7.7. Mini Programs

- [WeChat, Alipay Mini Program Implementation Principle Overview](https://segmentfault.com/a/1190000018631528)
- [Principles and some thoughts on the underlying implementation of small programs](https://github.com/berwin/Blog/issues/43)

### 7.8. Serverless

- [What does Serverless bring to the front end](https://zhuanlan.zhihu.com/p/58877583)
- [Upgrade of Taobao's front-end R&D model based on Serverless](https://www.infoq.cn/article/KFNcm7Pbq*eIV2dQIpRX)
- [Serverless, a technology that will bring great changes to front-end development? ](https://mp.weixin.qq.com/s/ooX7uMFjxFfSai9URo6kYw)
- [Why Netflix Rolled Its Own Node.js Functions-as-a-Service for its API Platform](https://thenewstack.io/why-netflix-rolled-its-own-node-js-functions-as-a -service-runtime?utm_source=mybridge&utm_medium=blog&utm_campaign=read_more)
## 8. Business related

> There are often some "business-independent" scenario requirements in business - almost any business will encounter them; therefore, in the process of change and change, we need to abstract these problems even more.

### 8.1. Data management report

- [How to accurately count the length of stay on the page](https://techblog.toutiao.com/2018/06/05/ru-he-jing-que-tong-ji-ye-mian-ting-liu-shi-chang/ )
- [Unveil the mystery of JS non-buried point technology](http://unclechen.github.io/2018/06/24/%E6%8F%AD%E5%BC%80JS%E6%97%A0%E5 %9F%8B%E7%82%B9%E6%8A%80%E6%9C%AF%E7%9A%84%E7%A5%9E%E7%A7%98%E9%9D%A2%E7%BA %B1/)

### 8.2. Front-end monitoring

- [Frontend Exception Monitoring Solution Research](https://cdc.tencent.com/2018/09/13/frontend-exception-monitor-research/)
- [Monitoring Platform Front-End SDK Development Practice](https://tech.meituan.com/hunt_sdk_practice.html)
- [Make front-end monitoring the ultimate](https://zhuanlan.zhihu.com/p/32262716)
- [Summary of front-end monitoring system exploration](https://juejin.im/post/5a3e121451882533f01ec66d)
- [60-day rapid self-research-build front-end buried point monitoring system](https://juejin.im/post/5d8d9eeaf265da5b783ef45c)

### 8.3. A/B testing

- Twitter's A/B testing practices:
  - [1. Why test and the significance of testing](http://www.infoq.com/cn/articles/twitter-ab-test-practise-part01)
  - [2. Technical overview](http://www.infoq.com/cn/articles/twitter-ab-test-practise-part02)
  - [3. Detecting and Avoiding Bucket Imbalance in A/B Test](http://www.infoq.com/cn/articles/twitter-ab-test-practise-part03)
  - [IV. Enlightenment of using multiple controls in A/B Test](http://www.infoq.com/cn/articles/twitter-ab-test-practise-part04)
- [Netflix A/B Test Experimentation Platform Practice \[English\]](https://medium.com/netflix-techblog/its-all-a-bout-testing-the-netflix-experimentation-platform-4e1ca458c15)
- Guidance method
  - [Seven kinds of problems that are easily encountered in experiments \[English\]](https://www.exp-platform.com/Documents/2009-ExPpitfalls.pdf)
  - [Seven Rules for Experiments\[English\]](https://www.exp-platform.com/Documents/2014%20experimentersRulesOfThumb.pdf)
  - [How to conduct AB test with small traffic](https://www.jianshu.com/p/3ab537f16b81)
- Case Studies
  - [Dianping AB testing framework Gemini](https://www.csdn.net/article/2015-03-24/2824303)
  - [Sina News Client AB Test and Grayscale Release](https://segmentfault.com/a/1190000012377139)
  - [Tmall App A/B Testing Practice](http://www.infoq.com/cn/articles/tmall-app-ab-test)
- tool
  - [AB Test Sample Size Calculator](https://www.eyeofcloud.com/124.html)
  - [AB Test Result Validity Analysis Tool](https://www.eyeofcloud.com/126.html)

### 8.4. "Server Push"

- [Principles and Examples of Various "Server Push" Techniques](https://juejin.im/post/5b135b78f265da6e420eab7d)
- [Comparison of mainstream server push technologies such as long connection/websocket/SSE](https://zhuanlan.zhihu.com/p/31297574)
- [Comet: "Server Push" Technology Based on HTTP Long Connection](https://www.ibm.com/developerworks/cn/web/wa-lo-comet/)
- [Dive into WebSockets, HTTP/2 SSE \[English\]](https://blog.sessionstack.com/how-javascript-works-deep-dive-into-websockets-and-http-2-with-sse- how-to-pick-the-right-path-584e6b8e3bf7)
- [Analysis of WebSocket Application Security Issues](https://security.tencent.com/index.php/blog/msg/119)

### 8.5. Animation

- [12 Principles of Animation Design 🎥 \[English\]](https://www.youtube.com/watch?v=uDqjIdI4bF4)
- [Bezier Curve Literacy](http://www.html-js.com/article/1628)
- [Animation: From AE to Web](https://aotu.io/notes/2018/03/06/ae2web/)
- The most complete and best use of the dynamic landing method:
  - [Basic knowledge](https://zhuanlan.zhihu.com/p/34501702)
  - [Landing method](https://zhuanlan.zhihu.com/p/34815524)

## 9. Others

> Unwinding is beneficial.

- [Recursion? We don't need no stinking recursion!](http://raganwald.com/2018/05/20/we-dont-need-no-stinking-recursion.html): How to change some recursion to cycle
- [Turning your web traffic into a Super Computer](https://ben.akrin.com/?p=5997): Connect computers all over the world into a supercomputer through Web Worker and WebSocket
- [Designing very large (JavaScript) applications](https://medium.com/@cramforce/designing-very-large-javascript-applications-6e013a3291a3): high-rise
- [Building a professional design tool on the web](https://www.figma.com/blog/building-a-professional-design-tool-on-the-web/): How to use web technologies to create a design /render system
- [Crafting Interpreters](https://craftinginterpreters.com/): details how to implement an interpreter
