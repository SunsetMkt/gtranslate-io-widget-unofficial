# gtranslate-io-widget-unofficial

Unofficial NPM package for gtranslate.io website translator widget free version.

## Background

[gtranslate.io website translator widget free version](https://gtranslate.io/download) is a wrapper for a deprecated Google Translate API website translator widget (`https://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit`). gtranslate.io widget provides a pretty interface to utilize the deprecated Google Translate API website translator widget.

It seems that the main script of gtranslate.io website translator widget is not updated since 2023.

## Usage

[![NPM Version](https://img.shields.io/npm/v/gtranslate-io-widget-unofficial)](https://www.npmjs.com/package/gtranslate-io-widget-unofficial)

See [gtranslate.io's Language Selector Widget page](https://gtranslate.io/website-translator-widget).

```html
<div class="gtranslate_wrapper"></div>
<script>
    window.gtranslateSettings = {
        default_language: "en",
        native_language_names: true,
        detect_browser_language: true,
        wrapper_selector: ".gtranslate_wrapper",
    };
</script>
<script src="https://cdn.gtranslate.net/widgets/latest/float.js" defer></script>
```

## Maintainence

Download latest script from [gtranslate.io](https://gtranslate.io/download) (use [mod_gtranslate.5.0.3.zip](https://gtranslate.net/downloads/mod_gtranslate.5.0.3.zip) in this package) and put the files in `dist` directory. Remove any unused template files. Do not modify gtranslate.io's copyright notice.

From the license file in `mod_gtranslate.5.0.3.zip`, gtranslate.io seems to publish the code under the GNU General Public License.
