<p align="center">
  <a href="https://zoff.me">
    <img src="https://raw.githubusercontent.com/zoff-music/.github/main/profile/assets/logo.png" alt="Zoff" width="152" height="152">
  </a>
</p>

<h1 align="center">Listen together with Zoff</h1>

<p align="center">
  Zoff is free shared listening for YouTube and SoundCloud.
  Start a room, invite your friends, and build the queue together. No account needed.
</p>

<p align="center">
  <a href="https://zoff.me"><strong>Open Zoff</strong></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/zoff-music/.github/main/profile/assets/frontpage.jpg" alt="Start a free Zoff room with YouTube and SoundCloud" width="640" height="450">
  <img src="https://raw.githubusercontent.com/zoff-music/.github/main/profile/assets/playlist.jpg" alt="Zoff's room player and shared queue with song voting" width="640" height="450">
</p>

## One room, everyone's music

- Build a shared queue, import playlists, and vote on what plays next.
- Listen together with server-controlled playback or let a host take control.
- Chat and see room activity, or switch chat off on your device.
- Start a playlist from an idea with prompt-based music discovery.
- Share a room link or QR code, embed a player, or pair a remote controller.
- Browse public rooms or keep a room link private. Each room has its own
  settings and optional administrator password, not a required Zoff account.

Zoff is always free to use. Playback uses the official YouTube and SoundCloud
players, with availability and playback restrictions set by those providers.

## Listen on your screen

The project includes the main web app, protected administration, an embeddable
player, a paired web remote, and a Chromecast receiver. Native mobile supports
iOS and Android phones and tablets. The TV app has Android TV and Samsung Tizen
delivery targets. Controls and features adapt to each runtime.

[Explore Zoff](https://zoff.me/discover/listen-together) ·
[Apps and devices](https://zoff.me/discover/apps) ·
[Create a room](https://zoff.me/rooms/create)

## Built in the open

| Repository | What lives here |
| --- | --- |
| [vibes-frontend](https://github.com/zoff-music/vibes-frontend) | Seven apps, typed API access, compiled validation schemas, shared state, and web/native UI |
| [vibes-backend](https://github.com/zoff-music/vibes-backend) | Go APIs, replayable incremental SSE, room permissions, provider integrations, and scheduled workers |
| [vibes-migrator](https://github.com/zoff-music/vibes-migrator) | PostgreSQL migration history and generated database documentation |
| [.github](https://github.com/zoff-music/.github) | This organization profile and its shared presentation assets |

The backend coordinates PostgreSQL state and Redis-backed event delivery;
clients share contracts without sharing platform-specific UI. Schema changes
live in the migrator rather than being applied by the API at startup.

Read the [architecture](https://github.com/zoff-music/vibes-backend/blob/main/docs/ARCHITECTURE.md)
and [application flows](https://github.com/zoff-music/vibes-backend/blob/main/docs/FLOWS.md)
for the full picture. Each repository's README covers setup, checks, and
contribution boundaries.
