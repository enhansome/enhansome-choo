# Awesome choo :steam\_locomotive::train::train::train::train::train: with stars

> [choo](https://choo.io/) is a `4kb` framework for creating
> sturdy frontend applications

## Contents

* [Official resources](#official-resources)
* [Dependencies](#dependencies)
* [Demos](#demos)
* [Community](#community)
* [Plugins and addons](#plugins-and-addons)
* [Elements](#elements)
* [CLI Templates](#cli-templates)
* [Resources](#resources)
* [Projects using choo](#projects-using-choo)

### Official resources

* [Docs](https://github.com/yoshuawuyts/choo/blob/master/README.md) ⭐ 6,770 | 🐛 44 | 🌐 JavaScript | 📅 2026-02-20
* [Repo](https://github.com/yoshuawuyts/choo) ⭐ 6,770 | 🐛 44 | 🌐 JavaScript | 📅 2026-02-20
* [Handbook](https://github.com/yoshuawuyts/choo-handbook) ⭐ 268 | 🐛 13 | 🌐 HTML | 📅 2019-05-16
* [Website](https://choo.io/)
* [Twitter thread](https://twitter.com/yoshuawuyts/status/730087077803528193)

### Dependencies

`choo` is a modular framework. These are the dependencies it glues together
under the hood:

* [hyperx](https://github.com/substack/hyperx) ⭐ 1,017 | 🐛 15 | 🌐 JavaScript | 📅 2023-11-02 - Convert template strings to
  library backends.
* [nanomorph](https://github.com/choojs/nanomorph) ⭐ 753 | 🐛 21 | 🌐 JavaScript | 📅 2021-06-01 - Hyper fast diffing algorithm for real DOM nodes.
* [bel](https://github.com/shama/bel) ⭐ 688 | 🐛 27 | 🌐 JavaScript | 📅 2022-10-12 - Create composable DOM elements using
  template strings.
* [nanobus](https://github.com/choojs/nanobus) ⭐ 228 | 🐛 3 | 🌐 JavaScript | 📅 2021-02-18 - Tiny message bus.
* [nanorouter](https://github.com/choojs/nanorouter) ⭐ 117 | 🐛 4 | 🌐 JavaScript | 📅 2019-06-09 - Smol frontend router.
* [nanoquery](https://github.com/choojs/nanoquery) ⭐ 49 | 🐛 2 | 🌐 JavaScript | 📅 2019-04-01 - Tiny querystring module.
* [nanohref](https://github.com/choojs/nanohref) ⭐ 41 | 🐛 1 | 🌐 JavaScript | 📅 2019-09-04 - Tiny href click handler library.
* [nanotiming](https://github.com/choojs/nanotiming) ⭐ 35 | 🐛 4 | 🌐 JavaScript | 📅 2018-04-16 - Small timing library.
* [nanolocation](https://github.com/choojs/nanolocation) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2018-04-11 - Small window\.location library.
* [nanoraf](https://github.com/yoshuawuyts/nanoraf) - Only call RAF when needed.

### Demos

* [Input example](http://requirebin.com/?gist=e589473373b3100a6ace29f7bbee3186) - ([repo](https://github.com/yoshuawuyts/choo/tree/master/examples/title) ⭐ 6,770 | 🐛 44 | 🌐 JavaScript | 📅 2026-02-20)
* [Mailbox routing](https://github.com/yoshuawuyts/choo/tree/master/examples/mailbox) ⭐ 6,770 | 🐛 44 | 🌐 JavaScript | 📅 2026-02-20
* [TodoMVC](http://shuheikagawa.com/todomvc-choo) - ([repo](https://github.com/shuhei/todomvc-choo) ⭐ 36 | 🐛 0 | 🌐 JavaScript | 📅 2017-01-22)
* [choo-firebase](https://choo-firebase-2ec21.firebaseapp.com) - ([repo](https://github.com/mw222rs/choo-firebase) ⭐ 19 | 🐛 0 | 🌐 JavaScript | 📅 2017-01-15)
* [choo-leaflet-demo](https://github.com/timwis/choo-leaflet-demo) ⭐ 16 | 🐛 0 | 🌐 JavaScript | 📅 2016-12-26
* [Grow](https://grow.static.land) - ([repo](https://github.com/sethvincent/grow) ⭐ 13 | 🐛 1 | 🌐 CSS | 📅 2016-06-24)
* [choo-scriber](https://zhouhansen.github.io/choo-scriber) - ([repo](https://github.com/ZhouHansen/choo-scriber) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2017-11-26)
* [Chatbot](http://chootbot.herokuapp.com) - ([repo](https://github.com/plaey/chatbot) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2016-07-12)
* [HTTP effects](https://hyperdev.com/#!/project/fork-fang)
* [chat-random](https://github.com/akiva/chat-random)

### Community

* [Freenode](https://webchat.freenode.net/?channels=choo)

### Plugins and addons

* [choo-log](https://github.com/yoshuawuyts/choo-log) ⚠️ Archived - Development logger for choo.
* [choo-persist](https://github.com/yoshuawuyts/choo-persist/) ⭐ 44 | 🐛 5 | 🌐 JavaScript | 📅 2018-04-25 - Synchronize choo state with LocalStorage.
* [choo-store](https://github.com/ungoldman/choo-store) ⭐ 37 | 🐛 0 | 🌐 JavaScript | 📅 2020-10-09 - Lightweight state structure for choo apps.
* [choo-websocket](https://github.com/YerkoPalma/choo-websocket) ⭐ 31 | 🐛 0 | 🌐 JavaScript | 📅 2017-12-29 - Small wraper around WebSocket browser API, for `choo` apps.
* [choo-service-worker](https://github.com/choojs/choo-service-worker) ⭐ 25 | 🐛 0 | 🌐 JavaScript | 📅 2019-06-09 - Service worker loader for `choo`.
* [choo-test](https://github.com/mantoni/choo-test) ⭐ 23 | 🐛 5 | 🌐 JavaScript | 📅 2023-04-17 - Easy choo app unit testing.
* [choo-redirect](https://github.com/yoshuawuyts/choo-redirect) ⭐ 19 | 🐛 0 | 🌐 JavaScript | 📅 2017-05-20 - Redirect a view to another view.
* [choo-detached](https://github.com/graforlock/choo-detached) ⭐ 19 | 🐛 0 | 🌐 JavaScript | 📅 2018-02-05 - Use `choo` as a mountable, simple stand-alone component (no routing).
* [choo-pull](https://github.com/yoshuawuyts/choo-pull) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2017-05-11 - Wrap handlers to use pull-stream in a choo plugin.
* [choo-resume](https://github.com/bengourley/choo-resume) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2017-03-23 - choo-resume + hot-rld = hot app reload in choo.
* [choo-model](https://github.com/yoshuawuyts/choo-model) ⭐ 14 | 🐛 0 | 🌐 JavaScript | 📅 2016-10-29 - Experimental state management lib for choo.
* [choo-location-electron](https://github.com/bcomnes/choo-location-electron) ⭐ 12 | 🐛 1 | 🌐 JavaScript | 📅 2017-08-06 - Fix `choo`'s router in electron.
* [choo-promise](https://github.com/rahatarmanahmed/choo-promise) ⭐ 4 | 🐛 1 | 🌐 JavaScript | 📅 2017-06-02 - Use promises in effects and subscriptions.

### Elements

* [dom-notifications](https://github.com/finnp/dom-notifications) ⭐ 105 | 🐛 0 | 🌐 CSS | 📅 2023-05-04 - Atom-inspired notifications component.
* [choodown](https://github.com/trainyard/choodown) ⭐ 14 | 🐛 0 | 🌐 JavaScript | 📅 2017-01-19 - A simple markdown component for choo.
* [choo-chartist](https://github.com/rexmortus/choo-chartist) ⭐ 8 | 🐛 2 | 🌐 JavaScript | 📅 2018-01-09 - A little component for using [Chartist](https://gionkunz.github.io/chartist-js/) with the choo framework.
* [choo-md-editor](https://github.com/dbtek/choo-md-editor) ⭐ 5 | 🐛 1 | 🌐 JavaScript | 📅 2017-07-17 - Lightweight markdown editor that can be used inside Choo app or as a standalone library.

### CLI Templates

Templates for [choo-cli](https://github.com/trainyard/choo-cli) ⭐ 65 | 🐛 0 | 🌐 JavaScript | 📅 2017-11-07

* [haroenv/template-webpack](https://github.com/haroenv/template-webpack) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2017-03-04
* [trainyard/template-basic](https://github.com/trainyard/template-basic) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2017-10-18
* [simonwjackson/atomic-choo](https://github.com/simonwjackson/atomic-choo) - An opinionated project seed to get started developing with electron, webpack and choo.

Other CLI templates

* [graforlock/choo-bandwagon](https://github.com/graforlock/choo-bandwagon) ⭐ 13 | 🐛 0 | 🌐 JavaScript | 📅 2019-05-24

### Resources

> :movie\_camera: : videos
> :computer: : tutorials
> :book: : articles

* :computer: [Your first choo app](https://yoshuawuyts.gitbooks.io/choo/content/02_your_first_app.html)
* :movie\_camera: [TCBY community live hangout](https://www.youtube.com/watch?v=a97Mw2z1SAI)
* :book: [A better frontend experience](https://medium.com/@yoshuawuyts/a-better-frontend-experience-7b0498c85658)
* :book: [Composition in CycleJS, choo, React and Angular2](http://blog.krawaller.se/posts/composition-in-cyclejs-choo-react-and-angular2)
* :book: [Stupidly smart components in choo](http://blog.krawaller.se/posts/stupidly-smart-components-in-choo)

### Projects using choo

* [Robotopia](https://github.com/robotopia-x/robotopia) ⚠️ Archived - Introducing kids to coding with tiny virtual robots!
* [hyperamp](https://github.com/hypermodules/hyperamp) ⭐ 307 | 🐛 4 | 🌐 JavaScript | 📅 2025-04-14 - Humble music player.
* [minidocs](https://github.com/freeman-lab/minidocs) ⭐ 137 | 🐛 15 | 🌐 JavaScript | 📅 2019-08-06 – A documentation site generator built with choo.
* [dataface](https://github.com/timwis/dataface) ⭐ 43 | 🐛 28 | 🌐 JavaScript | 📅 2017-08-04 - Desktop application to manage databases.
* [boowa](https://github.com/boowajs/boowa) ⭐ 43 | 🐛 0 | 🌐 JavaScript | 📅 2020-04-18 - A fun blog generator, built with `choo`.
* [enviar](https://github.com/timwis/enviar) ⭐ 38 | 🐛 31 | 🌐 JavaScript | 📅 2022-09-25 - Chat interface for SMS / text messages.
* [BlankUp](https://github.com/HoverBaum/BlankUp-Electron) ⭐ 37 | 🐛 6 | 🌐 CSS | 📅 2017-12-22 - Multiplatform markdown editor.
* [hackernews-choo](https://github.com/kvnneff/hackernews-choo) ⭐ 30 | 🐛 1 | 🌐 JavaScript | 📅 2016-08-24 - A Hacker News reader built with choo.
* [nekocafe](https://github.com/notenoughneon/nekocafe) ⭐ 17 | 🐛 2 | 🌐 JavaScript | 📅 2017-08-12 - Web chat room :cat: :speech\_balloon:.
* [boxcar](https://github.com/toddself/boxcar) ⭐ 11 | 🐛 3 | 🌐 JavaScript | 📅 2017-06-24 - A choo-based grid/spreadsheet editor.
* [hacker-choo](https://github.com/mw222rs/hacker-choo) ⭐ 11 | 🐛 0 | 🌐 JavaScript | 📅 2016-06-26 - Hacker Typer clone written in choo.
* [busca](https://github.com/afk-mcz/busca) ⭐ 10 | 🐛 6 | 🌐 JavaScript | 📅 2019-02-19 - A small web-extension to search the current tab on reddit.
* [tic-tac-choo](https://github.com/YerkoPalma/tic-tac-toe) ⭐ 6 | 🐛 4 | 🌐 JavaScript | 📅 2018-01-03 - Progressive tic tac toe game, made with choo.
* [choo-ban](https://github.com/luizbaldi/choo-ban) ⭐ 6 | 🐛 20 | 🌐 JavaScript | 📅 2022-12-10 - Simple kanban to manage board tasks, built with `choo`.
* [footprint-rechoo](https://github.com/npeihl/footprint-rechoo) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2016-07-20 - A choo rewrite of [footprint-review](http://github.com/sjcgis/footprint-review).
* [civicdr.org](https://github.com/CiviCDR/civicdr.org) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2017-06-09 - Website for [CiviCDR](https://civicdr.org/).
* [choo-sortable](https://github.com/willkessler/choo-sortable) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2016-06-24 - Building sortable code with choo.
* [kaktus](https://github.com/kaktus/kaktus) ⭐ 0 | 🐛 0 | 📅 2022-02-19 - A new minimalistic web browser, built on `choo` and IndexedDB.

### License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Yerko Palma](https://github.com/YerkoPalma) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-14._
