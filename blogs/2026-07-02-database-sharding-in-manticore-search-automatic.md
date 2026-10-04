---
title: "Database sharding in Manticore Search: automatic distribution and replication"
url: "https://manticoresearch.com/blog/sharding-in-manticore-search/"
date: "2026-07-02"
feed_url: "https://manticoresearch.com/blog/index.xml"
---
Manticore can split a table into shards and spread them across a cluster with a single CREATE TABLE statement. On one node, sharding parallelizes work across CPU cores. Across many nodes, it does the harder job: distributing data, replicating each shard to a configurable replication factor, and rebalancing automatically when nodes fail or join.
