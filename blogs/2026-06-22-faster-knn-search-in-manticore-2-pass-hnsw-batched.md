---
title: "Faster KNN search in Manticore: 2-pass HNSW, batched distances, and AVX-512"
url: "https://manticoresearch.com/blog/knn-hnsw-performance/"
date: "2026-06-22"
feed_url: "https://manticoresearch.com/blog/index.xml"
---
TL;DR: Three changes to the HNSW search engine improve KNN throughput by up to 29% at high k, with over 20% gains under concurrent load.
