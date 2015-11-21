# Contributing to KeeWeb

:+1: Thanks for taking the time to contribute!  

## Issues

If you have found an bug, please [open an issue](https://github.com/antelle/keeweb/issues/new) and fill in the app version and your user-agent 
(you can find these details in Settings/Help section). Please check [TODO](TODO.md) before creating a feature request.

Please, describe the issue in details: what were your actions which lead to the result? What has happened? 
Does it happen on Demo or New database? If no, how to reproduce this?

## Pull Requests

Plugins are not supported for now. So, if you want to add a feature, please, follow these steps:

1. make sure it's not listed in [https://github.com/antelle/keeweb/wiki/Unsupported-Features](banned features)
2. check compatibility with [TODO.md](the project roadmap) and key features: you should not break anything
3. if your feature is introducing a lot of new UI, or is changing any UX or design concept, please, open an issue to discuss it first
4. please, respect existing style in code, styles, markup
5. don't add any dependencies
6. test your code: it must work in browser, Windows, OSX and Linux
7. if your code is platform-dependent, please add corresponding switches
8. respect each platform: don't create behaviour which breaks interface guidelines or user expectations 
9. run `grunt` and make sure it's passing 