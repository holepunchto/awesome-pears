# **Awesome Pears**

🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 

Official collection of awesome things regarding [Pears](https://docs.pears.com).

Pears is Open Source Software dedicated to facilitating the development, deployment and discovery of peer-to-peer applications & systems.


🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐 ⭐️ 🍐

## Table of Contents

- [Stack Outline](#stack-outline)
- [Official Resources](#official-resources)
- [Quick Install](#quick-install)
- [Deployed P2P with Pear CLI](#deployed-p2p-with-pear-cli)
  - [Production Applications](#production-applications)
  - [Applied Demonstrations](#applied-demonstrations)
  - [Community Projects](#community-projects)
- [Learning Resources](#learning-resources)
- [Boilerplates](#boilerplates)
- [Articles](#articles)
- [Videos](#videos)
- [Stack Tools](#stack-tools)
- [Availability](#availability)
- [Testing](#testing)
- [Insights](#insights)
- [Interops](#interops)
- [Native](#native)
- [Engines](#engines)
- [Community Groups](#community-groups)
- [License](#license)

## Stack Outline

* [pear](https://docs.pears.com/reference/pear/cli/) - P2P Deployment & Installation Command Line Interface (CLI)
* [pear-runtime](https://github.com/holepunchto/pear-runtime) - P2P OTA Updates Module
* [hyper*](https://github.com/search?q=org%3Aholepunchto+hyper&type=repositories) module ecosystem - P2P Distribution Primitives
* [auto*](https://github.com/search?q=org%3Aholepunchto+auto&type=repositories) module ecosystem - P2P Coordination Primitives
* [bare](https://github.com/holepunchto/bare) - P2P-first JavaScript Runtime
* [bare-build](https://github.com/holepunchto/bare-build) - Application & Standalone Binary Builds
* [bare-kit](https://github.com/holepunchto/bare-kit) - Native mobile (iOS/Android) bare integration
* [bare*](https://github.com/search?q=org%3Aholepunchto+bare&type=repositories) module ecosystem - Native Primitives

## Official Resources

* [Install](https://install.pears.com)
* [Docs](https://docs.pears.com)
* [Reference](https://docs.pears.com/reference)
* [How To](https://docs.pears.com/how-to/)
* [News](https://pears.com/news)
* [Repositories](https://github.com/holepunchto)

## Quick Install

Linux & macOS [install script](https://install.pears.com/pear.sh):

```sh
curl https://install.pears.com/pear.sh | sh
```

Windows Powershell [install script](https://install.pears.com/pear.ps1):

```sh
irm https://install.pears.com/pear.ps1 | iex
```

Using `npx`, requires Node.js+npm to be installed on system:

```sh
npx pear
```

Whether via install script or package manager Pear CLI is always installed to the same location:

* macOS: `~/.local/bin/pear`
* Linux: `~/.local/bin/pear`
* Windows: `%LOCALAPPDATA%\Programs\pear\pear.exe`


## Deployed P2P with Pear CLI

These applications are deployed with [pear](https://docs.pears.com/reference/pear/cli/) and can be installed with `pear install pear://<key>` per the pear link in the applications `package.json` `upgrade` field.

### Production Applications

[Keet](https://keet.io) - peer-to-peer private messenger with audio/video calls, groups, broadcasts and more for Desktop & Mobile

[PearPass](https://pass.pears.com) - Open-Source peer-to-peer password manager for Desktop & Mobile.
  * [Desktop Repo](https://github.com/tetherto/pearpass-app-desktop)
  * [Mobile Repo](https://github.com/tetherto/pearpass-mobile-desktop)

### Applied Demonstrations

* [`swap`](https://github.com/holepunchto/swap) terminal program, atomically swap two file paths on-disk, evergreen command with peer-to-peer over-the-air updates
* [`snake`](https://github.com/holepunchto/snake) desktop app, peer-to-peer snake

### Community Projects

* [Pear Draw](https://github.com/stickyburn/pear-draw)
* [PearDrop](https://peardrop.online)
  * [Desktop Repo](https://github.com/geordangesink/PearDrop-Desktop)
  * [Mobile Repo](https://github.com/geordangesink/PearDrop-Mobile)
* [PearPetal](https://peerloomllc.com/pearpetal/)
  * [Mobile Repo](https://github.com/peerloomllc/pearpetal)

## Learning Resources

* [P2P From Scratch](https://heartit.tech/category/p2p-systems/) - Fundamentals Series

## Boilerplates

* Desktop
  * [Hello Pear Electron](https://github.com/holepunchto/hello-pear-electron)
<!--* Mobile
  * [Hello Pear React Native](https://github.com/holepunchto/hello-pear-react-native)-->
* Terminal
  * [Hello Pear Bare](https://github.com/holepunchto/hello-pear-bare) (default worker)
  * [Hello Pear Bare:Single Thread](https://github.com/holepunchto/hello-pear-bare/tree/variant/single-thread) (single-thread variant)
  * [Hello Pear Bare:Daemon Updater](https://github.com/holepunchto/hello-pear-bare/tree/variant/daemon) (daemon updater variant)
<!--* Hybrid
  * [Hello Pear Bare Native](https://github.com/holepunchto/hello-pear-bare-native)-->
* Local Backend
  * [Hello Pear Worker](https://github.com/holepunchto/hello-pear-worker)

## Articles

* [Pear Revolution](https://pears.com/news/pear-revolution/)
* [Pear Evolution](https://pears.com/news/pear-evolution/)
* [Hello Pear Boilerplates](https://pears.com/news/hello-pear-boilerplates/)

## Videos

* No Servers, No Clouds, No Masters: Make P2P Apps
  * [YouTube](https://www.youtube.com/watch?v=n76zGrt4aRY&t=140s)
  * [GitNation](https://gitnation.com/contents/pear-releasing-production-p2p-apps) (Includes Q&A)

## Stack Tools

Tools that use P2P capabilities but aren't P2P deployed with Pear CLI, `npm` + `node` are peer dependencies for installation and execution.

* [Drives](https://github.com/holepunchto/drives) - seed/mirror LocalDrives/HyperDrives
- [gip-transport](https://github.com/holepunchto/gip-transport) - Support for `git+pear://` Git remote links

## Availability

* [blind-peer](https://github.com/holepunchto/blind-peer) - make a peer that stores  data encrypted for offline peers, forwarding once online
* [blind-peering](https://github.com/holepunchto/blind-peering) - client for `blind-peer`, integrate into app to ensure availability
* [blind-relay](https://github.com/holepunchto/blind-relay) - make an encrypted relay peer for NAT traversal holepunch-fallback 

## Testing

- [brittle](https://github.com/holepunchto/brittle) - TAP test framework for Bare and Node.js
- [@hyperswarm/testnet](https://github.com/holepunchto/hyperswarm-testnet) - Local DHT testnet

## Insights

- [hyperswarm-doctor](https://github.com/holepunchto/hyperswarm-doctor) - Debugging tool for the swarm.
- [slab-hunter](https://github.com/holepunchto/slab-hunter) - Hunt for Buffer slabs indicative of a memory leak.
- [mininet](https://github.com/holepunchto/mininet) - Spin up and interact with virtual networks using Mininet and Node.js.

## Interops

* [hypercore-blob-server](https://github.com/holepunchto/hypercore-blob-server) - streaming HTTP blob server

## Native

* [bare-addon](https://github.com/holepunchto/bare-addon) template repo for creating native C-binding-to-JS Bare modules
* [bare-build](https://github.com/holepunchto/bare-build) application and binary builder, binaries are standalone custom bare builds
* [bare-make](https://github.com/holepunchto/bare-make) optionated build system for native builds, including `bare` itself
* [bare-kit](https://github.com/holepunchto/bare-kit) - Bare on Android & iOS

## Engines

Swap the default V8 engine out of Bare for lighter-weight engines for embedded execution.

Make runtime with engine: `bare-make generate --define BARE_ENGINE=github:holepunchto/<engine>`

Point `bare-build` at runtime for standalones: `bare-build --runtime <alt-engine-runtime>...`

- [libjs](https://github.com/holepunchto/libjs) ABI-stable C bindings to V8 built on libuv.
- [libjsc](https://github.com/holepunchto/libjsc) ABI-compatible replacement for libjs built on JavaScriptCore.
- [libjerry](https://github.com/holepunchto/libjerry) ABI-compatible replacement for libjs built on JerryScript.
- [libmqjs](https://github.com/holepunchto/libmqjs) ABI-compatible replacement for libjs built on Micro QuickJS.
- [libqjs](https://github.com/holepunchto/libqjs) ABI-compatible replacement for libjs built on QuickJS.

## Community Groups

* [Pear Development Room](https://keet.io/chat/#yfo6dbyb4iz9bhhdq6nzq888dto4b4mxttz94i8ttaidrppwnmtehgn4so6u5jy9cfg41x7aoht5egf8354wjaz7eip5am37ie9ffy3gpq4bngkz35fx4f9zxpeo53qt679q4e8bjazbxoo356pz96c9munhaye)

## License

Apache-2.0