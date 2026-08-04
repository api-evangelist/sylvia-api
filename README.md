# Sylvia API

Third-party Reddit data API — Reddit content as JSON, with full recursive comment threads, a live
feed, and bulk datasets.

- **Website:** https://sylvia-api.com/
- **OpenAPI:** https://sylvia-api.com/openapi.json
- **llms.txt:** https://sylvia-api.com/llms.txt
- **API base:** `https://api.sylvia-api.com/v1`

Part of the [API Evangelist](https://apievangelist.com) network. Submitted through the Add-API
pipeline, **parked for review**, and approved by hand on 2026-08-04 — see `X-Discovery` in
`apis.yml`.

## Surface

Twelve read operations: post and comment search, single-item lookup, subreddit and user timelines,
a live comments feed, dataset torrents for bulk access, and a usage endpoint. API key auth.

It sits in the gap Pushshift left — queryable Reddit history without going through OAuth on the
first-party API.

## Why it was parked, and why that was wrong

The pipeline scored it **low confidence**. `sylvia-api.com` returns an identical 3,122-byte page
for `/`, `/apis.json`, `/docs` **and** a control path `/zzz-control` — a site-wide HTML catch-all,
which normally means an artifact does not exist.

But `/openapi.json` (22,328 bytes) and `/llms.txt` (3,558 bytes) return **different bytes with
different checksums**. Both are real. The spec parses as OpenAPI 3.0.3 and **all 12 operations
carry an `operationId`**, which is better hygiene than most specs in this catalog.

A status code alone could not tell these apart. Comparing a candidate artifact against a control
path is what separates a real document from a catch-all, in both directions.
