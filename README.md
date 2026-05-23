# Awesome Discord Bots

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of notable Discord bots, organized by what they help a server do.

This repository is intended to become a browsable catalog, not a scrape of every bot directory. The primary taxonomy starts with top.gg's broad Discord bot categories and adds consolidated sections from recurring top.gg tags: `Fun`, `Moderation`, `Utility`, `Music`, `Economy`, `Social`, `Game`, `Meme`, `Leveling`, `Anime`, `Administration`, `AI`, `Automation`, `Crypto`, `Giveaways`, `Logging`, `Media`, `Onboarding`, `Productivity`, `Role Management`, `Security`, `Support & Tickets`, and `Temporary Voice Channels`. Each category becomes a section ("topic"), and each section holds a bulleted list of bots with a consistent metadata format.

See [Contributing](#contributing).

--------------------

## Table of contents

- [Bots](#bots)
  - [Fun](#fun)
  - [Moderation](#moderation)
  - [Utility](#utility)
  - [Music](#music)
  - [Economy](#economy)
  - [Social](#social)
  - [Game](#game)
  - [Meme](#meme)
  - [Leveling](#leveling)
  - [Anime](#anime)
  - [Administration](#administration)
  - [AI](#ai)
  - [Automation](#automation)
  - [Crypto](#crypto)
  - [Giveaways](#giveaways)
  - [Logging](#logging)
  - [Media](#media)
  - [Onboarding](#onboarding)
  - [Productivity](#productivity)
  - [Role Management](#role-management)
  - [Security](#security)
  - [Support & Tickets](#support--tickets)
  - [Temporary Voice Channels](#temporary-voice-channels)
- [Entry Format](#entry-format)
- [Cross-Cutting Indexes](#cross-cutting-indexes)
- [Inclusion Criteria](#inclusion-criteria)
- [List of Licenses](#list-of-licenses)
- [Anti-features](#anti-features)
- [Contributing](#contributing)
- [License](#license)

--------------------

## Bots

### Fun

**[`^        back to top        ^`](#awesome-discord-bots)**

Entertainment, casual interaction, party-game, novelty, and engagement bots. The catch-all category for bots that don't fit a more specific tag.

_Related: [Meme](#meme), [Game](#game), [Social](#social)_

- _Entries go here. See [Entry Format](#entry-format)._

### Moderation

**[`^        back to top        ^`](#awesome-discord-bots)**

Automod, anti-spam, raid protection, logging, permissions, warnings, bans, reports, member screening, and staff workflow bots.

_Related: [Utility](#utility), [Security](#security), [Logging](#logging), [Administration](#administration)_

- [MEE6](https://mee6.xyz/) - Moderation, leveling, and welcome/role automation bot. ([Invite](https://mee6.xyz/add), [Docs](https://help.mee6.xyz/)) `Proprietary` `Unknown` `Hosted` `Leveling` `Dashboard`
  <details><summary>Slash commands (8)</summary>

  **Moderation**
  - `/ban <user> [reason]` — Ban a member from the server.
  - `/kick <user> [reason]` — Kick a member from the server.
  - `/warn <user> <reason>` — Issue a warning to a member.
  - `/mute <user> <duration> [reason]` — Time-out a member.
  - `/clear <amount>` — Bulk-delete recent messages.

  **Leveling**
  - `/rank [user]` — Show a member's level, XP, and server rank.
  - `/levels` — Open the server XP leaderboard.
  - `/give-xp <user> <amount>` — Award XP to a member (admin-only).

  _Last verified: 2026-05-17 · [Full reference](https://help.mee6.xyz/)_
  </details>

### Utility

**[`^        back to top        ^`](#awesome-discord-bots)**

General server utilities: reminders, role menus, ticket systems, search, embeds, forms, polls, notifications, server stats, translators, and other "swiss army knife" bots.

_Related: [Moderation](#moderation), [Social](#social), [Automation](#automation), [Role Management](#role-management), [Support & Tickets](#support--tickets), [Productivity](#productivity)_

- _Entries go here._

### Music

**[`^        back to top        ^`](#awesome-discord-bots)**

Bots that play audio in voice channels — streaming from YouTube, Spotify, SoundCloud, direct URLs, or local libraries — with queueing, search, playlists, and playback controls.

_Related: [Media](#media)_

- _Entries go here._

### Economy

**[`^        back to top        ^`](#awesome-discord-bots)**

Virtual currency, shops, trading, rewards, gambling-style minigames, inventories, jobs, and cross-server progression systems.

_Related: [Game](#game), [Leveling](#leveling), [Crypto](#crypto)_

- _Entries go here._

### Social

**[`^        back to top        ^`](#awesome-discord-bots)**

Community interaction: profiles, reputation, introductions, birthdays, marriages, hugs, confessions, matchmaking, and other member-discovery features.

_Related: [Fun](#fun), [Leveling](#leveling), [Onboarding](#onboarding)_

- _Entries go here._

### Game

**[`^        back to top        ^`](#awesome-discord-bots)**

In-chat games (chess, poker, RPG, idle/clicker), companion bots for external games (stats lookups for League, Valorant, Minecraft, etc.), LFG/matchmaking, leaderboards, and game-server status integrations.

_Related: [Fun](#fun), [Economy](#economy)_

- _Entries go here._

### Meme

**[`^        back to top        ^`](#awesome-discord-bots)**

Meme generators, image macros, reaction-image libraries, joke commands, and bots whose entire purpose is to be very online.

_Related: [Fun](#fun)_

- _Entries go here._

### Leveling

**[`^        back to top        ^`](#awesome-discord-bots)**

XP and ranking systems that reward chat or voice activity with levels, role rewards, achievements, and leaderboards.

_Related: [Economy](#economy), [Social](#social), [Role Management](#role-management)_

- _Entries go here._

### Anime

**[`^        back to top        ^`](#awesome-discord-bots)**

Anime, manga, and weeb-culture bots: AniList/MAL lookups, character image commands, waifu/husbando gacha, fandom, roleplay, and Japanese-media trackers.

_Related: [Fun](#fun), [Game](#game), [Media](#media)_

- _Entries go here._

### Administration

**[`^        back to top        ^`](#awesome-discord-bots)**

Server setup and administration bots: configuration panels, permission workflows, channel/server management, staff utilities, announcement tooling, and management dashboards. Consolidates screenshot tags such as `Administration`, `Server Management`, `Management`, `Tools`, and `Web Dashboard`.

_Related: [Utility](#utility), [Moderation](#moderation), [Role Management](#role-management)_

- _Entries go here._

### AI

**[`^        back to top        ^`](#awesome-discord-bots)**

AI assistant, chatbot, summarization, image generation, prompt, and LLM-powered moderation or utility bots. Consolidates screenshot tags such as `ai`, `AI Chatbot`, `Artificial Intelligence`, `Chat bot`, and `image generation`.

_Related: [Utility](#utility), [Media](#media)_

- _Entries go here._

### Automation

**[`^        back to top        ^`](#awesome-discord-bots)**

Workflow automation bots: scheduled messages, trigger/action rules, recurring tasks, cross-service integrations, no-code automations, and configurable behavior systems.

_Related: [Utility](#utility), [Productivity](#productivity)_

- _Entries go here._

### Crypto

**[`^        back to top        ^`](#awesome-discord-bots)**

Cryptocurrency and Web3 bots: price tracking, token alerts, wallet or portfolio lookups, NFT/community utilities, and market notifications.

Not here: fictional server currencies, shops, and gambling economies (→ [Economy](#economy)).

_Related: [Economy](#economy), [Utility](#utility)_

- _Entries go here._

### Giveaways

**[`^        back to top        ^`](#awesome-discord-bots)**

Giveaway, raffle, contest, winner-picking, reward distribution, and timed event bots.

_Related: [Economy](#economy), [Social](#social)_

- _Entries go here._

### Logging

**[`^        back to top        ^`](#awesome-discord-bots)**

Audit and history bots: message logs, moderation logs, member join/leave logs, voice activity logs, invite tracking, transcript capture, and incident records.

_Related: [Moderation](#moderation), [Security](#security), [Support & Tickets](#support--tickets)_

- _Entries go here._

### Media

**[`^        back to top        ^`](#awesome-discord-bots)**

Media and feed bots: YouTube/Twitch/Reddit notifications, stream alerts, image search, image utilities, radio directories, Spotify metadata, and content lookup.

Not here: voice-channel music playback bots (→ [Music](#music)).

_Related: [Music](#music), [Utility](#utility), [AI](#ai)_

- _Entries go here._

### Onboarding

**[`^        back to top        ^`](#awesome-discord-bots)**

Welcomer, verification, captcha, rules acceptance, starter role, join-flow, and newcomer orientation bots.

_Related: [Moderation](#moderation), [Security](#security), [Role Management](#role-management)_

- _Entries go here._

### Productivity

**[`^        back to top        ^`](#awesome-discord-bots)**

Productivity and collaboration bots: reminders, notes, calendars, tasks, project tracking, documentation helpers, meeting support, and focused work utilities.

_Related: [Utility](#utility), [Automation](#automation)_

- _Entries go here._

### Role Management

**[`^        back to top        ^`](#awesome-discord-bots)**

Role assignment and permission bots: reaction roles, button/dropdown role menus, autoroles, temporary roles, role persistence, and role-based access control.

_Related: [Utility](#utility), [Leveling](#leveling), [Onboarding](#onboarding)_

- _Entries go here._

### Security

**[`^        back to top        ^`](#awesome-discord-bots)**

Server protection bots: anti-nuke, anti-raid, anti-spam, phishing/link filtering, alt detection, account-age checks, lockdown tools, and abuse prevention.

_Related: [Moderation](#moderation), [Logging](#logging), [Onboarding](#onboarding)_

- _Entries go here._

### Support & Tickets

**[`^        back to top        ^`](#awesome-discord-bots)**

Support desk and ticket bots: private ticket channels, staff assignment, forms, transcripts, escalation, support queues, and helpdesk workflows.

_Related: [Utility](#utility), [Logging](#logging), [Administration](#administration)_

- _Entries go here._

### Temporary Voice Channels

**[`^        back to top        ^`](#awesome-discord-bots)**

Dynamic voice-channel bots: temporary rooms, user-owned voice channels, channel locks, limits, renaming, voice lobbies, and cleanup automation.

_Related: [Social](#social), [Utility](#utility), [Automation](#automation)_

- _Entries go here._

--------------------

## Entry Format

Each bullet follows this pattern:

```markdown
- [Bot Name](primary-link) - One- or two-sentence description of what it does. ([Invite](invite-url), [Source Code](repo-url), [Docs](docs-url), [Support](support-server-invite)) `License` `Language/Stack` `Hosted|Self-hosted|Both`
```

Field-by-field:

- **Bot Name** — the bot's display name. Link target is the bot's landing page if it has one, otherwise its repository.
- **Description** — what the bot does, in plain language.
- **Parenthesised links** — any subset of the following, in this order, separated by commas. Omit the parentheses entirely if none apply.
  - `[Invite]` — direct OAuth2 invite URL.
  - `[Source Code]` — repository URL. Omit for closed-source bots.
  - `[Docs]` — user-facing command reference or guide.
  - `[Support]` — invite to the bot's support Discord server.
- **`License`** — SPDX identifier from the [List of Licenses](#list-of-licenses), or `Proprietary` for closed source.
- **`Language/Stack`** — primary language and/or framework, e.g. `Python/discord.py`, `Nodejs/discord.js`, `Rust/serenity`, `Go/DiscordGo`. `Unknown` is acceptable for closed-source bots.
- **`Hosted|Self-hosted|Both`** — whether the bot is offered as a public hosted instance you invite, something you run yourself, or both.

Additional descriptive tags may be appended in backticks: `Slash Commands`, `Dashboard`, `Premium`, secondary category tags such as `Utility`, etc.

[Anti-feature](#anti-features) markers are prepended to the entry, e.g. `- ⚠ 📢 [Bot Name](...) - ...`.

### Slash commands block

Each entry may include a collapsible list of the bot's notable slash commands, placed immediately below the entry line. Use GitHub's native `<details>` / `<summary>` so the commands stay hidden by default and the section remains scannable.

Shape:

```markdown
- [Bot Name](…) - Description. (…) `License` `Stack` `Hosted`
  <details><summary>Slash commands (N)</summary>

  **Sub-category**
  - `/command <required> [optional]` — Short description.
  - `/parent subcommand <arg>` — Short description.

  **Another sub-category**
  - `/foo` — Short description.

  _Last verified: YYYY-MM-DD · [Full reference](docs-url)_
  </details>
```

Rules:

- **Scope** — list the bot's *key* commands, capped at roughly 10–15. This is a catalog, not full documentation; link to the bot's own docs for the complete reference.
- **Notation** — `<arg>` for required options, `[arg]` for optional, matching Discord docs convention. Flatten subcommands into the slash path: `/giveaway start <duration> [winners]`, not nested entries.
- **Grouping** — group commands under bold sub-category headings (e.g. `**Moderation**`, `**Music**`) when the bot has more than ~5 commands; a flat list is fine below that.
- **`N` in summary** — actual count of commands listed in the block, not the bot's true total.
- **Footer** — every block ends with `_Last verified: YYYY-MM-DD · [Full reference](…)_`. The date is the day the list was confirmed against upstream; the reference link is the bot's official command docs.
- **Optional** — entries without a verified command list simply omit the block.

Rendering gotchas (these trip up the first time):

1. The `<details>` block is indented **2 spaces** so it stays inside the parent list item.
2. There must be a **blank line after `<summary>`** and a **blank line before `</details>`**, otherwise GitHub treats the body as raw HTML and the bullets won't render.
3. `<details>` is inline HTML — if a markdown linter is added later, allow-list the `details` and `summary` tags (markdownlint MD033).

Worked example (illustrative — verify the command list against the bot's docs before using this as a real curated entry):

```markdown
- [MEE6](https://mee6.xyz/) - Moderation, leveling, and welcome/role automation bot. ([Invite](https://mee6.xyz/add), [Docs](https://help.mee6.xyz/)) `Proprietary` `Unknown` `Hosted`
  <details><summary>Slash commands (8)</summary>

  **Moderation**
  - `/ban <user> [reason]` — Ban a member from the server.
  - `/kick <user> [reason]` — Kick a member from the server.
  - `/warn <user> <reason>` — Issue a warning to a member.
  - `/mute <user> <duration> [reason]` — Time-out a member.
  - `/clear <amount>` — Bulk-delete recent messages.

  **Leveling**
  - `/rank [user]` — Show a member's level, XP, and server rank.
  - `/levels` — Open the server XP leaderboard.
  - `/give-xp <user> <amount>` — Award XP to a member (admin-only).

  _Last verified: 2026-05-17 · [Full reference](https://help.mee6.xyz/)_
  </details>
```

Rendered, that produces an entry whose summary line shows `▶ Slash commands (8)` and expands to the grouped list when clicked.

--------------------

## Cross-Cutting Indexes

Secondary indexes, not the main taxonomy. Add them only when the list becomes large enough that tag sections alone are hard to scan.

- Open-source bots
- Self-hostable bots
- Bots with dashboards
- Developer- and API-focused bots
- Archived or inactive bots

--------------------

## Inclusion Criteria

A bot should meet most of these before it is added:

- Publicly usable, installable, or self-hostable.
- Has a clear landing page, documentation, or source repository.
- Solves a recognizable Discord server problem.
- Maintained, or its inactive status is clearly marked with `🛑`.
- Has enough reputation signals to justify curation: usage, community adoption, source availability, or strong documentation.

Avoid entries that are:

- Abandoned without notice or archived without a useful reason to keep them.
- Pure clones with no meaningful documentation or differentiation.
- Unclear about permissions, privacy-sensitive behavior, or required access.
- Only advertisements without enough public information to evaluate.

--------------------

## List of Licenses

**[`^        back to top        ^`](#awesome-discord-bots)**

SPDX short codes. Extend as needed.

- `AGPL-3.0` - [GNU Affero General Public License 3.0](https://spdx.org/licenses/AGPL-3.0.html)
- `Apache-2.0` - [Apache License, Version 2.0](https://spdx.org/licenses/Apache-2.0.html)
- `BSD-2-Clause` - [BSD 2-Clause "Simplified" License](https://spdx.org/licenses/BSD-2-Clause.html)
- `BSD-3-Clause` - [BSD 3-Clause "New" or "Revised" License](https://spdx.org/licenses/BSD-3-Clause.html)
- `GPL-2.0` - [GNU General Public License 2.0](https://spdx.org/licenses/GPL-2.0.html)
- `GPL-3.0` - [GNU General Public License 3.0](https://spdx.org/licenses/GPL-3.0.html)
- `LGPL-3.0` - [GNU Lesser General Public License 3.0](https://spdx.org/licenses/LGPL-3.0.html)
- `MIT` - [MIT License](https://spdx.org/licenses/MIT.html)
- `MPL-2.0` - [Mozilla Public License 2.0](https://spdx.org/licenses/MPL-2.0.html)
- `Unlicense` - [The Unlicense](https://spdx.org/licenses/Unlicense.html)
- `Proprietary` - Closed source, no public license terms.

--------------------

## Anti-features

**[`^        back to top        ^`](#awesome-discord-bots)**

Markers prepended to an entry to flag traits worth knowing before inviting a bot.

- `⚠` - Closed source / no public repository.
- `$` - Core advertised features are gated behind a paid premium tier.
- `📢` - Displays ads (in command output, status, or DMs).
- `🔒` - Requires `Administrator` or an unusually broad permission scope to function at all.
- `🛑` - Appears unmaintained (no release or commit in the last 12 months, or known to be EOL).
- `☁` - Hosted-only — no self-hosting option, even if the source is published.

--------------------

## Contributing

When adding a bot, choose exactly one primary category section and follow the [Entry Format](#entry-format). If a bot spans multiple categories, add secondary tags at the end of the entry instead of duplicating it.

Pull-request checklist:

1. Entry lives under the most appropriate category section.
2. Follows the exact [Entry Format](#entry-format), including spacing, punctuation, and field order.
3. Alphabetically sorted within its section.
4. Carries any applicable [anti-feature](#anti-features) markers.
5. Links to a bot that is currently online and accepting invites (or, for self-hosted bots, builds and runs from a current commit).

One bot per PR for first-time contributors; bulk additions are fine for trusted maintainers.

--------------------

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under the [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) public domain dedication.
