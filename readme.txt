=== Last 9 Photos - WebComponent ===
Contributors: ptkdev
Donate link: https://www.patreon.com/ptkdev
Tags: instagram, widget, last 9 photos, instagram widget, webcomponents
Requires at least: 5.0
Tested up to: 5.6
Requires PHP: 7.2
Stable tag: 2.9.0
License: MIT
License URI: https://github.com/ptkdev-components/webcomponent-instagram-widget/blob/nightly/LICENSE.md

Instagram Widget of your Instagram Profile for your blog. Show latest 9 pics from your instagram account.

== Description ==

# 🌉 WebComponent: Instagram Widget

[![](https://img.shields.io/badge/version-v2.9.0-lightgrey.svg)](https://github.com/ptkdev-components/webcomponent-instagram-widget/releases) [![](https://img.shields.io/npm/v/@ptkdev/webcomponent-instagram-widget.svg)](https://www.npmjs.com/package/@ptkdev/webcomponent-instagram-widget) [![](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/ptkdev-components/webcomponent-instagram-widget/blob/master/LICENSE.md) [![](https://img.shields.io/badge/ES-9-F7DF1E.svg)](https://wikipedia.org/wiki/ECMAScript) [![](https://snyk.io/test/github/ptkdev-components/webcomponent-instagram-widget/badge.svg)](https://snyk.io/test/github/ptkdev-components/webcomponent-instagram-widget) [![](https://discordapp.com/api/guilds/383373985666301975/embed.png)](http://discord.ptkdev.io)

Last 9 Photos: Instagram Widget of your Instagram Profile for your blog. Show latest 9 pics from your instagram account.

> ⛔ **DISCLAIMER**: This is an **unofficial** instagram library and offers no warranty! All trademarks and logos belong to their respective owners.

## 📎 Menu
- 💡 [Features](https://github.com/ptkdev-components/webcomponent-instagram-widget#-features)
- 🕹 [Demo](https://codepen.io/ptkdev/pen/WNQOYqy)
- 👔 [Screenshot](https://github.com/ptkdev-components/webcomponent-instagram-widget#-screenshot)
- 🚀 [How to use](https://github.com/ptkdev-components/webcomponent-instagram-widget#-installation)
- - 🌎 [Web](https://github.com/ptkdev-components/webcomponent-instagram-widget#-installation-web)
- - 📦 [Webpack/Browserify](https://github.com/ptkdev-components/webcomponent-instagram-widget#-installation-npm-module---browserifywebpack)
- - 📖 [Wordpress](https://github.com/ptkdev-components/webcomponent-instagram-widget#-installation-wordpress)
- - ⚛️ [React](https://github.com/ptkdev-components/webcomponent-instagram-widget#%EF%B8%8F-installation-react)
- - 🅰️ [Angular](https://github.com/ptkdev-components/webcomponent-instagram-widget#🅰%EF%B8%8F-installation-angular)
- 📚 [Documentation](https://github.com/ptkdev-components/webcomponent-instagram-widget#-documentation)
- - 🧰 [Options / Attributes](https://github.com/ptkdev-components/webcomponent-instagram-widget#-options--attributes)
- - 🎨 [CSS Customization](https://github.com/ptkdev-components/webcomponent-instagram-widget#-css-customization)
- 🔨 [Developer Mode](https://github.com/ptkdev-components/webcomponent-instagram-widget#-developer-mode)
- 👨‍💻 [Contributing](https://github.com/ptkdev-components/webcomponent-instagram-widget#-contributing)
- 🐛 [Known Bugs](https://github.com/ptkdev-components/webcomponent-instagram-widget/issues?q=is%3Aopen+is%3Aissue+label%3Abug)
- 🍻 Community:
  - <img src="https://raw.githubusercontent.com/ptkdev-components/webcomponent-instagram-widget/master/.github/assets/social_discord.png" height="18px"> [Discord](http://discord.ptkdev.io) ([🇬🇧 English Channel](https://discord.gg/YkMG26f) | [🇮🇹 Italian Channel](https://discord.gg/HFtdBAJ) | [🇵🇱 Polish Channel](https://discord.gg/TV5EXFd))

## 💡 Features
* [✔️] Easy to use
* [✔️] MIT License
* [✔️] Without jQuery depencence
* [✔️] Configurable with attributes
* [✔️] Work with: Browserify / Webpack / ReactJS / Angular / Wordpress
* [✔️] Photos Widget of your Instagram Profile for your blog or website with this WebComponent
* [✔️] Translations: 🇬🇧 🇮🇹 🇵🇱 (Help me ❤️)

## 📖 Installation
1. Download wordpress-plugin and install it.
2. Add code to your html widget, example: `Appearance` --> `Widget` --> insert `HTML Widget` and paste html code:


```
<instagram-widget username="@ptkdev" grid="3x3">
</instagram-widget>
```

NOTE: Replace `@ptkdev` with your instagram username. More settings are available [here](https://github.com/ptkdev-components/webcomponent-instagram-widget#-options--attributes).

You can insert this html code in posts, widget, html box or theme. Where you want see instagram photos box.

== Screenshots ==

See [Demo here](https://codepen.io/ptkdev/pen/WNQOYqy). Photos from @ptkdev account:

== Installation ==

1. Download wordpress-plugin and install it.
2. Add code to your html widget, example: `Appearance` --> `Widget` --> insert `HTML Widget` and paste html code:


```
<instagram-widget username="@ptkdev" grid="3x3">
</instagram-widget>
```

NOTE: Replace `@ptkdev` with your instagram username. More settings are available [here](https://github.com/ptkdev-components/webcomponent-instagram-widget#-options--attributes).

You can insert this html code in posts, widget, html box or theme. Where you want see instagram photos box.


== Changelog ==
# v3.0.0-nightly (TBD)

-   Feature: Fetch with instagram token/facebook open graph
-   Refactor: move to typescript

[![](https://img.shields.io/badge/donate-paypal-005EA6.svg?logo=paypal)](https://www.paypal.me/ptkdev) [![](https://img.shields.io/badge/donate-patreon-F87668.svg?logo=patreon)](https://www.patreon.com/ptkdev) [![](https://img.shields.io/badge/donate-sponsors-ea4aaa.svg?logo=github)](https://github.com/sponsors/ptkdev/) [![](https://img.shields.io/badge/donate-ko--fi-29abe0.svg?logo=ko-fi)](https://ko-fi.com/ptkdev)

# v2.9.0 (March 04, 2021)

-   API RATE LIMIT: Instagram added CORS to a public api `https://www.instagram.com/${this.options["username"]}/?__a=1` with `?__a` get parameter and this widget stopped work. Current workaround: we use google images proxy
-   Security: Update

# v2.8.0 (February 09, 2021)

-   Fix: Can't change default username [#6](https://github.com/ptkdev-components/webcomponent-instagram-widget/issues/6)
-   Fix: localstorage with username as key (cache all usernames)

# v2.7.1 (January 17, 2021)

-   Feature: fetch from backup if get limit api request (from localStorage)
-   Feature: loading spinner
-   Feature: error fetch message

# v2.6.1 (May 19, 2020)

-   New: Wordpress Plugin available on [store](https://wordpress.org/plugins/last-9-photos-webcomponent/).

# v2.6.0 (May 18, 2020)

-   Feature: Overwrite CSS Style with selector `::part`
-   New attribute: mouse-hover
-   New attribute: show-title
-   New attribute: shadows
-   Fix: Wordpress Plugin

# v2.5.0 (May 04, 2020)

-   Fix: now you can use multiple webcomponents in the same html page (#3)
-   NOTE: better to use the full close tag `<instagram-widget></instagram-widget>` than short `/>`

# v2.4.0 (May 02, 2020)

-   New attribute: `force-square`
-   Feature: wordpress-plugin

# v2.3.0 (May 01, 2020)

-   Fix: `border-corners` and `border-spacing` now work without `grid` attribute.
-   Fix: NPM Module give errors with require/import
-   Update: examples

# v2.2.0 (April 30, 2020)

-   Fix: `grid` now is more responsive (now use `calc()` function: `100%` - `spacing/padding/margin`)
-   Fix: default values now work (hello object reference my old dark friend)

# v2.1.1 (April 28, 2020)

-   New attribute: cache
-   New attribute: border-corners
-   New attribute: border-spacing
-   Performance: now component send api request only if you change `username`
-   Fix: refresh attributes random don't work

# v2.0.0 (April 28, 2020)

-   Removed "ptkdev-" prefix
-   Module for Browserify/Webpack (run: `npm install @ptkdev/webcomponent-instagram-widget`)
-   Fix: Grid bug
-   Installation guidelines: Browserify / Webpack / ReactJS / Angular / Wordpress

# v1.1.1 (April 27, 2020)

-   Update CDN (New url!)
-   Update build/dist

# v1.1.0 (April 27, 2020)

-   New attribute: items-limit
-   New attribute: grid
-   New attribute: image-width / image-height

# v1.0.1 (April 26, 2020)

-   Update CDN

# v1.0.0 (April 26, 2020)

-   First Release.
