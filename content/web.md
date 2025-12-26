---
title: Web
created: 2025-12-04, 12:33:20
modified: 2025-12-04, 15:50:18
---

> Generic external servers, web framework, etc., in Julia.

- [Julia Web](https://github.com/JuliaWeb) Organization

## HTTP

- [HTTP.jl](https://github.com/JuliaWeb/HTTP.jl) : HTTP for Julia.
- [HttpCommon.jl](https://github.com/JuliaWeb/HttpCommon.jl) : Provides types and helper functions for dealing with the HTTP protocol in Julia.
- [LibCURL.jl](https://github.com/JuliaWeb/LibCURL.jl) : Thin Julia wrapper of [libCURL](http://curl.haxx.se/libcurl/).
- [Mongoose.jl](https://github.com/AbrJA/Mongoose.jl) : a lightweight and efficient interface for building HTTP servers and web applications by the [Mongoose C library](https://github.com/cesanta/mongoose).

## HTML and CSS

- [Cascadia.jl](https://github.com/Algocircle/Cascadia.jl) : https://github.com/andybalholm/cascadia CSS Selector library in Julia.
- [CSSUtil.jl](https://github.com/JuliaGizmos/CSSUtil.jl) : to create and align various web elements on the DOM.
- [DisplayAs.jl](https://github.com/tkf/DisplayAs.jl) : to show objects in a chosen MIME type.
- [GeoIP.jl](https://github.com/JuliaWeb/GeoIP.jl) : estimating the geographic location of IP addresses.
- [Gumbo.jl](https://github.com/JuliaWeb/Gumbo.jl) : Julia wrapper around Google's [gumbo](https://github.com/google/gumbo-parser) HTML parser.
- [Hyperscript.jl](https://github.com/JuliaWeb/Hyperscript.jl) : A lightweight DOM representation for working with HTML, SVG, and CSS in Julia.
- [Kelpie.jl](https://github.com/MillironX/Kelpie.jl) : an HTML template engine in Julia.

## Email

- [SMTPClient.jl](https://github.com/aviks/SMTPClient.jl) : A CURL based SMTP client to send emails from Julia.

## Server backends

- [Canvas.jl](https://github.com/fredrikekre/Canvas.jl) : a Julia package for interacting with the [Canvas LMS REST API](https://canvas.instructure.com/doc/api/), a online education [platform](https://www.instructure.com/).
- [Discord.jl](https://github.com/Xh4H/Discord.jl) : Julia Discord API wrapper.
- [HoJBot.jl](https://github.com/Humans-of-Julia/HoJBot.jl) : The Discord bot for Humans of Julia community server.
- [NewsAPI.jl](https://github.com/joshday/NewsAPI.jl) : Helper functions for using [newsapi.org](https://newsapi.org)
- [Oxygen.jl](https://github.com/OxygenFramework/Oxygen.jl) : Oxygen is a micro-framework built on top of the HTTP.jl library.
- [Telegram.jl](https://github.com/Arkoniak/Telegram.jl) : Native Julia [Telegram bot api](https://core.telegram.org/bots/api#available-methods) wrapper.

## Web frameworks

- [Blink.jl](https://github.com/JuliaGizmos/Blink.jl) : Julia wrapper around [Electron](https://electronjs.org/).
- [Bonito.jl](https://github.com/SimonDanisch/Bonito.jl) : Easy way of building interactive applications from Julia.
- [Bukdu.jl](https://github.com/wookay/Bukdu.jl) : A web development framework for Julia, influenced by [Phoenix framework](https://www.phoenixframework.org/).
- [Dash.jl](https://github.com/plotly/Dash.jl) : A Julia interface to the [Dash](https://plotly.com/dash/) ecosystem for creating analytic web applications in Julia.
- [Diana.jl](https://github.com/neomatrixcode/Diana.jl) : [GraphQL](http://graphql.org/) for Julia.
- [Genie.jl](https://github.com/GenieFramework/Genie.jl) : The highly productive Julia web framework.
- [Merly.jl](https://github.com/neomatrixcode/Merly.jl) : A micro framework for web programming in Julia.
- [WebIO.jl](https://github.com/JuliaGizmos/WebIO.jl) : WebIO provides a simple abstraction for displaying and interacting with web content.

## Middleware

- [JuliaWebAPI.jl](https://github.com/JuliaWeb/JuliaWebAPI.jl) : Julia package for deploying APIs on JuliaBox to facilitate wrapping Julia functions into a remote callable API via ZMQ and HTTP.
- [Mux.jl](https://github.com/JuliaWeb/Mux.jl) : to define servers in terms of highly modular and composable components called middleware.
- [OpenAPI.jl](https://github.com/JuliaComputing/OpenAPI.jl) : [OpenAPI](https://github.com/OAI/OpenAPI-Specification) helper and code generator for Julia
- [ZMQ.jl](https://github.com/JuliaInterop/ZMQ.jl) : Julia interface to [ZeroMQ](https://zeromq.org/).

## Networking

- [DandelionWebSockets.jl](https://github.com/dandeliondeathray/DandelionWebSockets.jl) : A Julia package for client side WebSockets.
- [IPNets.jl](https://github.com/JuliaWeb/IPNets.jl) : IPv4 / IPv6 network abstractions for Julia.
- [LogParser.jl](https://github.com/randyzwitch/LogParser.jl) : A package for parsing server logs. Currently, only server logs having the Apache Combined format are supported (although Apache Common may parse as well).
- [RateLimiter.jl](https://github.com/chipkent/RateLimiter.jl) : Julia package for limiting the rate at which events occur.
- [Skans.jl](https://github.com/rikhuijzer/Skans.jl) : Monitor web pages and get notified when a page has changed.
- [TimeZones.jl](https://github.com/JuliaTime/TimeZones.jl) : Olsen Timezone Database Access for the Julia Programming Language.
- [WebSockets.jl](https://github.com/JuliaWeb/WebSockets.jl) : A WebSockets server library for Julia.

## Security

- [GoogleCloud.jl](https://github.com/JuliaCloud/GoogleCloud.jl) : OAuth2 support for Julia.
- [MbedTLS.jl](https://github.com/JuliaLang/MbedTLS.jl) : Wrapper around [mbedtls](https://github.com/Mbed-TLS/mbedtls).
- [OpenIDConnect.jl](https://github.com/tanmaykm/OpenIDConnect.jl) : [OpenID Connect](https://openid.net/specs/openid-connect-core-1_0.html) is a simple identity layer on top of the OAuth 2.0 protocol.

## URI and URL

- [Tinyurl.jl](https://github.com/rahulkp220/Tinyurl.jl) : The simplest URL shortener for Julia.
- [UAParser.jl](https://github.com/JuliaWeb/UAParser.jl) : UAParser is a Julia port of ua-parser, which itself is a multi-language port of BrowserScope's user agent string parser.
- [URIs.jl](https://github.com/JuliaWeb/URIs.jl) : URI parsing in Julia.

## Static site generators

- [StaticWebPages.jl](https://github.com/Humans-of-Julia/StaticWebPages.jl) : A black-box generator for static websites oriented toward academics and personal web-pages.

### Franklin.jl

[Franklin.jl](https://github.com/JuliaDocs/Franklin.jl) : static site generation with live Julia code evaluation.
- [FranklinTemplates.jl](https://github.com/JuliaDocs/FranklinTemplates.jl) : Simple website templates for Franklin.jl
- [PkgPage.jl](https://github.com/JuliaDocs/PkgPage.jl) : package front-pages powered by `Franklin.jl`.

### Pluto.jl

See [[devtools#Pluto notebooks]].
- [PlutoStaticHTML.jl](https://github.com/rikhuijzer/PlutoStaticHTML.jl) : Convert Pluto notebooks to pure HTML files. [Template for Julia tutorials](https://rikhuijzer.github.io/JuliaTutorialsTemplate/).
- [PlutoPages.jl](https://github.com/JuliaPluto/PlutoPages.jl) : `PlutoPages.jl` is a site generation system inspired by https://www.11ty.dev/.
- [Pluto static export template](https://github.com/JuliaPluto/static-export-template) to automatically convert Pluto notebooks to an HTML website with GitHub Pages.

### Bonito

- [BonitoBook.jl](https://github.com/SimonDanisch/BonitoBook.jl): BonitoBook is a Julia-native interactive notebook system built on [Bonito.jl](https://simondanisch.github.io/Bonito.jl/stable/) that seamlessly combines multi-language execution, AI integration, and modern web-based editing in one powerful platform.
