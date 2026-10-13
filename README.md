<div align="center">

# Kaushik Reddy Lingireddy

### I build AI systems that can prove they did the right thing.

Benchmarks that check what an agent actually *committed*, agents whose every decision is inspectable,<br/>
and the data plumbing underneath. Founder of [Thrill AI](https://thrill.vision/) · MS Data Science Engineering, George Mason '25.

[![Website](https://img.shields.io/badge/kaushikreddy.in-1f2328?style=flat-square&logo=googlechrome&logoColor=white)](https://kaushikreddy.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lingireddy-kaushik-reddy-995b54440)
[![Email](https://img.shields.io/badge/Email-c14438?style=flat-square&logo=gmail&logoColor=white)](mailto:kaushikreddylingireddy2002@gmail.com)

</div>

---

## Flagship projects

### 🏘️ [Settlement](https://github.com/Lingikaushikreddy/Settlement-Village): a village sim where you can read why every agent did what it did

Six residents bid for jobs, gather, build and recruit toward one objective you set. Open any of them to see the decision, the route and the memory behind it. It doubles as a testbed: point `npx settlement-testbed` at your own agent's HTTP endpoint and get a report anyone can re-verify.

[![Play in your browser](https://img.shields.io/badge/%E2%96%B6_Play_in_your_browser-no_signup,_no_API_key-38664a?style=for-the-badge)](https://settlement-village.vercel.app)
[![npm](https://img.shields.io/npm/v/settlement-testbed?style=for-the-badge&label=npx%20settlement-testbed&color=cb3837)](https://www.npmjs.com/package/settlement-testbed)

<a href="https://settlement-village.vercel.app"><img src="https://raw.githubusercontent.com/Lingikaushikreddy/Settlement-Village/main/docs/media/settlement-demo.gif" alt="Settlement: start Grow the village, residents gather and build, then the log shows why each one claimed its job" width="760"></a>

### 🛒 [IndicOrderBench](https://github.com/Lingikaushikreddy/indicorderbench): catches voice agents that place the wrong order

A voice agent can read back "one paneer wrap, no onion" and still commit two wraps with onion. IndicOrderBench scores the order that actually reached the backend, in English and Hinglish, with a CI exit code. No judge model, and the demo needs no API keys.

[![PyPI](https://img.shields.io/pypi/v/indicorderbench?style=flat-square&label=pip%20install%20indicorderbench)](https://pypi.org/project/indicorderbench/)

```bash
uvx --from indicorderbench iob demo --out demo-out
```

<img src="https://raw.githubusercontent.com/Lingikaushikreddy/indicorderbench/main/docs/images/iob-demo.gif" alt="iob demo: the buggy agent passes 20% of scenarios, the fixed one 100%" width="760">

### 🔐 [aegis-shred](https://github.com/Lingikaushikreddy/Aegis): delete a user by destroying one key

Crypto-shredding for application data: each user gets their own encryption key, so erasing a person makes every copy of their data unreadable, backups included. Rust core, Python package, `aegis` CLI. Alpha, not yet independently audited.

[![PyPI](https://img.shields.io/pypi/v/aegis-shred?style=flat-square&label=pip%20install%20aegis-shred)](https://pypi.org/project/aegis-shred/)

---

## Open source

**[libredb-studio](https://github.com/libredb/libredb-studio)** ★1.0k: 8 merged PRs and listed in CONTRIBUTORS. I built the [one-command Keycloak SSO demo stack](https://github.com/libredb/libredb-studio/pull/947), fixed MySQL schema diffs [emitting unquoted column defaults](https://github.com/libredb/libredb-studio/pull/1119), bound the demo stacks to loopback only ([#960](https://github.com/libredb/libredb-studio/pull/960), [#1004](https://github.com/libredb/libredb-studio/pull/1004)) and shipped four docs fixes ([#938](https://github.com/libredb/libredb-studio/pull/938), [#939](https://github.com/libredb/libredb-studio/pull/939), [#940](https://github.com/libredb/libredb-studio/pull/940), [#1657](https://github.com/libredb/libredb-studio/pull/1657)).

---

## More I've built

| | |
|---|---|
| [**aegiseval**](https://github.com/Lingikaushikreddy/aegiseval) | Red-teaming a tool-using RAG agent: threat model, 260-prompt golden set, validated LLM judge, mitigations measured before and after |
| [**MerchantLens**](https://github.com/Lingikaushikreddy/MerchantLens) | Databricks lakehouse where access rules are enforced by the query engine, not by asking the agent nicely |
| [**mcp-rust-sdk**](https://github.com/Lingikaushikreddy/mcp-rust-sdk) | Rust SDK for building Model Context Protocol servers |
| [**pulse**](https://github.com/Lingikaushikreddy/pulse) | Realtime task board that shows its own latency budget live |
| [**rocm-devops-starter**](https://github.com/Lingikaushikreddy/rocm-devops-starter) | Probe, smoke-test training run, container and CI for PyTorch on AMD GPUs, with a table of exactly what ran on real hardware |
| [**Contract & Invoice Intelligence**](https://github.com/Lingikaushikreddy/Thrill-AI-Contract-Invoice-Intelligence-System) | Checks invoices against their contracts and tracks precision/recall/F1 on the flags |

**Stack I reach for:** Python · TypeScript · Rust · SQL · FastAPI · Next.js · LangGraph · MCP · Databricks · Postgres · Docker · GitHub Actions

---

**Now:** getting IndicOrderBench and aegis-shred to their first outside users, and publishing measured ordering accuracy for real LLM voice stacks.
Open to **AI engineering, data/analytics engineering and data analyst** roles.

<sub>If something here is useful to you, a ⭐ or an issue with a real failure you've seen helps more than anything.</sub>
