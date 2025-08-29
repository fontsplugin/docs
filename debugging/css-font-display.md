# CSS Font Display

The Font Display setting controls what happens while a font is loading. There are four options, and **swap** is the default.

![](<../.gitbook/assets/image (20).png>)

**Block**

The browser will show invisible text for up to 3 seconds, it will then display the Google Font if it has downloaded.

**Swap**

The browser will initially show a system font, then once the Google Font has downloaded it will swap the fonts.

**Fallback**

The browser will initially show a fallback font. If the Google Font is downloaded within 3 seconds it will swap the fonts. If the Google Font can’t download in 3 seconds or less it will continue using the fallback.

**Optional**

This mode is very similar to fallback, except the wait time is a lot lower. If a font hasn’t downloaded within 100ms the fallback will persist. To realistically load in 100ms a Google Font must already be in the visitors cache.
