---
title: "How Indexfox Built an AI Site-Search Widget on Manticore"
url: "https://manticoresearch.com/blog/how-indexfox-built-an-ai-site-search-widget-on-manticore/"
date: "2026-04-27"
feed_url: "https://manticoresearch.com/blog/index.xml"
---
Indexfox is an AI search widget that any website can drop in with a single tag — automatic crawling, hybrid keyword + semantic results, and direct AI answers with source links. Under the hood, every query is served by Manticore Search: full-text MATCH with English lemmatization, KNN vector search over HNSW with 8-bit quantization, Reciprocal Rank Fusion to merge the two, and CALL AUTOCOMPLETE for as-you-type suggestions. This post walks through how Indexfox built a multi-tenant AI site-search product on top of Manticore, what features they leaned on, and why an open-source search engine turned
