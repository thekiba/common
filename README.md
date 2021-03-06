# ![logo](logo.svg) Common utils for Web APIs

> Part of <img src="web-api.svg" align="top"> [Web APIs for Angular](https://ng-web-apis.github.io/)

[![npm version](https://img.shields.io/npm/v/@ng-web-apis/common.svg)](https://npmjs.com/package/@ng-web-apis/common)
[![npm bundle size](https://img.shields.io/bundlephobia/minzip/@ng-web-apis/common)](https://bundlephobia.com/result?p=@ng-web-apis/common)
[![Travis (.org)](https://img.shields.io/travis/ng-web-apis/common)](https://travis-ci.org/ng-web-apis/common)
[![Coveralls github](https://img.shields.io/coveralls/github/ng-web-apis/common)](https://coveralls.io/github/ng-web-apis/common?branch=master)

A set of common utils for consuming Web APIs with Angular

## Tokens

-   `WINDOW` — provides access to global `window` object
-   `NAVIGATOR` — provides access to `window.navigator` object
-   `USER_AGENT` — provides access to `window.navigator.userAgent` string
-   `PERFORMANCE` — provides access to `window.performance` object
-   `ANIMATION_FRAME` — shared Observable based on `window.requestAnimationFrame`
-   `CSS` — provides access to `window.CSS` object or mock object if it's not available (i.e. in IE)
-   `LOCATION` — provides access to `window.location` object
-   `LOCAL_STORAGE` — provides access to `window.localStorage` object
-   `SESSION_STORAGE` — provides access to `window.sessionStorage` object
-   `PAGE_VISIBILITY` — wrapper for `document.addEventListener('visibilityChange')` api
