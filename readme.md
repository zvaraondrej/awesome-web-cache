# Awesome Cache [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated collection of resources for understanding caching.

>Caching is a technique that stores a copy of a given resource and serves it back when requested. When a web cache has a requested resource in its store, it intercepts the request and returns its copy instead of re-downloading from the originating server. This achieves several goals: it eases the load of the server that doesn’t need to serve all clients itself, and it improves performance by being closer to the client, i.e., it takes less time to transmit the resource back.
>
> -- <cite>[Mozilla Developer Network - HTTP Caching](https://developer.mozilla.org/en-US/docs/Web/HTTP/Caching)</cite> 


## Contents

- [Concepts](#concepts)
- [Learning Resources](#learning-resources)
- [Online Tools](#online-tools)


## Concepts

<!--About this section. Optional. Keep this short and focus on the list.-->

- [Mozilla Developer Network: HTTP Caching](https://developer.mozilla.org/en-US/docs/Web/HTTP/Caching) - A general introduction to caching mechanism with basic concepts and headers explained.
- [Google Developers: HTTP Caching](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching) - Caching concepts, directives and policy explained.
- [Heroku Dev Center: Increasing Application Performance With HTTP Cache Headers](https://devcenter.heroku.com/articles/increasing-application-performance-with-http-cache-headers) - Caching mechanism explained together with practical examples of conditional requests.
- [W3: Caching in HTTP/1.1](https://www.w3.org/Protocols/rfc2616/rfc2616-sec13.html) - Caching in official specification of HTTP/1.1.


## Learning Resources

- [Caching Tutorial For Web Authors And Webmasters](https://www.mnot.net/cache_docs/) - A conprehensive caching guide explaining browser and proxy caches with useful FAQ  section.
- [HTTP Cache Headers – A Complete Guide](https://www.keycdn.com/blog/http-cache-headers/) - An article examining cache headers from browser dev console.
- [Caching Best Practices & max-age Gotchas](https://jakearchibald.com/2016/caching-best-practices/) - Transparent explanation of caching policies with nice examples of the server-client communication. Service Worker cache busting example.
- [Mozilla Developer Network: Cache API](https://developer.mozilla.org/en-US/docs/Web/API/Cache) - Cache API interface of browser service worker. 


## Online Tools

- [REDbot HTTP Header Checker](https://redbot.org/) - An HTTP request header checker providing also suggestions of missing headers and explanations of their meanings.
- [HTTP Header Check - Analyze HTTP Response Headers](https://tools.keycdn.com/curl) - A HTTP headers examination using curl in the background. 


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Ondrej Zvara has waived all copyright and
related or neighboring rights to this work.
