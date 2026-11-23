# Alexander Shaham

Gameplay and full-stack engineer. I make games and web apps.

[Portfolio](https://portfolio.ajshaham.workers.dev) · [Discord](https://discord.com/users/249029416590639107) · [Email](mailto:ajshaham@gmail.com)

## Runefall

A classless arena-and-dungeon RPG where each player builds their own kit from ten abilities. I'm making it on my own at
Chuuken Studios, in Godot 4 and C# (.NET 10). It runs on a deterministic, server-authoritative 60 Hz simulation that
doesn't depend on the engine, and one CPU core runs 41 matches at once. It's playable online through Steam's relay
network, with lag compensation and reconnect. The server enforces fog of war, and a matchmaker fills empty seats with
bots. Arenas are 1v1, 2v2 and 3v3, best of three. There's also a five-player dungeon modeled on Mythic+ with a stand-in
boss, and the first real boss is next. More than 5,000 tests cover it.

Runefall is versioned in [Diversion](https://www.diversion.dev), not GitHub, so its history doesn't show up here.

## Web apps

| App | What it does | Code |
| --- | --- | --- |
| [Guild Golem](https://guildgolem.com)<br>_live beta_ | Guild management for World of Warcraft: Forever, with raids, the roster, loot and a Discord bot, plus built-in combat logs and sims. | The site is private. Public: the [addon](https://github.com/Nuja1337/gg-addon), the [Discord bot's docs](https://github.com/Nuja1337/gg-discord) and the [desktop app's plan](https://github.com/Nuja1337/gg-desktop) |
| [Heartbeat](https://heartbeat.ajshaham.workers.dev) | A browser aim trainer that records where and how you miss, finds your weak spot and gives you a drill for it. It keeps everything in the browser, with no account. | [heartbeat](https://github.com/Nuja1337/heartbeat) |
| Dojo<br>_private_ | Python and Korean study with spaced repetition: 137 Python lessons with exercises graded by real Python in the browser, and Korean built on the official learner vocabulary list. It works offline and syncs between devices. | Private |
| [Drafts](https://drafts.ajshaham.workers.dev) | Real-time League of Legends and Dota 2 draft rooms that suggest picks and bans. | [drafts](https://github.com/Nuja1337/drafts) |
| [Tally](https://tally.ajshaham.workers.dev) | A training and nutrition log that works offline and syncs across devices without an account. | [tally](https://github.com/Nuja1337/tally) |

All five run on Cloudflare Workers. Logs and Sims, my earlier combat-log analyzer and simulator for WoW Forever, were
retired in October 2026 and rebuilt inside Guild Golem.

## Tools

| Tool | What it does | Code |
| --- | --- | --- |
| JobQuery<br>_early version_ | A desktop app that finds jobs that fit, drafts each application from your résumé and notes, fills the form in your own browser and tracks every application. It uses your own AI key and keeps everything in one local SQLite file. | [jobquery](https://github.com/Nuja1337/jobquery) · [download](https://github.com/Nuja1337/jobquery/releases/latest) |
| WeakAuras for Forever | Five other authors' WeakAuras that I ported from the TBC Anniversary client to WoW Forever, where threat, buffs and power turn secret in combat. The Lua is tested outside the game. | [weakauras-forever](https://github.com/Nuja1337/weakauras-forever) |

## Before this

- Software engineer at HCL BigFix.
- B.S. in Computer Science: Computer Game Design, UC Santa Cruz.

If you'd like to talk about any of it, [email me](mailto:ajshaham@gmail.com).
