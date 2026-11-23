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

I'm also writing its world, a dark-fantasy setting kept separate from the mechanics. Excerpts are on request.

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
| [My portfolio](https://portfolio.ajshaham.workers.dev) | Version five, in Astro and TypeScript, with two skins, hero art generated in code at build time, a dev console and a blog. Tested with Vitest, Playwright and axe. | [portfolio](https://github.com/Nuja1337/portfolio) |
| Chuuken Studios website<br>_unannounced_ | The studio's public site and a private team site behind Cloudflare Access, built as two Workers from one repo. Before every deploy, a leak check scans the public build for secret terms. | Private |
| Chuuken Studios pipeline | A Discord dev server set up by a Node.js script, with GitHub webhooks for commits, pull requests, builds and issues, and a bot that posts a game design reading every morning. | Private |

## Games from school and game jams

| Game | What it is | My role |
| --- | --- | --- |
| Queen of the Hill | An idle clicker where you grow an ant colony one tap at a time. JavaScript. | Programmer and producer, team of 5 |
| Wordle Cube | Wordle, except the letters live on the faces of a Rubik's cube you have to solve. Unity. | Solo |
| RetrOsu | A precision clicking game inspired by osu!. JavaScript. | Programmer, team of 2 |
| Keepie Uppies | An infinite runner for Android about staying in the air, with themes to unlock. Unity. | Programmer, team of 5 |
| Puffed Up | A pufferfish knight fights through a dangerous dungeon. Phaser 3. | Programmer and producer, team of 3 |
| BarF | A salaryman's night of shenanigans after clocking out. Phaser 3. | Programmer and producer, team of 3 |
| Beast Within | A story-driven game made in 48 hours for Ludum Dare 49, on the theme Unstable. Phaser 3. | Programmer and producer, team of 3 |
| Scrapper Bots<br>_prototype_ | Turn-based tactics on a hex grid, where destroyed units leave wrecks your squad harvests for armor and charge. Unity. | Game designer, team of 7 |

Most of their code is private. The portfolio has more on each.

## Smaller projects

- **Fakebook Marketplace:** a recreation of Facebook Marketplace for UC Santa Cruz's web development course, on a team
  of 3. I built the React front end. The code stays private by course policy, so there's a
  [video walkthrough](https://www.youtube.com/watch?v=fYKFSpuTiNs).
- **Cloato:** a high-fidelity Figma prototype for organizing your closet and planning outfits. I did the UI/UX design on
  a team of 4.
- **Easy Waiver:** one-tap guest waivers for a gym's guest pass, so a guest doesn't refill a long form every visit.
- **Wordle Guesser:** lists every word your Wordle guesses still allow, likeliest first.

## Experience

- **Independent game developer, Chuuken Studios** (Feb 2026 to now): Runefall.
- **Software Engineer II, HCL BigFix** (May 2023 to Feb 2025, converted from intern): built the React and Material UI
  component library that 100+ engineers in 7+ apps shipped with, moved global state to Zustand, and added Tenable SC
  and IO to the security ingestion pipeline.
- **Independent trader** (Feb 2025 to Feb 2026): traded stocks full time with my own capital, using Python scripts for
  price data, backtests and alerts.
- **Freelance web developer** (Sep 2022 to Jan 2023): an accessible, multilingual React landing page for a healthcare
  clinic.
- **QA engineering intern, King Nutronics** (summer 2018): tested U.S. Navy calibration hardware and automated the test
  beds, cutting testing time by about 80%.
- **B.S. in Computer Science: Computer Game Design, UC Santa Cruz** (2017 to 2022).

## Skills

- **Languages:** C#, C++, TypeScript, JavaScript, Python, SQL, GDScript, Java
- **Engines:** Godot 4 (.NET), Unreal Engine 5 (C++, Blueprints, GAS), Unity, Phaser
- **Games:** server-authoritative netcode, deterministic simulation, Steamworks, combat and ability systems, PvP
  balance, encounter design
- **Web:** React, React Router, Next.js, Node.js, Hono, ASP.NET Core, PostgreSQL, SQLite, PWAs
- **Infrastructure:** Cloudflare Workers, D1, R2, Durable Objects, Docker, Linux, GitHub Actions
- **Testing:** xUnit, Vitest, Jest, Playwright

If you'd like to talk about any of it, [email me](mailto:ajshaham@gmail.com).
