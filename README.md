# Amari

An umbrella for the Amari security tooling: authorized network reconnaissance, adversary-emulation and purple-team automation, and a port scanner. Each project lives in its own repository and is linked below.

## Projects

| Project | What it does | Status |
|---|---|---|
| [Amari Offensive Automation Platform](https://github.com/Whoisyle/amari-offensive-automation-toolkit-) | ATT&CK-mapped planning, bounded local simulations, evidence capture, detection-coverage review, and reporting | Alpha (v2.0.0), 87 tests passing |
| [Amari Network Recon Tool](https://github.com/Whoisyle/Amari-Network-Recon-Tool) | Asset discovery, DNS and port checks, host classification, and scheduled scans | Working CLI; entry point fixed |
| [Amari Port Scanner](https://github.com/Whoisyle/amari-port-scanner) | TCP connect scanner with presets and JSON/CSV output | Being rebuilt |

## Shared principles

These apply across every project in this umbrella.

- **Authorization first.** Only scan or test systems you own or have written permission to test.
- **Safe by default.** Tools explain what they will do before doing it and avoid destructive or evasive behaviour.
- **Evidence over claims.** Results are recorded with enough context to be reproduced and verified.
- **Zero-trust defaults.** Credentials never live in source; CI uses short-lived tokens.

Each project's own `SECURITY.md` describes how to report vulnerabilities in that project.

## Layout

```
amari/
├── README.md        # this index
└── docs/
    └── roadmap.md   # cross-project plan
```

## Licence

Each project carries its own licence. See the individual repositories.
