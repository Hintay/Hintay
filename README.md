## Hi, I'm Hintay

I like the layer where software meets hardware and the network: wire protocols for microcontroller boards, the programs that talk to them, and the Go and Rust services that keep everything running. I live in Tokyo and I'm also a master's student at the University of Tsukuba.

### What I'm working on

- **[Nginx UI](https://github.com/0xJacky/nginx-ui)**: helping maintain it since 2022. Lately I've been building its plugin platform: the [plugin contract](https://github.com/nginxui/plugin-spec), SDKs for [Go](https://github.com/nginxui/plugin-sdk-go), [Rust](https://github.com/nginxui/plugin-sdk-rust) and the [web](https://github.com/nginxui/plugin-sdk-web), signed packages, and a [log analytics plugin](https://github.com/nginxui/plugin-log-analytics-tantivy) on Tantivy.
- **Signet** (private for now): a self-service SSH certificate authority in Rust, with KRL revocation, signed agent upgrades and login auditing.
- Running an LLM API gateway across four nodes, with PostgreSQL failover (Patroni, etcd), Redis replication and a small Go tool that decides when to fail over and back.
- A burn-in test rig controller rewritten in Rust, talking CAN FD and UDP with Cyphal.

### Research

At Tsukuba I use language models to annotate the mood states of people with bipolar disorder in their Reddit posts, and to follow how those states change over time.

- [*Few-Shot Prompt-Based Longitudinal Mood State Analysis of Bipolar Disorder on Social Media*](https://doi.org/10.1007/978-981-92-6910-5_13), BESC 2026, LNCS vol. 17175, Springer (first author)
- [bd-state-annotation](https://github.com/kalclab/bd-state-annotation): the annotation schema, prompts, pipeline and evaluation scripts from the paper

### Small things

- [power-admin](https://github.com/Hintay/power-admin): logging a house's power use from PZEM-004T meters
- [py-zebra-scanner-windows](https://github.com/Hintay/py-zebra-scanner-windows): driving Zebra barcode scanners from Python
- [opnsense-adguardhome-ha](https://github.com/Hintay/opnsense-adguardhome-ha): AdGuard Home with failover on OPNsense
- Fixes merged into [RustDesk](https://github.com/rustdesk/rustdesk/pull/16444), [pybind11](https://github.com/pybind/pybind11/pull/5378), [Netmaker](https://github.com/gravitl/netmaker/pull/1493) and [maroto](https://github.com/johnfercher/maroto/pull/363)

Mostly writing Go, Rust, Python and C these days. Find me on my [blog](https://kugeek.com) or [LinkedIn](https://www.linkedin.com/in/jiefeng-lin/).
