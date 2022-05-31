# Anatolii Osetsymskyi

_Rust/C++/GO Software and Blockchain Developer, Live in Amsterdam, Netherlands. A resident of Ukraine_  🇺🇦

[Email](mailto:xgreenx9999@gmail.com) / [LinkedIn](https://www.linkedin.com/in/aostesymskyi/) / [GitHub](https://github.com/xgreenx) / [Telegram](https://t.me/xgreenx99) / +380663944720

## 🔧 Development preferences

- Main languages:
  - Rust - is the language that I prefer the most. I enjoy its features, proc macros, and memory management.
  - C/C++ - my first language from the university. I like its low-level stuff.
  - Golang - is the language that I prefer to write asynchronous code cause goroutines are a fantastic feature.
- Secondary languages:
  - Javascript/Nodejs - every project that I worked on somehow required the usage of JS.
  - Swift/Objective-C - I like to develop some applications on my smartphone in my free time.
  - C#/Java - studied in the university and after interacting with it on different works.
  - Haxe - is an unusual language, but I used it for around two years together with C++.
  - Python - in the university, I played with machine learning, and I have basic knowledge of that language.
- OS:
  - Mac OS - last two years, I've been using that system as the main.
  - Linux - was the primary system for development before Mac OS. I worked with Ubuntu image and tried Debian and other distributives in most cases.
  - Windows - I used that system for development at the beginning of my career. But honestly, it doesn't fit for development=)


## 💼 Work experience

**Rust Core Blockchain Developer** [Supercolony](https://supercolony.net) _(April 2021 - Present)_

The work is related to evolving the ecosystem and WASM smart contract development. Except for that,
I worked on several projects for portfolio companies related to ink! and substrate development.
- Successfully ported two big projects from Solidity to ink!(30+ contracts) that increased the coverage of the audience.
- Designed and implemented [OpenBrush](https://github.com/Supercolony-net/openbrush-contracts) as a first library(analog of OpenZeppelin) to ease out WASM smart contract development experience in the dotsama community.
- Implemented functionality for upgradeable contracts on all execution layers.
- Designed(traits - soon link to the issue, [event](https://github.com/paritytech/ink/pull/1243) refactoring) and implemented([storage](https://github.com/paritytech/ink/issues/1134), [dispatching](https://github.com/paritytech/ink/pull/1017)) major features in the ink! to improve the language syntax and simplify the development.
- Designed the architecture of substrate-based blockchain with inner yield protocols.
- Decreased the size of smart contracts(10-15%) to improve on-chain performance.
- Designed and implemented standards of [Fungible](https://github.com/w3f/PSPs/blob/master/PSPs/psp-22.md), [Non-Fungible](https://github.com/w3f/PSPs/blob/master/PSPs/psp-34.md), and [Multi tokens](https://github.com/w3f/PSPs/blob/master/PSPs/drafts/psp-35.md) to unify the interface for the WASM smart contract ecosystem.
- Optimized(x25) the Graph indexer for PancakeSwap to process transactions with the speed of the binance smart chain.
- Technical interviewer for a dozen of candidates. Not to say I enjoy this, but I can quickly understand if a candidate fits a technical role.

**GO/C++/Rust Core Blockchain Developer** [ProximaX](https://www.proximax.io) _(April 2020 - April 2021)_

The main idea of the project is decentralized storage(DFMS written on Golang) built on top of
the blockchain(C++) with an execution layer for smart contracts(WASM Rust/TS Assemblyscript).
- Design(for the blockchain and DFMS) a new, more secure version of the storage with an improved flow for users and storage providers.
- Implemented main plugins(analogs of Cosmos Modules but on C++) of new business logic on the blockchain.
- Refactored the logic of the Merkel tree calculation and optimized(x2) the work of the unconfirmed cache.
- Refactored the [Golang SDK](https://github.com/proximax-storage/go-xpx-chain-sdk) to be compatible with a new blockchain version.
- Fully reworked the execution level of the DFMS:
  - Implemented a new system of events to parallelize the execution.
    - fix previous bugs related to conflicting executions.
  - Changed the storage's workflow to lock only data cells related to execution instead of the whole storage.
  - Added support for new host's functions
    - integrated them into VM to increase the functionality.
  - Designed and implemented the consensus of executors for non-deterministic operations(e.g. HTTP requests)
- Implemented simple [TS Assemblyscript](https://github.com/proximax-storage/ts-xpx-supercontract-sdk) to write smart contracts with TypeScript
  - compile them into WASM to run on executors.
- Refactored IPFS Merkle DAG module of the file system to be compatible with blockchain structure.
- Debugging and fixing bugs on the blockchain side related to
  - inconsistent state
  - corrupted pointers
  - incorrect state reverts
  - vulnerabilities related to DDoS
  - invalid transaction propagation

**C++/GO Blockchain Developer** [482.solutions](https://482.solutions) _(August 2018 - April 2020)_

It was a company where I started work with blockchain.
The main project was the customization and updating of the NEM blockchain,
adding new features, new plugins, performance testing, and optimizations.
Side projects were related to the integration of the blockchain with IoT.
- Added metrics into the code and created a framework for performance testing of the blockchain.
  Based on the results of the testing:
  - Optimized the processing of common transactions(x3) and custom transactions(x1.5).
  - Found and fixed several bugs with race conditions and reported them to the NEM team.
  - Found vulnerability with DDoS protection against invalid transactions that we fixed by changing the token economic model.
  - Those metrics and that framework were used during network upgrades to find and fix regressions.
- Designed and developed the first version of DFMS and integrated it with the blockchain. Integration includes:
  - Implement new plugins on the blockchain to support storage manipulations and charge tokens for storage usage.
  - Actualization and refactoring of the [Golang SDK](https://github.com/proximax-storage/go-xpx-chain-sdk) for interactions with blockchain.
  - Integration of new SDK and business logic into DFMS and CLI.
  - All changes include the unit and e2e testing.
- Developed a C++ SDK to interact with NEM/ProximaX blockchain from IoT devices.
- Developed several examples of how IoT devices can interact with blockchain to show
  various use cases where blockchain can be integrated into real life.

The work also included CI, adding and gathering logs from different users and their analysis via kibana and elasticsearch.

**Junior Haxe/C++ Developer** [The Product Engine](https://www.productengine.com) _(October 2016 - August 2018)_

Most tasks were support and development of a new UI(Haxe) for different DVRs.
But also were tasks related to performance, rendering, memory leaks, debugging and implementing a new API on the backend side.
- Refactored OneLineGuide(a separate screen to easily navigate TV shows)
  to be compatible with the new UI. Changed the layout logic to work faster and send fewer requests.
- Reimplemented the logic of the backend for Filtered Guide(a separate screen allows filtering content) to not crash with searches with a lot of content.
- Removed a lot of memory leaks during image loading and caching and decreased the application's memory consumption two times.
- Fixed different bugs related to text rendering in OpenFL on different platforms.
- Found the root cause of several strange issues that were faced by some users sometimes via objdumping and debugging assembler code.

During the work, I used a lot of Splunk to analyze the performance and stability of the screen developed by the team.

**Junior C++/QT Developer** [ODISW](http://sprut-ow.net) _(January 2016 - June 2016)_
Development of city lighting management project for several cities in Ukraine: Kirovograd, Mariupol, Mykolaiv, Theodosius, etc.
- Stabilization of the project to avoid crashes.
- Developed a new type of the user's terminal from scratch to work with an advanced electric control system remotely.

**Junior Swift/Objective-C** Freelance _(Jul 2015 - January 2016)_
Developing an application for managing surveillance cameras from IOS(iPhone or iPad) via FFmpeg.
POC of the client application and the MVP were developed quickly.
After the designer created mockups, I applied them to the project.
The project is not live in the App Store cause the customer changed his plans.

## 📖  Education
**Diploma Master's degree in the Applied Mathematics.** in Odessa National University I.I.Mechnikov<br>
[Mechnikov University](http://onu.edu.ua/en/) - Odessa, Ukraine _(2018 - 2020)_

**Diploma Bachelor of the Applied Mathematics** in Odessa National University I.I.Mechnikov<br>
[Mechnikov University](http://onu.edu.ua/en/) - Odessa, Ukraine _(2014 - 2018)_

**[Data Science: Deep Learning in Python](https://www.udemy.com/course/data-science-deep-learning-in-python/)** on Udemy<br>
[Course Udemy](https://www.udemy.com) by Lazy Programmer Inc. _(2018)_

## 🏆 Accomplishments

**Desktop Sharing Application** _(2019)_ <br>
Developed an analog of TeamViewer for local usage called [Desktop Sharing](https://github.com/xgreenx/desktop-sharing)
via go-libp2p, c-go, and FFmpeg.

**24th place on ½ ACM-ICPC programming olympiad** _(2017)_ <br>
My team [ONU_Luckomotive](https://icpc.global/regionals/finder/SEERC-2017/standings).

**Solved many programming olympiad problems** _(2016-2017)_ <br>
To improve my skill in olympiad programming solved many problems on different online platforms for training:
- [Timus](http://acm.timus.ru/author.aspx?id=189179)
- [Codeforces](http://codeforces.com/profile/xgreenx9999)
- [E-olymp](https://www.e-olymp.com/ru/users/XGreenX99)

## 👤 About
I have an inquisitive mind and enjoy solving different problems. I like to come up with a solution to the problem,
implement it and watch how well it works :)

In my free time, I like to spend time with friends playing board games 🎲 and computer games 👾.
Like everything related to mathematics :)

I put "=)", ":)" or "=D" everywhere in my messages =D. Always in a good mood :)

<style>
img.emoji {
    height: 1em;
    width: 1em;
    margin: 0 .05em 0 .1em;
    vertical-align: -0.1em;
}
</style>
<script src="https://twemoji.maxcdn.com/v/latest/twemoji.min.js"></script>
<script>window.onload = function () { twemoji.parse(document.body);}</script>