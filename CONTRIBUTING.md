# Contributing

Thank you for helping improve this catalog. This is a curated list, not a scrape of every bot directory, so entries should be useful, verifiable, and easy for server owners to compare.

## Entry Format

Each bot entry uses this shape:

```markdown
- [Bot Name](website-url) - One- or two-sentence description of what it does. ([Invite](invite-url), [top.gg](top-gg-url), [Docs](docs-url), [GitHub](repo-url), [Support Server](support-server-invite), [Privacy](privacy-url)) `License` `Language/Stack` `Hosted|Self-hosted|Both` `Prefix: /`
```

Field rules:

- **Bot Name** - The bot's display name. Link the name to the bot's landing page or website when one is known. If no website is known, leave the bot name as plain text and include the Top.gg profile in the parenthesized links as `[top.gg](top-gg-url)`.
- **Description** - State what the bot does in plain language. Avoid marketing claims such as "best", "ultimate", or "only bot you need".
- **Parenthesized links** - Add any subset of `[Invite]`, `[top.gg]`, `[Docs]`, `[GitHub]`, `[Support Server]`, and `[Privacy]`, in that order. Omit the parentheses entirely if none apply.
- **License** - Use an SPDX identifier from [SPDX](https://spdx.org/licenses/), or `Proprietary` for closed-source bots.
- **Language/Stack** - Use the primary language and framework when known, such as `Python/discord.py`, `Nodejs/discord.js`, `Rust/serenity`, or `Go/DiscordGo`. `Unknown` is acceptable for closed-source bots.
- **Hosting model** - Use `Hosted`, `Self-hosted`, or `Both`.
- **Prefix** - Add a backtick tag in the form `Prefix: value` when the public command prefix is known. Put it immediately after the hosting model and before descriptive tags. Use the exact value from the bot's public docs, Top.gg profile, or verified source; examples include `Prefix: /`, `Prefix: ! or /`, and `Prefix: custom`.

Additional descriptive tags may be appended in backticks after the required metadata and prefix tag, such as `Slash Commands`, `Dashboard`, `Premium`, or a secondary category like `Utility`.

## Category Mapping

Choose exactly one primary category. If a bot spans several areas, place it where a server owner would most likely look first and add secondary tags at the end of the entry.

The README sections normalize Top.gg's broad categories and recurring bot-directory tags into one vocabulary. Do not add a new primary README section unless the category mapping is updated here too.

- `Fun` - Entertainment, novelty, and casual engagement.
- `Moderation` - Staff actions, automod, warnings, bans, and general moderation workflow.
- `Utility` - General-purpose server helpers, search, polls, embeds, reminders, stats, translators, and mixed utilities.
- `Music` - Voice-channel music playback, queues, playlists, and audio controls.
- `Economy` - Fictional currencies, shops, rewards, gambling-style minigames, inventories, and jobs.
- `Social` - Profiles, reputation, birthdays, introductions, confessions, and member discovery.
- `Game` - In-chat games, companion bots for external games, LFG, game stats, and leaderboards.
- `Meme` - Meme generators, reaction images, joke commands, and meme-focused bots.
- `Leveling` - XP, ranks, achievements, role rewards, and activity leaderboards.
- `Anime` - Anime, manga, AniList/MAL, character images, roleplay, and fandom bots.
- `Administration` - Server setup, configuration panels, dashboards, permissions, and channel/server management.
- `AI` - Chatbots, assistants, summarization, image generation, and LLM-powered features.
- `Automation` - Scheduled messages, trigger/action workflows, recurring tasks, and external integrations.
- `Crypto` - Real cryptocurrency, Web3, NFT, token, wallet, portfolio, and market-alert bots.
- `Giveaways` - Giveaways, raffles, contests, winner picking, and timed reward events.
- `Logging` - Message, moderation, member, voice, invite, ticket transcript, and audit history.
- `Media` - Feeds and content lookup, such as YouTube, Twitch, Reddit, streams, radio, images, and Spotify metadata.
- `Onboarding` - Welcomes, verification, captcha, rules acceptance, starter roles, and join flows.
- `Productivity` - Notes, calendars, tasks, project tracking, meetings, documentation, and focused work.
- `Role Management` - Reaction roles, button/dropdown role menus, autoroles, temporary roles, and role persistence.
- `Security` - Anti-nuke, anti-raid, anti-spam, phishing filters, alt checks, lockdown, and abuse prevention.
- `Support & Tickets` - Ticket channels, support queues, assignment, transcripts, forms, and escalation.
- `Temporary Voice Channels` - User-owned temporary rooms, voice lobbies, limits, locks, renaming, and cleanup.

Ambiguous cases:

- Put fictional server currencies in `Economy`, not `Crypto`.
- Put voice-channel music playback in `Music`, not `Media`.
- Put phishing, raid, and anti-nuke tools in `Security`; put staff commands and warnings in `Moderation`.
- Put transcript capture and audit trails in `Logging`; put helpdesk workflows in `Support & Tickets`.
- Put reaction roles and autoroles in `Role Management`; put welcome/captcha flows in `Onboarding`.

## Inclusion Criteria

A bot should meet most of these before it is added:

- Publicly usable, installable, or self-hostable.
- Has a clear landing page, documentation, source repository, or support server.
- Solves a recognizable Discord server problem.
- Appears maintained, or its inactive status is clearly marked.
- Has enough reputation signals to justify curation, such as usage, community adoption, source availability, or strong documentation.
- Has permissions that make sense for its advertised features.
- Provides a privacy policy or clear data-handling information when it processes sensitive member, message, moderation, or analytics data.

Avoid entries that are:

- Abandoned without notice or archived without a useful reason to keep them.
- Pure clones with no meaningful documentation or differentiation.
- Unclear about permissions, privacy-sensitive behavior, or required access.
- Only advertisements without enough public information to evaluate.

## Anti-Feature Tags

Append these backtick tags when they add context beyond the core license and hosting fields:

- `Closed Source` - No public source repository.
- `Premium` - Core advertised features are gated behind a paid tier.
- `Ads` - Displays ads in command output, status, DMs, or dashboards.
- `Broad Permissions` - Requires `Administrator` or unusually broad permissions to function.
- `Inactive` - No release or commit in the last 12 months, or known to be EOL.
- `Hosted Only` - No self-hosting option, even if source is published.
- `AI Provider` - Sends user messages, member content, or server content to a third-party LLM or AI provider.

## Slash Commands

Slash-command blocks are optional. Prefer linking to official docs unless a short command summary materially improves the entry. Top.gg command data may be used when official docs are missing, but treat it as a public directory snapshot rather than a complete command reference.

If included, place the block immediately below the entry:

```markdown
- [Bot Name](website-url) - Description. ([Invite](invite-url), [top.gg](top-gg-url), [Docs](docs-url)) `License` `Stack` `Hosted` `Prefix: /` `Slash Commands`
  <!--lint disable awesome-list-item-->
  <details>
  <summary>Slash commands (N)</summary>

  Full source lists M commands; selected key commands below.

  Sub-category:

  - `/command <required> [optional]` - Short description.
  - `/parent subcommand <arg>` - Short description.

  _Last verified: YYYY-MM-DD - [Full reference](docs-url)_

  </details>
  <!--lint enable awesome-list-item-->
```

Rules:

- List only key commands, capped at roughly 10-15.
- Use `<arg>` for required options and `[arg]` for optional options.
- Flatten subcommands into the slash path, such as `/giveaway start <duration> [winners]`.
- Group commands under short sub-category labels when the bot has more than about five listed commands.
- Keep descriptions short enough to scan quickly.
- The `N` in the summary is the number of commands listed in the block.
- If the source exposes more commands than the README block lists, include a short "selected key commands" note so readers do not mistake the block for a full reference.
- End every block with a verification date and a reference link. Prefer official docs; use the Top.gg profile only when it is the source of the command data.

Rendering notes:

1. Indent the `<details>` block two spaces so it stays inside the parent list item.
2. Keep a blank line after `<summary>` and before `</details>`.
3. Keep the local `awesome-list-item` lint disable/enable comments around command blocks. Markdown bullets render best for readers, but awesome-list linters otherwise treat nested command bullets as separate list entries.

## Sorting

Sort entries alphabetically within each category by bot name. Do not duplicate a bot across categories; use secondary tags instead.

## Cross-Cutting Indexes

Secondary indexes can be added once the list is large enough that category sections are hard to scan. Useful indexes include:

- Open-source bots.
- Self-hostable bots.
- Bots with dashboards.
- Developer- and API-focused bots.
- Archived or inactive bots.

## Pull Request Checklist

1. Entry lives under the most appropriate category section.
2. Entry follows the exact format, including spacing, punctuation, and field order.
3. Section remains alphabetically sorted.
4. Applicable anti-feature tags are present.
5. Bot-name links point to the bot website when available; otherwise the bot name is plain text and the Top.gg profile appears as `[top.gg]`.
6. Links are current and the bot is online and accepting invites, or the self-hosted bot builds and runs from a current commit.
7. Prefix metadata is present when a public prefix can be verified.
8. For permission-sensitive bots, broad permissions are documented or tagged.

One bot per pull request is preferred for first-time contributors. Bulk additions are fine for trusted maintainers.
