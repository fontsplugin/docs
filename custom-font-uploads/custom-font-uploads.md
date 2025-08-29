---
description: How to upload font files from your device and use them in WordPress
---

# Custom Font Uploads

Click on _Fonts Plugin →_ _Upload Fonts_ in the admin sidebar.

<figure><img src="https://fontsplugin.com/wp-content/uploads/image-8.png?fit=932x1024" alt=""><figcaption></figcaption></figure>

On the _Upload Fonts_ screen you will be able to name and upload your font files.

For the font to display correctly you only need to upload one type of font file, we recommend the .woff2 format as it has the smallest file size.

**Name & Font Family**

If your font is split into multiple files, for example: _OpenSans-Regular.woff2_ and _OpenSans-Bold.woff2_ then you will need to enter a consistent **Font Family** value for each variant. This ensures that all variants are linked in the backend.

If the font you are adding only has one file, you don't need to enter a **Font Family** value.

In this example we are adding the Regular variant of the Roboto font:

<figure><img src="https://fontsplugin.com/wp-content/uploads/image-17.png?fit=817x1024" alt=""><figcaption><p>The name should be a unique value, so we can find the variant later if needed. So we have named it Roboto 400 for simplicity.</p></figcaption></figure>

Once you have pressed the 'Add New Font' button, your font is now ready to use. It can be used in the Customizer, Block Editor (Gutenberg) or the Classic Editor

#### Customizer

The Customizer is used to configure the typography of your entire website at once.

From within wp-admin, navigate to Fonts Plugin → Customize Fonts → Basic Settings

<figure><img src="https://fontsplugin.com/wp-content/uploads/image-11.png?fit=600x292" alt=""><figcaption></figcaption></figure>

Choose your font from the dropdown list and the change will be reflected instantly. You can also change the typography of specific elements by exploring the 'Advanced Settings'.

Clicking the blue icon to the right of the ‘Font Family’ control will reveal additional typography controls

#### Block Editor

To use your new font on a single paragraph or heading in the block editor, first create your content.

Next, while focusing on the block, click the first icon (Transform). The editor will reveal a list of possible transformations. Choose 'Fonts Plugin'.

Initially your content will look the same. However, you will now have access to the 'Fonts Plugin' sidebar where you can choose your new font:

<figure><img src="https://fontsplugin.com/wp-content/uploads/image-15.png?fit=988x800" alt=""><figcaption><p>Click 'Fonts Plugin' to transform the block.</p></figcaption></figure>

<figure><img src="https://fontsplugin.com/wp-content/uploads/image-14-e1716466787712.png?fit=559x768" alt=""><figcaption></figcaption></figure>

#### Classic Editor

To use your new font in the classic editor, first create your content.

Next, highlight your content and click the Font Family dropdown. Your new font should be near the top of the list.

<figure><img src="https://docs.fontsplugin.com/~gitbook/image?url=https%3A%2F%2F2103267599-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-legacy-files%2Fo%2Fassets%252F-LkTSjUWN2UHe7kspGpw%252F-LkcxZQCCDta4lDNCZex%252F-LkcxbwvBIHUdCAdSU_U%252F2019-07-25%252012.48.23.gif%3Falt%3Dmedia%26token%3D4ff79144-9e0c-4b5d-a228-1430f5e23406&#x26;width=768&#x26;dpr=2&#x26;quality=100&#x26;sign=4292e4b3cef38126869ef2ca527e0e2716dbe838bd7cc93fe61a46921d310955" alt=""><figcaption></figcaption></figure>

### How to Optimize Custom Fonts

When fully optimized, uploaded fonts don't add a large amount of weight to your page (30-50kb per variant) and shouldn't noticeably slow down your website. Here are the best ways to do that:

#### 1. **Limit the Font Variants**

There are 18 possible variants, as seen in the table below. Not all fonts support all 18, but if they do, it doesn't necessarily mean you need to upload them all.

| Thin (100)        | Thin Italic        |
| ----------------- | ------------------ |
| Extra Light (200) | Extra Light Italic |
| Light (300)       | Light Italic       |
| Normal (400)      | Normal Italic      |
| Medium (500)      | Medium Italic      |
| Semi Bold (600)   | Semi Bold Italic   |
| Bold (700)        | Bold Italic        |
| Extra Bold (800)  | Extra Bold Italic  |
| Black (900)       | Black Italic       |

Only upload the variants that are used in your design and content. In many cases this may only be four: Normal, Normal Italic, Bold and Bold italic.

#### 2. Preload the Fonts

Preloading is an optimization technique supported by all the major web browsers. It's a line of code on your website that signals to the browser that your website uses a custom font and it needs to be download immediately to reduce the chance of a FOUT (Flash of Unstyled Text).

Preloading is a [Fonts Plugin Pro](https://fontsplugin.com/pro-upgrade) feature and is automatically enabled for custom font uploads in the .woff and .woff2 formats. However you can also disable preloading for individual variants by unchecking the feature

<figure><img src="https://fontsplugin.com/wp-content/uploads/image-13.png?fit=1024x434" alt=""><figcaption></figcaption></figure>

#### 3. Use Optimized Formats

The format of the font files can have a huge effect on the font size. Here is a comparison of Roboto (regular) in different formats:

* TTF - 168kb
* WOFF - 26kb
* WOFF2 - 19kb

All modern browsers support both WOFF and WOFF2 format, so we highly recommend using those. If your fonts are not already in either of those formats, you can use the [Web Font Generator](https://www.fontsquirrel.com/tools/webfont-generator) to convert them.

#### 4. Local Hosting

Local hosting is when the font files are hosted and served from your own domain, and is the most efficient way to add fonts to your website. Using Fonts Plugin to add fonts to your website ensures your fonts are locally hosted automatically.
