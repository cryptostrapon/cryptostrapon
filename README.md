# CryptoStrapon

**We don't chase scammers. We document playbooks.**

A free AI crypto scam detector and an open education hub. Everything below is free to use and reuse.

## Start here

- **Check something suspicious:** [free AI scam detector](https://cryptostrapon.com/scam-detector), no sign-up
- **Read the cases:** [Dark Bits](https://cryptostrapon.com/dark-bits), 56 documented investigations
- **Learn the terms:** [glossary of 301 crypto scam terms](https://cryptostrapon.com/glossary)
- **Lost funds?** [What to do next](https://cryptostrapon.com/report-crypto-theft)

## Open projects

| Project | What it is | Licence |
|---|---|---|
| [npm-install-audit](https://github.com/cryptostrapon/npm-install-audit) | Zero dependency Node CLI to run on a repo you did not write, before npm install: install hooks, risky code, git hooks, VS Code tasks and a project `.npmrc` that ships its own token or registry. Made for take-home tests from recruiters and unknown projects. Run `npx npm-install-audit ./repo` or add it to CI as a [GitHub Action](https://github.com/marketplace/actions/npm-install-audit). | MIT |
| [crypto-scam-quiz](https://github.com/cryptostrapon/crypto-scam-quiz) | 50 core scam scenarios as one HTML file and plain JSON (the website quiz has 107 and adds a question for every new investigation). [Try it](https://cryptostrapon.github.io/crypto-scam-quiz/) | MIT code, CC BY 4.0 content |
| [crypto-scam-glossary](https://github.com/cryptostrapon/crypto-scam-glossary) | 11 scam vectors in depth: how they work, red flags, what to do. The full 301 term glossary is on the website. [Read it](https://cryptostrapon.github.io/crypto-scam-glossary/) | MIT code, CC BY 4.0 content |
| [cryptostrapon-public](https://github.com/cryptostrapon/cryptostrapon-public) | Investigation and detector methodology, changelog | CC BY 4.0 |

## Recognition

- Our section "Inspecting a project you did not write" was merged into the [OWASP NPM Security Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/NPM_Security_Cheat_Sheet.html) ([PR #2908](https://github.com/OWASP/CheatSheetSeries/pull/2908)).
- Our note on project package manager config files was merged into the [Security Alliance (SEAL) Frameworks](https://github.com/security-alliance/frameworks), in the DevSecOps section on execution paths in untrusted code ([PR #680](https://github.com/security-alliance/frameworks/pull/680)).
- The quiz is listed in [Cybersecurity Educational Resources](https://github.com/CSIRT-MU/edu-resources) by CSIRT-MU, Masaryk University.
- The scam detector is listed in the [OSINT tool collection](https://github.com/cipher387/osint_stuff_tool_collection) by Cyb_detective and the [Awesome Crypto Tools Directory](https://github.com/CryptoToolsDirectory/Awesome-Crypto-Tools-Directory).
- Our investigations are listed in [Awesome Financial Crime](https://github.com/SKR-35/Awesome-Financial-Crime) and named in its v1.6.0 release notes.

## Contribute

New scenarios, translations and corrections are welcome. Look for issues labelled **good first issue** in npm-install-audit, the quiz and the glossary. We publish our own audits too: see the v1.1 note in the quiz changelog.

Contact: cryptostrapon@proton.me
