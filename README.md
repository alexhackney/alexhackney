# Alex Hackney

Full stack developer in Clearwater, FL. I build Laravel and Vue/React applications, video
streaming infrastructure, and cloud communications systems, and I open-source the packages I
needed along the way.

**[alexhackney.com](https://alexhackney.com)**

---

### Packages

**[laravel-doppler](https://github.com/alexhackney/laravel-doppler)**

Render a Laravel `.env` from [Doppler](https://www.doppler.com) secrets safely, atomically, and
with a round-trip guarantee.

Rendering an env file looks like a one-liner. It isn't. `env-no-quotes` silently truncates any
value containing `#`, which random-generated passwords contain routinely. `mv` across two
filesystems is not atomic, so it leaves a window where `.env` is half written. A root-written
`.env` produces a file php-fpm cannot read, so every config value silently becomes empty and the
app boots into failure. This package closes all of those by construction, and refuses to write
rather than write something wrong.

```bash
composer require alexhackney/laravel-doppler
php artisan env:sync
```

**[lara-nimble](https://github.com/alexhackney/lara-nimble)**

Laravel package for the Nimble Streamer API. Streams, DVR, sessions, restreaming, and transcoder
rules behind a clean interface.

**[laravel-socialbu](https://github.com/alexhackney/laravel-socialbu)**

Laravel package for the SocialBu social media API. Publish posts, upload media, manage accounts,
and handle webhooks.

**[scarlett-player](https://github.com/Hackney-Enterprises-Inc/scarlett-player)**

Modular, plugin-based video player. Lightweight core with HLS, DASH, and Chromecast as
first-class plugins.

---

### What I work with

**Backend:** PHP, Laravel, FrankenPHP, REST APIs, Pest, PHPUnit, TDD

**Frontend:** JavaScript, TypeScript, Vue, React, Alpine, Tailwind

**Infrastructure:** AWS, Docker, Linux, Nginx, Caddy, HAProxy, Traefik, Varnish, Proxmox, CI/CD

**Streaming:** RTMP, HLS, SRT, NDI, ingest, transcoding, VOD, CDN delivery

**Data:** MySQL, PostgreSQL, Redis, Valkey, Elasticsearch, Algolia

---

### Background

I have been running live streams and large-scale video production since the late 90s, which is
where most of the streaming work comes from. I have built cloud and on-premise PBX systems,
including a caller ID system used by thousands of people. These days it is mostly Laravel,
infrastructure, and the occasional package.

Dad to two daughters, grandfather to two granddaughters, and reliably powered by Coke Zero.

---

### Elsewhere

[Website](https://alexhackney.com) | [LinkedIn](https://linkedin.com/in/ahackney) | [Packagist](https://packagist.org/packages/alexhackney/)
