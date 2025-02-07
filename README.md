### Hi there 👋

<!-- Copy-paste in your Readme.md file -->

<a href="https://next.ossinsight.io/widgets/official/compose-user-dashboard-stats?user_id=13834276" target="_blank" style="display: block" align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/compose-user-dashboard-stats/thumbnail.png?user_id=13834276&image_size=auto&color_scheme=dark" width="771" height="auto">
    <img alt="Dashboard stats of @arturmelanchyk" src="https://next.ossinsight.io/widgets/official/compose-user-dashboard-stats/thumbnail.png?user_id=13834276&image_size=auto&color_scheme=light" width="771" height="auto">
  </picture>
</a>

<!-- Made with [OSS Insight](https://ossinsight.io/) -->

- TiDB:
   - br: use atomic for failedFilesCount [#52046](https://github.com/pingcap/tidb/pull/52046)

- Prometheus:
   - [STYLE] Promtool: lock-free counter in 'tsdb bench write' [#13834](https://github.com/prometheus/prometheus/pull/13834)
   - promtool: optimize labels slice allocation [#15866](https://github.com/prometheus/prometheus/pull/15866)

- Weaviate:
   - Lock-free DB::ratePerSecond counter [#4249](https://github.com/weaviate/weaviate/pull/4249)
   - refact: extract makeTenantResponse function [#6852](https://github.com/weaviate/weaviate/pull/6852)

- ImmuDB:
   - LRUCache optimizations [#1918](https://github.com/codenotary/immudb/pull/1918)

- Dgraph:
   - Reduce x.ParsedKey memory allocation from 72 to 56 bytes by optimizing struct memory alignment [#9047](https://github.com/dgraph-io/dgraph/pull/9047)

- Dolt
   - [store] use struct{} as a value in a hashset [#7706](https://github.com/dolthub/dolt/pull/7706)

- RQLite:
   - Atomic seqNum [#1749](https://github.com/rqlite/rqlite/pull/1749)
   - Allocate len(s.notifyingNodes) raftServers [#1750](https://github.com/rqlite/rqlite/pull/1750)
   - Reduce memory allocations in queryStmtWithConn [#2000](https://github.com/rqlite/rqlite/pull/2000)
   - Specify capacity [#2035](https://github.com/rqlite/rqlite/pull/2035)

- Minio:
   - fix: replace mutex with atomic [#20762](https://github.com/minio/minio/pull/20762)

- go-sql-driver
   - Make fileRegister a set [#1653](https://github.com/go-sql-driver/mysql/pull/1653)
 
- livekit
   - Reduce memory allocation in WritePaddingRTP / WriteProbePackets [#3288](https://github.com/livekit/livekit/pull/3288)

- DiceDB
   - Make processedFields a set [#1389](https://github.com/DiceDB/dice/pull/1389)
   - Single matrix memory allocation in DeepCopy [#1390](https://github.com/DiceDB/dice/pull/1390)
   - Single matrix memory allocation in DeserializeCMS [#1391](https://github.com/DiceDB/dice/pull/1391)
   - Single matrix memory allocation in newCountMinSketch [#1418](https://github.com/DiceDB/dice/pull/1418)

- Loki
   -  fix(util): specify map len [#15831](https://github.com/grafana/loki/pull/15831)
 
- etcd
   -  flags: optimise memory allocation [#19201](https://github.com/etcd-io/etcd/pull/19201)

- Xray-core
  -    Chore: Make some Maps into real Sets [#4362](https://github.com/XTLS/Xray-core/pull/4362)
