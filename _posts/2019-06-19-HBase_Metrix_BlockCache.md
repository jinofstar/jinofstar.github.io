---
layout: post
title: Hbase - Metrix - BlockCache
date:  2019-06-13 20:05
description: 
comments: true
tags:
- 
---

hbase.regionserver.blockCacheCount
Block cache item count in memory. This is the number of blocks of StoreFiles (HFiles) in the cache.

hbase.regionserver.blockCacheEvictedCount
Number of blocks that had to be evicted from the block cache due to heap size constraints.

hbase.regionserver.blockCacheFree
Block cache memory available (bytes).

hbase.regionserver.blockCacheHitCachingRatio
Block cache hit caching ratio (0 to 100). The cache-hit ratio for reads configured to look in the cache (i.e., cacheBlocks=true).

hbase.regionserver.blockCacheHitCount
Number of blocks of StoreFiles (HFiles) read from the cache.

hbase.regionserver.blockCa
cheHitRatio
Block cache hit ratio (0 to 100). Includes all read requests, although those with cacheBlocks=false will always read from disk and be counted as a “cache miss.”

hbase.regionserver.blockCacheMissCount
Number of blocks of StoreFiles (HFiles) requested but not read from the cache.

hbase.regionserver.blockCacheSize
Block cache size in memory (bytes), that is, memory in use by the BlockCache.

