<!-- Curated and reviewed: 2026-11-12 -->

<p align="center">
  <img src="https://i.pinimg.com/736x/56/c2/21/56c221d7b6291ec9ff889386b3a32863.jpg" alt="Free Anime APIs" width="70%" />
</p>

<p align="center">
  <a href="https://github.com/Munna-Scriptz/free-anime-apis/stargazers"><img src="https://img.shields.io/github/stars/Munna-Scriptz/free-anime-apis?style=flat-square&color=f4b860&label=stars" alt="GitHub stars" /></a>
  <a href="https://github.com/Munna-Scriptz/free-anime-apis/network/members"><img src="https://img.shields.io/github/forks/Munna-Scriptz/free-anime-apis?style=flat-square&color=8b9cf6&label=forks" alt="GitHub forks" /></a>
  <a href="https://github.com/Munna-Scriptz/free-anime-apis/commits/main"><img src="https://img.shields.io/github/last-commit/Munna-Scriptz/free-anime-apis?style=flat-square&color=65c7b5&label=updated" alt="Last commit" /></a>
  <img src="https://img.shields.io/badge/APIs-22-8b9cf6?style=flat-square" alt="22 APIs" />
  <a href="./LICENSE"><img src="https://img.shields.io/github/license/Munna-Scriptz/free-anime-apis?style=flat-square&color=65c7b5" alt="MIT license" /></a>
</p>

<p align="center">
  A curated collection of free and paid Anime, Manga, Streaming, Quotes, Waifu & Image APIs for developers.
</p>

<p align="center">
  <a href="#quick-picks">Quick Picks</a> ·
  <a href="#general-anime-data">Anime Data</a> ·
  <a href="#anime-streaming--episodes">Streaming</a> ·
  <a href="#manga-apis">Manga</a> ·
  <a href="#anime-quotes">Quotes</a> ·
  <a href="#waifu--anime-images">Images</a> ·
  <a href="#anime-database--reverse-image-search">Reverse Search</a>
</p>

---

> [!IMPORTANT]
> **Jikan's public API was discontinued on October 1, 2026.** The old `api.jikan.moe` hosted service is no longer available. [Tenrai API](https://api.tenrai.org/documentation) is a Jikan-compatible public alternative, currently in beta. See [status and migration notes](#status--migration-notes).

## About

**Free Anime APIs** is a curated collection of free and paid APIs for developers.

Whether you're building an anime website, streaming platform, Discord bot, mobile app, manga reader or dashboard — this repository has you covered.

- Anime & Manga Data
- Streaming Availability & Episodes
- Manga & Chapter Information
- Anime Quotes & Characters
- Waifu & Anime Images
- Reverse Image Search
- Anime Openings & Endings
- Anime Image Generation
- Official, Community & Unofficial APIs

## Quick Picks

