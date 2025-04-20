---
{"dg-publish":true,"permalink":"/1-projects/suivida/obsidian-plugin-configuration/","noteIcon":"2","created":"2025-04-15T06:23:59.129+02:00","updated":"2025-04-20T09:02:26.095+02:00"}
---

## Obsidian plugin configuration 
- 
- obsidian-plugin theme using eleventy.js, docs: https://www.11ty.dev/docs/config/
- obsidian-plugin digital garden docs: https://dg-docs.ole.dev/
- This is what i was searching to **activate all elements** on the site like navigation through folders, search and graph: 
- https://dg-docs.ole.dev/getting-started/03-note-settings/
- you can disable or enable this settings for individual notes with a property. but checkbox works only for enabling, disable needs to be text type : false
- What i didn't found yet: **how to always show sidebar folder navigation if space is available?**
- Also what didn't worked yet: show sitemap from headlines
- to try in the future if i want to change folder structure: 
**File path**
If you want your note to appear in a different file structure than what you have in your vault, you can use the dg-path attribute, like so:
```
---
dg-path: "Advanced/Features.md"
---
```
## Metatags

Setting metatags for a note can be done by adding a dg-metatags attribute like so:

```
dg-metatags:
 description: "some description"
 "og:image": "https://example.com/someimage.png"
```

Note that there is a single space before the "description" field, **not** a tab.

This feature can be used if you want custom titles and images when sharing links in social media. Using the example below will add a title and an image that will be used when sharing the link in social media.

```
dg-metatags:
 "og:title": "Title Appearing on Social Media Site"
 "og:image": "https://example.com/someimage.png"
```
how to change theme https://dg-docs.ole.dev/advanced/adding-custom-components/

Todo in the future:
Enable Vercel analytics:
https://github.com/oleeskild/obsidian-digital-garden/discussions/195