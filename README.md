<div align="center">

# Kaushik Reddy Lingireddy

### I build AI systems that can prove they did the right thing.

Benchmarks that check what an agent actually *committed*, agents whose every decision is inspectable,<br/>
and the data plumbing underneath. Founder of [Thrill AI](https://thrill.vision/) · MS in Data Science, George Mason '25.

[![Website](https://img.shields.io/badge/kaushikreddy.in-1f2328?style=flat-square&logo=googlechrome&logoColor=white)](https://kaushikreddy.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lingireddy-kaushik-reddy-995b54440)
[![Email](https://img.shields.io/badge/Email-c14438?style=flat-square&logo=gmail&logoColor=white)](mailto:kaushikreddylingireddy2002@gmail.com)

</div>

---

## Open source

**20 merged pull requests across 9 repositories**, including Roboflow, pydantic and sqlfluff.

**[roboflow/supervision](https://github.com/roboflow/supervision)** ★51k: 4 merged fixes to the metrics, dataset and image code. Mean average recall now [leaves crowd and ignored targets out](https://github.com/roboflow/supervision/pull/2750), oriented-box IoU is [compared with the thresholds in float32](https://github.com/roboflow/supervision/pull/2752) the way box IoU is, Pascal VOC export [rounds box corners instead of truncating them](https://github.com/roboflow/supervision/pull/2748), and the resize fallback [matches OpenCV's nearest-neighbour sampling](https://github.com/roboflow/supervision/pull/2722).

**[libredb-studio](https://github.com/libredb/libredb-studio)** ★1.3k: 8 merged PRs and listed in CONTRIBUTORS. I built the [one-command Keycloak SSO demo stack](https://github.com/libredb/libredb-studio/pull/947), fixed MySQL schema diffs [emitting unquoted column defaults](https://github.com/libredb/libredb-studio/pull/1119), bound the demo stacks to loopback only ([#960](https://github.com/libredb/libredb-studio/pull/960), [#1004](https://github.com/libredb/libredb-studio/pull/1004)) and shipped four docs fixes ([#938](https://github.com/libredb/libredb-studio/pull/938), [#939](https://github.com/libredb/libredb-studio/pull/939), [#940](https://github.com/libredb/libredb-studio/pull/940), [#1657](https://github.com/libredb/libredb-studio/pull/1657)).

Also merged: [sqlfluff #8664](https://github.com/sqlfluff/sqlfluff/pull/8664) (honour inline dialect directives when loading SQL files), [pydantic/httpx2 #1213](https://github.com/pydantic/httpx2/pull/1213), [roboflow-python #551](https://github.com/roboflow/roboflow-python/pull/551) and [PasarGuard/panel #907](https://github.com/PasarGuard/panel/pull/907).

---

## Flagship projects

### [Settlement](https://github.com/Lingikaushikreddy/Settlement-Village): a multi-agent simulation with an inspectable decision trail

Six residents bid for jobs, gather, build and recruit toward one objective you set. Open any of them to see the decision, the route and the memory behind it. It doubles as a testbed: point `npx settlement-testbed` at your own agent's HTTP endpoint and get a report anyone can re-verify.

[![Play in your browser](https://img.shields.io/badge/%E2%96%B6_Play_in_your_browser-no_signup,_no_API_key-38664a?style=for-the-badge)](https://settlement-village.vercel.app)
[![npm](https://img.shields.io/npm/v/settlement-testbed?style=for-the-badge&label=npx%20settlement-testbed&color=cb3837)](https://www.npmjs.com/package/settlement-testbed)

<a href="https://settlement-village.vercel.app"><img src="https://raw.githubusercontent.com/Lingikaushikreddy/Settlement-Village/main/docs/media/settlement-demo.gif" alt="Settlement: start Grow the village, residents gather and build, then the log shows why each one claimed its job" width="760"></a>

### [IndicOrderBench](https://github.com/Lingikaushikreddy/indicorderbench): a benchmark for voice-ordering agents

A voice agent can read back "one paneer wrap, no onion" and still commit two wraps with onion. IndicOrderBench scores the order that actually reached the backend, in English and Hinglish, with a CI exit code. No judge model, and the demo needs no API keys.

[![PyPI](https://img.shields.io/pypi/v/indicorderbench?style=flat-square&label=pip%20install%20indicorderbench)](https://pypi.org/project/indicorderbench/)

```bash
uvx --from indicorderbench iob demo --out demo-out
```

<img src="https://raw.githubusercontent.com/Lingikaushikreddy/indicorderbench/main/docs/images/iob-demo.gif" alt="iob demo: the buggy agent passes 20% of scenarios, the fixed one 100%" width="760">

### [aegis-shred](https://github.com/Lingikaushikreddy/Aegis): crypto-shredding for user data erasure

Crypto-shredding for application data: each user gets their own encryption key, so erasing a person makes every copy of their data unreadable, backups included. Rust core, Python package, `aegis` CLI. Alpha, not yet independently audited.

[![PyPI](https://img.shields.io/pypi/v/aegis-shred?style=flat-square&label=pip%20install%20aegis-shred)](https://pypi.org/project/aegis-shred/)

---

## Selected projects

| | |
|---|---|
| [**release-lens**](https://github.com/Lingikaushikreddy/release-lens) | Shows exactly what changed between two npm tarballs (byte growth, file hashes, manifest changes) without installing either one. [Browser app](https://lingikaushikreddy.github.io/release-lens/) and npm CLI |
| [**aegiseval**](https://github.com/Lingikaushikreddy/aegiseval) | Red-teaming a tool-using RAG agent: threat model, 260-prompt golden set, validated LLM judge, mitigations measured before and after |
| [**MerchantLens**](https://github.com/Lingikaushikreddy/MerchantLens) | Databricks lakehouse where access rules are enforced by the query engine rather than by the agent |
| [**Village Sentinel**](https://github.com/Lingikaushikreddy/Village-Sentinel) | Governance agent that routes each decision through a small Decider model, checks evidence when uncertain and escalates to Amazon Bedrock only when needed. [Live demo](https://lingikaushikreddy.github.io/Village-Sentinel/) |
| [**mcp-rust-sdk**](https://github.com/Lingikaushikreddy/mcp-rust-sdk) | Rust SDK for building Model Context Protocol servers |
| [**rocm-devops-starter**](https://github.com/Lingikaushikreddy/rocm-devops-starter) | Probe, smoke-test training run, container and CI for PyTorch on AMD GPUs, with a record of exactly what ran on real hardware |

**Core stack:** Python · TypeScript · Rust · SQL · FastAPI · Next.js · LangGraph · MCP · Databricks · Postgres · Docker · GitHub Actions

---

**Current focus:** contributing to Roboflow's computer-vision libraries, bringing IndicOrderBench and aegis-shred to their first external users, and publishing measured ordering accuracy for real LLM voice stacks.

Open to **AI/ML engineering (including computer vision), data engineering and data analyst** roles.
