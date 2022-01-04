<p align="center">
  <a href="https://boosted.orange.com/">
    <img src="https://boosted.orange.com/docs/5.1/assets/brand/orange-logo.svg" alt="Boosted" width="50" height="50">
  </a>
</p>

<h3 align="center">Boosted</h3>

<p align="center">
  Boosted is a fork of Bootstrap. Bootstrap is a sleek, intuitive, and powerful front-end framework for faster and easier web development.
  <br>
  <a href="https://boosted.orange.com/docs/5.1/"><strong>Visit Boosted</strong></a>
  <br>
  <br>
  <a href="https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/issues/new?assignees=-&labels=bug&template=bug_report.yml">Report bug</a>
  ·
  <a href="https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/issues/new?assignees=&labels=feature&template=feature_request.yml">Request feature</a>
</p>


## Table of contents

- [Quick start](#quick-start)
- [Status](#status)
- [What's included](#whats-included)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Versioning](#versioning)
- [Creators](#creators)
- [Thanks](#thanks)
- [Copyright and license](#copyright-and-license)


## Quick start

Several quick start options are available:

- [Download the latest release](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/archive/v5.1.3.zip)
- Clone the repo: `git clone https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap.git`
- Install with [npm](https://www.npmjs.com/): `npm install boosted`
- Install with [yarn](https://yarnpkg.com/): `yarn add boosted`
- Install with [Composer](https://getcomposer.org/): `composer require Orange-OpenSource/Orange-Boosted-Bootstrap:5.1.3`
- Install with [NuGet](https://www.nuget.org/): CSS: `Install-Package boosted` Sass: `Install-Package boosted.sass`

Read the [Getting started page](https://boosted.orange.com/docs/5.1/getting-started/introduction/) for information on the framework contents, templates, examples, and more.


## Status

[![Build Status](https://img.shields.io/github/workflow/status/Orange-OpenSource/Orange-Boosted-Bootstrap/JS%20Tests/main?label=JS%20Tests&logo=github)](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/actions?query=workflow%3AJS+Tests+branch%3Amain)
[![This project is using Percy.io for visual regression testing.](https://percy.io/static/images/percy-badge.svg)](https://percy.io/Boosted/Boosted)
[![npm version](https://img.shields.io/npm/v/boosted)](https://www.npmjs.com/package/boosted)
[![Packagist Prerelease](https://img.shields.io/packagist/vpre/Orange-OpenSource/Orange-Boosted-Bootstrap.svg)](https://packagist.org/packages/Orange-OpenSource/Orange-Boosted-Bootstrap)
[![NuGet](https://img.shields.io/nuget/vpre/boosted)](https://www.nuget.org/packages/boosted/absoluteLatest)
[![CSS gzip size](https://img.badgesize.io/Orange-OpenSource/Orange-Boosted-Bootstrap/main/dist/css/boosted.min.css?compression=gzip&label=CSS%20gzip%20size)](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/blob/main/dist/css/boosted.min.css)
[![CSS Brotli size](https://img.badgesize.io/Orange-OpenSource/Orange-Boosted-Bootstrap/main/dist/css/boosted.min.css?compression=brotli&label=CSS%20Brotli%20size)](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/blob/main/dist/css/boosted.min.css)
[![JS gzip size](https://img.badgesize.io/Orange-OpenSource/Orange-Boosted-Bootstrap/main/dist/js/boosted.min.js?compression=gzip&label=JS%20gzip%20size)](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/blob/main/dist/js/boosted.min.js)
[![JS Brotli size](https://img.badgesize.io/Orange-OpenSource/Orange-Boosted-Bootstrap/main/dist/js/boosted.min.js?compression=brotli&label=JS%20Brotli%20size)](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/blob/main/dist/js/boosted.min.js)
[![BrowserStack Status](https://automate.browserstack.com/badge.svg?badge_key=ZGR2VnBvQ1F6ajhoNDIwWEF3Wm1RcjJlak1rdFZpRXJSdFZjTjJxQU9udz0tLU5wS2lrODNRTkswdzZZVUxjSHFpTHc9PQ==--714e60c953cf25bd52082a2b494eb881db1736c0)](https://automate.browserstack.com/public-build/ZGR2VnBvQ1F6ajhoNDIwWEF3Wm1RcjJlak1rdFZpRXJSdFZjTjJxQU9udz0tLU5wS2lrODNRTkswdzZZVUxjSHFpTHc9PQ==--714e60c953cf25bd52082a2b494eb881db1736c0)
[![JS Delivr](https://data.jsdelivr.com/v1/package/npm/boosted/badge)](https://www.jsdelivr.com/package/npm/boosted)

## What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations.

<details><summary>Download contents</summary>

```text
boosted/
├── css/
│   ├── boosted-grid.css
│   ├── boosted-grid.css.map
│   ├── boosted-grid.min.css
│   ├── boosted-grid.min.css.map
│   ├── boosted-grid.rtl.css
│   ├── boosted-grid.rtl.css.map
│   ├── boosted-grid.rtl.min.css
│   ├── boosted-grid.rtl.min.css.map
│   ├── boosted-reboot.css
│   ├── boosted-reboot.css.map
│   ├── boosted-reboot.min.css
│   ├── boosted-reboot.min.css.map
│   ├── boosted-reboot.rtl.css
│   ├── boosted-reboot.rtl.css.map
│   ├── boosted-reboot.rtl.min.css
│   ├── boosted-reboot.rtl.min.css.map
│   ├── boosted-utilities.css
│   ├── boosted-utilities.css.map
│   ├── boosted-utilities.min.css
│   ├── boosted-utilities.min.css.map
│   ├── boosted-utilities.rtl.css
│   ├── boosted-utilities.rtl.css.map
│   ├── boosted-utilities.rtl.min.css
│   ├── boosted-utilities.rtl.min.css.map
│   ├── boosted.css
│   ├── boosted.css.map
│   ├── boosted.min.css
│   ├── boosted.min.css.map
│   ├── boosted.rtl.css
│   ├── boosted.rtl.css.map
│   ├── boosted.rtl.min.css
│   └── boosted.rtl.min.css.map
└── js/
    ├── boosted.bundle.js
    ├── boosted.bundle.js.map
    ├── boosted.bundle.min.js
    ├── boosted.bundle.min.js.map
    ├── boosted.esm.js
    ├── boosted.esm.js.map
    ├── boosted.esm.min.js
    ├── boosted.esm.min.js.map
    ├── boosted.js
    ├── boosted.js.map
    ├── boosted.min.js
    └── boosted.min.js.map
```
</details>

We provide compiled CSS and JS (`boosted.*`), as well as compiled and minified CSS and JS (`boosted.min.*`). [Source maps](https://developers.google.com/web/tools/chrome-devtools/javascript/source-maps) (`boosted.*.map`) are available for use with certain browsers' developer tools. Bundled JS files (`boosted.bundle.js` and minified `boosted.bundle.min.js`) include [Popper](https://popper.js.org/).


## Bugs and feature requests

Have a bug or a feature request? Please first read the [issue guidelines](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/blob/main/.github/CONTRIBUTING.md#using-the-issue-tracker) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/issues/new).


## Documentation

Boosted's documentation, included in this repo in the root directory, is built with [Hugo](https://gohugo.io/) and publicly hosted on GitHub Pages at <https://boosted.orange.com/>. The docs may also be run locally.

Documentation search is powered by [Algolia's DocSearch](https://community.algolia.com/docsearch/). Working on our search? Be sure to set `debug: true` in `site/assets/js/search.js` file.

### Running documentation locally

1. Run `npm install` to install the Node.js dependencies, including Hugo (the site builder).
2. Run `npm run test` (or a specific npm script) to rebuild distributed CSS and JavaScript files, as well as our docs assets.
3. From the root `/boosted` directory, run `npm run docs-serve` in the command line.
4. Open `http://localhost:9001/` in your browser, and voilà.

Learn more about using Hugo by reading its [documentation](https://gohugo.io/documentation/).

### Documentation for previous releases

You can find all our previous releases docs on <https://boosted.orange.com/docs/versions/>.

[Previous releases](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/releases) and their documentation are also available for download.


## Contributing

Please read through our [contributing guidelines](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/blob/main/.github/CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

Moreover, if your pull request contains JavaScript patches or features, you must include [relevant unit tests](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/tree/main/js/tests). All HTML and CSS should conform to the [Code Guide](https://github.com/mdo/code-guide), maintained by [Mark Otto](https://github.com/mdo).

Editor preferences are available in the [editor config](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/blob/main/.editorconfig) for easy use in common text editors. Read more and download plugins at <https://editorconfig.org/>.


## Versioning

For transparency into our release cycle and in striving to maintain backward compatibility, Boosted is maintained under [the Semantic Versioning guidelines](https://semver.org/). Sometimes we screw up, but we adhere to those rules whenever possible.

See [the Releases section of our GitHub project](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/releases) for changelogs for each release version of Boosted.

Our default branch is for development of our Boosted 5 release. Head to the [`v4-dev` branch](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/tree/v4-dev) to view the readme, documentation, and source code for Boosted 4.


## Creators

### Bootstrap

**Mark Otto**

- <https://twitter.com/mdo>
- <https://github.com/mdo>

**Jacob Thornton**

- <https://twitter.com/fat>
- <https://github.com/fat>


### Boosted

**Gaël Poupard**

- <https://github.com/ffoodd>


## Thanks

<a href="https://www.browserstack.com/">
  <img src="https://live.browserstack.com/images/opensource/browserstack-logo.svg" alt="BrowserStack Logo" width="192" height="42">
</a>

Thanks to [BrowserStack](https://www.browserstack.com/) for providing the infrastructure that allows us to test in real browsers!


<a href="https://www.netlify.com">
  <img src="https://www.netlify.com/img/global/badges/netlify-light.svg" height="51" width="114" alt="Deploys by Netlify"/>
</a>

Thanks to [Netlify](https://www.netlify.com/), we are able to deploy pre-releases at [Boosted](https://boosted.netlify.com) and auto-deploy pull requests.

## Copyright and license

Code and documentation copyright 2011-2022 the [Bootstrap Authors](https://github.com/twbs/bootstrap/graphs/contributors) and [Twitter, Inc.](https://twitter.com) Code released under the [MIT License](https://github.com/twbs/bootstrap/blob/main/LICENSE). Docs released under [Creative Commons](https://creativecommons.org/licenses/by/3.0/).

Boosted code and documentation copyright 2015-2022 the [Boosted Authors](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/graphs/contributors) and [Orange SA.](https://orange.com) Code released under the [MIT License](https://github.com/Orange-OpenSource/Orange-Boosted-Bootstrap/blob/main/LICENSE). Docs released under [Creative Commons](https://creativecommons.org/licenses/by/3.0/).

