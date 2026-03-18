# pubbr
This is a repository of sample JavaScript and JS-containing Epub files to support the development and testing of Pubbr, an Epub document reader app for Android. 

The Pubbr EPUB reader was developed with the specific goal of supporting a wide range of JavaScript features to make educational resources accessible on Android. Its user interface is intentionally clean and minimalist, offering keyword search, bookmarks, themes, and font size adjustment. By design, the app does not include a reading library feature; therefore, opening a new document erases all personalized information related to the previous document. Opening of external links is disabled by design. For safety reasons, I chose not to enable both external link access and local storage in random Epub files. If you need both features, the Reasily app may be an option.

Epub files contain Xhtml, not Html, files. The former are subject to stricter compliance criteria. Thus, JavaScript code that works in Html might not work in Xhtml. This is an important consideration when creating an Epub document that contains JavaScript code.

Pubbr was developed specifically to support JavaScript. Using, for example, dynamic colors would result in low contrast with dark colors on a dark background. This is why the application does not offer a dark theme. However, it is possible to design an Epub document with light text and graphics on a dark background, if needed.

The text copy function is currently disabled by design in the app, but it will be enabled in the next update.
