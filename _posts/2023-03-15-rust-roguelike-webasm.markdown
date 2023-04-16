---
title: "🦀🎮 Roguelike game prototype in Rust & WebAssembly"
layout: post
date: 2023-03-15 00:00
tag: rust, games
headerImage: false
projects: true
hidden: true
category: project
author: michelcarroll
externalLink: false
---

I wrote a small [roguelike game](https://en.wikipedia.org/wiki/Roguelike) prototype in Rust. It uses ECS to coordinate the various game components and systems, leveraging the [specs](https://github.com/amethyst/specs) crate. In order to make it more easily accessible and shareable, I target WebAssembly to run it in the browser.

My motivations for building this were:
- To gain a better mastery of the Rust 🦀 programming language, WebAssembly, and their ecosystems
- As a proof of concept for more complex data-driven and browser-based roguelike games
- As a tribute to the roguelike game genre
- For fun, of course 😊

Demo: [https://mcar.dev/assets/demo/rusty-roguelike/index.html](https://mcar.dev/assets/demo/rusty-roguelike/index.html)
(arrow keys to move)  
Codebase: [https://github.com/MichelCarroll/rusty-roguelike](https://github.com/MichelCarroll/rusty-roguelike)

