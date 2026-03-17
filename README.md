# pubbr
This is a repository of sample JavaScript and JS-containing Epub files to support the development and testing of Pubbr, an Epub document reader app for Android. 

Epub files contain Xhtml, not Html, files. The former are subject to stricter compliance criteria. Thus, JavaScript code that works in Html might not work in Xhtml. This is an important consideration when creating an Epub document that contains JavaScript code.

Pubbr was developed specifically to support JavaScript. Using, for example, dynamic colors would result in low contrast with dark colors on a dark background. This is why the application does not offer a dark theme. However, it is possible to design an Epub document with light text and graphics on a dark background, if needed.

The text copy function is currently disabled by design in the app, but it will be enabled in the next update.
