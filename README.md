# Wiki Live Feed

A tiny self-hosted dashboard that connects straight to Wikipedia's public,
real-time edit stream and shows every edit happening across Wikipedia as it
happens.

- Filter by wiki (English Wikipedia, Wikidata, Commons, German, French, or all)
- Hide bot edits to see only human activity
- Watch list: flag specific keywords or page titles, get a visual + sound alert
  the moment they're edited
- Optional text-to-speech: have edits read aloud live, either just the flagged
  ones or everything visible

Runs entirely off Wikipedia's own public [EventStreams API](https://stream.wikimedia.org/v2/stream/recentchange) —
no API key, no account, no backend logic beyond serving the page.

## Run it

```
git clone git@github.com:ytchaosstack/Wiki-live-feed.git
cd Wiki-live-feed
docker compose up
```

Then open **http://localhost:8080**.

## From the video

This project was built for a ChaosStack video. Watch it here: *(link added once published)*

More from the channel: [@ChaosStack](https://www.youtube.com/@ChaosStack)
