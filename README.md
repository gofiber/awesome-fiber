# Awesome-fiber

[![Discord](https://img.shields.io/badge/discord-join%20channel-7289DA)](https://gofiber.io/discord)

A collection of Fiber-related awesomeness

<a href="https://gofiber.io">
    <img alt="Fiber" height="125" src="https://raw.githubusercontent.com/gofiber/docs/master/static/fiber_v2_logo.svg">
</a>


## 🧬 Internal Middleware

Here is a list of middleware that are included within the Fiber framework.

| Middleware                                                                       | Description                                                                                                                                                                  |
| :------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [basicauth](https://github.com/gofiber/fiber/tree/master/middleware/basicauth)   | Basic auth middleware provides an HTTP basic authentication. It calls the next handler for valid credentials and 401 Unauthorized for missing or invalid credentials.        |
| [compress](https://github.com/gofiber/fiber/tree/master/middleware/compress)     | Compression middleware for Fiber, it supports `deflate`, `gzip` and `brotli` by default.                                                                                     |
| [cache](https://github.com/gofiber/fiber/tree/master/middleware/cache)           | Intercept and cache responses                                                                                                                                                |
| [cors](https://github.com/gofiber/fiber/tree/master/middleware/cors)             | Enable cross-origin resource sharing \(CORS\) with various options.                                                                                                          |
| [csrf](https://github.com/gofiber/fiber/tree/master/middleware/csrf)             | Protect from CSRF exploits.                                                                                                                                                  |
| [filesystem](https://github.com/gofiber/fiber/tree/master/middleware/filesystem) | FileSystem middleware for Fiber, special thanks and credits to Alireza Salary                                                                                                |
| [favicon](https://github.com/gofiber/fiber/tree/master/middleware/favicon)       | Ignore favicon from logs or serve from memory if a file path is provided.                                                                                                    |
| [limiter](https://github.com/gofiber/fiber/tree/master/middleware/limiter)       | Rate-limiting middleware for Fiber. Use to limit repeated requests to public APIs and/or endpoints such as password reset.                                                   |
| [logger](https://github.com/gofiber/fiber/tree/master/middleware/logger)         | HTTP request/response logger.                                                                                                                                                |
| [pprof](https://github.com/gofiber/fiber/tree/master/middleware/pprof)           | Special thanks to Matthew Lee \(@mthli\)                                                                                                                                     |
| [proxy](https://github.com/gofiber/fiber/tree/master/middleware/proxy)           | Allows you to proxy requests to a multiple servers                                                                                                                           |
| [requestid](https://github.com/gofiber/fiber/tree/master/middleware/requestid)   | Adds a requestid to every request.                                                                                                                                           |
| [recover](https://github.com/gofiber/fiber/tree/master/middleware/recover)       | Recover middleware recovers from panics anywhere in the stack chain and handles the control to the centralized[ ErrorHandler](https://docs.gofiber.io/guide/error-handling). |
| [timeout](https://github.com/gofiber/fiber/tree/master/middleware/timeout)       | Adds a max time for a request and forwards to ErrorHandler if it is exceeded.                                                                                                |

## 🧬 External Middleware

List of externally hosted middleware modules and maintained by the [Fiber team](https://github.com/orgs/gofiber/people).

| Middleware                                        | Description                                                                                                                                                         |
| :------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [adaptor](https://github.com/gofiber/adaptor)     | Converter for net/http handlers to/from Fiber request handlers, special thanks to @arsmn!                                                                           |
| [helmet](https://github.com/gofiber/helmet)       | Helps secure your apps by setting various HTTP headers.                                                                                                             |
| [jwt](https://github.com/gofiber/jwt)             | JWT returns a JSON Web Token \(JWT\) auth middleware.                                                                                                               |
| [keyauth](https://github.com/gofiber/keyauth)     | Key auth middleware provides a key based authentication.                                                                                                            |
| [rewrite](https://github.com/gofiber/rewrite)     | Rewrite middleware rewrites the URL path based on provided rules. It can be helpful for backward compatibility or just creating cleaner and more descriptive links. |
| [session](https://github.com/gofiber/session)     | This session middleware is build on top of fasthttp/session by @savsgio MIT. Special thanks to @thomasvvugt for helping with this middleware.                       |
| [template](https://github.com/gofiber/template)   | This package contains 8 template engines that can be used with Fiber `v1.10.x` Go version 1.13 or higher is required.                                               |
| [websocket](https://github.com/gofiber/websocket) | Based on Fasthttp WebSocket for Fiber with Locals support!                                                                                                          |

## 🌱 Third Party Middlewares

This is a list of middlewares that are created by the Fiber community, please create a PR if you want to see yours!

-   [arsmn/fiber-swagger](https://github.com/arsmn/fiber-swagger)
-   [arsmn/fiber-casbin](https://github.com/arsmn/fiber-casbin)
-   [arsmn/fiber-introspect](https://github.com/arsmn/fiber-introspect)
-   [shareed2k/fiber_tracing](https://github.com/shareed2k/fiber_tracing)
-   [shareed2k/fiber_limiter](https://github.com/shareed2k/fiber_limiter)
-   [thomasvvugt/fiber-boilerplate](https://github.com/thomasvvugt/fiber-boilerplate)
-   [arsmn/gqlgen](https://github.com/arsmn/gqlgen)
-   [kiyonlin/fiber_limiter](https://github.com/kiyonlin/fiber_limiter)
-   [juandiii/go-jwk-security](https://github.com/juandiii/go-jwk-security)
-   [sujit-baniya/fiber-boilerplate](https://github.com/sujit-baniya/fiber-boilerplate)
-   [ansrivas/fiberprometheus](https://github.com/ansrivas/fiberprometheus)
-   [LdDl/fiber-long-poll](https://github.com/LdDl/fiber-long-poll)
-   [K0enM/fiber_vhost](https://github.com/K0enM/fiber_vhost)
-   [sacsand/gofiber-firebaseauth](https://github.com/sacsand/gofiber-firebaseauth)
-   [theArtechnology/fiber-inertia](https://github.com/theArtechnology/fiber-inertia)
-   [aschenmaker/fiber-health-check](https://github.com/aschenmaker/fiber-health-check)
-   [elastic/apmfiber](https://github.com/elastic/apm-agent-go/tree/master/module/apmfiber)
-   [eozer/fiber_ldapauth](https://github.com/eozer/fiber_ldapauth)

WIP 
- https://github.com/Shareed2k/fiber_tracing


## 🚧 Boilerplates
WIP 
- https://github.com/gofiber/boilerplate/
- https://github.com/thomasvvugt/fiber-boilerplate
- https://github.com/sujit-baniya/fiber-boilerplate
- https://github.com/create-go-app/fiber-go-template
- https://github.com/embedmode/fiberseed


## 🍳 Recipes
WIP 
- https://github.com/gofiber/recipes
- https://github.com/kiyonlin/fiblar-demo
- https://github.com/koddr/tutorial-go-fiber-rest-api
- https://github.com/firebase007/go-rest-api-with-fiber
- https://github.com/embedmode/fiberseed
- https://github.com/chawk/go_fiber_quickstart
- https://github.com/EricLau1/go-fiber-auth-api

## 📖 Articles
WIP - check -> https://dev.to/search?q=fiber

- [Working with middlewares and boilerplates](https://dev.to/koddr/go-fiber-by-examples-working-with-middlewares-and-boilerplates-3p0m)
- [Testing the application](https://dev.to/koddr/go-fiber-by-examples-testing-the-application-1ldf)
- [Delving into built-in functions](https://dev.to/koddr/go-fiber-by-examples-delving-into-built-in-functions-1p3k)
```json


    {
      url: "https://dev.to/koddr/go-fiber-by-examples-how-can-the-fiber-web-framework-be-useful-487a",
      website: "dev.to",
      title: "📖 Go Fiber by Examples: How can the Fiber Web Framework be useful?",
      author: "Vic Shóstak",
      date: "august 16, 2021"
    },
    {
      url: "https://dev.to/koddr/build-a-restful-api-on-go-fiber-postgresql-jwt-and-swagger-docs-in-isolated-docker-containers-475j",
      website: "dev.to",
      title: "📖 Build a RESTful API on Go: Fiber, PostgreSQL, JWT and Swagger docs in isolated Docker containers",
      author: "Vic Shóstak",
      date: "march 22, 2021"
    },
    {
      url: "https://dev.to/fenny/getting-started-with-fiber-36b6",
      website: "dev.to",
      title: "Getting started with Fiber ⚡",
      author: "Fenny 🔥",
      date: "june 10, 2020"
    },
    {
      url: "https://blog.logrocket.com/express-style-api-go-fiber/",
      website: "logrocket.com",
      title: "Building an Express-style API in Go with Fiber",
      author: "Alexander Nnakwue",
      date: "june 10, 2020"
    },
    {
      url: "https://vugt.me/the-road-to-web-based-authentication-with-fiber/",
      website: "vugt.me",
      title: "The road to web-based authentication with Fiber ⚡",
      author: "Thomas van Vugt",
      date: "May 20, 2020"
    },
    {
      url: "https://dev.to/koddr/fiber-v1-9-5-how-to-improve-performance-by-817-and-stay-fast-flexible-and-friendly-2dp6",
      website: "dev.to",
      title: "Fiber v1.9.6 🔥 How to improve performance by 817% and stay fast, flexible and friendly?",
      author: "Vic Shóstak",
      date: "May 12, 2020"
    },
    {
      url: "https://blog.yongweilun.me/create-a-travel-list-app-with-go-fiber-angular-mongodb-and-google-cloud-secret-manager-ck9fgxy0p061pcss1xt1ubu8t",
      website: "yongweilun.me",
      title: "🌎 Create a travel list app with Go, Fiber, Angular, MongoDB and Google Cloud Secret Manager",
      author: "Wei Lun",
      date: "April 25, 2020"
    },
    {
      url: "https://tutorialedge.net/golang/basic-rest-api-go-fiber/",
      website: "tutorialedge.net",
      title: "Building a Basic REST API in Go using Fiber",
      author: "Elliot Forbes",
      date: "April 23, 2020"
    },
    {
      url:
        "https://dev.to/jozsefsallai/creating-fast-apis-in-go-using-fiber-59m9",
      website: "dev.to",
      title: "Creating Fast APIs In Go Using Fiber",
      author: "József Sallai",
      date: "April 7, 2020"
    },
    {
      url:
        "https://dev.to/koddr/are-sure-what-your-lovely-web-framework-running-so-fast-2jl1",
      website: "dev.to",
      title: "Is switching from Express to Fiber worth it? 🤔",
      author: "Vic Shóstak",
      date: "April 1, 2020"
    },
    {
      url:
        "https://dev.to/koddr/fiber-v1-8-what-s-new-updated-and-re-thinked-339h",
      website: "dev.to",
      title: "🚀 Fiber v1.8. What's new, updated and re-thinked?",
      author: "Vic Shóstak",
      date: "March 3, 2020"
    },
    {
      url:
        "https://dev.to/koddr/fiber-v2-is-out-now-what-s-new-and-is-he-still-fast-flexible-and-friendly-3ipf",
      website: "dev.to",
      title:
        "Fiber released v1.7! 🎉 What's new and is it still fast, flexible and friendly?",
      author: "Vic Shóstak",
      date: "February 21, 2020"
    },
    {
      url:
        "https://dev.to/koddr/welcome-to-fiber-an-express-js-styled-fastest-web-framework-written-with-on-golang-497",
      website: "dev.to",
      title:
        "Welcome to Fiber — an Express.js styled web framework written in Go with ❤️",
      author: "Vic Shóstak",
      date: "February 3, 2020"
    }
```


## 🤖 Benchmarks
WIP
- https://web-frameworks-benchmark.netlify.app/result
- https://www.techempower.com/benchmarks/#section=data-r20&hw=ph&test=json
- https://github.com/smallnest/go-web-framework-benchmark

## ⚙️ Tools
WIP
- https://github.com/gofiber/cli
- https://github.com/go-dawn/dawn
- https://github.com/tompston/gomakeme


https://github.com/search?l=Go&p=3&q=fiber&type=Repositories