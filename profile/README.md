<div align="center">

# Open Source BD

**Free, local-first tools and learning resources, built in Bangladesh and open to everyone.**

No accounts. No cloud lock-in. No paywalls. Just software you can run, read, and change.

[![Repositories](https://img.shields.io/badge/repositories-11-2ea44f?style=flat-square)](https://github.com/orgs/Open-Source-BD/repositories)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](#license)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)](#contributing)

</div>

---

## About

Open Source BD is a home for the projects I build in my own time. Most of them start the same way: a tool I use every day either costs money, needs an account, or sends my data somewhere I'd rather it didn't go. So I write a free version that runs on your own machine and publish the code.

The other half of the work is teaching. Good programming material in plain language is still hard to find, so some of these repos are courses written for people who want every line explained.

## Projects

### Developer tools

| Project | What it does | Stack |
| --- | --- | --- |
| [**VectisAPI**](https://github.com/Open-Source-BD/vectisapi) | Offline, cross-platform desktop API client. Requests go through a native Rust engine and everything is stored in one local SQLite file. A Postman alternative with no account and no CORS headaches. | TypeScript · Rust |
| [**next-postman**](https://github.com/Open-Source-BD/next-postman) | Browser-based, local-first API client. Send HTTP requests, run collections, stream WebSocket and SSE, and generate code and types. | TypeScript · Next.js |
| [**tunnel**](https://github.com/Open-Source-BD/tunnel) | Expose localhost to the internet with one command. A self-hosted tunnel server with TLS and auth, so you don't need a paid ngrok plan. | Rust |
| [**rs-js**](https://github.com/Open-Source-BD/rs-js) | Rust/WASM data engine for JavaScript. Deserialize once, query many times, up to 45× faster than plain JS for columnar analytics. | Rust · WASM · JavaScript |

### Apps

| Project | What it does | Stack |
| --- | --- | --- |
| [**Beluga**](https://github.com/Open-Source-BD/beluga-desktop) | Desktop AI chat and coding assistant that runs on your own OpenRouter key. Start on free models and pay only for what you use. *(Early preview)* | Rust |
| [**Alapon**](https://github.com/Open-Source-BD/alapon) | Open-source video meetings, a Google Meet alternative built on WebRTC with peer-to-peer connections and end-to-end encryption. | TypeScript · WebRTC |
| [**Calendry**](https://github.com/Open-Source-BD/calendry) | Scheduling platform in the style of Calendly. Create event types, publish availability, and let guests book through a public page. | TypeScript |
| [**CipherVault**](https://github.com/Open-Source-BD/CipherVault) | Offline-first password manager for Android. | Kotlin |

### Learning

| Project | What it does | Stack |
| --- | --- | --- |
| [**Rust for Humans**](https://github.com/Open-Source-BD/rustbook-for-human) | Learn-by-doing Rust course with a Run button on every example, a quiz after each topic, fix-the-code exercises, and flashcard review. | mdBook · JavaScript |
| [**Rust Backend for Humans**](https://github.com/Open-Source-BD/rust-book-backend) | Build a real backend with Axum, SeaORM and PostgreSQL, with every line explained. | Rust |
| [**FreeLearn**](https://github.com/Open-Source-BD/free-learn) | Free programming courses from YouTube, sorted by topic. No sign-up; your progress is saved in the browser. | TypeScript · Astro |

## What these projects have in common

- **Local first.** Your data stays on your machine unless you choose otherwise.
- **Free to use.** No subscriptions, no feature gates, no "pro" tier.
- **Readable code.** Written so someone learning can follow along.
- **MIT licensed.** Use it, fork it, ship it.

## Tech we use

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=for-the-badge&logo=webassembly&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white)

## Contributing

Bug reports, ideas and pull requests are all welcome. If you want to help:

1. Pick a project and read its README.
2. Look through the open issues, or open one describing what you'd like to change.
3. Fork the repo, make your change on a branch, and open a pull request.

Small fixes like typos, docs and tests are just as useful as new features. If you're new to open source, the learning repos are a friendly place to start.

## Support

If one of these tools saves you time, a ⭐ on the repo is the easiest way to say thanks, and it helps other people find it.

## License

Unless a repository says otherwise, projects here are released under the [MIT License](https://opensource.org/licenses/MIT).

<div align="center">

<sub>Made with care in Dhaka, Bangladesh 🇧🇩 by <a href="https://github.com/Open-Source-BD">Open Source BD</a></sub>

</div>
