# readinglists-extension-safari
A Safari extension for users of synchronized reading lists to add a Wikimedia wiki page from the browser.

Adds a toolbar button that can be clicked to add the current page to the default reading list for the logged in user.

__IMPORTANT__: Using this extension requires selecting the "keep me logged in" option when logging in to Wikipedia. 

See [debug installation instructions](https://developer.apple.com/library/content/documentation/Tools/Conceptual/SafariExtensionGuide/UsingExtensionBuilder/UsingExtensionBuilder.html).

## i18n message fetching
This extension bundles message translations provided by the volunteer translators at [TranslateWiki.net](https://translatewiki.net) as part of MediaWiki's [ReadingLists extension](https://www.mediawiki.org/wiki/Extension:ReadingLists).  These can be updated from the MediaWiki API at www.mediawiki.org using the `getMessages.js` script.

```
npm install
node getMessages.js
```

Note: Requires Node.js 7.6.0 or later.
