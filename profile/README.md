<p align="center">
  <a href="https://zoff.me">
    <img src="https://raw.githubusercontent.com/zoff-music/.github/main/profile/assets/header.webp" alt="Zoff: Listen. Watch. Together. Your people, one shared room." width="1920" height="823">
  </a>
</p>

<h1 align="center">Your people. One shared room.</h1>

<p align="center">
  Listen to music together or settle in for a watch party.<br>
  Share a link, build the queue, and enjoy it together.<br>
  <strong>Always free. No Zoff account needed.</strong>
</p>

<p align="center">
  <a href="https://zoff.me/features/music"><strong>Listen together</strong></a> ·
  <a href="https://zoff.me/features/watch"><strong>Watch together</strong></a> ·
  <a href="https://zoff.me/discovery/apps">Get the apps</a> ·
  <a href="https://x.com/zoffmusic">Follow on X</a>
</p>

## Two ways to spend time together

**Music rooms** bring YouTube and SoundCloud into a shared music queue. Add your
favorites, import a playlist, vote on the next track, or turn an idea into a queue
with AI-assisted discovery.

**Watch rooms** are for watching YouTube videos together. The host controls
playback and seeking, while everyone can add videos, vote, and chat. Watch rooms
search beyond music, so the queue can follow whatever you're into.

## Make the room yours

- **One shared queue.** Add items, vote, and see changes arrive in real time.
- **Keep the conversation going.** Chat and room activity sit alongside playback.
  Prefer just the queue? Switch chat off on your device.
- **Set the rules per room.** Choose who can add items, how skipping works, and
  whether played items stay in the queue. Optional administrator passwords
  protect room controls without requiring an account.
- **Bring your people.** Share a link or QR code, browse public rooms, or leave
  your room unlisted.
- **Use the screen that fits.** Open a party or cinema screen, cast to a TV,
  pair your phone as a remote, or embed a room on your own site.

Playback uses the official provider players. Embedding, age, country, and
autoplay restrictions still apply; Zoff does not bypass them.

## From your phone to the big screen

Use Zoff in your browser or on iOS and Android phones and tablets. The TV app
targets Android TV and Samsung Tizen, with a Chromecast receiver and a paired
web remote for shared-screen playback.

[Apps and devices](https://zoff.me/discovery/apps) · [Browse music rooms](https://zoff.me/rooms/explore?live=false) · [Browse watch rooms](https://zoff.me/rooms/explore?type=watch&live=false)

## Built in the open

| Repository | What's inside |
| --- | --- |
| [vibes-frontend](https://github.com/zoff-music/vibes-frontend) | Web, mobile, TV, Cast, embeds, remote control, and administration, with shared typed APIs and platform-specific UI |
| [vibes-backend](https://github.com/zoff-music/vibes-backend) | Go APIs, Music/Watch room rules, provider integrations, replayable SSE updates, and background workers |
| [vibes-migrator](https://github.com/zoff-music/vibes-migrator) | PostgreSQL migration history and generated database documentation |

PostgreSQL holds room state; Redis supports caching and real-time event delivery.
Versioned APIs keep the different clients working together as Zoff evolves.

Explore the [backend architecture](https://github.com/zoff-music/vibes-backend/blob/main/docs/ARCHITECTURE.md)
and [application flows](https://github.com/zoff-music/vibes-backend/blob/main/docs/FLOWS.md)
for the full picture. Each repository's README covers setup, checks, and
contribution boundaries.

[Privacy](https://zoff.me/privacy-policy) · [Terms](https://zoff.me/terms-of-service) · [Security](https://zoff.me/security)
