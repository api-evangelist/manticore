---
title: "Manticore Search: mmap speeds up columnar KNN rescoring"
url: "https://manticoresearch.com/blog/columnar-mmap/"
date: "2026-10-05"
feed_url: "https://manticoresearch.com/blog/index.xml"
---
Manticore Search supports both row-wise and columnar attribute storage . Row-wise storage works well when the working set fits in memory, but columnar storage becomes especially useful when large datasets exceed RAM: queries that need only a few attributes can read and cache mostly the data they actually use.