| What you're building | Recommended API | Why |
|---|---|---|
| Anime discovery app | [AniList](https://docs.anilist.co/guide/graphql/) | Powerful GraphQL anime and manga database |
| MAL-compatible REST app | [Tenrai](https://api.tenrai.org/documentation) | Jikan-compatible anime REST API |
| Official MAL integration | [MyAnimeList API](https://myanimelist.net/apiconfig/references/api/v2) | Official MAL catalogue and user lists |
| Anime tracking app | [Simkl](https://api.simkl.org/) | Watch history, lists and synchronization |
| Manga reader | [MangaDex](https://api.mangadex.org/docs/) | Manga, chapters, covers and groups |
| Anime schedules | [AnimeSchedule](https://animeschedule.net/api/v3/documentation) | Seasonal anime and release schedules |
| Streaming availability | [Watchmode](https://api.watchmode.com/docs) | Streaming platforms and watch links |
| Anime openings & endings | [AnimeThemes](https://api-docs.animethemes.moe/) | Anime OP/ED information and videos |
| Anime quotes | [Animechan](https://animechan.io/docs) | Random and searchable anime quotes |
| Reverse image search | [trace.moe](https://soruly.github.io/trace.moe-api/) | Identify anime from screenshots |

## API Access Types

| Type | Description |
|---|---|
| **Free** | Public API access without payment. Limits may apply. |
| **Free + Key** | Free access requiring an API key or registration. |
| **Freemium** | Free tier with paid upgrades or higher limits. |
| **Paid** | Paid subscription or usage-based pricing. |
| **Community** | Community-maintained or unofficial API. |
| **Beta** | Experimental API that may change or experience downtime. |

---

## General Anime Data

| API Source | Description | Auth | Type | Resources / Packages |
|---|---|---|---|---|
| [AniList API](https://docs.anilist.co/guide/graphql/) | GraphQL API with anime, manga, characters, staff, rankings, recommendations and airing schedules | OAuth for user data | Free | [GitHub](https://github.com/AniList) |
| [Tenrai API](https://api.tenrai.org/documentation) | MyAnimeList public catalogue with anime, manga, characters, people, seasons, schedules and rankings. Jikan v4-compatible | No (optional Server Key) | Free · Beta | [Docs](https://api.tenrai.org/documentation) |
| [MyAnimeList API v2](https://myanimelist.net/apiconfig/references/api/v2) | Official anime and manga database, rankings, seasonal anime, details and user lists | Client ID / OAuth 2.0 | Free | [API Reference](https://myanimelist.net/apiconfig/references/api/v2) |
| [Kitsu API](https://kitsu.docs.apiary.io/) | Anime and manga metadata, trending titles, categories, ratings, relationships and user libraries | No for public data | Free | [API Docs](https://kitsu.docs.apiary.io/) |
| [Shikimori API](https://shikimori.one/api/doc) | Anime, manga, ranobe, characters, people, reviews, ratings and user lists | OAuth 2.0 | Free | [OAuth Guide](https://shikimori.io/oauth) |
| [AnimeSchedule API](https://animeschedule.net/api/v3/documentation) | Anime database, seasonal schedules, upcoming episodes and release information | API Token | Free | [Documentation](https://animeschedule.net/api/v3/documentation) |
| [Simkl API](https://api.simkl.org/) | Anime, TV and movie tracking, watch history, ratings, lists, calendars and synchronization | Client ID / OAuth 2.0 | Free / Commercial licensing | [API Docs](https://api.simkl.org/) |
| [TMDB API](https://developer.themoviedb.org/docs) | Movie and TV database, anime metadata, posters, backdrops, cast, genres and streaming providers | API Key | Free / Paid Commercial | [GitHub](https://github.com/faridsafi/react-native-movie-db) |
| [AniDB API](https://wiki.anidb.net/HTTP_API_Definition) | Anime database with titles, episodes, characters, creators and file information | Registered API Client | Free | [API Wiki](https://wiki.anidb.net/API) |

**Note:** AniList's API is currently under a temporary degraded rate limit of 30 requests/minute, compared with its normal documented limit of 90 requests/minute. Always respect response rate-limit headers.

---

## Anime Streaming / Episodes

These APIs provide streaming availability, episode utilities or subtitle data. Streaming availability does not mean the API provides actual video playback.

| API Source | Description | Auth | Type | Resources / Packages |
|---|---|---|---|---|
| [Watchmode API](https://api.watchmode.com/docs) | Streaming availability, provider information, watch links and metadata across supported countries | API Key | Free + Paid | [Pricing](https://api.watchmode.com/pricing) |
| [TMDB Watch Providers](https://developer.themoviedb.org/reference/tv-watch-providers) | Streaming provider availability for movies and TV shows by country | API Key | Free / Paid Commercial | [API Docs](https://developer.themoviedb.org/docs) |
| [AniSkip API](https://api.aniskip.com/docs) | Community-submitted opening, ending and other skip timestamps for anime episodes | No | Free | [Documentation](https://api.aniskip.com/docs) |
| [OpenSubtitles API](https://opensubtitles.stoplight.io/docs/opensubtitles-api) | Search, download and upload subtitles using anime titles, release names, IMDb IDs or file hashes | API Key | Free + Paid | [Pricing](https://www.opensubtitles.com/) |
| [AnimeThemes API](https://api-docs.animethemes.moe/) | Anime opening and ending themes, theme metadata and video resources | No for public reads | Free / Community | [GitHub](https://github.com/AnimeThemes) |

> **Important:** Watchmode and TMDB provide legal streaming availability and provider links, not playable video streams. Be careful with unofficial streaming scrapers because they can disappear, change endpoints or distribute content without proper licensing.

---

## Manga APIs

| API Source | Description | Auth | Type | Resources / Packages |
|---|---|---|---|---|
| [MangaDex API](https://api.mangadex.org/docs/) | Manga catalogue, search, chapters, covers, authors, scanlation groups and tags | No for public reads | Free | [GitHub](https://github.com/mangadex) |
| [MangaUpdates API](https://mangaupdates.apidocumentation.com/) | Manga search, series information, authors, publishers, categories and release information | No for most public endpoints | Free | [API Docs](https://mangaupdates.apidocumentation.com/) |
| [AniList API](https://docs.anilist.co/guide/graphql/) | Manga metadata, rankings, characters, recommendations and user reading lists | OAuth for user data | Free | - |
| [Kitsu API](https://kitsu.docs.apiary.io/) | Manga catalogue, genres, categories, ratings and user libraries | No for public data | Free | - |
| [MyAnimeList API](https://myanimelist.net/apiconfig/references/api/v2) | Manga search, details, rankings and user reading lists | Client ID / OAuth 2.0 | Free | - |
| [Shikimori API](https://shikimori.one/api/doc) | Manga, ranobe, ratings, characters and user lists | OAuth 2.0 | Free | - |

---

## Anime Quotes

| API Source | Description | Auth | Type | Resources / Packages |
|---|---|---|---|---|
| [Animechan](https://animechan.io/docs) | Random quotes, searchable anime quotes, character quotes and anime information | No for free tier | Free + Paid | [Documentation](https://animechan.io/docs) |
| [AnimeQuotes API](https://github.com/sujalgoel/anime-quotes-api) | Community-maintained collection of 10,000+ anime quotes | No (dataset) | Free | [GitHub](https://github.com/sujalgoel/anime-quotes-api) |

**Animechan limits:** Free tier provides 100 requests/day per IP. Premium currently costs $5/month and provides 1,000 requests/hour.

---

## Waifu / Anime Images

| API Source | Description | Auth | Type | Resources / Packages |
|---|---|---|---|---|
| [Waifu.im](https://docs.waifu.im/docs/intro/) | Anime illustrations, tags, artists, filters, random images and albums | No for basic browsing | Free | [API Docs](https://docs.waifu.im/docs/api/) |
| [Nekos.best](https://docs.nekos.best/) | Anime images, GIFs and character categories with search and metadata | No | Free / Community | [Documentation](https://docs.nekos.best/getting-started/api-reference.html) |
| [Nekosia API](https://nekosia.cat/documentation) | Random anime images, metadata, tags, dominant colors and duplicate prevention | No for public GET | Free / Community | [Documentation](https://nekosia.cat/documentation) |
| [Waifu.pics](https://github.com/Waifu-pics/waifu-api) | User-contributed anime picture database with SFW and NSFW categories | No | Free / Community | [GitHub](https://github.com/Waifu-pics/waifu-api) |

**Important notes:**

- Waifu.im supports basic image browsing without authentication. Its documented rate is 20 requests/second.
- Nekos.best requires a descriptive User-Agent. Its documented limits are 200 requests/minute per category and 7 search requests per 5 seconds.
- Nekosia has host-specific rate limits. The API host currently documents 300 requests per 5 minutes.
- Nekos.best prohibits commercial use, bulk downloading, redistribution and AI-training use. Check the terms of every image provider before using its content.

---

## Anime Database / Reverse Image Search

| API Source | Description | Auth | Type | Resources / Packages |
|---|---|---|---|---|
| [trace.moe](https://soruly.github.io/trace.moe-api/) | Reverse image search for anime screenshots. Identifies anime, episode and timestamp | No for guest access | Free / Donation-supported | [Documentation](https://soruly.github.io/trace.moe-api/) |
| [AniDB HTTP API](https://wiki.anidb.net/HTTP_API_Definition) | Anime metadata, episode information, creators, characters and related resources | Registered Client | Free | [API Wiki](https://wiki.anidb.net/API) |

**AniDB note:** Its API has strict request limits. The HTTP API requires at least two seconds between requests. The legacy HTTP endpoint is not HTTPS, so take this into consideration when choosing it.

---

## Anime AI Image Generation

| API Source | Description | Auth | Type | Resources / Packages |
|---|---|---|---|---|
| [AnimeAPI.ai](https://animeapi.ai/docs/api-reference) | Anime-style AI image and video generation with multiple models, image sizes and output formats | API Key / Credits | Paid + Limited Demo | [API Documentation](https://animeapi.ai/docs/api-reference) |

---

## Status & Migration Notes

| API | Status | Notes |
|---|---|---|
| [Jikan API](https://github.com/jikan-me/jikan-rest) | Discontinued | Public hosted API discontinued on October 1, 2026. Self-hosting remains an option to investigate. |
| [Tenrai API](https://api.tenrai.org/documentation) | Active · Beta | Jikan-compatible alternative for public MyAnimeList catalogue data. |
| [AniAPI](https://github.com/AniAPI-Team/AniAPI) | Archived | Official AniAPI repositories are archived. Do not assume the old hosted service is maintained. |
| [OpenSubtitles.org XML-RPC](https://www.opensubtitles.com/) | Legacy / Discontinued | Use the current OpenSubtitles.com REST API instead. |
| [Enime API](https://enime-docs.vercel.app/) | Unverified | Current maintenance and hosted service availability could not be confirmed. |
| [Consumet](https://github.com/consumet/consumet.ts) | Not recommended as a hosted service | Old hosted streaming scrapers should not be assumed operational or licensed. |

---

## More

| Resource | Description | Type | Link |
|---|---|---|---|
| [MAL API v2](https://myanimelist.net/apiconfig/references/api/v2) | Official MyAnimeList developer API | Free | [Docs](https://myanimelist.net/apiconfig/references/api/v2) |
| [AniList GraphQL](https://docs.anilist.co/) | Full anime and manga GraphQL documentation | Free | [Docs](https://docs.anilist.co/) |
| [AnimeThemes](https://animethemes.moe/) | Anime openings and endings database | Free / Community | [API Docs](https://api-docs.animethemes.moe/) |
| [MangaUpdates](https://www.mangaupdates.com/) | Manga database and API | Free | [API Docs](https://mangaupdates.apidocumentation.com/) |

---

## Developer Notes

Before using an API, check:

- **Authentication:** API key, OAuth, client registration or no authentication.
- **Rate Limits:** Requests per second, minute, day or month.
- **Commercial Usage:** Whether commercial projects are permitted.
- **Attribution:** Whether the API requires source credits.
- **Reliability:** Whether the API is maintained and its documentation is current.

Always respect API rate limits, cache responses where permitted and keep private API keys out of frontend code.

## License

This project is licensed under the **MIT License**.

Third-party APIs, images, anime metadata, manga content and other resources remain subject to their respective owners' licenses and terms of service.
