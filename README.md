# CryptoStrapon

**We don't chase scammers. We document playbooks.**

A free AI crypto scam detector and an open education hub. Everything below is free to use and reuse.

<p align="center"><a href="https://cryptostrapon.github.io/crypto-scam-quiz/"><img src="https://raw.githubusercontent.com/cryptostrapon/crypto-scam-quiz/main/quiz_demo.gif" alt="Crypto scam quiz: pick the safe answer in real scam scenarios" width="640"></a></p>

<p align="center"><a href="https://cryptostrapon.github.io/crypto-scam-quiz/"><b>Take the crypto scam quiz</b></a> · 50 real-life scenarios · free, no sign-up · English and Spanish</p>

## Start here

- **Check something suspicious:** [free AI scam detector](https://cryptostrapon.com/scam-detector), no sign-up
- **Read the cases:** [Dark Bits](https://cryptostrapon.com/stories), 58 documented investigations (Dark Bits is CryptoStrapon's investigations series)
- **Learn the terms:** [glossary of 307 crypto scam terms](https://cryptostrapon.com/glossary)
- **Setting up a hardware wallet?** [Checklist before you start](https://github.com/cryptostrapon/cryptostrapon-public/blob/main/checklists/hardware-wallet-setup.md) ([ES](https://github.com/cryptostrapon/cryptostrapon-public/blob/main/checklists/hardware-wallet-setup.es.md))
- **Lost funds?** [What to do next](https://cryptostrapon.com/report-crypto-theft)

## Open projects

### Featured: review an unfamiliar repo before installing it

[npm-install-audit](https://github.com/cryptostrapon/npm-install-audit) checks a repo you did not write before you run npm install: install hooks, risky code, git hooks, VS Code tasks and package manager settings. Run it from a trusted copy outside the project you are checking. Findings need human review, and a clean result is not proof of safety.

| Project | What it is | Licence |
|---|---|---|
| [npm-install-audit](https://github.com/cryptostrapon/npm-install-audit) | Zero dependency Node CLI to run on a repo you did not write, before npm install: install hooks, risky code, git hooks, VS Code tasks and project package-manager settings. Start with the [trusted standalone workflow](https://github.com/cryptostrapon/npm-install-audit#quick-start), or add it to CI as a [GitHub Action](https://github.com/marketplace/actions/npm-install-audit). | MIT |
| [crypto-scam-quiz](https://github.com/cryptostrapon/crypto-scam-quiz) | 50 core scam scenarios as one HTML file and plain JSON (the website quiz has 108 and adds a question for every new investigation). [Try it](https://cryptostrapon.github.io/crypto-scam-quiz/) | MIT code, CC BY 4.0 content |
| [crypto-scam-glossary](https://github.com/cryptostrapon/crypto-scam-glossary) | 11 scam vectors in depth: how they work, red flags, what to do. The full 307 term glossary is on the website. [Read it](https://cryptostrapon.github.io/crypto-scam-glossary/) | MIT code, CC BY 4.0 content |
| [cryptostrapon-public](https://github.com/cryptostrapon/cryptostrapon-public) | Investigation and detector methodology, the [detector test set](https://github.com/cryptostrapon/cryptostrapon-public/blob/main/methodology/detector-test-set-v1.md) (100 inputs with expected results), checklists and changelog | CC BY 4.0 |

## Recognition

- Our section "Inspecting a project you did not write" was merged into the [OWASP NPM Security Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/NPM_Security_Cheat_Sheet.html) ([PR #2908](https://github.com/OWASP/CheatSheetSeries/pull/2908)).
- A second note in the same cheat sheet explains that npm ignores a `.npmrc` inside a workspace folder, so `ignore-scripts=true` belongs in the repository root ([PR #3028](https://github.com/OWASP/CheatSheetSeries/pull/3028)).
- A follow-up pins the npm documentation link in that note to a fixed commit, so the reference cannot drift ([PR #3031](https://github.com/OWASP/CheatSheetSeries/pull/3031)).
- Our fix in [lockfile-lint](https://github.com/lirantal/lockfile-lint), a tool that checks npm lockfiles for tampered package sources, makes it detect `npm-shrinkwrap.json` automatically ([PR #246](https://github.com/lirantal/lockfile-lint/pull/246)).
- Our note on project package manager config files is part of the [Security Alliance (SEAL) Frameworks](https://frameworks.securityalliance.org/devsecops/developer-targeted-intrusions/execution-paths), on the DevSecOps page about execution paths in untrusted code ([PR #680](https://github.com/security-alliance/frameworks/pull/680), named in the [v0.0.3 release notes](https://github.com/security-alliance/frameworks/releases/tag/v0.0.3)).
- The quiz is listed in [Cybersecurity Educational Resources](https://github.com/CSIRT-MU/edu-resources) by CSIRT-MU, Masaryk University.
- The scam detector is listed in the [OSINT tool collection](https://github.com/cipher387/osint_stuff_tool_collection) by Cyb_detective, the [Awesome Crypto Tools Directory](https://github.com/CryptoToolsDirectory/Awesome-Crypto-Tools-Directory), and [Awesome Blockchain Security](https://github.com/bunturx/Awesome-Blockchain-Security) ([merged PR #1](https://github.com/bunturx/Awesome-Blockchain-Security/pull/1)).
- Our investigations are listed in [Awesome Financial Crime](https://github.com/SKR-35/Awesome-Financial-Crime) and named in its v1.6.0 release notes.

## Contribute

New scenarios, translations and corrections are welcome. Issues labelled **good first issue** in npm-install-audit, the quiz and the glossary are a good start; npm-install-audit is also listed on [Up For Grabs](https://up-for-grabs.net) for first-time contributors. Seen a scam that is not covered yet? Post it in [Discussions](https://github.com/cryptostrapon/cryptostrapon-public/discussions).

Contact: cryptostrapon@proton.me
