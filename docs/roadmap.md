# Trickster Roadmap

The roadmap for Trickster in 2020 focuses on delivering incremental enhancements to the core Trickster application, as well as new supporting applications and cloud native integrations.

## Timeline

### Q1 2020

- [x] Trickster 1.0 GA Release
- [x] Submit Helm charts to Helm Hub
- [x] Trickster v1.1 Release
  - [x] Relocate project to `tricksterproxy` organization
  - [x] Release Binaries for Windows
  - [x] Change default frontend listen port to 8480
  - [x] Frontend HTTP 2.0 Support
  - [x] Rules-based Request Routing and Rewriting
  - [x] Use RWMutex for cache synchronization
  - [x] Reload configuration without process restart
  - [x] Add implementation-specific Tracing options in config
  - [x] Additional performance improvements
  - [x] Relocate and merge PromSim and RangeSim into a separate repo called [mockster](https://github.com/tricksterproxy/mockster)
  - [x] Relocate Helm charts to a [separate repo](https://github.com/tricksterproxy/helm-charts)
  - [x] Automate Helm chart releases via GitHub Workflows

### Q3 2020

- [ ] Kubernetes Ingress Controller
- [ ] Submit Trickster for CNCF Sandbox Consideration
- [ ] Register Official Docker Hub Repositories
- [ ] Trickster v2.0 Beta Release

### Q4 2020

- [ ] Trickster v2.0 GA Release
  - [ ] Common Time Series Format used internally for all TSDBs
  - [ ] Importable Golang Handler Package
  - [ ] Origin Pools w/ health checking for high availability and timeseries merge
  - [ ] L7 Load balancing: round robin, hash, latency, lru, fewest # conns
  - [ ] HA Request Spray: serve first response, or HA merge of time series responses
  - [ ] YAML config support
  - [ ] Support for InfluxDB 2.0 and Flux syntax
  - [ ] Extended support for ClickHouse
  - [ ] Purge object from cache by path or key
  - [ ] Short-term caching of non-timeseries read-only queries (e.g., SELECT statements)
- [ ] [Benchster](https://github.com/tricksterproxy/benchster) - RFC Compliance and Benchmarking Suite for Proxies

## How to Help

You can help by contributing to Trickster, or trying it out in your environment.

By giving Trickster a spin, you can help us identify and fix defects more quickly. Be sure to file issues if you find something wrong. If you can reliably reproduce the issue, provide detailed steps so that developers can more easily root-cause the issue.

If you want to contribute to Trickster, we'd love the help. Please take any issue that is not already assigned as per the contributing guidelines, or check with the maintainers to find out how best to get involved.

## Thank You

We are so excited to share the Trickster with the community. This is only possible through our great community of contributors, users and supporters. Thank you for all you in making this project a success!
