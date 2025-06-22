This repository provides an overview of software built around the Sugoma’s "IRC killer", the so-called RAC (Real Address Chat) protocol.

You're welcome to contribute by [sharing additional entries or information](https://github.com/MeexReay/RAC-Hub/pulls) to help expand this directory.

# Clients

| Title | Description | Author | Release | Status | Lang | RAC | WRAC |
| :---: | :---------: | :----: | :-----: | :----: | :--: | :-: | :--: |
| [bRAC](https://github.com/MeexReay/bRAC)[^1] | better RAC client (GUI) | MeexReay | [0.1.5+2.0](https://github.com/MeexReay/bRAC/releases/tag/0.1.5%2B2.0) | Active |    Rust | v2.0 | v2.0 |
| [сRACk](https://github.com/pansangg/cRACk)[^5] | client for RAC kettles (TUI) | pansangg | [v2.0-beta](https://github.com/pansangg/cRACk/releases/tag/v2.0-beta) | Active | Python | v2.0 | ❌ |
| clRAC | The official RAC client | Mr. Sugoma | [2.0.1](https://wdfiles.ru/Ofx7) | Active | C | v2.0 | ❌ |
| [Mefedroniy](https://github.com/OctoBanon-Main/mefedroniy-client) | TUI client for RAC | OctoBanon | [v1.3.1+1.99.2](https://github.com/OctoBanon-Main/mefedroniy-client/releases/tag/v1.3.1%2B1.99.2) | Active | Rust | v1.99.2 | ❌ |
| [RAC.rs](https://github.com/kostya-zero/rac-rs) | Rust library for RAC client (used by [Tower](https://github.com/kostya-zero/tower)) | Kostya Zero | [0.1.0](https://crates.io/crates/rac_rs/0.1.0) | Active | Rust | v2.0 | v2.0 |
| [Tower](https://github.com/kostya-zero/tower) | GUI client for RAC developed using Tauri | Kostya Zero | ❌ | Active | Rust | v2.0 | v2.0 |
| [Snowdrop](https://github.com/Forbirdden/Snowdrop) | WRAC GUI client | Forbirdden  | ❌ | Active | JavaScript | ❌ | v2.0 |
| [CRAB](https://gitea.bedohswe.eu.org/pixtaded/crab) | Bundle with both client and server | pixtaded | [2.0.0](https://gitea.bedohswe.eu.org/pixtaded/crab/releases/tag/2.0.0-snapshot-202502092015) | Frozen | Java | v1.99.2 | ❌ |
| [Dobroho Vechora](https://gitea.bedohswe.eu.org/bedohswe/dobroho_vechora) | The first open-source client | Bʰedoh₂ swé | [Source code](https://gitea.bedohswe.eu.org/bedohswe/dobroho_vechora/raw/branch/main/dobroho_vechora.bash) | Abandoned | Bash | v1.0[^2] | ❌ |
| lRAC | The first original RAC client using tkinter | Mr. Sugoma | [1.0.2](https://github.com/MeexReay/RAC-Hub-Archive/tree/main/lRAC/1.0.2) | Abandoned | Python | v1.0[^4] | ❌ |

<!-- | WebbyCRAB | Fork of CRAB that runs online using TeaVM | Forbirdden  | ❌ | Abandoned | Java | v1.0, v1.99.2 | ❌ | -->
<!-- | WinRAC | GUI client for RAC developed using WinForms | cat8753 |  | Abandoned | C# | v1.99.2 | ❌ | -->

[^1]: bRAC-0.1.3+2.0 requires GTK4 to be installed on Windows [(see more)](https://github.com/MeexReay/bRAC/releases/tag/0.1.3%2B2.0#user-content-window-gui-install)
[^2]: "_Я раньше хотел допилить его до v2, но мой bash код было трудно обновить_" - chunbyonga
[^5]: "_Не срал с утра или прошлого вечера, терпел ради cRACkа._" - pansangg

# Server software

| Title | Description | Author | Release | Status | Lang | RAC | WRAC |
| :---: | :---------: | :----: | :-----: | :----: | :--: | :-: | :--: |
| [sRAC](https://github.com/MeexReay/sRAC) | simple RAC server | MeexReay | [1.0.0](https://github.com/MeexReay/sRAC/releases) | Active | Rust | v2.0 | v2.0 |
| lRACd | The official RAC server | Mr. Sugoma | [2.0.9](https://wdfiles.ru/Obvt) | Active | C | v2.0 | ❌ |
| [CRAB](https://gitea.bedohswe.eu.org/pixtaded/crab) | Bundle with both client and server | pixtaded | [2.0.0](https://gitea.bedohswe.eu.org/pixtaded/crab/releases/tag/2.0.0-snapshot-202502092015) | Frozen | Java | v1.99.2 | ❌ | 
| [AlmatyD](https://gitea.bedohswe.eu.org/bedohswe/almatyd) | Open source server | Bʰedoh₂ swé | [Source code](https://gitea.bedohswe.eu.org/bedohswe/almatyd) | Abandoned[^3] | TypeScript | v1.0 | ❌ |

<!-- | Gashishnik | WRAC server | OctoBanon | Soon... | In development | Rust | ❌ | v2.0 | -->
<!-- | WebbyCRAB | Fork of CRAB that runs online using TeaVM | Forbirdden  | ❌ | Abandoned | Java | v1.99.2 |  ❌  | -->
<!-- | Butter | Simple Node.js RAC server | Forbirdden | ❌ | Abandoned | JavaScript | v1.99.2, v2.0 |  ❌  | -->

[^3]: "_Мне лень его допиливать. Если тебе зачем-то очень нужен RAC сервер, то ставь CRAB._" - chunbyonga

# Known servers

|       Address        |              Description              |                 Software                 | Status | Protocol  |   Auth   |
| :------------------: | :-----------------------------------: | :--------------------------------------: | :----: | :-------: | :------: |
| 91.192.22.20:42666   | Official server by Mr. Sugoma         | lRACd (2.0.9)                            | Active | RACv2.0   | Optional |
| meex.lol:11234       | WRACS tor proxy of 91.192.22.20:42666 | [sRAC](https://github.com/MeexReay/sRAC) | Active | WRACSv2.0 | Optional |
| meex.lol:42666       | RAC proxy of meex.lol:52667           | [sRAC](https://github.com/MeexReay/sRAC) | Active | RACv2.0   | Required |
| meex.lol:52667       | Official WRACS server                 | [sRAC](https://github.com/MeexReay/sRAC) | Active | WRACSv2.0 | Required |

# Protocol documentation

The following documents cover the structure, behavior, and expectations of RAC and WRAC protocols:

- [RACv1.0](RACv1.md)[^4]
- [RACv1.99.x](RACv1.99.md)
- [RACv2.0](RACv2.md)
- [WRACv2.0](WRAC.md)
- [Extensions](USERS_ADDITIONS.md)

[^4]: "_Про RAC 1 вообще забудь, это днище, его юзать нельзя._" - Mr. Sugoma

# See also

- [Project sources](https://github.com/MeexReay/RAC-Hub)
- [Historical archives](https://github.com/MeexReay/RAC-Hub-Archive)

<br>

[<img src="https://github.com/user-attachments/assets/f2be5caa-6246-4a6a-9bee-2b53086f9afb" height="50">]() [<img src="https://github.com/user-attachments/assets/4d35191d-1dbc-4391-a761-6ae7f76ba7af" height="50">]()

This project was inspired by the ideas from [The-Stratosphere-Solutions/RAC-Hub](https://github.com/The-Stratosphere-Solutions/RAC-Hub), but all text and documentation have been created independently.
