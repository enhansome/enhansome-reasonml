# Awesome reasonml with stars

### **Awesome ReasonML** [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 501,169 | 🐛 105 | 📅 2026-08-21

A collection of awesome things regarding Reason/OCaml ecosystem. Inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 501,169 | 🐛 105 | 📅 2026-08-21 list thing. Feel free to improve this list.

* [Reason](#reason)
  * [General Resources](#general-resources)
  * [Melange](#melange)
  * [Starter Kits](#starter-kits)
  * [Tutorials](#tutorials)
  * [Talks](#talks)
  * [Tools](#tools)
  * [Libraries](#libraries)
    * [Standard Libs](#standard-libs)
    * [Web](#web)
    * [JSON encoding and decoding](#json-encoding-and-decoding)
    * [Server](#server)
    * [Testing](#testing)
    * [GraphQL](#graphQL)
  * [Editor Plugins](#reason-editor-plugins)
* [Example Apps](#example-apps)
* [Contribution](#contribution)

## Reason

### General Resources

* [Reason Github](https://github.com/facebook/reason) ⭐ 10,322 | 🐛 190 | 🌐 OCaml | 📅 2026-08-13
* [Documentation](https://reasonml.org/)
* [Homepage](https://reasonml.github.io/)
* [Blog](https://reasonml.github.io/blog/)
* [Reason Twitter](https://twitter.com/reasonml)
* [Discord Community](https://discord.gg/reasonml)

### Melange

* [Homepage](https://melange.re/)
* [Melange documentation](https://melange.re/v4.0.0/what-is-melange.html)
* [Melange Playground](https://melange.re/unstable/playground)
* [Reason Playground](https://reasonml.github.io/en/try.html)
* [Reason package index](https://redex.github.io/)
* [Melange for React Devs](https://react-book.melange.re/)

### Starter Kits

* [create-melange-app](https://github.com/dmmulroy/create-melange-app) ⭐ 139 | 🐛 21 | 🌐 OCaml | 📅 2026-03-12
* [Melange Project template with opam](https://github.com/melange-re/melange-opam-template) ⭐ 61 | 🐛 2 | 🌐 Reason | 📅 2024-11-14
* [Melange Project template with esy](https://github.com/melange-re/melange-esy-template) ⭐ 41 | 🐛 1 | 🌐 Reason | 📅 2024-01-21
* [Reason Starter kit for Advent of Code](https://github.com/ManasJayanth/reason-aoc-starter) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2021-02-06
* [Example Project](https://reasonml.github.io/docs/en/installation)

### Tutorials

* [Intro to Reason Compilation](https://github.com/chenglou/intro-to-reason-compilation) ⭐ 270 | 🐛 6 | 🌐 Shell | 📅 2020-05-12
* [Melange for React Devs](https://react-book.melange.re/)
* [An Invitation to ReasonML](https://protoship.io/blog/2017/05/10/an-invitation-to-reasonml.html)
* [Armed with Reason](http://kcsrk.info/reason/arm/2016/05/16/armed-with-reason/) - Target Raspberry PI
* [Exploring ReasonML](http://reasonmlhub.com/exploring-reasonml/toc.html)
* [Build Tic-Tac-Toe with ReasonML](https://medium.freecodecamp.org/learn-reasonml-by-building-tic-tac-toe-in-react-334203dd513c)
* [Get Started with Reason (Free Video Course)](https://egghead.io/courses/get-started-with-reason)
* [Build a Simon Game in ReasonReact](https://medium.com/@arecvlohe/lets-build-a-simon-game-in-reasonreact-pt-1-randos-c6db32bf4c1)
* [Implement a chart layout algorithm in ReasonML](https://www.huy.dev/squarified-tree-map-reasonml-part-1-2019-03/)

### ReasonReact

* [A First ReasonReact App for JS Developers](https://jamesfriend.com.au/a-first-reason-react-app-for-js-developers)
* [A ReasonReact Tutorial](https://jaredforsyth.com/2017/07/05/a-reason-react-tutorial/)
* [Another ReasonReact Tutorial for Beginners](https://www.robinwieruch.de/reason-react-tutorial/)

### Talks

* 2024/03 - [@dillon\_mulroy](https://x.com/dillon_mulroy) - Frontrunners - [Melange: The Next Frontier in Type-Safe Web Development](https://www.youtube.com/watch?v=wl8zUq1FUzM)
* 2023/08 - [@davesnx](https://x.com/davesnx) - React Alicante - [Server side rendering React natively with Reason](https://www.youtube.com/watch?v=e3qY-Eg9zRY)
* 2019/09 - [@flaviocorpa](https://github.com/kutyel) - LambdAle - [What happens if you let the creator of React design a programming language](https://youtu.be/5IcG_BCGxEY)
* 2019/08 - [@jordwalke](https://github.com/jordwalke) - ReasonConf US - [React to the Future](https://www.youtube.com/watch?v=5fG_lyNuEAw)
* 2018/05 – [@cristianoc](https://github.com/cristianoc) – React Europe – [ReasonReact and local state](https://www.youtube.com/watch?v=qJnP-Vatp3M)
* 2017/11 - [@sgrove](https://github.com/sgrove) - [Finding joy in programming](https://vimeo.com/242081961)
* 2017/10 - [@bassjacob](https://github.com/bassjacob/) - [Universal Reason](https://www.youtube.com/watch?v=L0xz-ILKsLE)
* 2017 06 – [@bassjacob](https://github.com/bassjacob/) – [Node.ninjas Sydney](https://www.meetup/com/en-AU/sydney-node-ninjas/) – [Everything happens for a Reason ](https://www.youtube.com/watch?v=lLqLqFgsimQ\&ab_channel=ANZCoders)
* 2017/05 – [@chenglou](https://github.com/chenglou) – React Europe – [Imperfection](https://www.youtube.com/watch?v=tCVXp6gFD8o)
* 2017/05 – [@chenglou](https://github.com/chenglou) – React London – [What's in a language?](https://www.youtube.com/watch?v=24S5u_4gx7w)
* 2017/04 – [@chenglou](https://github.com/chenglou) – React Conf – [Taming the Meta Language](h/ttps://www.youtube.com/watch?v=_0T5OSSzxms)
* 2016 Phil Holden - Reason [slides](http://philholden.me.uk/reason/reason.pdf)
* 2016/11 - [@sgrove](https://github.com/sgrove) - [Age of Reason](https://www.youtube.com/watch?v=8LCmLQ1-YqQ\&t=6s) + [slides](https://sgrove.github.io/age-of-reason/)
* 2016/11 - [@ferakpeter](https://github.com/ferakpeter) - How to build your first Reason App/ - [slides](https://docs.google.com/presentation/d/1iua5cdq5ecvj8NZqisjwhuhNb_1ljP45K9xMhgLoj8o/edit)
* 2016 - Dawn of Reason - Sander Spies [slides](https://sanderspies.github.io/slides/dawn-of-reason.pdf)
* 2016/07 - [@sgrove](https://github.com/sgrove) - [From Unikernels to Databases to UIs: Truly full-stack apps in OCaml](https://youtu.be/QWfHrbSqnB0)

***

### Tools

* [reason-tools](https://github.com/reasonml/reason-tools) ⭐ 373 | 🐛 25 | 🌐 OCaml | 📅 2018-06-03 - Chrome/Firefox Reason extension
* [type-o-rama](https://github.com/stereobooster/type-o-rama) ⭐ 247 | 🐛 1 | 📅 2022-11-14 - JS type systems interportability
* [RED](https://github.com/frantic/red) ⭐ 82 | 🐛 4 | 🌐 Python | 📅 2023-07-20 - Native Reason/OCaml debugger
* [Vite plugin](https://github.com/pdelacroix/vite-plugin-melange) ⭐ 13 | 🐛 2 | 🌐 JavaScript | 📅 2026-04-21 - A Vite plugin for Melange
* [opam](https://opam.ocaml.org) - OCaml Package Manager
* [dune](https://dune.readthedocs.io/en/stable) - Dune is a build system for OCaml projects. Using it, you can build executables, libraries, run tests, and much more

### Libraries

#### Standard Libs

* [tablecloth](https://github.com/darklang/tablecloth) ⭐ 517 | 🐛 38 | 🌐 JavaScript | 📅 2023-04-20 - An ergonomic, cross-platform, standard library for ReasonML and OCaml
* [Rationale](https://github.com/jonlaing/rationale) ⭐ 275 | 🐛 12 | 🌐 OCaml | 📅 2023-01-03 - Ramda inspired library of helper functions for ReasonML
* [relude](https://github.com/reazen/relude) ⭐ 267 | 🐛 43 | 🌐 Reason | 📅 2026-01-21 - FP-inspired prelude/standard library for ReasonML projects.
* [Belt](https://melange.re/v4.0.0/api/re/melange/Belt/) - A stdlib shipped with Melange.
* [Js](https://melange.re/v4.0.0/api/re/melange/Js/) - Bindings to several browser and Node JavaScript APIs

#### Web

* [reason-react](https://github.com/reasonml/reason-react) ⭐ 3,263 | 🐛 34 | 🌐 Reason | 📅 2026-06-15 - React.js bindings
* [styled-ppx](https://github.com/davesnx/styled-ppx) ⭐ 413 | 🐛 31 | 🌐 OCaml | 📅 2026-07-22 - Type-safe styled components for ReScript, Melange and native with type-safe CSS
* [promise](https://github.com/aantron/promise) ⭐ 340 | 🐛 16 | 🌐 Reason | 📅 2023-10-04 - Light and type-safe binding to JS promises
* [melange-fetch](https://github.com/melange-community/melange-fetch) ⭐ 208 | 🐛 3 | 🌐 OCaml | 📅 2026-06-28 - Fetch bindings for Melange

#### JSON encoding and decoding

* [atd](https://github.com/ahrefs/atd) ⭐ 352 | 🐛 88 | 🌐 OCaml | 📅 2026-08-05 - Static types for JSON APIs
* [bs-decode](https://github.com/mlms13/bs-decode) ⭐ 103 | 🐛 15 | 🌐 Reason | 📅 2024-01-22 - Type-safe JSON decoding for ReasonML and OCaml ([documentation site](https://mlms13.github.io/bs-decode/docs/what-and-why))
* [ocaml-decoders](https://github.com/mattjbray/ocaml-decoders) ⭐ 85 | 🐛 9 | 🌐 OCaml | 📅 2026-01-21 - Elm-inspired decoders for Ocaml
* [melange-json](https://github.com/melange-community/melange-json) ⭐ 24 | 🐛 20 | 🌐 OCaml | 📅 2026-08-14 - Compositional JSON encode/decode library for Melange

#### Server

* [Dream](https://github.com/aantron/dream) ⭐ 1,878 | 🐛 109 | 🌐 OCaml | 📅 2026-05-23 - Tidy, feature-complete Web framework
* [server-reason-react](https://github.com/ml-in-barcelona/server-reason-react) ⭐ 175 | 🐛 6 | 🌐 OCaml | 📅 2026-08-27 - Server render Reason React components with OCaml natively
* [html\_of\_jsx](https://github.com/davesnx/html_of_jsx) ⭐ 52 | 🐛 0 | 🌐 OCaml | 📅 2026-08-17 - Render HTML with JSX

#### GraphQL

* [graphql\_ppx](https://github.com/teamwalnut/graphql-ppx) ⭐ 262 | 🐛 40 | 🌐 OCaml | 📅 2026-02-10 - GraphQL PPX rewriter for Bucklescript/ReasonML written in ReasonML.
* [reasonql](https://github.com/sainthkh/reasonql) ⭐ 96 | 🐛 10 | 🌐 JavaScript | 📅 2022-12-22 - Type-safe and simple GraphQL client for ReasonML
* [melange-relay](https://github.com/anmonteiro/melange-relay) ⭐ 5 | 🐛 0 | 🌐 OCaml | 📅 2026-01-28 - Use Relay with ReasonML

#### Testing

* [melange-fest](https://github.com/ahrefs/melange-fest) ⭐ 15 | 🐛 0 | 🌐 OCaml | 📅 2026-08-24 - A minimal test framework for Melange using Node test runner
* [melange-testing-library](https://github.com/melange-community/melange-testing-library) ⭐ 8 | 🐛 2 | 🌐 Reason | 📅 2026-06-28 - Melange bindings for testing-library (dom-testing-library and react-testing-library)
* [melange-jest](https://github.com/melange-community/melange-jest/) ⭐ 4 | 🐛 5 | 🌐 OCaml | 📅 2026-06-28 - Melange bindings for Jest

### Editor Plugins

See the official guide [here](https://reasonml.github.io/docs/en/editor-plugins)

* [ocaml-lsp](https://github.com/ocaml/ocaml-lsp) ⭐ 909 | 🐛 144 | 🌐 OCaml | 📅 2026-08-30 - OCaml Language Server Protocol implementation
* [vscode-ocaml-platform](https://github.com/ocamllabs/vscode-ocaml-platform) ⭐ 386 | 🐛 62 | 🌐 OCaml | 📅 2026-08-28 - Visual Studio Code extension for ReasonML and OCaml

***

### Example Apps

* [ReasonReact example](https://github.com/reasonml-community/reason-react-example) ⚠️ Archived - ReasonReact examples
* [ReasonReact Hacker News](https://github.com/reasonml-community/reason-react-hacker-news) ⭐ 594 | 🐛 23 | 🌐 Reason | 📅 2023-01-07 - Hacker News written in Reason
* [Gravitron](https://github.com/jaredly/gravitron) ⭐ 490 | 🐛 9 | 🌐 OCaml | 📅 2023-10-20 - A game about gravity on iOS/Android/Browser
* [ReLayout](https://github.com/jordwalke/ReLayout) ⭐ 389 | 🐛 8 | 🌐 Reason | 📅 2024-03-12 - Standalone CSS Flexbox Implementation in Reason
* [Mareo](https://github.com/reasonml-community/Mareo) ⭐ 382 | 🐛 2 | 🌐 JavaScript | 📅 2018-04-17 - Online Mario game demo drawn on canvas
* [ReasonML RealWorld example app #2](https://github.com/jihchi/reason-react-realworld-example-app) ⭐ 193 | 🐛 2 | 🌐 ReScript | 📅 2026-04-25 - Another Medium.com clone written using ReasonReact
* [Coronate](https://github.com/johnridesabike/coronate) ⭐ 175 | 🐛 9 | 🌐 ReScript | 📅 2026-07-25 - A Swiss-style chess tournament manager for the web and desktop, written with ReasonReact. [(web demo)](https://johnridesa.bike/coronate/)
* [99.re](https://github.com/shrynx/99.re) ⭐ 111 | 🐛 0 | 🌐 OCaml | 📅 2017-11-24 - Solutions to 99 problems implemented in Reason
* [ReasonML RealWorld example app](https://github.com/gothinkster/reasonml-realworld-example-app) ⭐ 59 | 🐛 1 | 🌐 Reason | 📅 2021-09-06 - Medium.com clone written using ReasonReact
* [re:bench](https://github.com/rebench/rebench.github.io) ⭐ 44 | 🐛 3 | 🌐 JavaScript | 📅 2018-06-11 - Benchmarking playground built with ReasonReact. A real app in real use.
* [Reason Maze](https://github.com/jaredly/reason-maze) ⭐ 39 | 🐛 0 | 🌐 OCaml | 📅 2017-11-22 - Amazing online maze generation
* [A\* pathfinder maze](https://github.com/puemos/reasonml-astar-maze) ⭐ 38 | 🐛 0 | 🌐 OCaml | 📅 2018-06-09 -  A\* search algorithm written in ReasonML [(demo)](https://puemos.github.io/reasonml-astar-maze)
* [Reason Catstagram](https://github.com/kutyel/reason-catstagram) ⭐ 32 | 🐛 1 | 🌐 Reason | 📅 2019-12-11 - A Catstagram built with Reason and React hooks!
* [reason-chess](https://github.com/venil7/reason-chess) ⭐ 23 | 🐛 2 | 🌐 OCaml | 📅 2018-03-30 - Chess engine for multiple platforms and web example chess game. [(demo)](http://darkruby.co.uk/reason-chess/)
* [Pomodoro](https://github.com/tkovs/pomodoro) ⭐ 23 | 🐛 0 | 🌐 ReScript | 📅 2021-05-15 - A pomodoro webapp written in ReasonReact, using webpack, and fully tested with bs-react-testing-library and reason-hooks-testing-library. [(demo)](https://pomodoro.tkovs.com)
* [Red](https://github.com/excitement-engineer/Red) ⭐ 18 | 🐛 0 | 🌐 OCaml | 📅 2017-11-12 - Simple to use pomodoro webapp
* [Si](https://github.com/scottcheng/si-reason) ⭐ 16 | 🐛 0 | 🌐 OCaml | 📅 2021-07-05 - A 3D connect four game
* [2048 Reasons](https://github.com/alanrsoares/2048-reasons) ⭐ 14 | 🐛 1 | 🌐 ReScript | 📅 2026-07-26 - A functional implementation of the viral 2048 game in Reason using ReasonReact. [(demo)](https://alanrsoares.github.io/2048-reasons/)
* [Dokusho](https://github.com/rawtoast/dokusho) ⭐ 14 | 🐛 17 | 🌐 OCaml | 📅 2023-05-08 - CRUD example with authentication, react toolbox, and CI.
* [Reason Reversi Game](https://github.com/marmelab/reversi-reason) ⚠️ Archived - Reversi Game in ReasonReact
* [Bouken](https://github.com/rawtoast/bouken) ⭐ 11 | 🐛 5 | 🌐 Reason | 📅 2025-11-20 - ASCII rogue written using ReasonReact. [(demo)](https://bouken-dtangmsuhe.now.sh)
* [Repos](https://github.com/lrosa007/repos) ⚠️ Archived - Fetches Github repos by username
* [Simon Game](https://github.com/arecvlohe/reason-react-simon-game/tree/master) ⭐ 9 | 🐛 21 | 🌐 OCaml | 📅 2022-12-08 - The handheld Simon game written in ReasonReact
* [Reason Game of Life](https://github.com/alanrsoares/reasonml-game-of-life) ⭐ 8 | 🐛 0 | 🌐 OCaml | 📅 2018-11-28 - Conway's Game of Life written in Reason using ReasonReact. [(demo)](https://alanrsoares.github.io/reasonml-game-of-life/)
* [TicTacToe ReasonML engine](https://github.com/venil7/ReasonML-TicTacToe) ⭐ 6 | 🐛 0 | 🌐 OCaml | 📅 2018-02-22 - Minimax Tic-Tac-Toe implementation in ReasonML
* [We Write](https://github.com/leomayleomay/we-write-app) ⭐ 6 | 🐛 20 | 🌐 CSS | 📅 2022-12-10 - the App utilizes Github API as the backend, so non-tech writers could collaborate
* [Reatris: ReasonReact tetris](https://github.com/denis-ok/reasonml-reatris) ⭐ 5 | 🐛 25 | 🌐 Reason | 📅 2023-01-06 - Classic tetris game written on ReasonReact [(demo)](https://denis-ok.github.io/reasonml-reatris/)
* [ReasonSplash](https://github.com/smartlogic/reasonsplash) ⚠️ Archived - Unsplash mobile client in Reason
* [Simple Calculator](https://github.com/jimmyhuco/simple-calculator) ⚠️ Archived - It's another calculator written on ReasonReact [(demo)](https://jimmyhuco.github.io/simple-calculator)
* [Re-Memory](https://github.com/dtasic/re-memory) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2018-03-03 - Memory game in ReasonReact
* [Another memory cards game](https://github.com/liubko/reason-memory-gifs) ⭐ 1 | 🐛 16 | 🌐 Reason | 📅 2022-12-07 - Memory cards game with GIFs [(demo)](https://liubko.github.io/reason-memory-gifs/)
* [Snake](https://github.com/rdavison/llama-snake/tree/master/websnake) - Snake game in ReasonReact [(demo)](http://192.241.133.216/projects/websnake/index.html)
* [ReasonML CRUD example](https://github.com/monadoy/reasonml-crud-example) - RealWorld CRUD entity example

***

## Contribution

Your contributions and suggestions are heartily♡ welcome. (✿◠‿◠)

***

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-30._
