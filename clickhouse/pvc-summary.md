# ClickHouse PVC 사용량 요약

| 구성요소 | PVC | 용량 |
|---------|-----|------|
| ClickHouse shard-0 | data-volume-chi-simple-ch-simple-0-0-0 | 50Gi |
| ClickHouse shard-1 | data-volume-chi-simple-ch-simple-1-0-0 | 50Gi |
| Zookeeper 0 | data-zookeeper-0 + datalog-zookeeper-0 | 10Gi + 5Gi |
| Zookeeper 1 | data-zookeeper-1 + datalog-zookeeper-1 | 10Gi + 5Gi |
| Zookeeper 2 | data-zookeeper-2 + datalog-zookeeper-2 | 10Gi + 5Gi |

**총합**: ClickHouse 100Gi + Zookeeper 45Gi = **145Gi**
