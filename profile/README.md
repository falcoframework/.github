<div align="center">

<p align="center">
  <img
    src="https://raw.githubusercontent.com/FalcoFramework/Falco/refs/heads/master/assets/social-banner.png"
    alt="Falco"
    width="360"
  />
</p>

[![NuGet Version](https://img.shields.io/nuget/v/Falco.svg)](https://www.nuget.org/packages/Falco)
[![build](https://github.com/FalcoFramework/Falco/actions/workflows/build.yml/badge.svg)](https://github.com/FalcoFramework/Falco/actions/workflows/build.yml)
[![license](https://img.shields.io/github/license/FalcoFramework/Falco.svg)](https://github.com/FalcoFramework/Falco/blob/master/LICENSE)
![net10.0](https://img.shields.io/badge/net-10.0-blue.svg)
![net9.0](https://img.shields.io/badge/net-890-blue.svg)
![net8.0](https://img.shields.io/badge/net-8.0-blue.svg)
![aot](https://img.shields.io/badge/aot-compatible-green.svg)


[Docs](https://www.falcoframework.com/docs) · [Code](https://github.com/FalcoFramework/Falco) · [Samples](https://github.com/FalcoFramework/Falco/tree/master/examples) · [Help](https://github.com/FalcoFramework/Falco/discussions)

[Get Started](https://www.falcoframework.com/docs/get-started.html) · [Learn More](https://www.falcoframework.com/#falco)

[Latest release: 5.2.0 (December, 21, 2025)](https://www.nuget.org/packages/Falco)

</div>

# Meet Falco

```fsharp
open Falco
open Microsoft.AspNetCore.Builder

let wapp = WebApplication.Create()

wapp.Run(Response.ofPlainText "Hello world")
```

A toolkit for building functional-first, full-stack web applications using F#.

- Built on the high-performance components of ASP.NET Core.
- Seamlessly integrates with existing .NET Core middleware and libraries.
- Designed to be simple, lightweight and easy to learn.

## Key Features

- Simple and powerful [routing](https://falcoframework.com/docs/routing) API.
- Uniform API for [accessing _any_ request data](https://falcoframework.com/docs/request).
- Native F# [view engine](https://falcoframework.com/docs/markup).
- Asynchronous [request handling](https://falcoframework.com/docs/response).
- [Authentication](https://falcoframework.com/docs/authentication) and [security](https://falcoframework.com/docs/cross-request-forgery.md) utilities.
- Built-in support for [large uploads](https://falcoframework.com/docs/request#multipartform-data-binding) and [binary responses](https://falcoframework.com/docs/response#content-disposition).

## Learn

The best way to get started is by visiting the [documentation](https://falcoframework.com/docs). For questions and support, please use [discussions](https://github.com/FalcoFramework/Falco/discussions). For chronological updates, refer to the [changelog](CHANGELOG.md).

## Why "Falco"?

[Kestrel](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/servers/kestrel) has been a game changer for the .NET web stack. In the animal kingdom, "Kestrel" is a name given to several members of the falcon genus. Also known as "Falco".

## Find a bug?

There's an [issue](https://github.com/FalcoFramework/Falco/issues) for that.

## License

Licensed under [Apache License 2.0](https://github.com/FalcoFramework/Falco/blob/master/LICENSE).
