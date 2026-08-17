# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.10.0](https://github.com/grpc/grpc-rust/compare/grpc-v0.9.0...grpc-v0.10.0) - 2026-08-17

### Added

- *(grpc)* add server-side Listener and Transport traits ([#2725](https://github.com/grpc/grpc-rust/pull/2725))
- *(codec)* add compression API, standard algorithms, and global reg… ([#2648](https://github.com/grpc/grpc-rust/pull/2648))
- *(grpc)* Add resolver wrapper to handle HTTP CONNECT proxy configuration ([#2679](https://github.com/grpc/grpc-rust/pull/2679))

### Fixed

- *(grpc)* percent-decode target URI path and reject non-UTF-8 characters ([#2677](https://github.com/grpc/grpc-rust/pull/2677))

### Other

- relax ordering requirement for values ([#2799](https://github.com/grpc/grpc-rust/pull/2799))
- support immediate cancellation of streams without sending End-of-Stream ([#2791](https://github.com/grpc/grpc-rust/pull/2791))
- combine client and server SecurityInfo ([#2798](https://github.com/grpc/grpc-rust/pull/2798))
- Move Address to core module; change Transport::connect to accept &Address ([#2793](https://github.com/grpc/grpc-rust/pull/2793))
- *(credentials)* make ServerCredentials trait dyn-compatible ([#2724](https://github.com/grpc/grpc-rust/pull/2724))
- fork headers/trailers to be separate between client/server ([#2792](https://github.com/grpc/grpc-rust/pull/2792))
- enable TCP no-delay and adaptive flow control ([#2781](https://github.com/grpc/grpc-rust/pull/2781))
- LICENSE and check for grpc-rust. ([#2748](https://github.com/grpc/grpc-rust/pull/2748))
- HTTP CONNECT proxy support in transport ([#2698](https://github.com/grpc/grpc-rust/pull/2698))
- License update ([#2749](https://github.com/grpc/grpc-rust/pull/2749))
- Implement grpc-status-details-bin rich error details ([#2716](https://github.com/grpc/grpc-rust/pull/2716))
- Fix typo in struct names ([#2736](https://github.com/grpc/grpc-rust/pull/2736))
- Implement Channel builder ([#2675](https://github.com/grpc/grpc-rust/pull/2675))
- expose unstable APIs behind __unstable feature ([#2728](https://github.com/grpc/grpc-rust/pull/2728))
- upgrade dependencies ([#2709](https://github.com/grpc/grpc-rust/pull/2709))
- remove duplicate "to" in graceful_switch doc comment ([#2656](https://github.com/grpc/grpc-rust/pull/2656))
- Make ChannelCredentials object safe ([#2703](https://github.com/grpc/grpc-rust/pull/2703))
- propagate trailers-only metadata ([#2691](https://github.com/grpc/grpc-rust/pull/2691))
- remove redundant timeout in transport ([#2692](https://github.com/grpc/grpc-rust/pull/2692))
- add as_bytes() for binary values ([#2690](https://github.com/grpc/grpc-rust/pull/2690))
- add payload to load_balancing's work/schedule_work ([#2670](https://github.com/grpc/grpc-rust/pull/2670))
- add subchannel attribute API ([#2672](https://github.com/grpc/grpc-rust/pull/2672))
