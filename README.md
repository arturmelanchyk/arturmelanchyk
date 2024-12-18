### Hi there 👋

- TiDB:
   - br: use atomic for failedFilesCount [#52046](https://github.com/pingcap/tidb/pull/52046)

- Prometheus:
   - [STYLE] Promtool: lock-free counter in 'tsdb bench write' [#13834](https://github.com/prometheus/prometheus/pull/13834)

- Weaviate:
   - Lock-free DB::ratePerSecond counter [#4249](https://github.com/weaviate/weaviate/pull/4249)

- ImmuDB:
   - LRUCache optimizations [#1918](https://github.com/codenotary/immudb/pull/1918)

- Dgraph:
   - Reduce x.ParsedKey memory allocation from 72 to 56 bytes by optimizing struct memory alignment [#9047](https://github.com/dgraph-io/dgraph/pull/9047)

- Dolt
   - [store] use struct{} as a value in a hashset [#7706](https://github.com/dolthub/dolt/pull/7706)

- RQLite:
   - Atomic seqNum [#1749](https://github.com/rqlite/rqlite/pull/1749)
   - Allocate len(s.notifyingNodes) raftServers [#1750](https://github.com/rqlite/rqlite/pull/1750)

- Minio:
   - fix: replace mutex with atomic [#20762](https://github.com/minio/minio/pull/20762#event-15649234409)
