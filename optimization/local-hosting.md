# Local Hosting

The local hosting feature allows you to host the fonts from your own server instead of Google’s. As well as being GDPR-friendly, this can also have performance benefits.

Enabling local hosting is a simple 1-click process.

Navigate to `Appearance` → `Customize` → `Google Fonts` → `Local Hosting`.

Then simply toggle the switch to the `on` position.

![](https://fontsplugin.com/wp-content/uploads/2019/04/local-hosting.png)

Press `Publish` and the plugin will do all the work in the background.

Font Files are cached on your server for **1 year** and they are regenerated each time you change fonts.If you need to re-generate the font files at any time that is possible: 

Navigate to https://yourwebsite.com/?action=gfp-reset-cache  
_\(replace yourwebsite.com with your own URL\)_

### WOFF2 File Format

By default Fonts Plugin uses the WOFF file format as it has the [highest compatibility across all browsers](https://caniuse.com/#search=woff). 

However, there is a more optimized file format that all modern browsers support, [WOFF2](https://caniuse.com/woff2). In our testing it reduces all font file sizes by at least 30%.

To enable WOFF2, toggle the switch:

![](../.gitbook/assets/image%20%2812%29.png)

You will then need to clear your font cache by navigating to https://yourwebsite.com/?action=gfp-reset-cache  
_\(replace yourwebsite.com with your own URL\)_

