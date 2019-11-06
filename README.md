# 技术框架收集

## 数据库
- RocksDB，facebook开源的嵌入式持久化KV数据库, https://github.com/facebook/rocksdb
- LevelDB，google开源的KV数据库，https://github.com/google/leveldb
- Distributed transactional key-value database, originally created to complement TiDB, https://github.com/tikv/tikv
- TiDB is an open source distributed HTAP database compatible with the MySQL protocol, https://github.com/pingcap/tidb
- VictoriaMetrics, 高性能时序数据库,可作Prometheus长久存储, https://github.com/VictoriaMetrics/VictoriaMetrics

## 二进制格式
- Go support for Google's protocol buffers, https://github.com/golang/protobuf
- A native Thrift package for Go, https://github.com/samuel/go-thrift
- Apache Avro, https://github.com/apache/avro
- Generate Go code to serialize and deserialize Avro schemas, https://github.com/actgardner/gogen-avro

## RPC
- The Go language implementation of gRPC. HTTP/2 based RPC, https://github.com/grpc/grpc-go
- gRPC to JSON proxy generator following the gRPC HTTP spec, https://github.com/grpc-ecosystem/grpc-gateway
- rpcx，A zero cost, faster multil-language bidirectional microservices framework in Go, like alibaba Dubbo, but with more features, Scale easily. https://github.com/smallnest/rpcx
- Java implementation for Baidu RPC, multi-protocol & high performance RPC. https://github.com/baidu/brpc-java

## HTTP

- Gin is a HTTP web framework written in Go (Golang). It features a Martini-like API with much better performance -- up to 40 times faster. If you need smashing performance, get yourself some Gin. https://github.com/gin-gonic/gin
- Fast HTTP package for Go. Tuned for high performance. Zero memory allocations in hot paths. Up to 10x faster than net/http. https://github.com/valyala/fasthttp

## 即时通讯
- Instant messaging server; backend in Go; iOS, Android, web, command line clients; chatbots. https://github.com/tinode/chat

## DNS
- fast dns proxy that can run anywhere, built to black-hole internet advertisements and malware servers. https://github.com/looterz/grimd
