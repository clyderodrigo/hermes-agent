# hermes-agent
CR46 hermes agent repository

## Taste Profile
AI power user tracking frontier model news (Anthropic, OpenAI, Claude) and dev ecosystem trends (GitHub Trending, Hacker News, dev.to, Microsoft Learn, Infor developer). Music taste spans mainstream chart hits and alternative, tracked via Spotify genre charts and Soundcharts rankings (top playlists, monthly listeners, alternative genre). Stays on top of Sri Lanka local news (News 1st, The Morning) and global headlines (Reuters, BBC, AP). Wants daily, concise, non-dump digests delivered to Telegram.

## Wishlist

| WL # | I want | How |
|------|--------|-----|
| 1 | Daily trends, rankings, curated TL:DR | Daily chron jobs for each of my interests - a curated and ranked TLDR feed from listed sources. Delivered to Telegram. |
| 2 | Block calendar for events | Google calendar skill or MCP with a rule like "add events that match my interests and don't conflict". |
| 3 | Build ideas and deploy to GitHub | A weekly job: pick one idea, build it in a sandbox, push to a new repo, send me the link. |
| 4 | Seek for tech jobs | Agent shortlists and drafts applications. |

### WL #1 — Interests & Sources

```json
{
  "AI power user": [
    "https://claude.com/resources",
    "https://openai.com/blog"
  ],
  "Development trends & events": [
    "https://github.com/trending",
    "https://dev.to/top/month",
    "https://learn.microsoft.com",
    "https://developer.infor.com"
  ],
  "Top & trending music": [
    "https://open.spotify.com/genre/0JQ5DAqbMKFQIL0AXnG5AK",
    "https://soundcharts.com/en/playlists/spotify",
    "https://soundcharts.com/en/artists/spotify-monthly-listeners",
    "https://soundcharts.com/en/artists/spotify-monthly-listeners/genre/alternative",
    "https://soundcharts.com/en/playlists/spotify/this-is"
  ],
  "Sri Lanka News": [
    "https://english.newsfirst.lk/latest",
    "https://www.themorning.lk/"
  ],
  "Global news": [
    "https://www.reuters.com/world/",
    "https://www.bbc.com/news",
    "https://apnews.com"
  ]
}
```
