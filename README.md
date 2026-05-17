# Awesome Discord Bots [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of notable Discord bots, organized by what they help a server do.

This repository is intended to become a browsable catalog, not a scrape of every bot directory. The primary taxonomy is a small, fixed set of categories — `Fun`, `Moderation`, `Utility`, `Music`, `Economy`, `Social`, `Game`, `Meme`, `Leveling`, `Anime` — covering the dominant use cases for Discord bots. The shape is borrowed from [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted): each category becomes a section ("topic"), and each section holds a bulleted list of bots with a consistent metadata format.

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

_Related: [Utility](#utility)_

- _Entries go here._

### Utility

**[`^        back to top        ^`](#awesome-discord-bots)**

General server utilities: reminders, role menus, ticket systems, search, embeds, forms, polls, notifications, server stats, translators, and other "swiss army knife" bots.

_Related: [Moderation](#moderation), [Social](#social)_

- _Entries go here._

### Music

**[`^        back to top        ^`](#awesome-discord-bots)**

Bots that play audio in voice channels — streaming from YouTube, Spotify, SoundCloud, direct URLs, or local libraries — with queueing, search, playlists, and playback controls.

- _Entries go here._

### Economy

**[`^        back to top        ^`](#awesome-discord-bots)**

Virtual currency, shops, trading, rewards, gambling-style minigames, inventories, jobs, and cross-server progression systems.

_Related: [Game](#game), [Leveling](#leveling)_

- _Entries go here._

### Social

**[`^        back to top        ^`](#awesome-discord-bots)**

Community interaction: profiles, reputation, introductions, birthdays, marriages, hugs, confessions, matchmaking, and other member-discovery features.

_Related: [Fun](#fun), [Leveling](#leveling)_

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

_Related: [Economy](#economy), [Social](#social)_

- _Entries go here._

### Anime

**[`^        back to top        ^`](#awesome-discord-bots)**

Anime, manga, and weeb-culture bots: AniList/MAL lookups, character image commands, waifu/husbando gacha, fandom, roleplay, and Japanese-media trackers.

_Related: [Fun](#fun), [Game](#game)_

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

SPDX short codes, mirroring the awesome-selfhosted convention. Extend as needed.

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

Markers prepended to an entry to flag traits worth knowing before inviting a bot. Adapted from awesome-selfhosted's `⚠` convention, with additions specific to Discord bots.

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

[![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)

This list is released under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).
