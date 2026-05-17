# Awesome Discord Bots [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of notable Discord bots, organized by what they help a server do.

This repository is intended to become a browsable catalog, not a scrape of every
bot directory entry. The first taxonomy should follow the public Top.gg bot tags
captured in [top_gg-tags.md](top_gg-tags.md), with light normalization for
readability.

## Contents

- [Curation Model](#curation-model)
- [Entry Format](#entry-format)
- [Bots by Top.gg Tag](#bots-by-topgg-tag)
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
- [Cross-Cutting Indexes](#cross-cutting-indexes)
- [Inclusion Criteria](#inclusion-criteria)
- [Research Notes](#research-notes)
- [Contributing](#contributing)
- [License](#license)

## Curation Model

Use Top.gg tags as the main topic sections. Each bot should appear once, under
its strongest primary use case, and any secondary uses should be expressed as
inline metadata tags.

Recommended rules:

- Keep sections alphabetical by bot name once entries are added.
- Prefer the bot's official site, docs, or Top.gg page as the main link.
- Add source code only when the bot is actually open source.
- Do not include live server counts, votes, or pricing claims unless they are
  generated from maintained data.
- Use short, neutral descriptions that say what the bot does, not how great it is.
- Put multi-purpose bots under their clearest primary category instead of
  duplicating them across sections.

## Entry Format

```markdown
- [Bot Name](https://example.com/) - One-sentence objective description.
  ([Top.gg](https://top.gg/), [Website](https://example.com/), [Docs](https://example.com/docs), [Source Code](https://github.com/example/bot)) `Secondary Tag` `Open Source` `Dashboard`
```

Suggested optional metadata:

- `Open Source`
- `Dashboard`
- `Self-hostable`
- `Slash Commands`
- `Premium`
- Secondary Top.gg tags such as `Utility`, `Economy`, or `Anime`

## Bots by Top.gg Tag

### Fun

Entertainment, casual interaction, party-game, novelty, and engagement bots.

### Moderation

Automod, logging, anti-spam, permissions, warnings, bans, reports, and staff
workflow bots.

### Utility

General server utilities, reminders, search, embeds, forms, automation,
notifications, statistics, and workflow helpers.

### Music

Audio playback, queues, playlists, radio, voice-channel entertainment, and music
control bots.

### Economy

Virtual currency, shops, trading, rewards, gambling-style minigames, inventory,
and progression systems.

### Social

Community interaction, profiles, reputation, introductions, birthdays, events,
polls, and relationship or member-discovery features.

### Game

Game-specific integrations, gaming communities, match tracking, leaderboards,
LFG, esports, and interactive game bots.

### Meme

Image macros, meme generation, reaction content, joke commands, and humorous
media bots.

### Leveling

XP, ranks, role rewards, activity tracking, leaderboards, achievements, and
member progression bots.

### Anime

Anime, manga, character, gacha, fandom, roleplay, and media lookup bots.

## Cross-Cutting Indexes

These should remain secondary indexes, not the main taxonomy. Add them only when
the list becomes large enough that tag sections alone are hard to scan.

- Open-source bots
- Self-hostable bots
- Bots with dashboards
- Developer and API-focused bots
- Archived or inactive bots

## Inclusion Criteria

A bot should meet most of these before it is added:

- It is publicly usable, installable, or self-hostable.
- It has a clear landing page, documentation, Top.gg listing, or source
  repository.
- It solves a recognizable Discord server problem.
- It is maintained, or its inactive status is clearly marked.
- It has enough reputation signals to justify curation, such as usage,
  community adoption, source availability, or strong documentation.

Avoid entries that are:

- Abandoned without notice or archived without a useful reason to keep them.
- Pure clones with no meaningful documentation or differentiation.
- Unclear about permissions, privacy-sensitive behavior, or required access.
- Only advertisements without enough public information to evaluate.

## Research Notes

The proposed structure borrows the broad shape of
[awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted):
topic sections, concise section descriptions, bullet entries, optional related
links, and metadata at the end of each entry.

It also follows the common Awesome list convention from
[sindresorhus/awesome](https://github.com/sindresorhus/awesome): a short title,
a concise description, a `Contents` section, categorized entries, and consistent
one-line descriptions.

Existing Discord-related awesome lists often use broad buckets such as bots,
libraries, dashboards, and developer tools, as seen in
[jacc/awesome-discord](https://github.com/jacc/awesome-discord) and
[discord-united/awesome-discord](https://github.com/discord-united/awesome-discord).
This repository should stay narrower: Discord bots first, with Top.gg tags as
the main discovery path.

## Contributing

When adding a bot, choose exactly one primary Top.gg tag section and follow the
entry format above. If a bot spans multiple categories, add secondary tags at the
end of the entry instead of duplicating it.

## License

To be decided.
