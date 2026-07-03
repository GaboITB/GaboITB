### Hi, I'm Gaëtan 👋

Systems &amp; network administration student in Belgium, focused on **defensive security**, homelab infrastructure, and AI tooling.

## 🛡️ MCP Shield

[**MCP Shield**](https://github.com/GaboITB/mcp-shield) — a security audit framework for Model Context Protocol (MCP) servers, scanning them **before installation** for supply-chain attacks, prompt injection, tool poisoning, and rug pulls.

- **17 detectors** across 3 surfaces (source code, MCP metadata, runtime delta)
- **359 tests**, **zero dependencies** (Python stdlib only)
- Battle-tested on **31+ real-world MCP servers**
- `pip install mcp-shield-audit` · [PyPI](https://pypi.org/project/mcp-shield-audit/)

## 🔎 Responsible disclosures

Security issues I reported to real-world MCP projects (discovered with MCP Shield):

| Project | Finding |
| --- | --- |
| [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp/issues/1811) | Telemetry enabled by default without explicit opt-in |
| [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server/issues/254) | Auth token passed as CLI argument, visible in the process list (CWE-214) |
| [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp/issues/19) | Command injection via `shell=True` on unsanitized input |
| [0xKoda/WireMCP](https://github.com/0xKoda/WireMCP/issues/16) | Command injection via unsanitized `exec()` parameters |
| [gilby125/mcp-proxmox](https://github.com/gilby125/mcp-proxmox/issues/6) | TLS certificate verification disabled by default |

## 🧰 Focus

`Defensive security` · `MCP / LLM security` · `Homelab (Proxmox, WireGuard)` · `Python` · `Automation`
