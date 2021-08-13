# @virginmoneyuk/create-react-app

An ambitious development, build, and testing toolkit for brighter react web apps.

## Contents

## Installation

## Requirements

## Features

- Superfast JavaScript/TypeScript compilation and production minification using the Rust-based `swc` project. Delivering up to a 70x performance improvement over standard JS based tooling (babel).
- Support for compiling code into modern ES module format for modern browsers, while additionally shipping an ES5 `"nomodule"` version for legacy browser compatibility.
- A more aggressive chunk-splitting approach to reduce duplicate code appearing in chunks with share dependencies.
- Powered by Webpack 5.
- An Advanced HTMLWebpackPlugin configuration that generates `rel="modulepreload preload"` and `rel="preload"` `<link />` tags in the `<head>`for entry chunks and static resources.
- Support for non-blocking CSS stylesheet loading for enhanced initial load performance
- Injected script tags use the `defer` attribute
- Prettier support using the standardized `@virginmoneyuk/prettier-config` package
- ESLint support using `@virginmoneyuk/esling-config` package
- Out-of-the-box Storybook JS support, with useful plugins setup like Axe Accessibility Testing.
- Unit Test Support with `jest` and `@testing-library/react`
- End-to-End Behaviour testing support with Cypress
- Local API and Network Mocking using Mock Service Worker (msw)
- A starter template leveraging some of the best libraries we use for ambitious web apps, including `@reduxjs/toolkit`, `react-router-dom`, `connected-react-router` and `final-form`, combined together into an example we hope you'll be happy to clone and tweak for the products you build that help deliver our purpose.

## Future Roadmap

- Runtime-configurable Public CDN support
- Webpack Module Federation Compatibility
- Multiple HTML Entry Point Configuration

Got an idea or request? Let us know! `<link here>`

## Contributing and Maintainance

A lot of the project structue is inherited from the original `@facebook/create-react-app` project. We strongly reccomend you follow the steps and guidelines explained in CONTRIBUTING.md before getting started. You will need to install some tools globally that you may not have used before.
