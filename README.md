Deploy Yesod dependencies (alongside ghc) to Heroku
===================================================

This buildpack is intended to be used with https://github.com/ddollar/heroku-buildpack-multi and https://github.com/begriffs/heroku-buildpack-ghc

When deploying a clean yesod app to heroku I found that the `pcre` C library was missing and needs to be installed separately. Anticipating more of these sorts of dependencies in yesod, I created this buildpack as a helper to keep track of them.

In the likely event that I'm unable to maintain this library, please don't hesitate to nominate yourself as a maintainer - feel free to send me a message (perhaps on google+ if I don't respond on github). I will happily transfer ownership of the upstream fork to anyone willing to deal with it.

