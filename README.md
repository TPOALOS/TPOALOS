# Hi, I'm TPOALOS

I build small-to-mid-sized command line tools in **pure Python, with no dependencies**. Each one is a
single repo with tests, a README, CI and an MIT license. Everything is defensive: there are no attack tools here.

## Security

| Project | What it does |
|---|---|
| [hostguard](https://github.com/TPOALOS/hostguard) | Read-only hardening auditor for Linux and macOS: 76 checks, score, HTML report, drift detection |
| [portlens](https://github.com/TPOALOS/portlens) | Defensive attack-surface scanner (nmap-style) with a scope guard and rate caps |
| [pcaplens](https://github.com/TPOALOS/pcaplens) | pcap/pcapng analyzer: TCP reassembly, scan/beacon/DNS-tunnel detectors |
| [ctfhost](https://github.com/TPOALOS/ctfhost) | Platform for hosting your own CTF: scrypt auth, CSRF, dynamic scoring |

## Finance

| Project | What it does |
|---|---|
| [pocketledger](https://github.com/TPOALOS/pocketledger) | Private, local personal finance ledger: bank CSV import, budgets, subscriptions, net worth |
| [backtestlint](https://github.com/TPOALOS/backtestlint) | Finds look-ahead bias and data leakage in Python backtest code |
| [riskmetrics](https://github.com/TPOALOS/riskmetrics) | Sharpe, drawdowns, bootstrap intervals, deflated Sharpe and multiple-testing corrections |

## Smaller tools

[secretscan](https://github.com/TPOALOS/secretscan) · [fimcheck](https://github.com/TPOALOS/fimcheck) ·
[permaudit](https://github.com/TPOALOS/permaudit) · [certwatch](https://github.com/TPOALOS/certwatch) ·
[authlog-summary](https://github.com/TPOALOS/authlog-summary) · [logscrub](https://github.com/TPOALOS/logscrub) ·
[gha-audit](https://github.com/TPOALOS/gha-audit) · [dockerfile-audit](https://github.com/TPOALOS/dockerfile-audit) ·
[reqpin](https://github.com/TPOALOS/reqpin) · [jwtlint](https://github.com/TPOALOS/jwtlint) ·
[headercheck](https://github.com/TPOALOS/headercheck) · [sshcfg-audit](https://github.com/TPOALOS/sshcfg-audit) ·
[sshkey-audit](https://github.com/TPOALOS/sshkey-audit) · [mailtriage](https://github.com/TPOALOS/mailtriage) ·
[urlcheck](https://github.com/TPOALOS/urlcheck) · [envdrift](https://github.com/TPOALOS/envdrift) ·
[cronnext](https://github.com/TPOALOS/cronnext) · [githook-guard](https://github.com/TPOALOS/githook-guard) ·
[gitidentity-audit](https://github.com/TPOALOS/gitidentity-audit) · [shellhist-scrub](https://github.com/TPOALOS/shellhist-scrub)

## Principles

- Standard library only: nothing to install, nothing to audit.
- Read-only by default, and honest about limits.
- No telemetry, no network calls unless the tool's whole job is to check a host you own.

Issues and pull requests are welcome.
