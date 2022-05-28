# Anatolii Osetsymskyi

_Rust/C++/GO Software and Blockchain Developer, Live in Amsterdam, Netherland. Resident of Ukraine_

[Email](xgreenx9999@gmail.com) / [LinkedIn](https://www.linkedin.com/in/aostesymskyi/) / [GitHub](https://github.com/xgreenx) / [Telegram](https://t.me/xgreenx99) / +380663944720

## 🔧 Development preferences 

- Main languages:
  - Rust - the language that I want to work with right now. I enjoy its features, proc macros, and memory management.
  - C/C++ - my first language from the university. I like its low-level stuff.
  - Golang - goroutines are a fantastic feature and a perfect fit for writing asynchronous code.
- Secondary languages:
  - Javescript/Nodejs - every project that I worked on somehow required the usage of JS.
  - Swift/Objective-C - in my free time, I like to develop some applications on my smartphone.
  - C#/Java - studied in the university and after interacting with it on different works.
  - Haxe - it is an unusual language, but I used it for around two years together with C++.
  - Python - in the university, I played with machine learning, and I have basic knowledge of that language.
- OS:
  - Mac OS - last 2 years I'm using that system as main.
  - Linux - it was the primary system for development before Mac OS. I worked with Ubuntu image and tried Debian and other distributives in most cases.
  - Windows - used that system for development at the beginning of my career. But honestly, it doesn't fit for development=)
	

## 👩🏼‍💻 Work experience

**Rust Core Blockchain Developer** [Supercolony](https://supercolony.net) _(April 2021 - Present)_

The work is related to evolving of the ecosystem and WASM smart contract development. Except for that, 
there was several project of portfolio companies related to ink!, substrate development.
- Successfully ported two big projects from Solidity to ink!(30+ contracts) that increased the coverage of audience.
- Designed and implemented [OpenBrush](https://github.com/Supercolony-net/openbrush-contracts) as a first library(analog of OpenZeppelin) to ease out WASM smart contract development experience in the dotsama community.
- Implemented functionality for upgradeable contracts on all execution layers.
- Designed(traits - soon link to the issue, [event](https://github.com/paritytech/ink/pull/1243) refactoring) and implemented([storage](https://github.com/paritytech/ink/issues/1134), [dispatching](https://github.com/paritytech/ink/pull/1017)) major features in the ink! to improve the language syntax and simplify the development.
- Designed the architecture of substrate-based blockchain with inner yield protocols.
- Decreased the size of smart contracts(10-15%) to improve on-chain performance.
- Designed and implemented standards of [Fungible](https://github.com/w3f/PSPs/blob/master/PSPs/psp-22.md), [Non-Fungible](https://github.com/w3f/PSPs/blob/master/PSPs/psp-34.md), and [Multi tokens](https://github.com/w3f/PSPs/blob/master/PSPs/drafts/psp-35.md) to unify the interface for the WASM smart contract ecosystem.
- Optimized(x25) the Graph indexer for PancakeSwap to process transactions with the speed of the binance smart chain.

During the work, I interviewed candidates.

**GO/C++/Rust Core Blockchain Developer** [ProximaX](https://www.proximax.io) _(April 2020 - April 2021)_

The main idea of the project is decentralized storage(DFMS written on Golang) built on top of 
the blockchain(C++) with an execution layer for smart contracts(WASM Rust/TS Assemblyscript).
- Design(for the blockchain and DFMS) a new, more secure version of the storage with an improved flow for users and storage providers.
- Implemented main plugins(analogs of Cosmos Modules but on C++) of a new business logic on the blockchain.
- Refactored the logic of the Merkel tree calculation and optimized(x2) the work of the unconfirmed cache.
- Refactored the [Golang SDK](https://github.com/proximax-storage/go-xpx-chain-sdk) to be compatible with a new blockchain version.
- Fully rework the execution level of the DFMS.
  - Implemented a new system of events to parallelize the execution and fix previous bugs related to conflicting executions.
  - Changed the work with storage to lock only data cells related to execution instead of the whole storage.
  - Added support of new host functions and integrated them into VM to increase the functionality.
  - Designed and implemented the consensus of executors for non-deterministic operations like HTTP requests etc.
- Implemented simple [TS Assemblyscript](https://github.com/proximax-storage/ts-xpx-supercontract-sdk) to write smart contracts with TypeSccript and compile them into WASM to run on executors. 
- Debugging and fixing bugs on the blockchain side related to an inconsistent state, corrupted pointers, incorrect state reverts, vulnerabilities related to DDoS, and invalid transaction propagation.


**C++/GO Blockchain Developer** [482.solutions](https://482.solutions) _(August 2018 - April 2020)_




TODO:
Board games
Mathematic
