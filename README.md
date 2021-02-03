# Learning Code Splitting

Teaching myself how to use code splitting.

Code splitting according to the MDN Web Docs is a way of organizing code into various components or bundles which can be loaded on demand or in parallel. 

This is done to reduce complexity. Meaning, as apps become more complex and the code base grows, developers need to be able organize and maintain code in a way that enhances the performance of their application(s) over time. 

Developers also don't want browsers to have to load large files which can slow down an app's performance. 

Instead, enourmous files can be split into smaller ones which reduce the work the browser has to perform at any given time. 

The browser can load the features it needs at loading time and delay the loading of additional features until needed based on a user's activity; this is called [lazy loading](https://developer.mozilla.org/en-US/docs/Glossary/Lazy_load).
