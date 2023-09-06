---
title: Web
draft: false
tags:
---

> Generic external servers, web framework, etc., in Julia.

- [Julia Web](https://github.com/JuliaWeb) Organization

## HTML and CSS

- [Cascadia.jl](https://github.com/Algocircle/Cascadia.jl) : A CSS Selector library in Julia.
- [CSSUtil.jl](https://github.com/JuliaGizmos/CSSUtil.jl) : utilities to create and align various web elements on the DOM.
- [DisplayAs.jl](https://github.com/tkf/DisplayAs.jl) : It provides functions to show objects in a chosen MIME type.
- [Hyperscript.jl](https://github.com/JuliaWeb/Hyperscript.jl) : A lightweight DOM representation for working with HTML, SVG, and CSS in Julia.
- [Kelpie.jl](https://github.com/MillironX/Kelpie.jl) : an HTML templating engine in Julia.
- [Gumbo.jl](https://github.com/JuliaWeb/Gumbo.jl) : Julia wrapper around Google's [gumbo](https://github.com/google/gumbo-parser) HTML parser.
- [GeoIP.jl](https://github.com/JuliaWeb/GeoIP.jl) : estimating the geographic location of IP addresses.

## Email

- [SMTPClient.jl](https://github.com/aviks/SMTPClient.jl) : An SMTP client to send emails from Julia.

## Server backends

- [Canvas.jl](https://github.com/fredrikekre/Canvas.jl) (by @fredrikekre) : a Julia package for interacting with the [Canvas LMS REST API](https://canvas.instructure.com/doc/api/), which is a online education [platform](https://www.instructure.com/).
- [Discord.jl](https://github.com/Xh4H/Discord.jl) : Julia Discord wrapper.
- [HoJBot.jl](https://github.com/Humans-of-Julia/HoJBot.jl) : The Discord bot for Humans of Julia community server.
- [Joseki.jl](https://github.com/Joseki-jl/Joseki.jl) : Suggested opening moves for building APIs in Julia.
- [NewsAPI.jl](https://github.com/joshday/NewsAPI.jl) : Helper functions for using [newsapi.org](https://newsapi.org)
- [Telegram.jl](https://github.com/Arkoniak/Telegram.jl) : Native Julia [Telegram bot api](https://core.telegram.org/bots/api#available-methods) wrapper.
- [Twitter.jl](https://github.com/randyzwitch/Twitter.jl) : Julia package to access the Twitter API.

## Web frameworks

- [Blink.jl](https://github.com/JuliaGizmos/Blink.jl) : Julia wrapper around [Electron](https://electronjs.org/).
- [Bukdu.jl](https://github.com/wookay/Bukdu.jl) : A web development framework for Julia, influenced by [Phoenix framework](https://www.phoenixframework.org/).
- [Dash.jl](https://github.com/plotly/Dash.jl) : A Julia interface to the [Dash](https://plotly.com/dash/) ecosystem for creating analytic web applications in Julia.
- [Diana.jl](https://github.com/neomatrixcode/Diana.jl) : [GraphQL](http://graphql.org/) for Julia.
- [Genie.jl](https://github.com/GenieFramework/Genie.jl) : The highly productive Julia web framework.
- [Merly.jl](https://github.com/neomatrixcode/Merly.jl) : A micro framework for web programming in Julia.
- [Pages.jl](https://github.com/EricForgy/Pages.jl) : A simple way to create and interact with web pages.

## Middleware

- [JuliaWebAPI.jl](https://github.com/JuliaWeb/JuliaWebAPI.jl) : Julia package for deploying APIs on JuliaBox to facilitate wrapping Julia functions into a remote callable API via ZMQ and HTTP.
- [Mux.jl](https://github.com/JuliaWeb/Mux.jl) : `Mux.jl` allows you to define servers in terms of highly modular and composable components called middleware.
- [ZMQ.jl](https://github.com/JuliaInterop/ZMQ.jl) : Julia interface to [ZeroMQ](https://zeromq.org/).

## Networking

- [DandelionWebSockets.jl](https://github.com/dandeliondeathray/DandelionWebSockets.jl) : A Julia package for client side WebSockets.
- [IPNets.jl](https://github.com/JuliaWeb/IPNets.jl) : IPv4 / IPv6 network abstractions for Julia.
- [LogParser.jl](https://github.com/randyzwitch/LogParser.jl) : A package for parsing server logs. Currently, only server logs having the Apache Combined format are supported (although Apache Common may parse as well).
- [RateLimiter.jl](https://github.com/chipkent/RateLimiter.jl) : Julia package for limiting the rate at which events occur.
- [TimeZones.jl](https://github.com/JuliaTime/TimeZones.jl) : Olsen Timezone Database Access for the Julia Programming Language.
- [WebSockets.jl](https://github.com/JuliaWeb/WebSockets.jl) : A WebSockets server library for Julia.
- [DandelionWebSockets.jl](https://github.com/dandeliondeathray/DandelionWebSockets.jl) : client-side WebSockets.
- [WebIO.jl](https://github.com/JuliaGizmos/WebIO.jl) : WebIO provides a simple abstraction for displaying and interacting with web content.
- [Skans.jl](https://github.com/rikhuijzer/Skans.jl) : Monitor web pages and get notified when a page has changed.

## Security

- [GnuTLS.jl](https://github.com/JuliaWeb/GnuTLS.jl) : Transport Level Security for Julia Streams provided by GnuTLS.
- [MbedTLS.jl](https://github.com/JuliaLang/MbedTLS.jl) : Wrapper around [mbedtls](https://tls.mbed.org/).
- [OAuth.jl](https://github.com/randyzwitch/OAuth.jl) : Pure Julia implementation of OAuth v1.0a.
- [GoogleCloud.jl](https://github.com/JuliaCloud/GoogleCloud.jl) : OAuth2 support for Julia.

## HTTP

- [HTTP.jl](https://github.com/JuliaWeb/HTTP.jl) : HTTP for Julia.
- [HttpCommon.jl](https://github.com/JuliaWeb/HttpCommon.jl) : Provides types and helper functions for dealing with the HTTP protocol in Julia.
- [LibCURL.jl](https://github.com/JuliaWeb/LibCURL.jl) : Thin Julia wrapper of [libCURL](http://curl.haxx.se/libcurl/).

## URI and URL

- [Tinyurl.jl](https://github.com/rahulkp220/Tinyurl.jl) : The simplest URL shortener for Julia.
- [UAParser.jl](https://github.com/JuliaWeb/UAParser.jl) : UAParser is a Julia port of ua-parser, which itself is a multi-language port of BrowserScope's user agent string parser.
- [URIs.jl](https://github.com/JuliaWeb/URIs.jl) : URI parsing in Julia.

## Static site generators

- [StaticWebPages.jl](https://github.com/Humans-of-Julia/StaticWebPages.jl) : A black-box generator for static websites oriented toward academics and personal web-pages.

### Franklin.jl

- [Franklin.jl](https://github.com/tlienart/Franklin.jl) : static site generation with live Julia code evaulation. See also  [FranklinTemplates.jl](https://github.com/tlienart/FranklinTemplates.jl)
- [PkgPage.jl](https://tlienart.github.io/PkgPage.jl) : package front-pages powered by `Franklin.jl`.

### Pluto.jl

- [PlutoSliderServer.jl](https://github.com/JuliaPluto/PlutoSliderServer.jl) : Web server to host Pluto notebooks supporting static conversion to HTML files.
- [PlutoStaticHTML.jl](https://github.com/rikhuijzer/PlutoStaticHTML.jl) : Convert Pluto notebooks to pure HTML files. [Template for Julia tutorials](https://rikhuijzer.github.io/JuliaTutorialsTemplate/).
